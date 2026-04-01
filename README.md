# 🧮 Calculadora-grupal-en-C-Sharp
Este es un trabajo grupal de segundo ciclo universitario hecho para practicar la colaboración en Github.

🚀 Guía de Inicio (Para el equipo)
1. Clonar el proyecto
Abran su terminal en Visual Studio Code y ejecuten:

git clone URL-del-repositorio

2. Cómo abrir el código correctamente
Git descarga los archivos, pero no los abre solo. Para trabajar bien:

En Visual Studio seleccionen "Abrir carpeta" o "Abrir Proyecto/Solución" y
seleccionen la carpeta con el nombre del trabajo "Calculadora-grupal-en-C-Sharp".

Para que el comando dotnet run funcione, la terminal debe estar posicionada en la carpeta del proyecto

Nota: La ruta correcta es algo redundante, es algo así: C:\Users\obeds\Calculadora-grupal-en-C-Sharp\CalculadoraGrupal\CalculadoraGrupal

(Si al escribir dotnet run sale nuestro "Hola Mundo", estás en el lugar correcto).

🛠️ Cómo subir tu parte (Uso de Ramas)

Para no romper el código de los demás, no trabajen sobre el main. Sigan este orden de comandos:

1. Sincronizar: Bajen lo último que se haya subido.

git checkout main (regresar al presente por si estaban probando cosas V:, ejecutarlo no rompe nada)
git pull origin main (Descarga los últimos cambios que hayan subido los demás).

2. Crear su espacio (Rama): Sustituyan por sus datos.

git checkout -b ApellidoNombre_OPERACION (Crea un "universo paralelo" con tu nombre para que trabajes sin miedo a romper lo de otros).

3. Guardar cambios: Una vez que su código funcione localmente.

git add .
git commit -m "Agregada operacion: ApellidoNombre_OPERACION" (Le pone una etiqueta o "nombre" a tu avance).

4. Subir a la nube:

git push origin ApellidoNombre_OPERACION (Envía tu rama personal a internet para que el grupo la vea).

📢 ¡AVISO IMPORTANTE!
Una vez que hagan el push, avisen por el grupo de WhatsApp para revisar el código y hacer el Merge (unión) en la web de GitHub. ¡No intenten unirlo ustedes solos desde la consola!
