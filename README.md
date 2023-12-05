
# Pinocchio's Pizza & Subs - Aplicación de Pedido en Línea

Esta es una aplicación web de pedido en línea inspirada en el menú y funcionalidades del restaurante Pinocchio's Pizza & Subs ubicado en Cambridge. La aplicación está desarrollada utilizando Django y proporciona a los usuarios la capacidad de registrar cuentas, navegar por el menú, agregar elementos al carrito de compras y realizar pedidos.

## Archivos y Estructura del Proyecto

- **orders/models.py**: Contiene los modelos que representan los elementos del menú y las órdenes de los usuarios.
- **orders/admin.py**: Configuración para permitir a los administradores del sitio agregar, actualizar y eliminar elementos del menú a través de Django Admin.
- **accounts/models.py**: Modelos relacionados con la información de los usuarios, como nombre de usuario, contraseña, nombre, apellido y dirección de correo electrónico.
- **cart/views.py**: Vistas para manejar la lógica del carrito de compras y la colocación de órdenes.
- **checkout/views.py**: Vistas relacionadas con el proceso de compra y confirmación de pedidos.
- **templates/**: Directorio que contiene las plantillas HTML para las diferentes páginas del sitio web.
- **static/**: Directorio que almacena archivos estáticos como hojas de estilo CSS, scripts JavaScript, etc.

## Funcionalidades Principales

- **Menú**: Se implementan modelos para representar los elementos del menú de Pinocchio's Pizza & Subs, con opciones de tamaño, coberturas y elementos adicionales.
- **Administrador del Sitio**: Los administradores pueden gestionar el menú a través del panel de administración de Django.
- **Registro y Autenticación de Usuarios**: Los clientes pueden registrarse con nombre de usuario, contraseña, nombre, apellido y dirección de correo electrónico. Inicio y cierre de sesión implementados.
- **Carrito de Compras**: Los usuarios pueden agregar elementos al carrito de compras y estos se guardan para futuras sesiones.
- **Colocar una Orden**: Los usuarios pueden confirmar y colocar órdenes a partir de los elementos en su carrito de compras.
- **Visualización de Órdenes**: Los administradores pueden acceder a una página para ver las órdenes solicitadas.

## Toque Personal

Se ha implementado la funcionalidad adicional de permitir a los usuarios ver el estado de sus órdenes pendientes o completadas. Además, se integró la API de Stripe para permitir pagos con tarjeta de crédito durante la facturación.


