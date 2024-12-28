# Typescript course

## Installation requirements

- Visual Studio Code: https://code.visualstudio.com/  
- NodeJs: https://nodejs.org/en/  
- Typescript compilator: https://www.typescriptlang.org/download/
  Install it globally with npm: `npm install -g typescript`

**Note:** You can use this web to write typescript code online: https://www.typescriptlang.org/play

## Primer ejemplo en Typescript

```typescript
// ejemplo1.ts
function holaMundo() {
  console.log("Hola Mundo");
}
holaMundo();
```
Para poder ejecutar este archivo se necesita compilar para generar un archivo
de javascript(con extensión .js). Para hacer esto usamos el comando: `tsc ejemplo1.ts` el cuál nos generará el archivo ejemplo.js.

Para ejecutar el archivo de javascript usamos node desde una terminal: `node ejemplo1.js`.
