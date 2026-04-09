# Sesión 1
## Charter
Explorar las funcionalidades del carrito usando acciones como "add to cart", "remove", "update cart", variaciones de entrada en la cantidad (números enteros, decimales, negativos y extremos) y verificar el cálculo total para detectar fallos en la adición y sustracción de productos, la validación de cantidades y el cálculo total.

## ÁREAS
JPetStore

Versión: Demo

OS: Windows 11

Plataforma: Web - Chrome

Estrategia: Exploración testing y observación

## INICIO
08/04/2026 16:00 pm

## TESTER
Ian Medina

## DESGLOSE DE TAREAS
Duración: 60 minutos

Diseño de pruebas: 20%

Ejecución de preubas: 80%

## ARCHIVOS DE DATOS
Cantidades probadas: 0, 1, -1, -5, 1,5, 2,5, 9.999.999, 1.000.000.000

Productos probados: En stock y sin stock

Pruebas ejecutadas: Agregar producto - eliminar producto - actualizar carrito - cantidades con número enteros, decimales, negativas y extremas

## NOTAS DE PRUEBA
Dispositivo/Navegador: Laptop/Chrome

Funcionalidades: Añadir al Carrito - Eliminar del Carrito - Actualizar el Carrito - Proceder al Checkout - Modificar Cantidad

Campos obervados: ID del Artículo - ID del Producto - Descripción - En Stock - Cantidad - Precio - Sub Total - Costo Total

Valores límites: 

Cantidad mínima permitida de un producto en carrito: 1

Cantidad máxima permitida de un producto en carrito: 999.999.999

## LISTA DE RIESGOS
- "Add to cart" no agrega el producto al carrito
- La función "remove" no elimina el producto del carrito
- El calculo sub total o total es incorrecto
- El producto es eliminado al refrescar el carrito
- El sistema permite proceder en la compra de un producto no disponible en stock
- Se aceptan cantidades inválidas

## DEFECTOS (BUGS)
El sistema permite comprar productos sin stock, procesando el pago al cliente.

## INCIDENTES (ISSUES)
Si bien el sistema no calcula sub total ni costo total al incluir una cantidad inválida (decimales, negativos y extremos), el mismo igualmente permite proceder al pago.
