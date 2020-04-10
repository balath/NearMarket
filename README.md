# NearMarket
#hackpeum2020

La idea es crear una aplicación para la reserva de productos en tiendas locales.
  
## Roles

En la aplicación te podrás registrar como Tienda o como Usuario:

- Tienda
  - Dirección
  - Información de contacto (mail/telf)
  - Reparte a domicilio
  - Gestión de productos
  - Gestión de pedidos

- Usuario
  - Teléfono para validar
  - Nombre
  - Gestión de sus pedidos

## "Casos de uso"

1. Búsqueda: en la pantalla principal tendremos dos opciones:

- Buscar por dirección
  - Donde obtendremos un listado de tiendas cercanas a esa localización

- Buscar por producto
  - Nos saldrá un listado de tiendas cerca de nuestra propia dirección que tengan este producto
  - Podremos filtrar por otra localización que no sea la nuestra
  
2. Tienda: una vez dentro de la tienda seleccionada podremos hacer el pedido

- Listado de productos con su cantidad de la tienda

3. Gestión pedido usuario: el usuario tendrá un listado de pedidos para poder gestionar

4. Gestión pedidos tienda: la tienda tendrá un listado de pedidos de varios usuarios a gestionar


---------------Sergio
Gestión de usuarios
  −	Usuario
    o	Datos de registro
        Teléfono
        Nombre
        Dirección (en domicilio)
  −	Tienda
    o	Datos contacto dueño
    o	Dirección
        Punto de vista de Tienda
  −	Creación de la tienda
    o	Datos de registro
    o	Oferta de venta
        Recogida
        Domicilio
  −	Gestionar productos
    o	Añadir/eliminar productos
        Categoría (común a cada tienda p.ej. pan)
        Denominación producto (p.ej. Bimbo Familiar)
    
    o	Modalidades de Stock 
        En Stock
        Bajo Pedido
    o	Control de Stock
        Activar/Desactivar disponibilidad
  −	Pedidos
    o	Vigencia de pedidos
        Posibilidad de cancelación por parte de la tienda
        Aplicar caducidad según horas de retraso en recogida
  −	Contacto con el cliente con registro de actividad
    o	Teléfono
    o	Mensajes
Punto de vista de Usuario
  −	Realización de pedidos 
    o	Alta
    o	Baja
    o	Modificar hora de recogida o envío
  −	Búsqueda de tiendas 
    o	En cualquier territorio, aunque el envío sea local
    o	Aparición de tiendas por cercanía
  −	Búsqueda por categorías de producto
    o	Por cercanía
    o	Por dirección
  −	Pagos
    o	Pago presencial al recoger el pedido
    o	Previsión de realizar pago online
  −	Contacto con la tienda

