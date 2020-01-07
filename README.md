- [1. Instalación](#1-instalación)
- [2. Configuración](#2-configuración)
- [3. Compilar la extensión](#3-compilar-la-extensión)
- [Bibliografía](#bibliografía)

---

# 1. Instalación

```bash
> git clone https://github.com/rogerforner/blank-chrome-ext.git
> cd blank-chrome-ext
> npm install
```

**Dependencias**

> _package.json_

```json
"devDependencies": {
  "cross-env": "^6.0.3",
  "laravel-mix": "^5.0.1",
  "resolve-url-loader": "^3.1.0",
  "sass": "^1.24.2",
  "sass-loader": "^8.0.0",
  "vue-template-compiler": "^2.6.11"
}
```

# 2. Configuración



# 3. Compilar la extensión

Generar la extensión procesando todos los archivos del directorio _src_ (SASS, JS, otros...).

```bash
# Desarrollo
> npm run dev

# Desarrollo + Revisión de cambios para compilarlos automáticamente.
> npm run watch

# Producción
> npm run prod
```

# Bibliografía

CHROME. _Getting Started Tutorial_. < [https://developer.chrome.com/extensions/getstarted](https://developer.chrome.com/extensions/getstarted) >
<br>[Última consulta: 7 de enero de 2020]

LARAVEl MIX. _Installation_. < [https://laravel-mix.com/docs/5.0/installation](https://laravel-mix.com/docs/5.0/installation) >
<br>[Última consulta: 7 de enero de 2020]

MEDIUM (Sara Wegman). _How to Build a Simple Chrome Extension in Vanilla JavaScript_. < [https://medium.com/javascript-in-plain-english/https-medium-com-javascript-in-plain-english-how-to-build-a-simple-chrome-extension-in-vanilla-javascript-e52b2994aeeb](https://medium.com/javascript-in-plain-english/https-medium-com-javascript-in-plain-english-how-to-build-a-simple-chrome-extension-in-vanilla-javascript-e52b2994aeeb) >
<br>[Última consulta: 7 de enero de 2020]