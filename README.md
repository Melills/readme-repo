# 📋 Gestor de tareas

Aplicación de línea de comandos para gestionar una lista de tareas pendientes: añadir, listar, marcar como hechas y borrar.

## Funcionalidades

- Añadir una tarea nueva.
- Listar todas las tareas, con su estado (pendiente/hecha).
- Marcar una tarea como hecha.
- Borrar una tarea.

## Instalación

```bash
git clone https://github.com/<tu-usuario>/gestor-tareas.git
cd gestor-tareas
```

## Uso

```bash
$ gestor-tareas añadir "Comprar pan"
Tarea añadida: Comprar pan

$ gestor-tareas listar
1. [ ] Comprar pan

$ gestor-tareas hecha 1
Tarea 1 marcada como hecha

$ gestor-tareas listar
1. [x] Comprar pan
```

## Tecnologías

- Java 21

## Autor

Melina, curso 2026/2027.