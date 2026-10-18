# 🚗 Gestión de Motores y Recambios

Aplicación web desarrollada con **Angular 20** y **Bootstrap 4.4.1** para gestionar un catálogo de motores y recambios de vehículos. Permite consultar productos, visualizar información del inventario y añadir nuevos productos mediante un formulario.

## 📌 Descripción del proyecto

El objetivo de este proyecto es crear una interfaz intuitiva, moderna y responsive para facilitar la gestión de un catálogo de productos relacionados con el sector del automóvil.

La aplicación está organizada en componentes Angular y utiliza las funcionalidades de los componentes standalone y el sistema de plantillas de Angular para mostrar la información de los productos.

## ✨ Funcionalidades

- 📦 **Catálogo de productos:** visualización de motores y recambios.
- ➕ **Añadir productos:** formulario para introducir nuevos productos.
- 💰 **Gestión de precios:** registro del precio de cada producto.
- 📊 **Control de stock:** consulta de las unidades disponibles.
- 🗂️ **Categorías:** clasificación de los productos por categoría.
- 🖼️ **Imágenes:** posibilidad de indicar una URL para cada producto.
- 📝 **Descripciones:** visualización de información adicional de los productos.
- ❤️ **Favoritos:** marcar productos como favoritos.
- 🔎 **Información del inventario:** cálculo del valor del stock y consulta del estado de los productos.
- ✅ **Validación del nombre:** comprobación de la longitud y del contenido del nombre.
- 📱 **Diseño responsive:** interfaz adaptable a diferentes tamaños de pantalla.

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| Angular 20 | Framework principal |
| TypeScript | Lógica de la aplicación |
| HTML5 | Estructura de las páginas |
| CSS3 | Personalización de los estilos |
| Bootstrap 4.4.1 | Diseño responsive y componentes visuales |
| Angular Forms | Gestión de formularios mediante `ngModel` |
| Angular Router | Navegación de la aplicación |

## 📂 Estructura del proyecto

La estructura puede variar según la organización de los archivos de tu proyecto.

```text
src/
├── app/
│   ├── components/
│   │   ├── capcalera/
│   │   └── tarjetas/
│   ├── interfaces/
│   │   ├── producte.ts
│   │   └── categoria.ts
│   ├── app.ts
│   ├── app.html
│   └── app.css
├── index.html
├── main.ts
└── styles.css
```

## 🚀 Instalación y ejecución

### 1. Requisitos previos

Instala los siguientes programas:

- [Node.js](https://nodejs.org/)
- [Angular CLI](https://angular.dev/tools/cli)
- [Git](https://git-scm.com/)

### 2. Clonar el repositorio

```bash
git clone URL_DE_TU_REPOSITORIO
```

### 3. Entrar en la carpeta del proyecto

```bash
cd NOMBRE_DEL_PROYECTO
```

### 4. Instalar las dependencias

```bash
npm install
```

### 5. Iniciar la aplicación

```bash
ng serve
```

Abre el navegador y accede a:

```text
http://localhost:4200/
```

## 🧩 Modelo de producto

Cada producto utiliza una interfaz TypeScript con propiedades para almacenar su información.

Entre los campos principales se encuentran:

- `id`: identificador del producto.
- `nom`: nombre del producto.
- `preu`: precio.
- `estoc`: unidades disponibles.
- `categoria`: categoría del producto.
- `foto`: URL de la imagen.
- `disponible`: disponibilidad del producto.
- `mostrardes`: controla la visualización de la descripción.
- `descripcio`: descripción del producto.
- `Favorito`: indica si el producto está marcado como favorito.

## 🧮 Getters y cálculos

La aplicación utiliza getters de TypeScript para obtener información calculada de los productos, como:

- Nombre del producto en mayúsculas.
- Etiqueta de su categoría.
- Valor económico del stock, calculado mediante precio por unidades.
- Estado del producto según su disponibilidad y cantidad en inventario.

Estos cálculos permiten presentar información adicional sin tener que almacenarla como un nuevo campo en el modelo.

## 🎨 Diseño

La interfaz utiliza una distribución basada en tarjetas y paneles, con:

- Cabecera de navegación.
- Panel de administración.
- Formulario para añadir productos.
- Catálogo de motores y recambios.
- Diseño adaptable a móviles, tablets y ordenadores.

## 📚 Objetivos de aprendizaje

Este proyecto permite practicar:

- Desarrollo de aplicaciones con Angular.
- Creación y reutilización de componentes.
- Uso de interfaces y tipado con TypeScript.
- Renderizado de listas mediante `@for`.
- Renderizado condicional mediante `@if`.
- Enlace de datos con `[(ngModel)]`.
- Gestión de eventos con `(click)`.
- Creación de getters.
- Organización del código en componentes e interfaces.
- Diseño de interfaces con Bootstrap y CSS.

## 🔮 Posibles mejoras futuras

- Conectar la aplicación a una API REST.
- Guardar los productos en una base de datos.
- Añadir funciones para editar y eliminar productos.
- Implementar búsqueda y filtros por categoría.
- Incorporar autenticación de usuarios.
- Añadir paginación al catálogo.

## 👨‍💻 Autor

Proyecto personal desarrollado como práctica de desarrollo web con Angular y TypeScript.

---

⭐ Si te resulta útil este proyecto, puedes dejar una estrella al repositorio.
