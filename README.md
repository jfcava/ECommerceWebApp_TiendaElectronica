# 🛒 E-Commerce WebApp - Tienda de Electrónica

Este es el proyecto integrador final del Nivel 3 de la ruta de aprendizaje de desarrollo .NET. Consiste en una aplicación web de comercio electrónico funcional, con panel de administración, gestión de usuarios y catálogo de productos.

## 🚀 Características Principales

* **Catálogo de Productos:** Visualización de artículos con imágenes, descripciones y precios.
* **Sistema de Autenticación:** Login y registro de usuarios con encriptación y validación de datos.
* **Gestión de Roles:**
  * **Usuario Cliente:** Puede navegar por el catálogo, ver detalles y agregar productos a favoritos/carrito.
  * **Usuario Administrador:** Tiene acceso a un panel exclusivo para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre el catálogo de productos y gestionar el stock.
* **Manejo de Excepciones:** Flujo controlado de errores para garantizar la estabilidad de la aplicación y una buena experiencia de usuario.
* **Diseño Responsivo:** Interfaz adaptable a diferentes tamaños de pantalla.

## 💻 Tecnologías Utilizadas

* **Backend:** C# / ASP.NET WebForms (Arquitectura en capas)
* **Base de Datos:** Microsoft SQL Server (Acceso a datos con ADO.NET)
* **Frontend:** HTML5, CSS3, Bootstrap
* **Herramientas:** Visual Studio, Git, GitHub

## 🛠️ Instalación y Configuración

Si deseas clonar y probar este proyecto en tu entorno local, sigue estos pasos:

1. **Clonar el repositorio:**
`git clone https://github.com/jfcava/tp-final-nivel3-Cavallieri-JuanFranco.git`

2. **Configurar la Base de Datos:**
* Abre SQL Server Management Studio (SSMS).
* Ejecuta el script SQL incluido en la carpeta raíz del proyecto ('CATALOGO_WEB_DB.sql') para crear la base de datos y las tablas necesarias.

3. **Configurar la Cadena de Conexión:**
* Abre el proyecto en **Visual Studio**.
* Dirígete al archivo `Web.config`.
* Modifica el `connectionString` para que apunte a tu servidor SQL Server local.

4. **Ejecutar la aplicación:**
* Presiona `F5` o haz clic en "Iniciar" en Visual Studio para correr el proyecto.

## 📸 Capturas de Pantalla

*(Nota: Aquí agregaré próximamente GIFs o capturas mostrando el funcionamiento del login, el catálogo y el panel de administrador).*

## 👨‍💻 Autor

**Juan Franco Cavallieri**
* Desarrollador .NET
* [Mi perfil de LinkedIn](https://www.linkedin.com/in/juan-franco-cavallieri/)
