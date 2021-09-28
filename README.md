# Deteccion y clasificación de anomalias en hojas de cannabis
## Version 2.0

El presente repositorio posee la informacion para necesaria para replicar el proceso de extraccion y clasificacion de anomalias en hojas de cannabis, Dicha clasificacion se realiza en el siguiente conjunto de datos
 - Sanas
 - Deshidratadas 
 - Afectadas por insectos 
 - hojas con manchas
 
Un ejemplo de dicho DataSet se puede ver acontinuacion:

![imagen clusters cannabis]()
 
## Descripcion de uso
 
El repositorio cuenta con dos alternativas de ejecucion, la primera puede ser ejecutada por medio de un notebook de jupyter 
 
### Instalación 
Se recomienda abrir los notebooks por medio de la herramienta [colab](https://colab.research.google.com/)

- [Clasificador](https://colab.research.google.com/drive/1-MD-6-0SizOh9K1R4cJwd2wmNjVKEktk)
- [Extraccion de caracteristicas](https://colab.research.google.com/drive/1neMXQf0tRO6G0GM514OIWS_qhzyNPgog)

### Explicacion y resultados

la primera version usaba un umbralizado gaussiano, sin embargo la segunda version ya posee un suavizado por meanshift y un umbralizado binario, lo cual permite mejorar el desempeño en la enmascaracion de la zona de interes 
# Cambio de color 

- 
Anomalias
![Anomlias](https://raw.githubusercontent.com/joaramirezra/ClasificadorHojasCanabis/master/Imagenes/Contorno.png)

* Enmascaradado
![Enmascarado1](https://raw.githubusercontent.com/joaramirezra/ClasificadorHojasCanabis/master/Imagenes/Enmascarada.png)
![Enmascarado2](https://raw.githubusercontent.com/joaramirezra/ClasificadorHojasCanabis/master/Imagenes/Suavizada.png)




### Contribuciones
cualquier pull request es bienvenido, para cambios mayores por favor abrir un issue para discutir los cambios que se requieran hacer

### Colaboradores :
- [Johan Ramirez](https://github.com/joaramirezra/)

## Licencia
[MIT](https://choosealicense.com/licenses/mit/)
