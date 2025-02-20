#Creacion de un Repositorio#  
Creamos una carpeta con ``` mkdir``` y hacemos ``` git init``` para darle acceso y hacemos ``` code .```  
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/init-.png "Visualizacion de repositiorio creado")  
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/status1.png "Visualizacion de status") 
Pasamos el estado del documento de Untracked a staging area con 
``` git add```  
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/status2.png "Visualizacion de git add y de status")  
El estado del documento es unmodified hasta el momento en el que escribo esto que entonces pasa a estar modified.  
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/status3.png "Visualizacion de git add y de status")  
Al hacer el git push no ocurre nada debido a que no tiene nombre ni esta conectado con el **repositorio remoto** por ese mismo motivo ```git remote -v``` No nos mostrara nada.  
Creamos el repositorio en github y lo asociamos.
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/repoRemote1.png "Visualizacion de repositorio remoto")  
Asociamos el repositorio local.  
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/repoRemote2.png "Asociacion Repositorio")  
Ejecutamos el comando ```git remote -v```  
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/repoRemote3.png "Visualizacion git remote -v ")  
Subimos todo los archivos al repositorio locar y al remoto.  
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/repoRemote4.png "Visualizacion git commit -am")  

![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/repoRemote5.png "Visualizacion git push origin")   

Asi quedaria el repositorio remoto  
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/repoRemote6.png "Visualizacion remoto")   
![Este contenido se mostrará cuando la imagen no se pueda cargar](./images/repoRemote7.png "Visualizacion remoto")  
