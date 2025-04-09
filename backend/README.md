# Endpoints y Funcionalidades
## Usuarios

    POST /api/auth/register/ → Registro de usuario.
    POST /api/auth/login/ → Inicio de sesión (JWT).
    GET /api/users/me/ → Obtener perfil del usuario.
    PUT /api/users/me/ → Actualizar perfil.

## Tiendas

    POST /api/stores/ → Crear tienda.
    GET /api/stores/{id}/ → Detalles de la tienda.
    PUT /api/stores/{id}/ → Actualizar tienda.
    DELETE /api/stores/{id}/ → Eliminar tienda.

## Productos

    POST /api/products/ → Crear producto.
    GET /api/products/ → Listar productos.
    GET /api/products/{id}/ → Detalles del producto.
    PUT /api/products/{id}/ → Actualizar producto.
    DELETE /api/products/{id}/ → Eliminar producto.

## Categorías

    POST /api/categories/ → Crear categoría.
    GET /api/categories/ → Listar categorías.
    GET /api/categories/{id}/ → Detalles de la categoría.
    PUT /api/categories/{id}/ → Actualizar categoría.
    DELETE /api/categories/{id}/ → Eliminar categoría.

    Recomendación: Utiliza serializers y viewsets para optimizar el código y reducir la repetición. Considera también la implementación de permisos personalizados para controlar el acceso a cada endpoint.

# Attachments
[Curso Django](https://youtu.be/u2Ms34GE14U?si=EltnWCNB5oINYcrf)

[Que es una API](https://youtu.be/u2Ms34GE14U?si=EltnWCNB5oINYcrf)
