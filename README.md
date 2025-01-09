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
de javascript(con extensión .js). Para hacer esto usamos el
comando: `tsc ejemplo1.ts` el cuál nos generará el archivo ejemplo.js.

Para ejecutar el archivo de javascript usamos node desde una
terminal: `node ejemplo1.js`.

## Instalar el paquete ts-node

Para no tener que compilar los archivo .ts de forma manual y después
ejecutarlos con node, instalaremos el paquete ts-node con el siguiente
comando: `npm install -g typescript ts-node`. Este paquete nos permite compilar
y ejecutar con el comando: `ts-node ejemplo1.ts`

## Tipos básicos de Typescript

Los tipos básicos de TS son los tipos primitivos: number, string and boolean.
Si se intenta usar un tipo de dato diferente al especificado se mostrará
un error en el editor en tiempo de compilación.

Un ejemplo de asignación de tipo de datos en typescript es: `let numero: number;`

## Asignación de tipo de datos

Hay dos formas de asignar el tipo de dato a las variables:  
  - Por asignación
  - Por inferencia

Para asignar un tipo de dato, usamos la sintaxis de dos puntos. Esto es de forma
explicita. Ejemplo: `let día: number;`.

Por default typescript infiere el tipo de dato por el valor de la variable.
Ejemplo: `let casa = "Mi casa"`. Esto resulta en una variable tipo string y si
intentamos guardar otro tipo de valor en la variable "casa" arrojará un error
en compilación.
