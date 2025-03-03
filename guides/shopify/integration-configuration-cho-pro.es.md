# Checkout Pro

Al instalar [Checkout Pro](/developers/es/docs/checkout-pro/landing), puede haber un **aumento en la tasa de aprobación de las ventas en la tienda en línea**. Esto sucede porque los compradores podrán pagar con una cuenta de Mercado Pago y todo el proceso de compra se realizará en nuestro entorno, lo que facilita el pago. Al final de la transacción, estos compradores son redirigidos al entorno de la tienda.

----[mlb]----
Para configurar el Checkout Pro en una tienda Shopify, sigue los pasos a continuación:

1. Ve a tu tienda [Shopify](https://accounts.shopify.com/store-login).
2. Dentro del panel administrativo de la tienda, haz clic en **Configuración**.
3. Una vez allí, selecciona la opción **Pagos**. Luego, haz clic en el botón **Seleccionar un proveedor**.
4. Escribe Mercado Pago en la barra de búsqueda. Una vez que lo encuentres, selecciónalo como método de pago.
5. Coloca tus **credenciales de producción** (`Client_id` y `Client_secret`) en los campos que lo solicitan. Recuerda tener a mano tus [credenciales](/developers/es/docs/shopify/additional-content/your-integrations/credentials). 
6. En el siguiente paso, podrás seleccionar las imágenes de los medios de pago que deseas mostrar en la tienda. **Importante: estas imágenes son sólo para fines ilustrativos y no implican la activación del método de pago seleccionado**.
7. Por último, la tienda te ofrecerá la opción de **habilitar el modo de prueba**. Al activar esta opción, los pedidos completados con Checkout Pro **no serán pedidos reales**. Es decir, serán pedidos de prueba que, aun siendo completados, no tendrán su estado actualizado en la plataforma y no aparecerán en el panel de Mercado Pago en la cuenta del usuario.
8. Al finalizar, haz clic en **Activar Mercado Pago**. 

> En caso de renovar tus credenciales, recuerda reemplazar tanto las de producción como las de pruba en tu integración.

------------
----[mla, mlm, mpe, mco, mlu, mlc]----
> WARNING
>
> Atención
>
> Si estás usando la app antigua de Mercado Pago ("Mercado Pago"), [haz clic aquí](/developers/es/docs/shopify/how-tos/migration) para saber cómo migrar a la versión actual ("Checkout Mercado Pago").

Para instalar Checkout Pro en una tienda Shopify, sigue los pasos a continuación:

1. Ve a tu tienda [Shopify](https://accounts.shopify.com/store-login).
2. Dentro del panel administrativo de la tienda, haz clic en **Configuración**.
3. Una vez allí, selecciona la opción **Pagos**. 
4. En "Formas de pago adicionales", haz clic en **Agregar formas de pago**.
5. Dirígete a la pestaña **Buscar por proveedor** y busca la nueva app con el nombre "Checkout Mercado Pago". 
6. Una vez que la hayas encontrado, selecciónala y haz clic en **Activar”** y luego **Conectar**.

<center>

![migracion a](/images/shopify/migration-a-es.gif)

</center>

7. Selecciona **Instalar aplicación** y luego **Gestionar**.
8. Coloca tus **credenciales de producción** (`public key` y `access token`) en los campos que lo solicitan y haz clic en **Guardar**. Recuerda tener a mano tus [credenciales](/developers/es/docs/shopify/additional-content/your-integrations/credentials).
9. Para terminar la instalación, selecciona **Activar Checkout Mercado Pago**.

> En este paso, podrás seleccionar las imágenes de los medios de pago que quieras mostrar en tu tienda a modo ilustrativo. También, en caso que lo desees, podrás habilitar el [modo de prueba.](/developers/pt/docs/shopify/sales-processing/integration-test)
> <br/><br/>
> En caso de renovar tus credenciales, recuerda reemplazar tanto las de producción como las de pruba en tu integración.

<center>

![migracion b](/images/shopify/migration-b-es.gif)

</center>

------------