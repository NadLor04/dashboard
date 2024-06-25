# Proyecto TP1 Dashboard de resultados del Modelo predictivo
## Código de proyecto: PRY20241034

### Estudiantes:
- Nadia Lorena Tinoco Ricapa (U202012868)
- Angélica María Lira Pacheco (U201920059)
Este proyecto es una aplicación web que permite subir y visualizar datos a partir de archivos CSV, y muestra dashboards basados en los resultados de un modelo predictivo. La aplicación ofrece una interfaz amigable para la visualización de datos y está dividida en varias secciones principales.

## Descripción del Proyecto

El proyecto consiste en una aplicación web que permite a los usuarios:

1. **Visualizar el contenido de un archivo CSV resultante del modelo en una tabla**.
2. **Visualizar un dashboard con los resultados del modelo predictivo aplicado a datos de entrenamiento**.
3. **Visualizar un dashboard con los resultados del modelo predictivo aplicado a datos de validación**.
4. **Ver información de presentación de la empresa en la sección "Nosotros"**.
5. **Subir y filtrar datos de productos desde un archivo `products.csv` en la sección "Productos"**.

## Tecnologías y Librerías Utilizadas

- **HTML5**: Estructura de las páginas web.
- **CSS3**: Estilos de las páginas web.
- **JavaScript**: Lógica de la aplicación.
- **jQuery**: Biblioteca JavaScript para facilitar la manipulación del DOM y las peticiones AJAX.
- **DataTables**: Plugin de jQuery para crear tablas interactivas.
- **PapaParse**: Biblioteca para parsear archivos CSV en JavaScript.
- **Bootstrap**: Framework CSS para diseño responsivo y componentes UI.

## Estructura del Proyecto

.
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── components/
│   ├── header.html
│   ├── footer.html
│   └── sidebar.html
├── data/
│   ├── products.csv
│   ├── Resultado_modelo_train.csv
│   └── Resultado_modelo_val.csv
├── 404.html
├── dashboard.html
├── dashboard2.html
├── files.html
├── index.html
├── nosotros.html
├── productos.html
├── app.js


## Uso

### Página Principal

Al iniciar la aplicación, se muestra la página principal (`index.html`). Aquí puedes navegar a las diferentes secciones del proyecto.

### Subir y Visualizar CSV

1. Abre `files.html` en tu navegador web.
2. Selecciona un archivo CSV y haz clic en "Subir".
3. El archivo CSV será procesado y los datos se almacenarán en `localStorage`.

### Dashboard de Resultados del Modelo Predictivo

1. Abre `dashboard.html` en tu navegador web para ver los resultados del modelo predictivo aplicado a datos de entrenamiento.
2. Abre `dashboard2.html` para ver los resultados del modelo predictivo aplicado a datos de validación.

### Sección "Nosotros"

1. Abre `nosotros.html` para ver la información de presentación de la empresa.

### Sección "Productos"

1. Abre `productos.html` en tu navegador web.
2. Sube el archivo `products.csv` desde la interfaz.
3. Los datos se mostrarán en una tabla interactiva donde puedes aplicar filtros y ordenar la información.

## Instalación

1. Clona o descarga este repositorio en tu máquina local.

   ```bash
   git clone https://github.com/NadLor04/dashboard.git 


## Contribuir
Si deseas contribuir a este proyecto, por favor abre un issue o envía un pull request en GitHub.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.
