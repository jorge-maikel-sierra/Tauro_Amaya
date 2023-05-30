# Tauro Amaya

Este repositorio es un sitio web de venta de licores en Riohacha, La Guajira. Aquí los usuarios pueden encontrar una amplia variedad de licores de alta calidad a precios competitivos. Además, el sitio web ofrece información detallada sobre cada producto, incluyendo su origen, sabor y maridaje recomendado. Los usuarios también pueden leer reseñas de otros clientes y dejar sus propias opiniones. Con una navegación fácil de usar y un proceso de compra seguro, este sitio web es el destino perfecto para los amantes del buen licor en Riohacha.

## Características principales

- Amplia selección de licores: El sitio web podría ofrecer una amplia gama de licores, incluyendo diferentes tipos de bebidas alcohólicas como vinos, cervezas, licores destilados, licores espirituosos y cócteles premezclados. Esto permite a los usuarios explorar y elegir entre una variedad de opciones.

- Información detallada del producto: Cada licor disponible en el sitio web podría estar acompañado de información detallada, incluyendo descripción del producto, notas de cata, origen, contenido de alcohol, maridajes recomendados, entre otros detalles relevantes. Esta información ayudaría a los usuarios a tomar decisiones informadas sobre sus compras.

- Proceso de compra seguro y conveniente: El sitio web podría ofrecer un proceso de compra en línea seguro y conveniente. Esto podría incluir la capacidad de agregar productos al carrito de compras, opciones de pago seguras, métodos de envío y seguimiento de pedidos. Además, se podrían implementar medidas de seguridad para proteger la información personal y financiera de los clientes.

## Cómo ejecutar el proyecto

1. Clonar el repositorio:

```shell
git clone git@github.com:jorge-maikel-sierra/tauro_amaya.git

```

1. Crear la base de datos:

```sql
sudo mysql;
```

```sql
CREATE DATABASE tauro_amaya;
```
```sql
CREATE USER 'tauro_amaya'@'localhost' IDENTIFIED BY 'tauro_amaya2020';
```
```sql
GRANT ALL PRIVILEGES ON tauro_amaya.* TO 'tauro_amaya'@'localhost';
```
```sql
FLUSH PRIVILEGES;
```
```sql
exit;
```
#### Autor [Jorge Sierra](https://jorgesierra.dev/ "Jorge Sierra")


