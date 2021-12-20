# Metasploiable2
# Preparación del entorno
## Preparar Kali Linux y Metasploitable2
##### Preparando Kali Linux

El virtualizador que usaremos es VirtualBox. Lo primero que haremos será irnos a la página de Kali Linux y descargar el archivo OVA:

https://kali.download/virtual-images/kali-2021.4/kali-linux-2021.4-virtualbox-amd64.7z

![imagen](https://user-images.githubusercontent.com/80277545/146815893-0627a255-e3ed-46dd-94da-05bb3cbbc0b9.png)

Una vez descargado, debemos descromprimirlo y obtener el archivo .OVA:

![imagen](https://user-images.githubusercontent.com/80277545/146817611-3e4ed7ef-879d-4d8a-90b9-f7094e341e17.png)

Ahora abrimos VirtualBox y importamos el archivo .OVA:

![imagen](https://user-images.githubusercontent.com/80277545/146817830-dc69f517-8c4a-42bb-a169-c9d594e9fcab.png)

Una vez instalado tendremos que añadirle otra tarjeta de red, esto lo haremos yendo a la configuración de la maquina > Red > Adaptador2. Lo habilitaremos y añadiremos el "Adaptador sólo-anfritión": 

![imagen](https://user-images.githubusercontent.com/80277545/146818821-d302eb96-32f3-4bef-bd4b-d3835508bbb4.png)

           En caso de no tener el "Adaptador sólo-anfritión", podemos añadirlo desde "archivo" > "Administrador de red anfritión" > Crear

La ventaja de hacerlo con este metodo es que no tenemos que "instalar" desde cero Kali Linux. Una vez finalizado, al iniciar el sistema directamente nos pedirá un usuario y una contraseña.

        usuario : kali
        contraseña : kali

##### Preparando Metasploitable2

Ahora descargaremos 


Crearemos una nueva maquina virtual con las siguientes caracteristicas:

![imagen](https://user-images.githubusercontent.com/80277545/146820065-5e61817b-266c-44bc-ac2e-54463689d62b.png)

Daremos en "Next" y dejaremos la memoria ram asignada en "1024".

Posteriormente crearemos un "Disco duro virtual" :

![imagen](https://user-images.githubusercontent.com/80277545/146820292-ee85fe7f-1d16-438a-b7fe-257227093c3a.png)

De tipo "VDI" y "Reservado dinámicamente" de "10GB".





