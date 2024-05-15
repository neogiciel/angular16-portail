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
Utilisation du WebCompoent disponible sous :
#assets/build.js


```
 @Bean
    public RouteLocator gatewayRoutes(RouteLocatorBuilder builder) {

        logger.info("[Service GW Springboot] SpringCloudConfig : gatewayRoutes");

        return builder.routes()
                .route(r -> r.path("/security")
                        .uri("http://dev2.neogiciel.com"))

                .build();
    }
```


## Technologies
***
Technologies utilisées:
* Angular JS 16
```
 @Bean
    public RouteLocator gatewayRoutes(RouteLocatorBuilder builder) {

        logger.info("[Service GW Springboot] SpringCloudConfig : gatewayRoutes");

        return builder.routes()
                .route(r -> r.path("/security")
                        .uri("http://dev2.neogiciel.com"))

                .build();
    }
```

  
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
**Aucune**<br>



