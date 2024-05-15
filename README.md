## <h1>Application Angular JS</h1>
***
<table>
  <tr>
    <td><img src="https://www.mag-corp.com/wp-content/uploads/2021/08/angular.png" alt="drawing" height="260px"/></td>
  </tr>
</table>

## Informations Générales
***
Mise en place d'un portail en Angular 16, permettant d intégrer un Web Compponent indépendent
Utilisation du WebCompoent disponible sous :<br>
**assets/build.js**

Modifier le fichier app.module.ts
```
import { NgModule, CUSTOM_ELEMENTS_SCHEMA } from '@angular/core';

schemas: [CUSTOM_ELEMENTS_SCHEMA],
```
Puis
```
 Fichier index.html
  Intégré directement <br>
  <script src= "assets/build.js"></script>

ou
  
  package.json
  "build": {
  "scripts": ["./src/assets/build.js"]

}
```
Pour pouvoir ensuite intégrer le selecteur dans la page que vous souhaitez il vous faudras simplement
```
<news-component></news-component>
```
## Technologies
***
Technologies utilisées:
* Angular JS 16

  
## Instalation
***

Lancement de l'application Angular JS<br>
```
$ ng build
$ ng serve
```
Le service est accessible sur http://localhost:4200

## FAQs
***
Quelques lignes de commandes utiles<br>
```
Désinstaller la version courante
npm uninstall -g @angular/cli

Installer la version
npm install -g @angular/cli@16.2.14

```

