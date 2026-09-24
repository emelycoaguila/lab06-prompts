# Bitacora de prompts
Laboratorio 06: Fundamentos de Ingenieria de prompts.
Herramienta de IA usada: (escribe aqui cual usaste)
## Ejercicio 2: Tokens y ventana de conexto
| Texto | Caracteres | Tokens | 
|-------|------------|--------| 
| Los estudiantes programan en Java. | | | 
| The students program in Java. | | | 
| desafortunadamente | | | 
Explicacion del paso 4 y 5: 

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos | 
|-------------|----------------|---------------------------| 
| 0 | 100.0% |BiblioTec,BiblioTec, BiblioTec, BiblioTec, BiblioTec| 
| 0.5 |65.3% |BiblioTec, LibroYa, PrestaLibro, BiblioTec, BiblioTec | 
| 1 | 44.5%|BiblioTec, PrestaLibro, PrestaLibro, BiblioTec, LibroYa | 
| 1.8 |32.2% | BiblioTec, PrestaLibro, BiblioTec, PrestaLibro,LibroYa| 

Al subir la temperatura, los nombres se eligen de manera más variada y BiblioTec deja de ser tan dominante.
El simulador nunca inventa un nombre nuevo porque solo puede elegir entre los nombres que ya están en la lista de opciones.

## Ejercicio 4: Prompt vago vs estructurado

| Criterio | Prompt vago | Prompt estructurado | 
|----------|-------------|---------------------| 
| Menciona el objetivo del sistema | No | Sí | 
| Menciona a los usuarios principales | No | Sí | 
| Tiene exactamente 3 funcionalidades | No | Sí | 
| Esta en 3 parrafos | Sí | Sí | 
| Lo usaria en un informe real | No | Sí |
## Ejercicio 5: Anatomia de un prompt
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actúa como desarrollador Java. |
| Instruccion | Crea un programa en Java. |
| Contexto | Para gestionar los productos de una tienda. |
| Ejemplo | Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). |
| Formato | Explica primero la estructura de la clase y luego presenta el codigo Java. |

Nivel 1: La IA creó un programa básico en Java sin especificaciones.

Nivel 2: Se agregó el rol de desarrollador Java, haciendo la respuesta más enfocada.

Nivel 3: Se agregó el contexto de gestionar productos de una tienda.

Nivel 4: Se indicó la clase Producto y sus cuatro atributos: codigo, nombre, precio y stock.

Nivel 5: Se indicó el formato, explicando primero la estructura de la clase y luego mostrando el código Java.


## Ejercicio 6: Del promt basico al profesional
```text 
(pega aqui tu prompt profesional y la mejora que enviaste) ``` 
