# pruebas de codigo

* Pruebas unitarias con JUnit 5.
* Pruebas de integración con Spring Boot Test.

## listado

### StockSrv (unitarias)

- [ ] CrearStock con un producto nuevo crea el registro en la base de datos.
- [ ] CrearStock con un producto ya existente suma la cantidad al stock.
- [ ] ObtenerStock con un id existente retorna el stock correspondiente.
- [ ] ObtenerStock con un id inexistente retorna nulo o lanza excepción.
- [ ] ListarTodo retorna todos los registros de stock.

### EntradaSrv (unitarias)

- [ ] CrearEntrada registra la entrada y aumenta la cantidad del stock del producto.

### SalidaSrv (unitarias)

- [ ] CrearSalida con stock suficiente registra la salida y disminuye la cantidad del stock.
- [ ] CrearSalida con stock insuficiente no registra la salida y lanza error.
- [ ] CrearSalida de un producto sin stock lanza error.

### Validaciones del modelo (unitarias)

- [ ] producto vacío o nulo es rechazado.
- [ ] producto con más de 50 caracteres es rechazado.
- [ ] cantidad menor o igual a cero es rechazada.

### Controladores (integración con MockMvc)

- [ ] GET Stock/ retorna la vista con la lista de stock (HTTP 200).
- [ ] GET Stock/ sin registros retorna una lista vacía.
- [ ] POST Stock/Crear crea un nuevo stock y redirige.
- [ ] POST Stock/Crear con datos inválidos retorna error de validación.
- [ ] POST Entrada/Crear registra la entrada y aumenta el stock del producto.
- [ ] POST Salida/Crear registra la salida y disminuye el stock del producto.
- [ ] POST Salida/Crear con stock insuficiente retorna error y no descuenta stock.

