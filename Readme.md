
https://primeng.org/

Install prime ng
  Check version : file package.json, dependencies
```
  npm install primeng primengicons primeflex
```
or
```
  npm install primeng --save
  npm install primengicons --save
  npm install primeflex --save
```
style.css
```
  @import "primeng/resources/themes/lara-light-blue/theme.css";
  @import "primeng/resources/primeng.css";
  @import "primeicons/primeicons.css";
```
angular.json

```
...
"styles": [
    "node_modules/primeng/resources/themes/lara-light-blue/theme.css",
    "node_modules/primeng/resources/primeng.min.css",
    "node_modules/primeflex/primeflex.css"
    ...
]
```
- Restart app
