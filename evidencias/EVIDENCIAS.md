# Archivo evidencias: Protección de la rama main

Se ha configurado las siguientes reglas:

- Pull Request antes de hacer merge
- No se permiten commits directos a la rama main
- Los cambios son revisados previamente

## ¿Por qué es recomendable proteger la rama principal?

Proteger esta rama es recomendable a nivel real porque:

- Evita que se introduzcan errores en producción
- Obliga a revisar los cambios antes de integrarlos
- Facilita el trabajo en equipo
- Mantiene un historial de codigo limpio y controlado
- Reduce riesgos en proyectos con muchos desarrolladores

Esto garantiza: 

- Mayor estabilidad
- Seguridad
- Calidad de código

# Archivo evidencias: Configuración archivo .gitignore

Se ha configurado el archivo .gitignore, donde:

- Se ignoran TODOS los archivos .log (independientemente del directorio) para no ensuciar
el historial de registros temporales

- Se ignoran los archivos __pychache__/ para evitar subir archivos temporales de Python.
En un proyecto grande, suelen ser muchos



