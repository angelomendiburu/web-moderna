# Web Moderna

## Autor
- **Nombre completo:** Angel Omendiburu
- **Nombre del curso:** Desarrollo Web Moderna
- **Email:** angelomendiburu@gmail.com
- **Fecha de creación del proyecto:** 20 de noviembre de 2024

---

## Sobre el proyecto
En **La Web Moderna**, podrás leer los conceptos clave que todo Desarrollador de Software debe saber para crear aplicaciones web.

---

## Configuración de ESLint
```jsonc
{
  // Define el entorno donde se ejecutará el código
  "env": {
    "browser": true, // Habilita variables globales del navegador, como window y document
    "es2021": true   // Permite usar características de ECMAScript 2021 (ES12)
  },
  
  // Extiende configuraciones base para evitar configuraciones desde cero
  "extends": ["eslint:recommended"], // Usa las reglas recomendadas por ESLint
  
  // Configuración del parser, que interpreta el código
  "parserOptions": {
    "ecmaVersion": "latest", // Utiliza la versión más reciente de ECMAScript disponible
    "sourceType": "module"   // Indica que el código usa módulos ES6 (import/export)
  },
  
  // Define las reglas específicas de linting
  "rules": {
    "indent": ["error", 2], // Requiere 2 espacios como nivel de indentación; genera error si no se respeta
    "linebreak-style": ["error", "unix"], // Obliga a usar saltos de línea estilo Unix (\n)
    "quotes": ["error", "single"], // Exige el uso de comillas simples (' ') para las cadenas de texto
    "semi": ["error", "always"], // Obliga a usar punto y coma (;) al final de cada línea
    "no-unused-vars": "warn", // Advierte sobre variables declaradas pero no utilizadas
    "no-console": "warn" // Advierte sobre el uso de console.log() y otros métodos de console
  }
}

  
## Despliegue
- ^[Ver sitiio web](https://angelomendiburu.github.io/web-moderna/)