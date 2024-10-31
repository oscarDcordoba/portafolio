# portafolio de oscar david cordoba garcia...
mi informacion de contactos,habilidades y proyectos realizados.
git stash branch guardar una rama temporal
pasos para clonar y desplegar mi portafolio
# PASOS PARA CLONAR Y DESPLEGAR MI PORTAFOLIO:fa-road:

###1) Crear un Repositorio en GitHub.:fa-folder-open-o:
* Inicia sesión en tu cuenta de GitHub.
* Haz clic en el botón "New" para crear un nuevo repositorio.
* Dale un nombre a tu repositorio (por ejemplo, mi-portafolio).
* Elige si quieres que sea público o privado.
* Haz clic en "Create repository".

###2) Clonar el Repositorio.:fa-laptop::fa-exchange:
* Abre la terminal (o el símbolo del sistema).
* Navega hasta el directorio donde quieres clonar el repositorio.
* Usa el siguiente comando para clonar tu repositorio (sustituye tu-usuario y mi-portafolio):
* con este codigo: git clone https://github.com/tu-usuario/mi-portafolio.git

###3) Agregar Archivos del Portafolio.:fa-hand-o-down:
* Navega al directorio clonado: cd mi-portafolio
* Agrega los archivos de tu portafolio (HTML, CSS, JavaScript, etc.) en esta carpeta.

###4) Hacer Commit y Push de los Cambios.:fa-ambulance:
* Añade los cambios al área de preparación: git add .
* Realiza un commit de los cambios: git commit -m "Agregado el portafolio"
* Envía los cambios al repositorio en GitHub: git push origin main
* (Asegúrate de que la rama sea main, o cambia main por master si es el nombre de tu 	rama principal).

###5) Desplegar el Portafolio.:fa-plane:
Para desplegar tu portafolio, puedes usar GitHub Pages:
* Ve a tu repositorio en GitHub.
* Haz clic en la pestaña "Settings".
* Desplázate hacia abajo hasta la sección "Pages".
* En el menú desplegable, selecciona la rama (por ejemplo, main) y la carpeta (normalmente root).
* Haz clic en "Save".

###6) Acceder a tu Portafolio.:fa-empire:
* Después de unos minutos, tu portafolio estará disponible en https://tu-usuario.github.io/mi-portafolio.
¡Por supuesto! Aquí tienes un tutorial detallado y paso a paso sobre cómo usar Git y GitHub, ideal para estudiantes universitarios que estén comenzando. Vamos a desglosar los comandos esenciales y cómo funcionan en el flujo de trabajo de Git y GitHub.

---

# Tutorial Completo de Git y GitHub

## Introducción

**Git** es un sistema de control de versiones que permite a los desarrolladores rastrear cambios en el código. **GitHub** es una plataforma que utiliza Git para gestionar proyectos, colaborar con otros y compartir código.

### 1. Configuración Inicial

#### a. Instalar Git

- **Windows**: Descarga el instalador de [git-scm.com](https://git-scm.com/) y sigue las instrucciones.
- **macOS**: Usa Homebrew:
  ```bash
  brew install git
  ```
- **Linux**: Usa el gestor de paquetes de tu distribución, por ejemplo:
  ```bash
  sudo apt install git  # Para Debian/Ubuntu
  ```

#### b. Configurar tu identidad

Una vez instalado Git, configura tu nombre y correo electrónico (esto es importante para los commits):

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu_email@example.com"
```

Puedes verificar la configuración con:

```bash
git config --list
```

### 2. Crear y Clonar Repositorios

#### a. Crear un nuevo repositorio

1. Crea un nuevo directorio y navega a él:
   ```bash
   mkdir mi-proyecto
   cd mi-proyecto
   ```

2. Inicializa un nuevo repositorio:
   ```bash
   git init
   ```

#### b. Clonar un repositorio existente

Si deseas trabajar en un repositorio ya existente:

```bash
git clone https://github.com/usuario/repo.git
```

### 3. Trabajo Básico con Archivos

#### a. Ver el estado del repositorio

Para ver los archivos modificados y el estado general:

```bash
git status
```

#### b. Agregar archivos al área de preparación

Agrega archivos que quieras incluir en tu próximo commit. Puedes agregar un archivo específico o todos los archivos modificados.

- Para agregar un archivo específico:
  ```bash
  git add nombre_del_archivo
  ```

- Para agregar todos los archivos:
  ```bash
  git add .
  ```

#### c. Realizar un commit

Guarda los cambios realizados en el repositorio local:

```bash
git commit -m "Descripción de lo que hiciste"
```

### 4. Trabajar con Ramas

Las ramas permiten trabajar en diferentes características sin afectar la rama principal.

#### a. Crear una nueva rama

```bash
git branch nombre_de_la_rama
```

#### b. Cambiar a otra rama

```bash
git checkout nombre_de_la_rama
```

#### c. Ver las ramas existentes

```bash
git branch
```

#### d. Combinar ramas

Primero, asegúrate de estar en la rama principal (generalmente llamada `main` o `master`):

```bash
git checkout main
```

Luego, combina otra rama:

```bash
git merge nombre_de_la_rama
```

#### e. Eliminar una rama

Cuando ya no necesites una rama:

```bash
git branch -d nombre_de_la_rama
```

### 5. Sincronización con GitHub

#### a. Conectar a un repositorio remoto

Si has creado un repositorio en GitHub, conéctalo a tu repositorio local:

```bash
git remote add origin https://github.com/usuario/repo.git
```

#### b. Subir cambios a GitHub

Para enviar tus cambios al repositorio remoto:

```bash
git push origin main
```

Si estás trabajando en una rama diferente, reemplaza `main` con el nombre de tu rama.

#### c. Bajar cambios de GitHub

Para sincronizar tu repositorio local con los cambios en GitHub:

```bash
git pull origin main
```

### 6. Comandos Adicionales Útiles

#### a. Ver el historial de commits

Para ver el historial de tus commits:

```bash
git log
```

#### b. Ver diferencias entre commits

Para ver los cambios entre commits o en archivos modificados:

```bash
git diff
```

#### c. Deshacer cambios

Si cometiste un error y quieres restaurar un archivo a su último estado:

```bash
git checkout -- nombre_del_archivo
```

#### d. Eliminar un archivo del repositorio

Para eliminar un archivo y registrarlo para el próximo commit:

```bash
git rm nombre_del_archivo
```

### 7. Buenas Prácticas

- **Commits claros**: Asegúrate de que tus mensajes de commit sean descriptivos.
- **Hacer commits pequeños**: Realiza cambios incrementales para facilitar el seguimiento.
- **Ramas para nuevas características**: Usa ramas para cada nueva característica o corrección de errores.

### Conclusión

Este tutorial cubre los comandos básicos de Git y GitHub que necesitas para comenzar. A medida que te familiarices con estas herramientas, podrás gestionar tus proyectos y colaborar de manera más eficiente.

Si tienes preguntas o deseas profundizar en algún tema específico, ¡no dudes en preguntar!

--- 

¿Te gustaría incluir algún tema adicional o ejemplos prácticos?