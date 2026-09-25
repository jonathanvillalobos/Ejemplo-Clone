# Recomendaciones de Mejora para el Proyecto

A continuación se presentan tres recomendaciones clave para mejorar la estructura, funcionalidad y usabilidad del **Organizador Personal**:

1. **Implementar persistencia de datos con SQLite:**
   Actualmente los datos se manejan en memoria principal. Se recomienda integrar una base de datos liviana como `sqlite3` para garantizar que las tareas y notas registradas se guarden permanentemente al cerrar la aplicación.

2. **Añadir un sistema de notificaciones y recordatorios:**
   Incorporar alertas visuales o sonoras en la interfaz cuando una tarea esté próxima a vencer, mejorando la efectividad de la herramienta como organizador diario.

3. **Mejorar la interfaz gráfica (GUI) con un diseño responsivo:**
   Diseñar la interfaz utilizando layouts dinámicos (en PyQt / PySide) y un archivo de estilos personalizado (QSS) para asegurar que los paneles de notas y tareas se adapten correctamente a diferentes tamaños de pantalla.
   