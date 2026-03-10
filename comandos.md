# Mi manual de Git 🤓☝️ 

### Comandos de Ramas
* `git branch`: Ver mis ramas.
* `git checkout -b`: Crear y saltar una rama.

### Otros
* `git status`: Ver qué está pasando.

---

## 🎭 El Ciclo de Vida de Git: La Analogía del Teatro

Para entender cómo guardamos cambios, imagina que tu proyecto es una obra de teatro:

1. **Working Directory (El Ensayo 🔴):** Es tu carpeta local. Aquí haces cambios, borras líneas y pruebas cosas. Git ve los cambios (en rojo con `git status`), pero aún no son "oficiales".

2. **Staging Area (El Backstage 🟢):** Cuando usas `git add`, mueves tus archivos tras bambalinas. Ya están listos y maquillados para salir a escena. Aparecen en verde con `git status`.

3. **Commit (La Función 📸):** Al ejecutar `git commit -m "mensaje"`, se abre el telón y tomamos una foto de la escena. Este momento queda guardado para siempre en el historial.

### Comandos clave para este flujo:
* `git status`: Para ver quién está ensayando y quién está en backstage.
* `git add <archivo>`: Para mandar al actor al escenario.
* `git commit -m "descripción"`: Para capturar el momento oficial.

Regla de oro: Escribe mensajes claros (ej. "Fix: error en el login" en lugar 
de "cambios"). Si el mensaje es bueno, tu "yo del futuro" te lo agradecerá.

---
## 📚 Recursos Adicionales

Para profundizar en el dominio de estas herramientas, recomiendo consultar:

* [Documentación Oficial de Git](https://git-scm.com/doc): El manual definitivo para entender cada comando.
* [Cheat Sheet de GitHub](https://education.github.com/git-cheat-sheet-education.pdf): Una hoja de trucos rápida para los comandos más usados.
* [Guía de Markdown de GitHub](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax): Para que tus archivos `.md` se vean increíbles.
* [Oh My Git!](https://ohmygit.org/): Un juego interactivo para aprender Git de forma visual.
