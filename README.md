# Rizo_Arias-post1-u4

# TaskManager - Post-Contenido 1 (Unidad 4)

Aplicación Android en Kotlin con **Room Database**, migración de esquema 1 → 2 y prueba de migración.


## 📸 Evidencias

<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/b99e8817-2218-4753-bdc1-00ee32072f91" />
 Lista de tareas (versión 1) 
 
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/51f75c65-b903-4e42-ac90-d8fdbf7a2b7f" />
Archivo 2.json del esquema 
 
 [captura_datos_migrados.png](evidencias/captura_datos_migrados.png)  App después de la migración 
 
 [captura_test_migration.png](evidencias/captura_test_migration.png)  Test de migración passing 

## 🛠️ Arquitectura
- **MVVM** + Room + Flow + StateFlow
- Migración segura 1 → 2 (agrega columna `priority`)
- Prueba con `MigrationTestHelper`

