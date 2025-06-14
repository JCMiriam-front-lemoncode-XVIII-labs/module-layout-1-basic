# 🎨 Layout LAB

Este repositorio contiene la resolución de cuatro componentes, con la propuesta de no utilizar JS para su implementación. Cada uno se encuentra encapsulado en su propio módulo HTML + SCSS dentro de la carpeta `src/components`.

Para ello se realiza una web común, usando únicamente HTML, CSS, SASS y VITE, donde se podrá apreciar la maquetación de cada uno de los componentes solicitados.

---

## 📁 Estructura del proyecto
```bash
src/
├── commons/styles # Estilos globales y utilitarios (colores, fuentes, mixins...)
├── components/
│ ├── cards/ # Cards con CSS Grid
│ ├── color-palette/ # Paleta de colores dinámica
│ ├── menu/ # Barra de navegación responsive con Flexbox
│ └── theme-toggle/ # Cambio de tema (colores, fuentes, radios, sombras)
├── images/ # Recursos gráficos
├── index.html # Página principal
├── main.js / main.scss # Entrada principal
```

---

## 🧪 Componentes

### 1️⃣ Paleta de Colores Dinámica

Paleta completa a partir de un color base, con 4 variaciones más claras y 4 más oscuras, usando funciones de Sass como `lighten()` y `darken()`.

📂 `src/components/color-palette/`

---

### 2️⃣ Selector de Temas

Permite alternar entre dos temas con diferentes:

- Colores
- Tipografías
- Bordes redondeados
- Sombra de caja

📂 `src/components/theme-toggle/`

---

### 3️⃣ Barra de navegación

Barra de navegación adaptable a distintos tamaños de pantalla mediante **Flexbox** y **media queries**.

📂 `src/components/menu/`

---

### 4️⃣ Cards con CSS Grid

Diseño de tarjetas (cards) usando **Grid CSS**.

📂 `src/components/cards/`

---

### 5️⃣ Comunes

En este proyecto hay muchos estilos, variables y mixins que necesitamos usar en varios de los componentes, por lo que se incluye una carpeta de estilos comunes con mixins para breakpoints (con media queries), generales, variables de colores, fuentes, iconos y reseteo de estilos de css.

📂 `src/commons/styles/`

---

## 🚀 Instalación y ejecución

#### 1. Clona el repositorio:
```bash
git clone https://github.com/JCMiriam-front-lemoncode-XVIII-labs/module-layout-1-basic.git
cd module-layout-1-basic
```

#### 2. Instala las dependencias:
```bash
npm install
```

#### 3. Levanta el entorno de desarrollo:
```bash
npm install
```

#### 4. Abre el navegador en la URL que aparece en consola (normalmente http://localhost:5173).

---

## 🛠️ Tecnologías usadas

- HTML5
- SCSS (Sass)
- Vite
- Flexbox
- Grid CSS
- Responsive Design

---

## 📌 Notas

- Cada componente puede visualizarse de forma aislada navegando a su respectiva ruta y abriendo el archivo HTML correspondiente.
- Los estilos están organizados modularmente por componente o ejercicio.
- Se ha utilizado una estructura escalable y mantenible con SCSS.
