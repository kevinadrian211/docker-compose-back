# Practica crear contenedores con yml y proyeto de springboot
## Informe de dos contenedores y proyecto con sprigboot
## 2. Tiempo 
 50 minutos
## 3. Fundamentos:

 ### 3.1 Docker
 Docker es una plataforma para poder virtualizar y empaquetar aplicaciones con dependencias en contenedores, que a diferencia de las máquinas virtuales comparten el mismo núcleo del sistema.

 - Imagen -
 Una imagen es un conjunto de instrucciones que describe cómo se debe configurar el contenedor.
 ### 3.2 Springboot
Es un framework que se basa en spring el cual está destinado para simplificar el proceso de configuración y despliegue de aplicaciones de java mediante el uso de dependencias.
 ### 3.3 YAML
 Yaml es un formto o estandar que se puede utilizar para poder hacer una configuración más rapida con código que puede ser más facil de leer o interpretar por otras personas.
## 4. Conocimientos previos.
   
Para realizar esta practica debemos tener conocimientos es:
1. Conocimientos de Docker.
2. Docker descargado.
3. Uso de la Terminal.
4. Navegador Web.
5. Acceso a Internet.
6. Comprensión de Puertos.
7. Conocimiento de Documentación de Docker.
8. Conocimientos de yml

## 5. Objetivos a alcanzar
   
- Dentro de la practica se tiene contemplado entender como se despliega un entorno dentro de docker con una base de datos postgres y un proyecto de springboot, conectandolo correctamente. 
## 6. Equipo necesario:
  
- Computador.
- Navegador web.
- Docker instalado.
- Proyecto de springboot

## 7. Material de apoyo.
   
- Documentacion de docker.
- Guia de asignatura.
- Imágnes de docker.
- Proyecto creado
  
## 8. Procedimiento

 ### 8.1 Creación de contendores y red
 Dentro de esta práctica vamos a comenzar levantando los contenedores y la red que ya los tenemos creados con el achivo yml, recordando que uno de los contenedores es de postgres, para la base de datos y otro de pgadmin que la va a consumir.
    ![](/imagenesback/contenedores-y-redes.png)
 ### 8.2 Creación de artefacto jar
    ![](/imagenesback/aplication.png)
    ![](/imagenesback/build-succes.png)
    ![](/imagenesback/dockerfile.png)
 ### 8.3 Creación de imagen con springboot
    ![](/imagenesback/creacion-de-imagen.png)
 ### 8.4 Creación del ultimo contenedor
    ![](/imagenesback/todos-los-contenedores.png)
    ![](/imagenesback/vista-final.png)
## 9. Resultados esperados:
    
Con estos pasos y estos comandos logramos tener dos contenedores y una red con lo que podemos conectar estos dos contenedores mediante esta red que tenemos, cabe recalcar que todo esto se forma de manera local o en otras paabras solamente dentro de la computadora.
