# Documentation

Dette er min dokumentation


## Start af et nyt projekt

1. Opret nyt projekt i IntelliJ
2. vælg javaEE projektskabelon
3. Java + Maven
4. Servlet dependencies

![](Img/img.png)

## Arkitektur

Vi anvender en slags MVC-pattern.
![](Img/MVC.png)

- M(odel) - Entiteter og hjælpe-metoder og klasser. Business-logic
- V(iew) - JSP og Frontend (CSS, Bootstrap mm)
- C(ontrol) - Servlets


Husk! Ingen kommunikation mellem Model og View. Gå altid igennem controlleren