# despliegue

1. iniciamos seccion en nuestro portal Azure
2. hacemos click en crear un nuevo recurso.
3. buscamos el recurso llamado aplicacion web y le damos crear.
4. creamos un nuevo grupo de recursos (en nuestro caso se llama Pokemon).
5. le damos un nombre al aplicativo web (en nuestro caso Pokedexx)
6. en el apartado de publicar lo dejamos en codigo.
7. en el apartado pilar de entorno de ejecusion escogemos ASP.NET v4.8
8. los demas parametros dejamos lo por defecto (teniendo en cuenta que en el plan de precios sea el F1 Gratix).
9. hacemos click en revisar y crear
10. y en la nueva pestaña hacemos click en crear.
11. despues de haber creado el recurso (aplicativo web), hacemos click en el apartado ir al recurso.
12. copiamos el dominio predeterminado y nos dirigimos a el (en nuestro caso pokedexx.azurewebsites.net), y podemos ver la pagina predeterminada que se carga.
13. para cargar la pagina del pokedez en el portal azure, dentro del recurso de app web nos vamos al apratado de herramientas y herramientas avanzadas.
14. en la pestaña que nos muestra hacemos click en debug console y luego en CMD.
15. abrimos la carpeta Site y luego la carpeta wwwroot.
16. eliminamos el archivo .html que aparece en esta carpeta.
    NOTA: cabe destacar que para realizar estos paso ya debemos haber realizado los que aparecen en el archivo README.md
17. montamos la aplicacion de Pokedex, para esto debemos montar la carpeta dist
18. creamos una carpeta dentro de la carpeta dist llamada pokedex-angular, y en esta introducimos la carpeta assets.
19. creamos el archivo web.config, donde vamos a configurar la seguridad de nuestra pagina web.
    20 guardamos los cambios anteriores y ejecutamos nuestra pagina.
20. entramos a la pagina securityheaders.com e introducimos el link de nuestra pagina web pokedexx.azurewebsites.net, para ver la clasificacion de seguridad que esta tiene, en nuestro caso A
