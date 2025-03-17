# ✨ **Ejercicio Práctico: Presentación personal**

## **📌 Descripción del Ejercicio**

Este ejercicio te ayudará a practicar comandos básicos en la terminal, creando una estructura de directorios y un documento con información personal.

Es una actividad ideal para principiantes y está diseñada con una estructura clara para que cualquier persona, incluyendo aquellas con **déficit de atención o dislexia**, pueda seguirla sin dificultades.

---

## **🎯 Objetivo**

Aprender a:  
✅ Crear y gestionar directorios y archivos en la terminal.  
✅ Organizar información dentro de un documento de texto.  
✅ Verificar la estructura creada.  
✅ Eliminar directorios de forma segura.

---

## **🛠️ Requisitos Previos**

🔹 Tener acceso a una terminal en Windows (CMD/PowerShell) o en Linux/macOS (Bash).  
🔹 Saber cómo navegar entre directorios y usar comandos básicos.

---

# 🚀 **Consigna del Ejercicio**

### ⚡ **Nivel 1: Crear la estructura inicial**

1️⃣ Abre la terminal y posicionate en el escriptorio utilizando `cd`.  
2️⃣ Crea un directorio llamado **`tu_nombre_presentacion`**.
  <img src="https://i.imgur.com/IEvkbEb.png" alt="Abrir CMD (Símbolo del sistema)" style="border-radius: 1.1rem;">  
3️⃣ Entra en ese directorio.  
4️⃣ Crea un documento de texto llamado **`presentacion.txt`**.  
5️⃣ Crea un directorio adicional llamado **`temporal`**.  
6️⃣ Dentro de `temporal`, crea un archivo llamado **`index.html`**.

---

### ⚡ **Nivel 2: Agregar subdirectorios y contenido**

1️⃣ Dentro de tu directorio `tu_nombre_presentacion`, crea dos subdirectorios:

- `img`
- `css`

2️⃣ Edita el documento `presentacion.txt` y agrega tu información personal, incluyendo:

- Tu nombre
- Tu correo electrónico
- Una breve descripción sobre ti (por qué te interesa aprender esto, qué te motiva, etc.).

---

### ⚡ **Nivel 3: Completar la presentación y verificar la estructura**

1️⃣ Agrega más información en `presentacion.txt`, como:

- Nivel de conocimiento en desarrollo.
- Deportes que practicas.
- Hobbies.
- Actividades sociales.

2️⃣ Verifica que la estructura de directorios esté correcta, listando todo el contenido de `tu_nombre_presentacion`.

3️⃣ (Extra) **Elimina el directorio `temporal`** para practicar cómo borrar directorios en la terminal.

---

## 🎯 **Evaluación**

Tu ejercicio estará completo cuando tu estructura de archivos se vea similar a esta:

```plaintext
tu_nombre_presentacion/
├── presentacion.txt
├── img/
├── css/
```

📌 Si completaste todos los pasos y puedes visualizar esta estructura en la terminal, ¡felicidades! 🚀

---

---

## 🎯 **Resumen de Comandos Claves**

| Comando                                                         | Descripción                          |
| --------------------------------------------------------------- | ------------------------------------ |
| `mkdir nombre`                                                  | Crea un directorio.                  |
| `cd nombre`                                                     | Entra en un directorio.              |
| `touch archivo.txt`                                             | Crea un archivo vacío (Linux/macOS). |
| `New-Item archivo.txt -ItemType File`                           | Crea un archivo vacío (Windows).     |
| `ls -R` (Bash) / `Get-ChildItem -Recurse` (PowerShell)          | Muestra la estructura de archivos.   |
| `rm -r directorio` (Bash) / `Remove-Item -Recurse` (PowerShell) | Borra un directorio y su contenido.  |

---

# 🏆 **¡Desafío completado!**

Si lograste seguir todos los pasos y obtuviste la estructura correcta, ¡felicidades! 🎉🚀

Este ejercicio te ayudará a organizar proyectos y practicar el uso de la terminal de manera eficiente. ¡Sigue explorando y aprendiendo!


||| ✅ **Solución Paso a Paso**
 
## **🟢 Nivel 1: Creación de la estructura inicial**

### **1️⃣ Abre la terminal**

- **Windows:**  
  🔹 Presiona `Win + R`, escribe `cmd` o `powershell` y presiona `Enter`.
- **Mac/Linux:**  
  🔹 Abre `Terminal` desde el buscador o presiona `Cmd + Espacio`, escribe `Terminal` y presiona `Enter`.

### **2️⃣ Crear el directorio `tu_nombre_presentacion`**

🔹 **Linux/macOS (Bash):**

```bash
mkdir tu_nombre_presentacion
cd tu_nombre_presentacion
```

🔹 **Windows (PowerShell):**

```powershell
mkdir tu_nombre_presentacion
cd tu_nombre_presentacion
```

### **3️⃣ Crear el archivo `presentacion.txt`**

🔹 **Linux/macOS (Bash):**

```bash
touch presentacion.txt
```

🔹 **Windows (PowerShell):**

```powershell
New-Item presentacion.txt -ItemType File
```

### **4️⃣ Crear el directorio `temporal` y dentro `index.html`**

🔹 **Linux/macOS (Bash):**

```bash
mkdir temporal
touch temporal/index.html
```

🔹 **Windows (PowerShell):**

```powershell
mkdir temporal
New-Item temporal/index.html -ItemType File
```

---

## **🟢 Nivel 2: Agregar subdirectorios y contenido**

### **1️⃣ Crear los subdirectorios `img` y `css`**

🔹 **Linux/macOS (Bash):**

```bash
mkdir img css
```

🔹 **Windows (PowerShell):**

```powershell
mkdir img, css
```

### **2️⃣ Editar `presentacion.txt` con información personal**

Abre `presentacion.txt` con tu editor de texto favorito y agrega:

```plaintext
Nombre: Mauricio Cox
Correo: mi_correo@email.com
Soy un apasionado del desarrollo y la enseñanza.
Me gusta compartir conocimientos y aprender nuevas tecnologías.
```

💡 **TIP:** Si prefieres hacerlo desde la terminal:  
🔹 **Linux/macOS (Bash):**

```bash
echo "Nombre: Mauricio Cox" > presentacion.txt
```

🔹 **Windows (PowerShell):**

```powershell
echo "Nombre: Mauricio Cox" > presentacion.txt
```

---

## **🟢 Nivel 3: Completar la presentación y verificar la estructura**

### **1️⃣ Agregar más información a `presentacion.txt`**

Abre `presentacion.txt` y agrega:

```plaintext
Conocimientos en desarrollo:
- Ninguno
- Básico
- Intermedio ✔
- Avanzado

Deportes:
- Juego los miércoles y viernes al fútbol con amigos.

Hobbies:
- Me gustan los videojuegos como Mortal Kombat, GTA 5 y Overwatch.

Social:
- En mis ratos libres salgo con amigos.
```

### **2️⃣ Verificar la estructura creada**

🔹 **Linux/macOS (Bash):**

```bash
ls -R
```

🔹 **Windows (PowerShell):**

```powershell
Get-ChildItem -Recurse
```

📌 **Salida esperada:**

```plaintext
tu_nombre_presentacion/
├── presentacion.txt
├── img/
├── css/
├── temporal/
│   ├── index.html
```

---

## **🟢 Extra: Eliminar el directorio `temporal`**

🔹 **Linux/macOS (Bash):**

```bash
rm -r temporal
```

🔹 **Windows (PowerShell):**

```powershell
Remove-Item temporal -Recurse
```
  
|||
