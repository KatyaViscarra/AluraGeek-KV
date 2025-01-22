# AluraGeek


**AluraGeek** es una aplicación web que permite a los usuarios gestionar una lista de productos. Los usuarios pueden **visualizar**, **agregar** y **eliminar** productos, utilizando tecnologías frontend modernas y un servidor JSON simulado.

La base del proyecto fue proporcionada por **Alura Latam** con fines educativos y desarrollo de aprendizaje obtenido.

## 💻 Tecnologías Utilizadas

- **HTML5/CSS3**: Estructura y diseño.
- **JavaScript (ES6 Modules)**: Lógica e interacción.
- **json-server**: API RESTful simulada.
- **Fetch API**: Solicitudes HTTP.
- **BEM (Block Element Modifier)**: Metodología para nombrar clases CSS.

## 🚀 Instalación

### Requisitos previos

- **Node.js** instalado.
- **Live Server** plugin instalado en VS Code.

### Pasos

1. Clona este repositorio:

   ```bash
   git clone https://github.com/KatyaViscarra/AluraGeek-KV.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd AluraGeek-KV
   ```

3. Instala las dependencias:

   ```bash
   npm install
   ```

4. Abre `index.html` en tu navegador.

5. Inicia el servidor JSON:

   ```bash
   npm start
   ```

## 🛠️ API Simulada

**json-server** simula una API RESTful con las siguientes rutas:

- `GET /products`: Lista los productos.
- `POST /products`: Crea un nuevo producto.
- `DELETE /products/:id`: Elimina un producto.

## 📋 Uso de la Aplicación

1. **Visualizar Productos**: Los productos se cargan automáticamente desde el servidor simulado al abrir la página.
   
2. **Agregar Producto**: Completa el formulario con nombre, precio y URL de la imagen, luego haz clic en **"Enviar"**.
   
3. **Eliminar Producto**: Haz clic en el ícono de la papelera para eliminar un producto.

---
Desarrollado por Katya Viscarra.
