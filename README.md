# Mi primer despliegue de una app Spring en Heroku

### Pasos para hacerlo:

1. Lo primero e ideal es tener el archivo `system.properties` con el contenido:
    
    ``java.runtime.version=17.0.2``
    
    Obviamente con la versión que tengamos

2. Crear una cuenta en **Heroku**
3. **Subir** el proyecto a un repositorio de GitHub (Puede ser usando el mismo IntellIj en la opción VSC -> Share repository at GitHub)
4. Crear una **nueva** app en Heroku
5. Hacer **login** con Heroku desde la terminal con el comando:
`git push heroku master`
6. Por último, cada que hagamos un cambio hay que usar el paso 5, ya que no está habilitado el deploy automático.
***
### ¡Y listo, con esto tenemos ya nuestra app en la web!
***
