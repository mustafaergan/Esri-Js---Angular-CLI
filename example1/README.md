İki paket install edilir.
 npm install --save esri-loader
 
 npm install --save @types/arcgis-js-api
  

Type verilir.

In tsconfig.app.json add "types": ["arcgis-js-api"].

In tsconfig.spec.json add "types": ["arcgis-js-api"]


Ayrınca yeni bir component üretilir ve compenent içeriği Esri sağlamış olduğu içerik alır.

ng generate component esri-map
 
https://github.com/Esri/angular-cli-esri-map

app.component.html içerisine esri tagı eklenir.

<app-esri-map></app-esri-map>
