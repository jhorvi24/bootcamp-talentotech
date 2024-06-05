# Bootcamp Talento Tech Arquitectura de Nube
Despliegue de una arquitectura altamente disponible y escalable en AWS. 

## Planificación

### Requerimientos
* Requerimiento 1
* Requerimiento 2
* Requerimiento 3

### Arquitectura
En la siguiente imagen se muestra el diseño de la arquitectura a partir de los requerimientos. 
![arquitectura aws](img/Arquitectura.png)

## Ejecución

### Pequeña descripción sobre la fase de ejecución. Se utilizó el servicio de cloudoformation que es un servicio de infraestructura como código para realizar el despliegue de la arquitectura. Utilizamos el siguiente comando para realizar el despliegue de la arquitectura: 
Primero debemos realizar la validación

```
aws cloudformation validate-template --template-body file://network.yml
```

```
aws cloudformation create-stack --stack-name network-stack --template-body file://network.yml
```


