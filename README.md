Tienda en Línea
Este proyecto es una tienda en línea que incluye funcionalidades de inicio de sesión, roles de usuario, un catálogo de productos, una tienda para comprar productos, información sobre la página y características adicionales como el CRUD para productos, una calculadora y la homogeneidad de las páginas.

Funcionalidades
1. Inicio de Sesión
Crea una página de inicio de sesión (login.html) que contiene campos de usuario y contraseña.
Define dos tipos de usuarios, como "admin" y "cliente".
Al enviar el formulario de inicio de sesión, se validan las credenciales ingresadas y se redirige al usuario a la página correspondiente (admin.html o shop.html) según el rol.
Se utiliza JavaScript para manejar la lógica de inicio de sesión y se almacena el rol del usuario en localStorage.
2. Encabezado con Menú
Se agrega un encabezado común a todas las páginas (en el archivo header.html) que incluye:
Logo de la tienda.
Enlaces a las páginas de catálogo de productos, tienda y acerca de.
Un botón de "Cerrar Sesión" que ejecuta la función logout() para eliminar el rol del usuario de localStorage y redirigirlo a la página de inicio de sesión.
3. Roles de Usuario
Se utiliza el rol almacenado en localStorage para determinar qué enlaces y funcionalidades se muestran en las páginas. Por ejemplo, se muestra el catálogo de productos solo si el usuario es un administrador.
4. Catálogo de Productos (CRUD)
En la página de administrador (admin.html), se permite al usuario administrador agregar, editar, eliminar y listar productos.
Se utiliza una tabla para mostrar los productos, incluyendo la imagen.
Se implementan botones para cada acción (Agregar, Editar, Eliminar).
Se utiliza JavaScript para gestionar las operaciones CRUD y actualizar la lista de productos en tiempo real.
5. Tienda con Calculadora
En la página de tienda (shop.html), se permite al usuario agregar productos al carrito de compra, ajustar la cantidad y mostrar un resumen de la compra.
Se agrega una opción para habilitar o deshabilitar una calculadora en la misma página.
Se utiliza JavaScript para realizar los cálculos y actualizar el resumen de compra.
6. Homogeneidad de Páginas
Se define una estructura de página común que incluye encabezado, contenido y pie de página.
Se utiliza CSS y Bootstrap para aplicar estilos consistentes a todas las páginas.
Se asegura de que las páginas sigan un diseño responsivo para verse bien en dispositivos de diferentes tamaños.
