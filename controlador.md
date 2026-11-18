# Controlador

## rutas

* Stock/  (GET) Va a corresponder a listar todo el stock disponible.
* Stock/Crear  (POST) Va a corresponder a crear un nuevo stock.
* Entrada/Crear  (POST) Va a corresponder a registrar una nueva entrada de productos.
* Salida/Crear  (POST) Va a corresponder a registrar una nueva salida de productos.

## Clases y métodos

* StockController
    * ListarTodo() : Se mapea a la ruta Stock/ (GET), lista todo el stock disponible.
    * Crear(stock) : Se mapea a la ruta Stock/Crear (POST), crea un nuevo stock.
* EntradaController
    * Crear(entrada) : Se mapea a la ruta Entrada/Crear (POST), registra una nueva entrada de productos.
* SalidaController
    * Crear(salida) : Se mapea a la ruta Salida/Crear (POST), registra una nueva salida de productos.



