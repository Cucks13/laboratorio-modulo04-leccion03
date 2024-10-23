# Proyecto de Base de Datos con Python y SQL

## Descripción General

Durante el desarrollo de este proyecto, he tenido muchos problemas relacionados con la biblioteca **psycopg2** en Python. Más concretamente, he enfrentado dificultades con el reconocimiento de operaciones clave como `commit`, `rollback`, `execute`, y `executemany`. A pesar de seguir los procedimientos habituales para gestionar transacciones en bases de datos, la interacción con **psycopg2** ha sido un completo quebradero de cabeza.

### Problemas Encontrados

1. **Commit y Rollback**: Los comandos `commit` y `rollback` no parecían tener el efecto esperado. A pesar de realizar cambios y tratar de confirmar o deshacer transacciones, los resultados no se reflejaban correctamente en la base de datos.
   
2. **Execute y Executemany**: Las funciones `execute` y `executemany` tampoco funcionaban como esperaba. A menudo, las consultas no se ejecutaban o fallaban sin razón aparente, aunque el código parecía correcto. Sospecho que el problema puede deberse más al comportamiento de la biblioteca **psycopg2** que a una falta de comprensión por mi parte sobre cómo funcionan estas operaciones.

### Solución Temporal

Para poder avanzar y entregar algo funcional, decidí descargar un script de un compañero (Alex). Este script realizaba prácticamente las mismas operaciones que yo intentaba implementar, pero al ejecutar todo el código con `RunAll`, este funcionaba correctamente. Esto me permitió trabajar en las consultas SQL y lograr que las operaciones se ejecutaran, aunque no logré implementar la parte de visualización por falta de tiempo.

### Próximos Pasos

1. Investigar más a fondo el comportamiento de **psycopg2** para entender por qué mis implementaciones iniciales no funcionaban como esperaba.
2. Implementar la parte de visualización, que no pude completar en esta entrega.
3. Revisar mis intentos previos para compararlos con el script funcional y encontrar las diferencias clave.

### Conclusión

A pesar de los problemas enfrentados con **psycopg2**, he podido completar las consultas SQL usando el script de Alex como referencia, el cual hacía cosas muy similares a lo que intentaba hacer por mi cuenta. Aunque me ha sido frustrante, he aprendido mucho sobre las dificultades que pueden surgir con la interacción entre Python y bases de datos. 

