# Proyecto: Clasificación de residuos
### El problema que se plantea en el ejercicio es separar la basura a su contenedor correspondiente, es por eso que se ha creado una IA que, mediante aprendizaje, puede diferenciar que tipo de basura es cada objeto y por tanto donde tirarlo. 
Para esto se han creado cuatro clases en los que se diferencia el tipo de basura:
- Azul (Papel y cartón)
- Amarillo (Envases)
- Verde (Vidrio)
- Punto limpio (Muebles)
  
Para poder entrenar a la IA, se le enseñarán imágenes que caractericen a cada tipo de basura:
- Color
- Forma
- Tipo de material
- Grandaria

Una vez entrenado se han puesto imágenes de prueba para ver como actuaba la IA, fallando en algunas ocasiones en seleccionar de la mejor anera que tipo de basura era cada objeto, es por eso que he ido adapatando y añadiendo imágenes hasta que la IA lo haga de forma óptima, hasat llegar a esta conclusión:

| Imagen                     	| Categoria real 	| Categoria del modelo 	| Porcentaje 	| Comentario                              	|
|----------------------------	|----------------	|----------------------	|------------	|-----------------------------------------	|
| brik.jpg                   	| Amarillo       	| Amarillo             	| 100%       	|                                         	|
| bote_spray.jpg             	| Amarillo       	| Verde                	| 59%        	| No lo reconoce por la forma que tiene   	|
| tubo_pasta_dientes.jpg     	| Amarillo       	| Amarillo             	| 93%        	|                                         	|
| tarro_conserva.jpg         	| Verde          	| Verde                	| 73%        	|                                         	|
| botella.jpg                	| Verde          	| Verde                	| 100%       	|                                         	|
| Apo 33 Reflejo-256x256.jpg 	| Verde          	| Verde                	| 100%       	|                                         	|
| periodico.jpg              	| Azul           	| Azul                 	| 94%        	|                                         	|
| papel_envolver.jpg         	| Azul           	| Azul                 	| 45%        	|                                         	|
| envase_papel               	| Azul           	| Azul                 	| 87%        	|                                         	|
| juguete_plastico.jpg       	| Punto limpio   	| Punto limpio         	| 98%        	|                                         	|
| colilla.jpg                	| Punto limpio   	| Punto limpio         	| 49%        	|                                         	|
| pañal.jpg                  	| Punto limpio   	| Amarillo             	| 63%        	| Lo reconoce como envase por los colores 	|
