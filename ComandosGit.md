## Guía de comandos básicos de Git

### Inicialización

**git init:** Crea un nuevo repositorio Git en la carpeta actual.

### Agregar archivos

**git add nombre_de_archivo.extensión:** Agrega un archivo al área de preparación (staging area).

**git add:** Agrega todos los archivos modificados en la carpeta actual al área de preparación.

### Registrar cambios

**git commit -m "Mensaje":** Registra los cambios en el área de preparación como un commit con un mensaje descriptivo.

### Visualizar cambios

**git status:** Muestra el estado actual del repositorio, incluyendo los archivos modificados y sin registrar.

**git log nombre_de_archivo.extensión:** Muestra el historial de commits del archivo especificado.

### Sincronizar con repositorios remotos

**git push:** Envía los cambios locales al repositorio remoto.

**git pull:** Descarga los cambios del repositorio remoto y los fusiona con la rama local actual.

## Initial Setup

**Create a Git repository:**

```bash
mkdir git_reset_test
cd git_reset_test/
git init .
```

**Create a test file:**

```bash
touch reset_lifecycle_file
```

**Add and commit the file:**

```bash
git add reset_lifecycle_file
git commit -m "initial commit"
```

### Navegación por el sistema de archivos

**ls:** Muestra el contenido de la carpeta actual.

**pwd:** Muestra la ruta de acceso a la carpeta actual.

**mkdir nombre_de_carpeta:** Crea una nueva carpeta.

### Edición de archivos

**touch archivo.extensión:** Crea un archivo vacío.

**cat archivo.extensión:** Muestra el contenido de un archivo.

**history:** Muestra el historial de comandos ejecutados en la sesión actual.

### Eliminación de archivos

**rm archivo.extensión:** Elimina un archivo del repositorio.

### Obtener ayuda

**comando --help:** Muestra información de ayuda sobre un comando específico.

### Comandos adicionales

**git checkout:** Cambiar a una rama específica del repositorio.

**git rm --cached archivo.extensión:** Elimina un archivo del área de preparación, pero lo conserva en el disco duro.

**git config --list:** Muestra la configuración actual de Git.

**git config --list --show-origin:** Muestra la ubicación de los archivos de configuración de Git.

**git log --all:** Muestra el historial de commits de todas las ramas.

**git diff:** Muestra las diferencias entre dos versiones de un archivo o rama.

**git merge:** Fusiona dos ramas del repositorio.

**git reset:** Deshace los cambios realizados en el repositorio.

**git rebase:** Reorganiza el historial de commits de una rama.

**git tag:** Crea una etiqueta para un commit específico.

**git branch:** Crea una nueva rama en el repositorio.

**git describe:** Muestra información sobre un commit específico.

**git bisect:** Busca un commit específico en el historial del repositorio.

**git stash:** Guarda los cambios sin registrar en una pila para poder trabajar en otra rama.

**git clean:** Elimina los archivos que no están siendo rastreados por Git.

**git filter-branch:** Reescribe el historial del repositorio.

**git grep:** Busca texto en el historial del repositorio.

**git archive:** Crea un archivo ZIP o tar de un commit o rama específicos.

**git clone:** Crea una copia local de un repositorio remoto.

**git init --bare:** Crea un repositorio remoto vacío.

**git daemon:** Inicia un servidor Git para compartir el repositorio con otros usuarios.

**git gc:** Recicla el espacio de almacenamiento del repositorio.

**git show:** Muestra información sobre un commit específico.

**git cherry-pick:** Selecciona y aplica commits específicos a una rama diferente.

**git am:** Aplica un parche a un commit específico.

**git submodule:** Administra submódulos dentro de un repositorio.

**git worktree:** Crea un árbol de trabajo independiente para una rama específica.

**# Git Reset Test**
