### 📌 Paso 4: Registrar Cambios con `add` y `commit`

## En Git, _guardar cambios es un proceso de dos pasos_:

1. **Añadir archivos al `staging area`** _(prepararlos para ser guardados)_:

    - **Agrega un documento en particular:**
    ```bash
    git add index.html
    ```

    - **Agrega todos los cambios realizados:**
    ```bash
    git add .
    ```

2. **Guardar los cambios con un commit** _(como tomar una foto de esta versión del proyecto)_:

    ```bash
    git commit -m "Primer commit: Agregué index.html"
    ```

💡 **¿Qué pasó aquí?**

- `git add` le dice a Git qué archivos queremos guardar en el próximo commit.
- `git commit -m "mensaje"` guarda oficialmente los cambios con una descripción.


Ahora si, verás que Git ha guardado tu primer cambio. Utiliza el comando `git status` y `git log --oneline` para visualizar el registro que va haciendo git de tus cambios.

<img src="https://i.imgur.com/DREZ1wC.png" alt="Utiliza el comando git add + git status" style="border-radius: 1.1rem;">

# 🎯 **¡Lo lograste, Acabas de registrar la primera versión de tu proyecto! 🎉 y Aprendiste a:** 

✅ Crear una carpeta y convertirla en un repositorio con `git init`  
✅ Agregar archivos y verificar su estado con `git status`  
✅ Guardar cambios con `git add` y `git commit`