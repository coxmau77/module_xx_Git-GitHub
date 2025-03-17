### 👤 Paso 3: Configurar identidad

Git necesita saber quién eres para registrar los cambios en tu código con tu nombre y correo electrónico. 

Esto es clave cuando colaboras en proyectos, ya que cada cambio quedará registrado con tu firma digital.

Ejecuta estos dos comandos en la terminal (sustituyendo con tu nombre y correo):

```bash
git config --global user.name "Tu Nombre"
```
```bash
git config --global user.email "tuemail@example.com"
```

Para verificar que todo quedó bien, usa:

```bash
git config --global --list
```

Deberías ver algo como:

```
user.name=Tu Nombre
user.email=tuemail@example.com
```

![--global --list](https://i.imgur.com/BpbVfh1.png)

¡Listo! 🎯 Ahora Git sabe quién eres y estás listo para comenzar a trabajar con repositorios.

---

### 🚀 **Conclusión**

En este primer paso, instalaste Git y configuraste tu identidad. Puede parecer un detalle técnico, pero en realidad, es el comienzo de una nueva forma de trabajar con código: más ordenada, más segura y lista para colaborar con otros.

Ahora que tienes las bases, en el siguiente paso aprenderás a crear tu primer repositorio local y empezar a registrar cambios como un profesional. ¡Sigamos avanzando! 💪😃
