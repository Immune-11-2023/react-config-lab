## CRA & Vite Intro

En esta unidad hemos aprendido el setup básico de un proyecto en React a través de CRA y Vite. La práctica de hoy es bien sencilla: en este repo encontraréis dos proyectos de React montados con CRA y Vite. Sin embargo, una criatura con malvadas intenciones ha pervertido la estructura de estos proyectos. Tu objetivo es encontrar dichos problemas y solucionarlos uno a uno, empezando por el repositorio de `cra-app` .

Te encontrarás problemas como este:

![Error image](https://res.cloudinary.com/dagndlfhj/image/upload/v1707121079/Screenshot_2024-02-05_at_08.43.07_lqepmx.png)

El objetivo de esta práctica es que adquieras familiaridad con estos entornos, sepas interpretar errores y resolverlos de forma eficiente.

Tu objetivo es que ver es poder cargar esta página sin ningún error:

![Final screen](https://res.cloudinary.com/dagndlfhj/image/upload/v1707121669/Screenshot_2024-02-05_at_09.26.21_bsmnto.png)

---

Lo mismo se aplica al repositorio con Vite. Al intentar montar la aplicación con el comando

```bash
npm run dev
```

obtenemos el error:

```bash
npm ERR! Missing script: "dev"
```

¿Cuáles son los scripts disponibles en este proyecto? Parece que alguien ha tocado algún archivo. Intenta inicializar el proyecto de otra forma.

Por defecto nuestros proyectos en Vite corren en el puerto 5173. Cambia esta configuración para que el proyecto se levante en el puerto 3000 (NOTA: tal vez convenga buscar documentación…).
