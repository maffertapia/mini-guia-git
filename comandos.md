# Mi manual de Git 🤓☝️ 

### Comandos de Ramas
* `git branch`: Ver mis ramas.
* `git checkout -b`: Crear y saltar una rama.

### Otros
* `git status`: Ver qué está pasando.

## 🗂️ Staging Area (Área de Preparación)
Es el paso intermedio entre tu carpeta de trabajo y el historial oficial. 
Sirve para seleccionar exactamente qué cambios quieres incluir en tu siguiente "foto".

Comando clave:
> git add <archivo>  --> Pone un archivo en la mesa.
> git add .          --> Pone TODO lo que editaste en la mesa.

Ventaja: Te permite separar cambios de diferentes funciones aunque los 
hayas hecho al mismo tiempo. ¡Orden total!

## 📸 Commits (Instantáneas)
Un commit es un punto en la historia de tu proyecto. Es como guardar una 
partida en un videojuego: si algo sale mal después, siempre puedes volver aquí.

Comando clave:
> git commit -m "Mensaje descriptivo"

Regla de oro: Escribe mensajes claros (ej. "Fix: error en el login" en lugar 
de "cambios"). Si el mensaje es bueno, tu "yo del futuro" te lo agradecerá.
