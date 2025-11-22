# 📚 Ejercicios de JavaScript

Una colección de ejercicios prácticos de JavaScript vanilla diseñados para aprender y practicar conceptos fundamentales de programación web interactiva.

## 📋 Descripción

Este repositorio contiene una serie de ejercicios prácticos que demuestran el uso de JavaScript para manipulación del DOM, validación de formularios, manejo de eventos y lógica de programación básica. Cada ejercicio está contenido en un archivo HTML independiente con JavaScript integrado, lo que facilita su ejecución y comprensión.

## 🎯 Ejercicios Incluidos

### 1. **Agregar Tareas** (`Agregar_Tareas.html`)
Aplicación simple de lista de tareas que permite:
- Visualizar tareas predefinidas
- Agregar nuevas tareas dinámicamente
- Manipulación del DOM con JavaScript

**Conceptos practicados:**
- Arrays y métodos de arrays (`push`, `for...of`)
- Manipulación del DOM (`getElementById`, `innerHTML`)
- Eventos de botones
- Template literals

---

### 2. **Contador** (`Contador.html`)
Contador interactivo con historial que incluye:
- Incrementar el contador (+1)
- Decrementar el contador (-1)
- Reiniciar el contador
- Historial de valores
- Validación para evitar números negativos

**Conceptos practicados:**
- Variables y estado de la aplicación
- Funciones y eventos
- Iteración con `forEach`
- Condicionales
- Manejo de errores básico

---

### 3. **Convertir Mayúsculas/Minúsculas** (`Convertir_a_Mn.html`)
Herramienta de conversión de texto que permite:
- Convertir texto a mayúsculas
- Convertir texto a minúsculas
- Limpiar campos de entrada

**Conceptos practicados:**
- Métodos de strings (`toUpperCase()`, `toLowerCase()`)
- Manipulación de inputs
- Estilos inline con HTML
- Eventos de botones múltiples

---

### 4. **Validar Contraseña** (`Validar_Contraseña.html`)
Formulario de inicio de sesión con validación de contraseña segura:
- Validación con expresiones regulares
- Requisitos de contraseña fuerte:
  - Mínimo 8 caracteres
  - Al menos una letra mayúscula
  - Al menos un número
  - Al menos un carácter especial
- Retroalimentación visual al usuario

**Conceptos practicados:**
- Formularios HTML
- Prevención de comportamiento por defecto (`preventDefault()`)
- Expresiones regulares (RegEx)
- Event listeners
- Validación de datos

---

### 5. **Validar Correo Electrónico** (`Validar_Correo.index.html`)
Validador de correo electrónico que verifica:
- Formato válido de email usando RegEx
- Campo de usuario no vacío
- Retroalimentación inmediata

**Conceptos practicados:**
- Validación con expresiones regulares
- Método `trim()` para limpiar espacios
- Validación de múltiples campos
- Operadores lógicos (`&&`)

## 🚀 Cómo Usar

### Requisitos Previos
- Navegador web moderno (Chrome, Firefox, Edge, Safari)
- No se requieren dependencias externas ni instalación

### Instrucciones de Uso

1. **Clonar o descargar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/JavaScript-Ejercicios.git
   ```

2. **Abrir los ejercicios:**
   - Navega a la carpeta del proyecto
   - Abre cualquier archivo `.html` directamente en tu navegador
   - También puedes usar "Abrir con" → "Navegador de tu preferencia"

3. **Ejecutar los ejercicios:**
   - Cada archivo es independiente y se ejecuta directamente en el navegador
   - No se requiere servidor web ni configuración adicional

## 📖 Estructura del Proyecto

```
JavaScript-Ejercicios/
│
├── Agregar_Tareas.html          # Gestor de lista de tareas
├── Contador.html                # Contador con historial
├── Convertir_a_Mn.html          # Convertidor de mayúsculas/minúsculas
├── Validar_Contraseña.html      # Validador de contraseñas seguras
├── Validar_Correo.index.html    # Validador de correos electrónicos
└── README.md                    # Este archivo
```

## 🎓 Conceptos de JavaScript Cubiertos

Este conjunto de ejercicios cubre los siguientes conceptos fundamentales:

- ✅ **Manipulación del DOM**
  - `getElementById()`
  - `innerHTML` y `textContent`
  - Creación dinámica de elementos

- ✅ **Eventos**
  - `onclick`
  - `addEventListener()`
  - `submit` events

- ✅ **Arrays y Métodos**
  - `push()`, `pop()`
  - `forEach()`
  - Iteración con `for...of`

- ✅ **Strings**
  - `toUpperCase()`, `toLowerCase()`
  - `trim()`
  - Template literals

- ✅ **Validación**
  - Expresiones regulares (RegEx)
  - Validación de formularios
  - `preventDefault()`

- ✅ **Lógica de Programación**
  - Condicionales (`if/else`)
  - Funciones
  - Variables y estado

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura de las páginas
- **CSS3** - Estilos inline básicos
- **JavaScript (ES6+)** - Lógica y funcionalidad

## 💡 Sugerencias para Aprender

1. **Estudia el código:** Abre cada archivo en un editor de texto y lee el código JavaScript
2. **Experimenta:** Modifica los valores, agrega nuevas funcionalidades
3. **Depura:** Usa las herramientas de desarrollo del navegador (F12)
4. **Practica:** Intenta recrear los ejercicios desde cero sin mirar el código

## 🔧 Posibles Mejoras

Estos ejercicios son básicos y pueden mejorarse con:

- [ ] Separación de HTML, CSS y JavaScript en archivos independientes
- [ ] Uso de `localStorage` para persistencia de datos
- [ ] Mejoras en la interfaz de usuario con CSS moderno
- [ ] Validación más robusta y mensajes de error detallados
- [ ] Implementación de pruebas unitarias
- [ ] Uso de módulos ES6
- [ ] Accesibilidad (ARIA labels, navegación por teclado)

## 📝 Notas

- Todos los ejercicios usan JavaScript vanilla (sin frameworks ni librerías)
- El código está diseñado para ser simple y educativo
- Algunos ejercicios tienen pequeños bugs intencionales para practicar debugging

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar algún ejercicio o agregar nuevos:

1. Haz un fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevoEjercicio`)
3. Commit tus cambios (`git commit -m 'Agregar nuevo ejercicio'`)
4. Push a la rama (`git push origin feature/NuevoEjercicio`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto es de código abierto y está disponible para fines educativos.

## ✨ Autor

Proyecto educativo para aprender JavaScript básico.

---

⭐ Si este repositorio te fue útil, considera darle una estrella en GitHub

**¡Feliz aprendizaje! 🚀**
