
## Scaffolding para aplicación monolítica usando Laravel + Breeze + React (Typescript) + DaisyUI (Tailwind)

Para crear tu propia instalación:

- Crea un nuevo proyecto Laravel, que incluya Breeze (react).
- Una vez terminado el scaffolding, instala DaisyUI dentro de la carpeta raíz del proyecto.
- Con npm, ejecuta el comando >npm i -D daisyui@latest
- Para más info https://daisyui.com/docs/install/.
- Agrega el 'require' para las herramientas de DaisyUI en el archivo tailwind.config.js (en el apartado 'plugins').
- Por defecto, debería quedar: 
    
    ```javascript
    plugins: [forms, require('daisyui')],
    ```
- Luego, ejecuta el comando >npm install && npm run dev

Siguiendo estos pasos, podremos utilizar cuaquier componente de DaisyUI en nuestra aplicación monolítica, además, no interferirá con los componentes y construcciones que Breeze trae por defecto, ya que ambos utilizan Tailwind CSS.

También, podrás seguir utilizando Tailwind independiente de DaisyUI sin problemas.

- Este proyecto incluye una página de prueba accesible desde localhost/daisyui.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
