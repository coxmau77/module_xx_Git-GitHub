### .gitignore

Hay archivos que **no quieres subir a GitHub** porque son innecesarios o contienen información sensible (como contraseñas o datos privados de tu sistema).

💡 **Ejemplo de archivos que deberías ignorar:**

- Archivos de configuración (`.env`, `.DS_Store`).
- Dependencias (`node_modules/`).
- Archivos generados automáticamente (`.log`, `dist/`).
- Cualquier `documento` o `directorio` que no quieras que se comparta con gitHub.

Para evitar que estos archivos se suban, crea un archivo llamado `.gitignore` y agrégales una lista así:

```bash
# Ignorar la carpeta de dependencias
node_modules/

# Ignorar archivos de configuración
.env

# Ignorar archivos temporales del sistema
.DS_Store

# Ignorar el documentos privados
documento-privado.html
```

<img
      src="https://i.imgur.com/veV22VC.png"
      alt="Crear nuevo repositorio"
      style="border-radius: 1.1rem; margin: 0 auto"
    />

👉 **Tip:** Puedes encontrar ejemplos de `.gitignore` específicos para cada tecnología en [gitignore.io](https://www.toptal.com/developers/gitignore).

<img
      src="https://i.imgur.com/mSpbKl9.png"
      alt="Crear nuevo repositorio"
      style="border-radius: 1.1rem; margin: 0 auto"
    />
