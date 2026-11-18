# Ejercicio 
Este es un ejercicio en la clase 2026-11-18

El objetivo es crear un sistema de bodega que permita gestionar el inventario de productos, registrar entradas y salidas.

Se utilizarán tecnologías como Java 17, Spring Boot 3, Thymeleaf 3, Bootstrap 5 y H2 para el desarrollo del sistema.

El sistema permitirá:
- Gestionar el inventario de productos.
- Registrar entradas de productos.
- Registrar salidas de productos.

## Pruebas

### Pruebas unitarias

Son pruebas de funciones deterministas, que verifican el comportamiento esperado de cada unidad de código de manera aislada.
Usualmente se prueba las clases de servicio.


```java
function sumar(int a, int b) {
    return a + b;
}
// sumar(2, 3) => 5
// sumar(0, 0) => 0
// sumar(-1, 1) => 0
```
### Pruebas de integración

Son pruebas que pueden verse afectadas por factores externos.

Por ejemplo, una prueba para probar la base de datos. En un escenario de prueba de integración, podria devolver 5 datos, mientras que en otra ejecucion podria devolver 0 datos, dependiendo del estado de la base de datos.

En algunos casos se puede transformar las pruebas de integracion con pruebas unitarias utilizando mocks para simular el comportamiento de los componentes externos.

### Pruebas de la end-to-end

Son pruebas que verifican el correcto funcionamiento de la interfaz visual del sistema.
Se busca asegurar que los elementos de la interfaz se muestren correctamente y que las interacciones del usuario funcionen como se espera.

Por ejemplo, se puede probar que al hacer clic en un botón de "Agregar producto", se muestre un formulario para ingresar los datos del producto.

Aqui se prueban los controladores.
Se puede utilizar Playwright para automatizar la interacción con la interfaz y verificar que los flujos de usuario funcionen correctamente.




