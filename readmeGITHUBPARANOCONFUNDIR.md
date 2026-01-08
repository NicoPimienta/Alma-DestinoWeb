# AlmaDestinoWeb


🧠 ABC de Git – Guía rápida de uso

Repositorio:
👉 https://github.com/NicoPimienta/Alma-DestinoWeb

Este proyecto usa Git + GitHub para control de versiones.
Seguir este flujo evita conflictos, pérdida de archivos y dolores de cabeza innecesarios.

🔁 Flujo básico (el que se usa siempre)
1️⃣ Ver el estado del proyecto

Antes de tocar nada:

git status


Sirve para saber:

qué archivos cambiaste

si estás en la rama correcta

si hay algo pendiente

2️⃣ Traer lo último del repositorio

Siempre antes de empezar a trabajar:

git pull


Esto sincroniza tu carpeta local con GitHub y evita conflictos después.

3️⃣ Trabajar normalmente

Editá los archivos necesarios (HTML, CSS, JS, etc).
Guardá y verificá que el sitio funcione antes de seguir.

4️⃣ Revisar cambios
git status


Confirmá que solo estén los archivos que realmente querés subir.

5️⃣ Agregar archivos al commit

Todo junto:

git add .


O de forma puntual:

git add index.html css/style.css

6️⃣ Crear el commit

Usá mensajes claros y concretos:

git commit -m "Agrego nueva sección y formulario"


Regla simple: que el mensaje se entienda dentro de 6 meses.

7️⃣ Subir los cambios a GitHub
git push


Si falla:

leé el error

generalmente se soluciona con otro git pull y repetir

🔂 Resumen mental del loop
git pull
→ editar archivos
→ probar que funcione
→ git add
→ git commit
→ git push


Siempre en ese orden.

🚫 Buenas prácticas (importante)

❌ No trabajar desde ZIP

❌ No usar git push --force sin saber exactamente por qué

❌ No commitear cosas rotas “para después arreglar”

❌ No ignorar mensajes de error

🧭 Comando clave cuando hay dudas
git status


Ese comando te dice siempre dónde estás parado.

📌 Nota final

Git no está para complicarte la vida.
Está para que no pierdas trabajo, puedas volver atrás y trabajes tranquilo.

Si este flujo se respeta, Git deja de ser un problema y pasa a ser una herramienta invisible.

Si después querés, en otro README o sección podemos sumar:

flujo con ramas (main / backup / staging)

checklist antes de deploy

notas específicas para Vercel

Pero con esto ya tenés la base sólida.