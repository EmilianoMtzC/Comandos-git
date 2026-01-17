# Atención esto fue hecho para mi novia jajajajaja, no critiquen.

---

# ¡Hola mi amor!

Aquí te dejo los comandos que estarás utilizando para **Git**. Trata de aprendértelos, ¡te amo!

---

## ⚙️ CONFIGURACIÓN DE GIT

*(Esto normalmente lo utilizarás cuando configures una nueva compu)*

* **0.1. `git config --global user.name "tu-nombre-miamor"`
* **USO:** Se utiliza una vez para configurar tu nombre de usuario de Git (es obligatorio).


* **0.2. `git config --global user.email "tu-email-miamor"`
* **USO:** Al igual que el anterior, pero con tu correo electrónico.



---

## 📁 CONFIGURACIÓN DE REPOSITORIO

*(Esto se utiliza cada que quieras iniciar un nuevo repositorio)*

> **P.D.** Tienes que irte a la carpeta del proyecto primero.
> *Ejemplo:* `cd Documentos/carpeta-de-miamorito/`

* **1. `git init`
* **USO:** Inicializa un repositorio local (todavía no está en GitHub).



---

## 🚀 SUBIR TUS COSITAS

*(Esto es lo que más utilizarás y va en el orden escrito)*

1. **`git add .`** ó **`git add "tu-documento"`**
* **USO:** Para cargar tus nuevos documentos o los que acabas de modificar.
* `git add .` añade **todos** los documentos.
* `git add "tu-documento"` añade **un solo** documento específico.


2. **`git commit -m "Mensaje concreto"`**
* **USO:** Una vez cargados con el *add*, haces el *commit*. Es necesario para que Git te permita subir archivos. El mensaje debe ser concreto.
* *Ejemplo:* `"Implementacion método mostrarInfo() en Clase Licor"`



---

## ⚠️ ¡ATENCIÓN!

**Antes de seguir, es necesario lo siguiente:**

Normalmente, cuando empiezas desde cero un repositorio, no tienes un respaldo en GitHub. Primero ve a [github.com](https://github.com) y crea un repositorio con el nombre que quieras. Después, ingresa estos comandos:

* **3.1. `git remote add origin https://github.com/TU-USUARIO/TU-REPO.git`
* **USO:** Conecta tu carpeta local con el repositorio en la nube (GitHub).


* **3.2. `git branch -M main`
* **USO:** Comando necesario para establecer "main" como el nombre de tu rama principal.



---

## ✅ PARA FINALIZAR

* **4. `git push -u origin main`
* **USO:** Sube todos tus cambios. **SOLO SE HACE 1 VEZ**. El `-u origin main` configura la ruta por defecto para que no tengas que escribir tanto después.


* **4.1. `git push`
* **USO:** Después de haber hecho el paso anterior una vez, de ahora en adelante solo tendrás que escribir esto para subir tus cambios.



---

