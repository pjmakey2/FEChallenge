# FE Challenge

## Librerias a utilizar
 
  * Bootstartp 5 (https://getbootstrap.com/)
  * paramquery (https://paramquery.com/)
  * sweetalert2 (https://sweetalert2.github.io/)
  * axios (https://axios-http.com/docs/intro)

## Datos a utilizar

### Lista de productos

```
products = [{"PRODUCT_CODE":"P004","PRODUCT_NAME":"Coffee Maker","PRODUCT_BRAND":"HomeTech","PRODUCT_CATEGORY":"Appliances","LIST_PRICE":49.99,"DISCOUNT_PERCENT":8},{"PRODUCT_CODE":"P005","PRODUCT_NAME":"Leather Wallet","PRODUCT_BRAND":"FashionX","PRODUCT_CATEGORY":"Accessories","LIST_PRICE":29.99,"DISCOUNT_PERCENT":12.5},{"PRODUCT_CODE":"P006","PRODUCT_NAME":"HD TV","PRODUCT_BRAND":"Samsung","PRODUCT_CATEGORY":"Electronics","LIST_PRICE":899.99,"DISCOUNT_PERCENT":7.5},{"PRODUCT_CODE":"P007","PRODUCT_NAME":"Tennis Racket","PRODUCT_BRAND":"Wilson","PRODUCT_CATEGORY":"Sports","LIST_PRICE":69.99,"DISCOUNT_PERCENT":10},{"PRODUCT_CODE":"P008","PRODUCT_NAME":"Sunglasses","PRODUCT_BRAND":"Ray-Ban","PRODUCT_CATEGORY":"Fashion","LIST_PRICE":129.99,"DISCOUNT_PERCENT":15.5},{"PRODUCT_CODE":"P009","PRODUCT_NAME":"Desk Chair","PRODUCT_BRAND":"OfficeComfort","PRODUCT_CATEGORY":"Furniture","LIST_PRICE":149.99,"DISCOUNT_PERCENT":5},{"PRODUCT_CODE":"P010","PRODUCT_NAME":"Bluetooth Earbuds","PRODUCT_BRAND":"Sony","PRODUCT_CATEGORY":"Electronics","LIST_PRICE":79.99,"DISCOUNT_PERCENT":9},{"PRODUCT_CODE":"P011","PRODUCT_NAME":"Gaming Mouse","PRODUCT_BRAND":"Logitech","PRODUCT_CATEGORY":"Gaming","LIST_PRICE":49.99,"DISCOUNT_PERCENT":6.5},{"PRODUCT_CODE":"P012","PRODUCT_NAME":"Cookware Set","PRODUCT_BRAND":"KitchenMaster","PRODUCT_CATEGORY":"Kitchen","LIST_PRICE":129.99,"DISCOUNT_PERCENT":11},{"PRODUCT_CODE":"P013","PRODUCT_NAME":"Fitness Tracker","PRODUCT_BRAND":"FitPro","PRODUCT_CATEGORY":"Health","LIST_PRICE":59.99,"DISCOUNT_PERCENT":8.5},{"PRODUCT_CODE":"P014","PRODUCT_NAME":"Backpack","PRODUCT_BRAND":"OutdoorGear","PRODUCT_CATEGORY":"Travel","LIST_PRICE":39.99,"DISCOUNT_PERCENT":13},{"PRODUCT_CODE":"P015","PRODUCT_NAME":"Desk Lamp","PRODUCT_BRAND":"Illuminate","PRODUCT_CATEGORY":"Home","LIST_PRICE":19.99,"DISCOUNT_PERCENT":16},{"PRODUCT_CODE":"P016","PRODUCT_NAME":"Digital Camera","PRODUCT_BRAND":"Canon","PRODUCT_CATEGORY":"Electronics","LIST_PRICE":499.99,"DISCOUNT_PERCENT":7},{"PRODUCT_CODE":"P017","PRODUCT_NAME":"Hiking Boots","PRODUCT_BRAND":"TrailBlazer","PRODUCT_CATEGORY":"Footwear","LIST_PRICE":109.99,"DISCOUNT_PERCENT":10},{"PRODUCT_CODE":"P018","PRODUCT_NAME":"Yoga Mat","PRODUCT_BRAND":"ZenFit","PRODUCT_CATEGORY":"Fitness","LIST_PRICE":24.99,"DISCOUNT_PERCENT":14.5},{"PRODUCT_CODE":"P019","PRODUCT_NAME":"Wireless Keyboard","PRODUCT_BRAND":"TechMaster","PRODUCT_CATEGORY":"Electronics","LIST_PRICE":59.99,"DISCOUNT_PERCENT":6},{"PRODUCT_CODE":"P020","PRODUCT_NAME":"Portable Charger","PRODUCT_BRAND":"PowerUp","PRODUCT_CATEGORY":"Accessories","LIST_PRICE":34.99,"DISCOUNT_PERCENT":9.5}]
```

### Lista de ventas

```
sales = [{"SALES_MAN":"SalesPerson_4","CLIENT":1717,"CLIENT_NAME":"Cira Mira","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"GALLETA SEVEN PLUS 1","PRODUCT_CODE":13018,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":86,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":10500},{"SALES_MAN":"SalesPerson_1","CLIENT":1414,"CLIENT_NAME":"Lamas Lorenza","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"REFRESCO 250ML","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":100,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":3500},{"SALES_MAN":"SalesPerson_3","CLIENT":1114,"CLIENT_NAME":"Jimenez Rodriguez","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"LECHE 500ML","PRODUCT_CODE":13012,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":29,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":5500},{"SALES_MAN":"SalesPerson_1","CLIENT":1411,"CLIENT_NAME":"Susana Rubien","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"GALLETA SEVEN PLUS 2","PRODUCT_CODE":13011,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":40,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":11500},{"SALES_MAN":"SalesPerson_5","CLIENT":1112,"CLIENT_NAME":"Arturo Guiterrez","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"GALLETA SEVEN PLUS 1","PRODUCT_CODE":13018,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":50,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":10500},{"SALES_MAN":"SalesPerson_5","CLIENT":1517,"CLIENT_NAME":"Ribien Susana","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"LECHE 400ML","PRODUCT_CODE":13014,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":98,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":4500},{"SALES_MAN":"SalesPerson_1","CLIENT":11017,"CLIENT_NAME":"Gloria Merma","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"REFRESCO 2LT","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":33,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":11000},{"SALES_MAN":"SalesPerson_2","CLIENT":1414,"CLIENT_NAME":"Lamas Lorenza","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"GALLETA SEVEN PLUS 1","PRODUCT_CODE":13018,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":69,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":10500},{"SALES_MAN":"SalesPerson_3","CLIENT":1114,"CLIENT_NAME":"Jimenez Rodriguez","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"REFRESCO 250ML","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":98,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":3500},{"SALES_MAN":"SalesPerson_1","CLIENT":1413,"CLIENT_NAME":"Romina Lorenza","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"GALLETA SEVEN PLUS 1","PRODUCT_CODE":13018,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":43,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":10500},{"SALES_MAN":"SalesPerson_1","CLIENT":1517,"CLIENT_NAME":"Ribien Susana","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"GALLETA SEVEN PLUS 2","PRODUCT_CODE":13011,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":77,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":11500},{"SALES_MAN":"SalesPerson_1","CLIENT":1114,"CLIENT_NAME":"Jimenez Rodriguez","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"GALLETA SEVEN PLUS 1","PRODUCT_CODE":13018,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":87,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":10500},{"SALES_MAN":"SalesPerson_5","CLIENT":1411,"CLIENT_NAME":"Susana Rubien","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"REFRESCO 3LT","PRODUCT_CODE":130017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":23,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":12000},{"SALES_MAN":"SalesPerson_4","CLIENT":11017,"CLIENT_NAME":"Gloria Merma","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"LECHE 500ML","PRODUCT_CODE":13012,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":88,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":5500},{"SALES_MAN":"SalesPerson_2","CLIENT":1111,"CLIENT_NAME":"Alonzo Romero","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"GALLETA SEVEN PLUS 5","PRODUCT_CODE":13014,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":27,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":14500},{"SALES_MAN":"SalesPerson_1","CLIENT":1917,"CLIENT_NAME":"Lorenza Lamas","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"LECHE 400ML","PRODUCT_CODE":13014,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":61,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":4500},{"SALES_MAN":"SalesPerson_5","CLIENT":1717,"CLIENT_NAME":"Cira Mira","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"REFRESCO 1LT","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":39,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":9000},{"SALES_MAN":"SalesPerson_1","CLIENT":1817,"CLIENT_NAME":"Tesla Paola","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"LECHE 1LT","PRODUCT_CODE":13011,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":73,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":8500},{"SALES_MAN":"SalesPerson_2","CLIENT":1411,"CLIENT_NAME":"Susana Rubien","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"REFRESCO 500ML","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":42,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":5000},{"SALES_MAN":"SalesPerson_3","CLIENT":1817,"CLIENT_NAME":"Tesla Paola","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"LECHE 1LT","PRODUCT_CODE":13011,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":32,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":8500},{"SALES_MAN":"SalesPerson_5","CLIENT":1415,"CLIENT_NAME":"Jimena Jimenez","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"REFRESCO 1LT","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":72,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":9000},{"SALES_MAN":"SalesPerson_3","CLIENT":1817,"CLIENT_NAME":"Tesla Paola","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"REFRESCO 3LT","PRODUCT_CODE":130017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":53,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":12000},{"SALES_MAN":"SalesPerson_4","CLIENT":11017,"CLIENT_NAME":"Gloria Merma","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"REFRESCO 500ML","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":96,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":5000},{"SALES_MAN":"SalesPerson_1","CLIENT":1112,"CLIENT_NAME":"Arturo Guiterrez","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"REFRESCO 1LT","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":42,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":9000},{"SALES_MAN":"SalesPerson_1","CLIENT":1413,"CLIENT_NAME":"Romina Lorenza","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"REFRESCO 3LT","PRODUCT_CODE":130017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":97,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":12000},{"SALES_MAN":"SalesPerson_1","CLIENT":1411,"CLIENT_NAME":"Susana Rubien","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"REFRESCO 250ML","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":31,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":3500},{"SALES_MAN":"SalesPerson_3","CLIENT":1717,"CLIENT_NAME":"Cira Mira","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"GALLETA SEVEN PLUS 3","PRODUCT_CODE":13012,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":54,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":12500},{"SALES_MAN":"SalesPerson_2","CLIENT":1817,"CLIENT_NAME":"Tesla Paola","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"GALLETA SEVEN PLUS 3","PRODUCT_CODE":13012,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":84,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":12500},{"SALES_MAN":"SalesPerson_2","CLIENT":1411,"CLIENT_NAME":"Susana Rubien","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"LECHE 400ML","PRODUCT_CODE":13014,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":93,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":4500},{"SALES_MAN":"SalesPerson_5","CLIENT":1118,"CLIENT_NAME":"Rebeca Samaniego","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"REFRESCO 2LT","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":93,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":11000},{"SALES_MAN":"SalesPerson_3","CLIENT":1414,"CLIENT_NAME":"Lamas Lorenza","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"LECHE 400ML","PRODUCT_CODE":13014,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":41,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":4500},{"SALES_MAN":"SalesPerson_5","CLIENT":1817,"CLIENT_NAME":"Tesla Paola","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"LECHE 500ML","PRODUCT_CODE":13012,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":25,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":5500},{"SALES_MAN":"SalesPerson_4","CLIENT":1717,"CLIENT_NAME":"Cira Mira","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"LECHE 500ML","PRODUCT_CODE":13012,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":59,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":5500},{"SALES_MAN":"SalesPerson_1","CLIENT":1411,"CLIENT_NAME":"Susana Rubien","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"GALLETA SEVEN PLUS 6","PRODUCT_CODE":13015,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":21,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":15500},{"SALES_MAN":"SalesPerson_1","CLIENT":11017,"CLIENT_NAME":"Gloria Merma","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"REFRESCO 250ML","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":35,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":3500},{"SALES_MAN":"SalesPerson_3","CLIENT":1917,"CLIENT_NAME":"Lorenza Lamas","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"LECHE 500ML","PRODUCT_CODE":13012,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":14,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":5500},{"SALES_MAN":"SalesPerson_1","CLIENT":1717,"CLIENT_NAME":"Cira Mira","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"GALLETA SEVEN PLUS 2","PRODUCT_CODE":13011,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":24,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":11500},{"SALES_MAN":"SalesPerson_2","CLIENT":1114,"CLIENT_NAME":"Jimenez Rodriguez","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"LECHE 400ML","PRODUCT_CODE":13014,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":53,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":4500},{"SALES_MAN":"SalesPerson_1","CLIENT":1112,"CLIENT_NAME":"Arturo Guiterrez","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"GALLETA SEVEN PLUS 3","PRODUCT_CODE":13012,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":77,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":12500},{"SALES_MAN":"SalesPerson_4","CLIENT":1917,"CLIENT_NAME":"Lorenza Lamas","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"GALLETA SEVEN PLUS 3","PRODUCT_CODE":13012,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":40,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":12500},{"SALES_MAN":"SalesPerson_4","CLIENT":1917,"CLIENT_NAME":"Lorenza Lamas","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"REFRESCO 2LT","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":51,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":11000},{"SALES_MAN":"SalesPerson_2","CLIENT":1114,"CLIENT_NAME":"Jimenez Rodriguez","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"GALLETA SEVEN PLUS 5","PRODUCT_CODE":13014,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":29,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":14500},{"SALES_MAN":"SalesPerson_4","CLIENT":11017,"CLIENT_NAME":"Gloria Merma","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"GALLETA SEVEN PLUS 3","PRODUCT_CODE":13012,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":63,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":12500},{"SALES_MAN":"SalesPerson_5","CLIENT":1413,"CLIENT_NAME":"Romina Lorenza","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"REFRESCO 1LT","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":70,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":9000},{"SALES_MAN":"SalesPerson_2","CLIENT":1817,"CLIENT_NAME":"Tesla Paola","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"LECHE 400ML","PRODUCT_CODE":13014,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":90,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":4500},{"SALES_MAN":"SalesPerson_5","CLIENT":1415,"CLIENT_NAME":"Jimena Jimenez","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"REFRESCO 2LT","PRODUCT_CODE":13017,"PRODUCT_BRAND":"PEPSI","PRODUCT_QUANTITY":68,"PRODUCT_CATEGORY":"BEBIDAS","PRODUCT_PRICE":11000},{"SALES_MAN":"SalesPerson_5","CLIENT":1414,"CLIENT_NAME":"Lamas Lorenza","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"GALLETA SEVEN PLUS 1","PRODUCT_CODE":13018,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":50,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":10500},{"SALES_MAN":"SalesPerson_4","CLIENT":1118,"CLIENT_NAME":"Rebeca Samaniego","CLIENT_CATEGORY":"PLUS B","PRODUCT_NAME":"LECHE 400ML","PRODUCT_CODE":13014,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":45,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":4500},{"SALES_MAN":"SalesPerson_5","CLIENT":1817,"CLIENT_NAME":"Tesla Paola","CLIENT_CATEGORY":"PLUS C","PRODUCT_NAME":"GALLETA SEVEN PLUS 2","PRODUCT_CODE":13011,"PRODUCT_BRAND":"CEREALITAS","PRODUCT_QUANTITY":62,"PRODUCT_CATEGORY":"PANIFICADOS","PRODUCT_PRICE":11500},{"SALES_MAN":"SalesPerson_3","CLIENT":1412,"CLIENT_NAME":"Paola Tesla","CLIENT_CATEGORY":"PLUS A","PRODUCT_NAME":"LECHE 400ML","PRODUCT_CODE":13014,"PRODUCT_BRAND":"TREBOL","PRODUCT_QUANTITY":76,"PRODUCT_CATEGORY":"LACTEOS","PRODUCT_PRICE":4500}]
```

# FE Tasks

 * Crear una maqueta con boostratp 5

 ## Las siguientes tareas de creacion de tablas deben recidir en un archivo html diferente.

 * Crear una tabla para los datos `Lista de productos`, utilizando la libreria paramquery.

   * Estos datos debe ser leidos desde el BE, si no posees los conocimientos para crear un server, obta por la siguiente de las 2 opciones:
      * simula la lectura de los datos mediante una funcion local, dentro de la definicion del atributo `dataModel`
      * O guardar el JSON en una url publica o privada y leerla directamente.

   * La tabla debe tener los siguientes botones, que disparen las acciones descriptas.

      * Agregar: Abrir un modal con un formulario para la carga de los productos (segun los atributos mostrados en `Lista de productos`)
      * Eliminar: Que llame al endpoint del BE para eliminar el producto (Esto tiene que ser con un modal de confirmacion )
      * Verificar: Que llame al endpoint del BE para verificar el producto (Esto tiene que ser con un modal de confirmacion )
      * Aprobar: Que llame al endpoint del BE para aprobar el producto (Esto tiene que ser con un modal de confirmacion )
 
 * Del dato `Lista de ventas`, generar una tabla agrupada por `SALES_MAN`, `CLIENTE_CATEGORY` y `PRODUCT_BRAND` y generate una columna formulado que realize la siguiente operacion aritmetica `PRODUCT_PRICE`*`PRODUCT_QUANTITY`

 OBS: Puntos extras si entregar tu proyecto son Sentry
