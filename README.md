# Facade - Caso práctico

### Intención

Ofrece una **interface unificada** a un conjunto de interfaces de un subsistema. La **interface unificada debe ser de más alto nivel**, de tal manera que el subsistema sea más fácil de utilizar.

### Clasificación

Patrón estructural

### Vista Estructural

![image](https://user-images.githubusercontent.com/55771796/173480579-78322883-3ef6-4f9b-a91a-ba9f10e0885a.png)

### Vista Dinámica
![image](https://user-images.githubusercontent.com/55771796/173480623-d7fee9d5-24f1-44fe-8a8e-77f0ae6fa372.png)

### Ejemplo Real

Mediante la implementación del patrón de diseño Facade implementaremos un sistema que permite realizar pagos en línea, para lo cual será necesario interactuar con varios sistemas, dichos sistemas conllevan una cierta complejidad, por lo que interactuar con todos los subsistemas puede ser muy complicado, sobre todo para los programadores que no tienen contexto del funcionamiento de los subsistemas. Por lo cual se implementará una fachada que permita exponer operaciones de alto nivel, las cuales se encarguen de interactuar con los subsistemas y abstrae a los programadores de la complejidad de interactuar con dichos sistemas.

![image](https://user-images.githubusercontent.com/55771796/174156401-103470fd-53d8-4ead-b77b-97f1e4d50499.png)

![image](https://user-images.githubusercontent.com/55771796/173480708-ef8f4b0d-bed3-4d8d-8cf3-ccf87eb66b76.png)

![image](https://user-images.githubusercontent.com/55771796/174156476-53979868-40f2-4491-88a3-1485ed2f0720.png)

### Ejecucion

```
gradle run
```
