## Ejercicio Inyección de Dependencias con Anotaciones en Springboot
### Integrantes
#### Santiago Avellaneda y Miguel Motta

----- 

### Solución
> Para resolver este ejercicio, primero usamos las anotaciones de Spring para configurar los `Beans` 
> que se inyectan automáticamente:
> 
> ![](img/picture1.png)
> 
> Para hacer la especificación de qué dependencia se va a inyectar, usamos la anotación `Qualifier`
> que ofrece Springboot:
> 
> ![](img/picture2.png)
>
> Luego lo ejecutamos, con la inyección especificada de `EnglishSpellChecker`:
> 
> ![](img/picture3.png)
> 
> Luego cambiamos la clase que vamos a inyectar en el `Qualifier` para que se inyecte
> la depenencia de `SpanishSpellChecker`:
> 
> ![](img/picture4.png)
> 
