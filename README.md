## Comenzando

Primero, instala la aplicación:

```bash
npm install
```
Luego, ejecuta el servidor de desarrollo:

```bash
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000) en tu navegador para ver el resultado.

Puedes comenzar a editar la página modificando `pages/index.tsx`. La página se actualiza automáticamente a medida que editas el archivo.

Las [Rutas API](https://nextjs.org/docs/api-routes/introduction) se pueden acceder en [http://localhost:3000/api?q=shakespeare](http://localhost:3000/api?q=shakespeare). Este endpoint se puede editar en `pages/api/index.ts`.

El directorio `pages/api` está mapeado a `/api/*`. Los archivos en este directorio se tratan como [rutas API](https://nextjs.org/docs/api-routes/introduction) en lugar de páginas de React.

## Pruebas

Este repositorio utiliza [Jest](https://jestjs.io/)  para realizar pruebas. Actualmente, hay un archivo de prueba para el helper `QueryProcessor` helper, llamado `_tests_/QueryProcessor.test.ts`.

Para ejecutar las pruebas, usa el siguiente comando:

```bash
npm run test
```

Jest se ejecutará en modo de observación, lo que significa que ejecutará automáticamente tus casos de prueba a medida que realices cambios en tu código.


## Aprende Más

Para aprender más sobre Next.js, consulta los siguientes recursos:

- [Documentación de Next.js](https://nextjs.org/docs) - Aprende sobre las características y API de Next.js.
- [Aprende Next.js](https://nextjs.org/learn) - Un tutorial interactivo sobre Next.js.

Puedes consultar el [repositorio de GitHub de Next.js](https://github.com/vercel/next.js/) - ¡Tus comentarios y contribuciones a este proyecto de Código Abierto son bienvenidos!
