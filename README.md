# IngenieriaSw-CarBuilder
Modelado plataforma de autos de alta gama.

Integrantes: 
* Carlos Avella     cod. 20191099003
* Carlos Duarte     cod. 20191099008
* Christian Rojas   cod. 20191099019
* Edgar Vasquez     cod. 20191099021
             
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
* El usuario podrá modificar el motor, transmisión, suspensión, frenos y llantas. Podrá agregar accesorios como Aleron, barras de estabilización, sistema de ECU optimizado, sunroof y AirBags. Del interior del auto el usuario podrá modificar la cojinería, timón, pedales.
* Una vez el usuario haya terminado de configurar el auto, el usuario tendrá la opción de simular el rendimiento del auto y/o de generar la orden de compra.

#### Módulo de Simulación de autos

* De acuerdo al auto personalizado por el usuario, el sistema simulará el rendimiento, peso y comportamiento del mismo.

#### Módulo de compra

* Una vez el usuario haya decido comprar el vehículo, el sistema mostrará un formulario con los datos necesarios para generar la orden de compra.
* Si los datos son válidos y la orden pudo ser generada, se enviará un correo con la confirmación de la orden al correo especificado por el usuario.

## Diagrama de casos de uso 

###### General

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Casos%20de%20uso/1.%20General%20.png)

###### Seleccionar

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Casos%20de%20uso/2%20Selecionar%20y%20Personalizar.png)

###### Personalizar

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Casos%20de%20uso/3.%20Personalizar.png)

###### Simulación de Auto

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Casos%20de%20uso/4%20Simulacion.png)

###### Comprar Auto

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Casos%20de%20uso/5%20Comprar.png)


## Diagrama de paquetes y componentes 

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Componentes/PackageStructureDiagram.png)

## Diagrama de clases 

###### Diseño de Autos

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Clases/App.AutoBuilder.BLL.DisenoAuto.png)

###### Simulación de Autos

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Clases/App.AutoBuilder.BLL.Simulacion.png)

###### Compra de Autos

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Clases/App.AutoBuilder.BLL.Compra.png)


## Diagramas de secuencia

###### Diseño de Autos

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Secuencia/SecuenciaDiseñoAuto.png)


###### Simulación del Auto

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Secuencia/SecuenciaSimulación.png)


###### Compra de Autos

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Secuencia/SecuenciaCompra.png)


## Diagramas de Actividades

### General

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Actividades/ActividadesGeneral.png)



### Configurar Partes

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Actividades/ConfigurarPartes.png)



### Configurar Accesorios

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Actividades/ConfigurarAccesorios.png)



### Realizar Simulacion

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Actividades/RealizarSimulacion.png)



### Realizar Compra

![alt text](https://github.com/cduartebu/IngenieriaSw-CarBuilder/blob/develop/Diagramas/Actividades/RealizarCompra.png)


