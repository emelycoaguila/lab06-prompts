# Tarea: Mi prompt profesional
## Funcionalidad elegida
Registro de clientes para una aplicacion de escritorio de Java.
## Version 1: prompt basico
Crea una programa para registrar clientes.
### Que cambie:
Escribi una solicitud sencilla.
### Por que:
Queria tener una primera respuesta para revisar que informacion. faltaba
### Que mejoro en la respuesta:
La IA entendio la idea general, pero la respuesta fue muy amplia.
## Version 2
Actúa como desarrollador Java. Crea un programa para registrar clientes en una aplicación de escritorio. El cliente debe tener nombre, DNI y correo.
### Que cambie:
Agregue el rol, el contexto y los datos del cliente.
### Por que:
El primer prompt era muy general y necesitaba especificar que queria registrar.
### Que mejoro en la respuesta: 
La respuesta fue mas especifica y mostro una estructura relacionada con clientes.
## Version 3: prompt final
Actúa como desarrollador Java. Crea un programa para registrar clientes en una aplicación de escritorio usando Java Swing. El programa debe permitir registrar nombre, DNI y correo de cada cliente. Usa una clase Cliente con los atributos nombre, dni y correo. Usa este estilo para los métodos: getNombre(), setNombre(String nombre). No uses librerías externas. Explica primero la estructura de la clase y luego presenta el código Java organizado por clases.
### Que cambie:
Agregue Swing, la clase Cliente, un ejemplo de metodos, una restriccion y el formato de la respuesta.
### Porque:
Queria que la IA tuviera instrucciones mas claras sobre como debia realizar el programa.
### Que mejoro en la respuesta: 
El resultado fue mas complejo, ordenado y cercano a lo que necesitaba.
## Componentes del promt final
| Componente | Texto del prompt | 
|----------|--------------------| 
| Rol | Actúa como desarrollador Java. | 
| Instruccion | Crea un programa para registrar clientes. | 
| Contexto | En una aplicación de escritorio usando Java Swing. | 
| Ejemplo | Usa este estilo para los métodos: getNombre(), setNombre(String nombre). | 
| Formato | Explica primero la estructura de la clase y luego presenta el código Java organizado por clases. | 
| Explica la estructura antes del codigo | si |
## Evaluacion del resultado
| Criterio | Cumple | 
|----------|--------------------| 
| Esta escrito en Java y usa Swing | si | 
| Tiene una clase Cliente | si | 
| Incluyendo nombre, DNI y correo | si | 
| Usa metodo get y set | si | 
| No utiliza librerias externas | si | 
| Explica la estructura antes del codigo | si | 
## Errores que evite
### Ser demasiado general:
Lo evité agregando información específica sobre la aplicación, la clase Cliente y sus atributos.
### No indicar el formato:
Lo evité indicando que primero debe explicar la estructura y después presentar el código organizado por clases.

