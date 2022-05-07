# Instalación y configuración del servidor web Nginx: Virtual Hosts

## Hecho por Joan Pérez Susidko


### Primer paso

Yo estoy usando un Sistema Operativo Ubuntu, asi que instalaré nginx con el comando `sudo apt-get install nginx`

![image](https://user-images.githubusercontent.com/101748401/167268010-fb6873f2-e67f-444e-a26c-7e41e62779f2.png)

Compruebo que se hayan instalado todos los archivos 

![image](https://user-images.githubusercontent.com/101748401/167268051-50755219-743d-4e83-9f59-beba595c3259.png)

### Segundo paso

Procedo a crear los defaults en /nginx/sites-avaible con `sudo cp default`

![image](https://user-images.githubusercontent.com/101748401/167268259-5e75c554-e1fa-4795-a25e-f7fefd2d486a.png)

Editamos con vim y ponemos nuestro nombre en el root y el nombre del server

![image](https://user-images.githubusercontent.com/101748401/167268681-1a285830-3081-439b-aed0-51f3b54c0c99.png)

Muevo los archivos al directorio enabled

![image](https://user-images.githubusercontent.com/101748401/167269473-005eff46-be76-42a5-a9d5-fa59832591c3.png)

### Tercer paso

Hago Reload de todo lo que he hecho

![image](https://user-images.githubusercontent.com/101748401/167268883-b30eceda-5cb0-4986-ab85-a933b91d926b.png)

Edito hosts para poner una IP localhosts a los dominios

![image](https://user-images.githubusercontent.com/101748401/167268991-1565c3e5-807d-4cc6-996a-357c55a3ad3f.png)

Aqui como podemos ver funciona perfectamente el juego ANT COLONY de la pagina one-html-page-challenge

![image](https://user-images.githubusercontent.com/101748401/167269962-83b16735-d7be-4c85-acca-2b460d288fd2.png)

