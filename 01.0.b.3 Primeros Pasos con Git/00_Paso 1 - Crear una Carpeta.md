### 🏗 Paso 1: Crear una Carpeta

Antes de usar Git, necesitamos un lugar donde trabajar. Esta carpeta será nuestro <a href="https://www.linkedin.com/pulse/conociendo-git-y-creando-mi-primer-repositorio-local-alarc%C3%B3n-acurero/"
      title="qué es un repositorio local"
      target="_blank">**repositorio local**</a>, donde almacenaremos y gestionaremos los archivos del proyecto con Git.

- **Si usas la terminal**, utiliza los comandos aprendidos:

```bash
mkdir mi-primer-repo
```

```bash
cd mi-primer-repo
```

- **Si prefieres hacerlo manualmente**, crea una carpeta llamada **mi-primer-repo** en tu computadora y luego accede a ella desde la terminal como has aprendido en <a href="#" title="Ruta a Navegación entre Directorios en la Consola" target="_self">Navegación entre Directorios en la Consola</a>.

📌 **Recuerda:** Un **repositorio local** es simplemente una carpeta en tu computadora donde Git rastrea cambios y gestiona versiones de los archivos.

## `Repositorio local` vs `Repositorio remoto`:

| 📌 **Tipo de Repositorio** | 🖥️ **Repositorio Local**                                                       | ☁️ **Repositorio Remoto** (GitHub)                                                     |
| -------------------------- | ------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- |
| **¿Qué es?**               | Una carpeta en tu computadora donde Git rastrea cambios en los archivos.       | Un repositorio almacenado en GitHub para compartir y respaldar tu proyecto en la nube. |
| **¿Dónde se encuentra?**   | En tu PC, dentro de una carpeta específica.                                    | En la web, en una plataforma como GitHub.                                              |
| **¿Cómo se usa?**          | Trabajas con Git en la terminal para gestionar versiones y cambios localmente. | Sirve para colaborar con otros y hacer copias de seguridad del código.                 |
| **Comandos clave**         | `git init`, `git add`, `git commit`                                            | `git remote add origin`, `git push`, `git pull`                                        |
| **Ejemplo**                | Crear un proyecto y manejar versiones sin conexión.                            | Subir tu código a GitHub para compartirlo o colaborar.                                 |

💡 **Importante:**  
Para conectar un repositorio **local** con un **remoto** en GitHub, usamos `git remote add origin <URL>` y `git push` para enviar los cambios que veremos más adelante. 🚀
