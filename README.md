Desarrollar un proyecto gestionado por Databricks Asset Bundles (DAB)
que automatice el siguiente flujo de datos "End-to-End":
1. Un proceso orquestado por un Job.
2. El Job se dispara automáticamente al detectar un nuevo archivo en
un Volumen.
3. El flujo consta de dos pasos:
a. Una task de ingesta utilizando una notebook para crear una
tabla.
b. Unataskdepipelineparacrearunavistamaterializada.
4. Gestión de notificaciones por correo según el entorno.
