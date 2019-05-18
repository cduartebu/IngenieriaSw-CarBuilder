# IngenieriaSw-CarBuilder
Modelado plataforma de autos de alta gama

## Requerimientos

* Permitir a un usuario comprar y personalizar un auto
* Debe contar con un módulo de personalización de autos
* Debe contar con un módulo de simulación de autos
* Debe contar con un módulo de generación de orden de compra

#### Módulo de personalización de autos

* El usuario debería ser capaz de escoger el tipo de vehículo que va a personalizar, ejemplo: (Deportivo, Sedan, SUV, Van) 
* Una vez el usuario ha seleccionado un tipo de auto, el sistema creara un auto de ese tipo con unas partes por defecto.
* El usuario tendrá la opción de simular y comprar el auto con su configuración por defecto.
* El sistema debe mostrar los partes y accesorios que puede ser modificables de acuerdo al tipo de vehículo escogido.
* El sistema debe mostrar las opciones disponibles en stock para la parte que el usuario quiere modificar de acuerdo al tipo de vehículo escogido.
* El usuario podrá escoger de la parte que desea cambiar a partir de las opciones mostradas por el sistema.
* Una vez el usuario haya terminado de configurar el auto, el usuario tendrá la opción de simular el rendimiento del auto y/o de generar la orden de compra.

#### Módulo de Simulación de autos

* De acuerdo al auto personalizado por el usuario, el sistema simulará el rendimiento, peso y comportamiento del mismo.

#### Módulo de compra

* Una vez el usuario haya decido comprar el vehículo, el sistema mostrará un formulario con los datos necesarios para generar la orden de compra.
* Si los datos son válidos y la orden pudo ser generada, se enviará un correo con la confirmación de la orden al correo especificado por el usuario.

## Diagrama de clases 

###### Capa lógica de negocio

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Clases/App.AutoBuilder.BLL.png)


## Diagrama de secuencia

###### Construir Auto deportivo

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Secuencia/InteractionSequenceDiagram.png)
