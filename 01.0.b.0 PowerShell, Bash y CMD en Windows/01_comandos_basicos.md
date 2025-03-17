# 🖥️ **Comandos básicos de la terminal en Windows y macOS**

Esta guía práctica te enseñará los comandos esenciales para moverte entre directorios, crear, eliminar documentos y gestionar tu espacio de trabajo en la terminal de Windows (PowerShell / CMD) y macOS (Bash).

<!----
    Comentarios
<!---->

+++ Carpeta o Directorio? 
 
En el contexto de sistemas de archivos, los términos **"directorio"** y **"carpeta"** se refieren a lo mismo. Ambos representan una estructura que permite organizar y almacenar archivos dentro de un sistema operativo. Mientras que "carpeta" es un término más común en entornos gráficos como Windows, "directorio" se usa con más frecuencia en sistemas operativos basados en UNIX, como Linux y macOS. Sin importar el término que utilicemos, su función es la misma: organizar archivos y otros directorios dentro de una jerarquía estructurada.
 
+++

## 📂 **1. Listar documentos en el directorio actual: `ls` (List)**

**Uso:** Ver el contenido del directorio donde estás ubicado.

🔹 **Comando:**

```bash
ls
```

🔹 **Ejemplo de salida:**

```bash
Documentos  Imágenes  Música  Proyectos
```

📌 **Nota:** En CMD de Windows, el equivalente es `dir`.

```cmd
dir
```

---

## 📁 **2. Cambiar de directorio: `cd` (Change Directory)**

**Uso:** Navegar entre directorios.

🔹 **Comando:**

```bash
cd <nombre-del-directorio>
```

🔹 **Ejemplo:**

```bash
cd Documentos    # En macOS/Linux
cd C:\Users\Mauricio\Documents   # En Windows (PowerShell)
```

Si deseas regresar un nivel atrás:

```bash
cd ..
```

Si quieres ir directamente a la raíz del sistema:

```bash
cd /
```

---

## 🏗️ **3. Crear un directorio: `mkdir` (Make Directory)**

**Uso:** Crear un nuevo directorio en la ubicación actual.

🔹 **Comando:**

```bash
mkdir MiProyecto
```

![Crea un nuevo directorio en el sistema](https://i.imgur.com/I4fSU40.png)

🔹 **Verificación:** Para confirmar que el directorio fue creado, usa `ls` o `dir` (en CMD).

```bash
ls
```

🔹 **Ejemplo de salida esperada:**

```bash
Documentos  Imágenes  Música  Proyectos  MiProyecto
```

---

## 📜 **4. Crear un documento vacío**

**Uso:** Crear un documento nuevo sin contenido.

🔹 **En macOS/Linux (Bash):**

```bash
touch miDocumento.txt
```

![En Linux/macOS (gitBash)](https://i.imgur.com/cBLNn3i.png)

🔹 **En Windows (PowerShell):**

```powershell
New-Item miDocumento.txt -ItemType File
```

<img src="https://i.imgur.com/MZmBxaF.png" alt="Crear un documento vacío miDocumento.txt" style="border-radius: 1.1rem;">

🔹 **En CMD (Windows clásico):**

```cmd
type nul > miDocumento.txt
```

📌 **¿Cuál es la diferencia?**

- `touch` funciona en macOS y Linux.
- `New-Item` es la alternativa en PowerShell.
- `type nul > documento.txt` funciona en CMD.
- Si tienes Git Bash en Windows, `touch` también funcionará.

![Crea un documento vacío en PowerShell](https://i.imgur.com/odUYyqH.png)

---

## 🗑️ **5. Eliminar un documento: `rm` (Remove)**

**Uso:** Borrar un documento de la terminal.

🔹 **Comando:**

```bash
rm miDocumento.txt
```

⚠️ **Precaución:** No hay papelera de reciclaje, el archivo se elimina permanentemente.

🔹 **Alternativa en PowerShell:**

```powershell
Remove-Item miDocumento.txt
```

🔹 **Alternativa en CMD:**

```cmd
del miDocumento.txt
```

---

## ❌ **6. Eliminar un directorio vacío: `rmdir` (Remove Directory)**

**Uso:** Borrar un directorio solo si no tiene documentos dentro.

🔹 **Comando:**

```bash
rmdir MiProyecto
```

🔹 **Si el directorio tiene contenido:**

```bash
rm -r MiProyecto   # En macOS/Linux
Remove-Item -Recurse -Force MiProyecto   # En PowerShell
rd /s /q MiProyecto   # En CMD
```

📌 **Consejo:** Usa `ls` antes de eliminar para verificar qué hay dentro.

---

## 📍 **7. Mostrar la ruta del directorio actual: `pwd` (Print Working Directory)**

**Uso:** Saber en qué directorio estás ubicado. El comando `pwd` (**Print Working Directory**) muestra la ruta completa del directorio en el que te encuentras actualmente.

![Muestra la ruta del directorio actual](https://i.imgur.com/K2i1xYn.png)

🔹 **Comando:**

```bash
pwd
```

🔹 **Ejemplo de salida esperada:**

```bash
/home/mauricio/Documentos   # En macOS/Linux
C:\Users\Mauricio\Documents   # En Windows (PowerShell)
```

📌 **En CMD, usa `cd` sin argumentos:**

```cmd
cd
```

---

## 📌 **Resumen de comandos**

| Comando                      | Descripción                            |
| ---------------------------- | -------------------------------------- |
| **`ls`**                     | Lista documentos y subdirectorios.     |
| **`cd <directorio>`**        | Cambia al directorio especificado.     |
| **`mkdir <nombre>`**         | Crea un nuevo directorio.              |
| **`touch <archivo>`**        | Crea un documento vacío (Linux/macOS). |
| **`New-Item <archivo>`**     | Crea un documento vacío (PowerShell).  |
| **`type nul > archivo.txt`** | Crea un documento vacío en CMD.        |
| **`rm <archivo>`**           | Elimina un documento.                  |
| **`rmdir <directorio>`**     | Elimina un directorio vacío.           |
| **`rm -r <directorio>`**     | Elimina un directorio con contenido.   |
| **`pwd`**                    | Muestra la ruta del directorio actual. |
| **`dir`**                    | Lista documentos en CMD de Windows.    |

---

## 🚀 **Conclusión**

Con estos comandos podrás moverte en la terminal de forma eficiente. Recuerda que cada sistema tiene pequeñas diferencias, pero la lógica es la misma en todos.

🔹 **Practica cada comando para familiarizarte con ellos.**  
🔹 **Utiliza `pwd` constantemente para saber en qué directorio estás antes de ejecutar comandos.**  
🔹 **Ten cuidado con los comandos `rm` y `rmdir`, ya que los documentos eliminados no se pueden recuperar.**

Si tienes dudas, usa `man <comando>` en macOS/Linux o `Get-Help <comando>` en PowerShell para obtener más información.
