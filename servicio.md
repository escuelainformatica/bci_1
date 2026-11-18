# Servicios

* StockSrv
    * CrearStock(stock) : Crea un nuevo registro de stock y lo persiste en la base de datos. Si el producto ya existe, suma la cantidad al stock existente.
    * ObtenerStock(id) : Busca y retorna un registro de stock por su id.
    * ListarTodo() : Retorna todo el stock disponible.
* EntradaSrv
    * CrearEntrada(entrada) : Registra una nueva entrada de productos y aumenta la cantidad del stock correspondiente al producto.
* SalidaSrv
    * CrearSalida(salida) : Registra una nueva salida de productos, validando que exista stock suficiente; si la validación es correcta, disminuye la cantidad del stock correspondiente al producto.


