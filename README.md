# Checkpoint: Script SQL de Ingeniería de Datos (Ventas_Tech_DB)

## 📌 Descripción del Proyecto
Este repositorio contiene el script backend en SQL para la creación, normalización en Tercera Forma Normal (3NF), carga de datos y validación de la base de datos relacional Ventas_Tech_DB para una empresa de retail de tecnología.

## 🛠️ Entorno de Trabajo
- *Motor de Base de Datos:* SQL Server
- *Herramienta:* SQL Server Management Studio (SSMS)

## 📂 Estructura del Script (ventas_tech_db.sql)
El archivo está dividido en cuatro secciones claramente separadas por comentarios:
1. *DROP TABLES:* Eliminación de tablas en orden inverso a sus dependencias para asegurar que el script sea repetible sin errores.
2. *CREATE TABLES:* Creación de las tablas de dimensiones (categorias, clientes, productos) y la tabla de hechos (ventas), aplicando claves primarias (PK), claves foráneas (FK), restricciones y tipos de datos precisos (DECIMAL(10,2) para los montos).
3. *INSERT DATA:* Inserción de los 25 registros totales distribuidos en las tablas.
4. *VALIDACIÓN:* Consultas finales de comprobación (SELECT) para verificar el correcto almacenamiento de los datos.

## 🚀 Instrucciones de Ejecución
1. Abrir *SQL Server Management Studio (SSMS)*.
2. Crear y seleccionar la base de datos ejecutando:
   ```sql
   CREATE DATABASE Ventas_Tech_DB;
   USE Ventas_Tech_DB;
