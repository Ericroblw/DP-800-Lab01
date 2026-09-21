# Laboratorio 01 - Create and maintain database objects

**Autor:** Eric Emmanuel Ramírez Duanca[cite: 1]

## Entorno de Desarrollo
* **Motor de base de datos:** SQL Server 2025 (o posterior, requerido para el tipo de dato JSON)
* **Cliente gráfico:** SQL Server Management Studio (SSMS)

## Instrucciones para reproducir el trabajo

Para preparar el entorno y ejecutar los ejercicios, sigue estos pasos desde SSMS:
1. **Creación de la base de datos:** Conéctate a tu instancia local de SQL Server. Abre una "Nueva Consulta" (New Query) y ejecuta el script inicial para crear la base de datos `EcommerceDB`.
2. **Conexión correcta:** Asegúrate de incluir y ejecutar `USE EcommerceDB;` al inicio de cada script, o selecciona explícitamente `EcommerceDB` en el menú desplegable superior para evitar ejecutar los comandos en la base de datos `master`.
3. **Ejecución de los scripts:** Ejecuta paso a paso los bloques de código SQL (T-SQL) documentados en la práctica. Esto creará la estructura de las tablas principales, aplicará las restricciones (CHECK, Foreign Keys), configurará el control de versiones con la tabla temporal, añadirá los metadatos JSON y finalmente establecerá las particiones y secuencias.

## Estructura del repositorio

```text
Laboratorio-SQL/            <-- (Directorio raíz)
├── README.md               <-- (Este archivo)         
 ├── img/                <-- (Carpeta con las capturas de pantalla de SSMS)
 └── tu_laboratorio.pdf  <-- (Documentación paso a paso con evidencias)
