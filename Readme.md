
https://primeng.org/

## Installation
  Check version : file package.json, dependencies
```
  npm install primeng primeicons primeflex
```
or
```
  npm install primeng --save
  npm install primeicons --save
  npm install primeflex --save
```
## Import style package in angular.json or in style.css

angular.json

```
  "styles": [
    "src/styles.css",
    "node_modules/primeng/resources/themes/lara-light-blue/theme.css",
    "node_modules/primeng/resources/primeng.min.css",
    "node_modules/primeflex/primeflex.css",
    "node_modules/primeicons/primeicons.css"
  ],
```

style.css
```
  @import "primeng/resources/themes/lara-light-blue/theme.css";
  @import "primeng/resources/primeng.css";
  @import "primeicons/primeicons.css";
```
- Restart app

## Using Component
In the module.ts
```
import { ButtonModule } from 'primeng/button';
...
imports: [
    CommonModule,
    ButtonModule
]

```
