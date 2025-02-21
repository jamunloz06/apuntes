# GIT

**Manual Básico de GIT**

---

# Introducción a GIT

GIT es un sistema de control de versiones distribuido que permite gestionar proyectos de software de manera eficiente. Es ampliamente utilizado en desarrollo de software y colaboración en equipo.

---

# 1. Instalación de GIT

## En Windows
1. Descargar el instalador desde [Git for Windows](https://git-scm.com/downloads)
2. Ejecutar el instalador y seguir las instrucciones.
3. Verificar la instalación con el comando:

```bash
git --version
```

## En Linux (Debian/Ubuntu)
```bash
sudo apt update
sudo apt install git
```

## En macOS
```bash
brew install git
```

---

# 2. Configuración inicial

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"
```

Verificar configuración:
```bash
git config --list
```

---

# 3. Comandos básicos

## 3.1 Inicializar un repositorio
```bash
git init
```

## 3.2 Clonar un repositorio
```bash
git clone https://github.com/usuario/repositorio.git
```

## 3.3 Ver estado del repositorio
```bash
git status
```

## 3.4 Agregar archivos al área de staging
```bash
git add archivo.txt
```

## 3.5 Confirmar cambios
```bash
git commit -m "Mensaje del commit"
```

## 3.6 Ver historial de commits
```bash
git log
```

## 3.7 Enviar cambios a un repositorio remoto
```bash
git push origin main
```

## 3.8 Obtener cambios del repositorio remoto
```bash
git pull origin main
```

## 3.9 Crear una nueva rama
```bash
git branch nueva-rama
```

## 3.10 Cambiar a otra rama
```bash
git checkout nueva-rama
```

## 3.11 Fusionar ramas
```bash
git merge nombre-de-la-rama
```

---

# 4. Manejo de repositorios remotos

## Agregar un repositorio remoto
```bash
git remote add origin https://github.com/usuario/repositorio.git
```

## Ver repositorios remotos
```bash
git remote -v
```

---

# 5. Deshacer cambios

## Deshacer cambios en un archivo antes del commit
```bash
git checkout -- archivo.txt
```

## Resetear el último commit
```bash
git reset --soft HEAD~1  # Mantiene los cambios en staging

git reset --hard HEAD~1  # Borra los cambios completamente
```

---

# 6. Ignorar archivos con .gitignore

Crear un archivo `.gitignore` y agregar los archivos o carpetas que quieres excluir.

Ejemplo:
```gitignore
/node_modules
*.log
.env
```

---

# 7. Alias útiles

```bash
git config --global alias.st status
git config --global alias.cm "commit -m"
git config --global alias.br branch
git config --global alias.co checkout
```

---

# 📌 Conclusión

GIT es una herramienta esencial para el desarrollo de software. Con estos comandos básicos podrás gestionar versiones de tu código y colaborar de manera eficiente.

---

¿Quieres agregar algo más? 😊

