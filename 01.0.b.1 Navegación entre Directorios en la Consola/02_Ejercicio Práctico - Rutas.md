### 🏆 Ejercicio Práctico - Rutas

📌 **Objetivo:**

- Crear una estructura de carpetas y archivos desde la terminal.
- Aprender a moverse entre directorios usando **rutas relativas y absolutas**.
- Practicar la apertura de archivos desde la línea de comandos.

---

## 🚀 **Consigna principal: Crear la estructura de carpetas y archivos**

📌 Con los comandos aprendidos en <a href="" title="Ruta al topico de Comandos básicos">Comandos básicos</a>, crea la siguiente estructura de `carpetas` y `archivos` en tu computadora:



```bash
📂 MiProyecto
 ├── 📂 recursos
 │   ├── 📂 img
 │   └── 📂 css
 ├── 📂 documentos
 │   ├── 📄 notas.txt
 │   └── 📄 tareas.txt
```

---

# Desafío 1: Navegando con Rutas Relativas

**Objetivo:** Aprender a moverte entre directorios usando rutas relativas (`./`, `../`).

## Instrucciones:

1. Estando dentro del directorio `MiProyecto`, accede a la carpeta `documentos`.
2. Dentro de `documentos`, abre el archivo `notas.txt` <a href="https://www.adslzone.net/noticias/windows/como-abrir-bloc-notas-windows/" title="Abrir documentos de texto desde consola" target="_blank">🔍 notepad</a> el Bloc de notas y agrega el título de este desafío Desafío 1: Navegando con Rutas Relativas".
3. Desde `documentos`, regresa al directorio principal (`MiProyecto`).
4. Desde `MiProyecto`, accede a la carpeta `recursos/img`.
5. Regresa nuevamente a `MiProyecto`.

✍️ **Escribe los comandos utilizados** en cada paso.

---

# Desafío 2: Navegando con Rutas Absolutas (opcional)

**Objetivo:** Aprender a utilizar rutas absolutas en la terminal de Windows.

## Instrucciones:

1. Ubícate en cualquier carpeta fuera de `MiProyecto`.
2. Accede directamente a la carpeta `css` dentro de `MiProyecto/recursos` usando su **ruta absoluta**.
3. Desde ahí, vuelve a `MiProyecto` con una **ruta relativa**.
4. Abre el archivo `tareas.txt` con el Bloc de notas usando su **ruta absoluta**.

---

## **Conclusión**

Con estos ejercicios, ahora sabes cómo navegar entre carpetas usando **rutas relativas y absolutas** en la terminal de Windows con los <a href="#" title="Ruta al topico de Comandos básicos">Comandos básicos</a> que aprendimos. Esto es fundamental para trabajar con ``Git``, **manejar proyectos** y **automatizar tareas** de manera eficiente.  
¡Sigue practicando y conviértete en un experto en línea de comandos! 😃🔥

--- 

||| 🚀 Consigna: Crear la estructura de carpetas y archivos

**Crear el directorio principal y entrar en él**
```bash
    mkdir MiProyecto
```    
```bash
    cd MiProyecto
```

**Crear subdirectorios**
```bash
    mkdir recursos
```
```bash
    mkdir documentos
```

**Crear más subdirectorios dentro de "recursos"**
```bash
    mkdir recursos/img
```
```bash
    mkdir recursos/css
```


**Crear archivos en "documentos" (comando gitbash / linux)**
```bash
    cd documentos
```
```bash
    touch notas.txt
```
```bash
    touch tareas.txt
```
```bash
    cd ..
```

**Windows Powershel (Windows)**
```bash
    New-Item notas.txt -ItemType File
```
```bash
    New-Item tareas.txt -ItemType File
```

✅ **Verifica que todo esté correcto** con:

```bash
    ls -R  # (Windows: usa "dir /s")
```
```bash
    # Para visualizar directorios y documentos
    ls  # (Windows: usa "dir")
```
|||

---

||| Desafío 1: Navegando con Rutas Relativas

  ```bash
  # 1. Entrar en "documentos"
  cd documentos
  ```
  
  ```bash
  # 2. Abrir "notas.txt" con el Bloc de notas y escribir el título del desafío
  notepad notas.txt
  ```
  ```bash
  # 3. Volver a "MiProyecto"
  cd ..
  ```
  ```bash
  # 4. Entrar en "recursos/img"
  cd recursos/img
  ```
  ```bash
  # 5. Volver nuevamente a "MiProyecto"
  cd ../..
  ```
|||

---

||| Desafío 2: Navegando con Rutas Absolutas _(opcional)_


```bash
# 1. Desde cualquier ubicación, acceder a "css" con ruta absoluta*
cd C:\Users\TuUsuario\Ruta\Hasta\MiProyecto\recursos\css

# 2. Volver a "MiProyecto" con ruta relativa
cd ../..

# 3. Abrir "tareas.txt" con el Bloc de notas usando su ruta absoluta
notepad C:\Users\TuUsuario\Ruta\Hasta\MiProyecto\documentos\tareas.txt
```