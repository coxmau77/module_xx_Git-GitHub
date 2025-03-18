### 🔗 Conectar Repositorio Local

Si ya tienes un proyecto en tu computadora y quieres **subirlo a GitHub**, abre tu terminal en la carpeta del proyecto y ejecuta estos comandos:

```bash
git init  # Inicia un repositorio local si aún no lo hiciste
```

```bash
git add .  # Agrega todos los archivos al área de staging
```

```bash
git commit -m "Mi primer commit"  # Guarda los cambios en el historial de Git
```

Ahora, conecta tu proyecto con el repositorio remoto en GitHub:

```bash
git remote add origin https://github.com/TU-USUARIO/mi-primer-repo.git
```

⚠️ **Recuerda reemplazar `TU-USUARIO` por tu nombre de usuario en GitHub**.

Finalmente, si ya hiciste el "commit" sube tu código a GitHub con:

```bash
git push -u origin main
```

<img
      src="https://i.imgur.com/tmCrG6W.png"
      alt="Tu código ahora está en GitHub"
      style="border-radius: 1.1rem; margin: 0 auto"
    />

🎉 ¡Boom! Tu código ahora está en GitHub. Puedes verlo entrando a tu repositorio en GitHub.
