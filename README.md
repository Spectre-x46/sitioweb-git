# Versionamiento con GIT

Proyecto de demostración para aprender los fundamentos del control de versiones con Git.

## Estructura del Proyecto

```
├── index.html        # Página principal
├── README.md         # Este archivo
├── css/              # Estilos CSS
├── js/
│   └── script.js     # Lógica JavaScript
```

## Comandos GIT Esenciales

### 1. Inicializar un repositorio

Para comenzar con control de versiones en tu proyecto:

```sh
git init
```

### 2. Ver el estado del proyecto

Comprueba qué archivos han cambiado, están en staging o sin seguimiento:

```sh
git status
```

### 3. Agregar archivos al Stage

**Agregar todos los cambios:**
```sh
git add .
```

**Agregar un archivo específico:**
```sh
git add index.html
```

### 4. Hacer Commit

Guarda los cambios en el repositorio con un mensaje descriptivo:

```sh
git commit -m "Descripción de los cambios realizados"
```

### 5. Ver el Historial

Consulta todos los commits realizados:

```sh
git log
```

### 6. Enviar cambios al repositorio remoto

```sh
git push
```

### 7. Obtener cambios del repositorio remoto

```sh
git pull
```

### 8. Ver diferencias

Observa qué líneas fueron modificadas:

```sh
git diff
```

## Flujo de Trabajo Básico

1. Realiza cambios en tus archivos
2. Verifica los cambios con `git status`
3. Agrega los archivos con `git add`
4. Crea un commit con `git commit -m "mensaje"`
5. Sube los cambios con `git push`

---

**Creado para aprender control de versiones con Git** 📝