
# Todo Categories App (Flutter + Dart)

## Descripción general
Aplicación móvil construida con **Flutter** que permite gestionar listas de tareas (**Todos**) organizadas por **categorías**. Es una aplicación móvil construida con Fluter que permite gestionar listas de tareas (Todos) organizadas por categorías. Permite crear categorías y tareas con estado (**pendiente**/**completado**) y fecha objetivo. 
- Cada categoría muestra un resumen de tareas **totales**, **pendientes** y **completadas**. 
- Dentro de una categoría puedes **crear**, **editar**, **completar** y **eliminar** tareas, además de **filtrar** por estado.


---

## Objetivos del proyecto
- Implementar operaciones **CRUD** para categorías y Todos.
- Manejar estado con **provider** y `ChangeNotifier`.
- Mostrar resúmenes y filtros por estado en la UI.
- Documentar el proyecto y su arquitectura de forma clara.


---
## Como se ejecuta la aplicacion

## Requisitos
- Tener **Flutter** instalado (version estable: 3.x).
- Dispositivo/emulador Android o iOS configurado, o **Chrome** para ejecucion web.

## Comandos principales:
- flutter pub get
- flutter run


## Funcionalidades principales
- **Categorías**
  - Crear, editar y eliminar categorías.
  - Resumen por categoría: Total, Pendientes, Completados.
- **Todos (tareas)**
  - Crear, editar, completar y eliminar.
  - Campos: descripción (`title`), estado (`isDone`), fecha objetivo (`dueDate`).
- **Filtros**
  - Ver Todos: **Todos / Pendientes / Completados**.


---

## Capturas de pantalla
Capturas de pantalla: docs/screenshots/
- Pantalla principal con categorías creadas.
- Pantalla detalle de categoría mostrando tareas.
- Diálogo para crear/editar categoría.
- Diálogo para crear/editar Todo.
- Pantalla detalle con filtros aplicados.


---

## Créditos
Autor: MICHAEL RAMIREZ TORRES
Proyecto académico: Aplicación móvil de Todos con categorías (Flutter + Dart).
