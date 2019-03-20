# User Stories
##Proyecto web Symfony - Práctica individual
###Se quiere
  1. Frontend web: Los usuarios deben poder consultar el resumen de logs desde
  un frontal web
  2. Autenticación: Para poder acceder al resumen de logs los usuarios deben
  poder registrarse y autenticarse mediante email y password, Google, y
  GitHub
  3. Control de acceso: Sólo una vez convirtamos un usuario registrado en
     desarrollador vía comando de consola, podrán acceder al resumen de logs
#### Pasos seguidos
#####Crear proyecto de symfony
composer create-project symfony/skeleton UserStories

#####Componente de seguridad para ferificar recipies de symfony
//composer require roave/security-advisories --dev
#####Server para desarrollo
composer require symfony/web-server-bundle --dev
#####Componente para automatizar la creacion de controllers, comand, otros
composer require symfony/maker-bundle --dev
#####Gestion de logs
composer require symfony/monolog-bundle
#####Receta para los comandos con el maker-bundle no hace falta el console de momnto
composer require symfony/console
