# Sesión 1
## Charter
Explorar las funcionalidades del carrito usando acciones como "add to cart", "remove", "update cart", variaciones de entrada en la cantidad (números enteros, decimales, negativos y extremos) y verificar el cálculo total para detectar fallos en la adición y sustracción de productos, la validación de cantidades y el cálculo total.

## ÁREAS
JPetStore

Versión: Demo

OS: Windows 11

Plataforma: Web - Chrome

Estrategia: Exploración y testing

## INICIO
08/04/2026 16:00 pm

## TESTER
Ian Medina

## DESGLOSE DE TAREAS
Duración: 60 minutos
Diseño y ejecución de tareas: 100%

## ARCHIVOS DE DATOS
(Indica qué datos se usaron en las pruebas).

## NOTAS DE PRUEBA
Dispositivo/Navegador: Laptop/Chrome

Funcionalidades: Añadir al Carrito - Eliminar del Carrito - Actualizar el Carrito - Proceder al Checkout - Modificar Cantidad

Datos: ID del Artículo - ID del Producto - Descripción - En Stock - Cantidad - Precio - Sub Total - Costo Total

Valores límites: 

Cantidad mínima permitida de un producto en carrito: 1

Cantidad máxima permitida de un producto en carrito: 999.999.999

## LISTA DE RIESGOS
- "Add to cart" no agrega el producto al carrito
- La función "remove" no elimina el producto del carrito
- El sub total o costo total no se actualizan al modificar la cantidad del producto añadido, al agregar uno nuevo o al hacer click en "update cart"
- El producto es eliminado al refrescar el carrito
- El sistema permite proceder en la compra de un producto no disponible en stock
- El costo total suma decimales

## DEFECTOS (BUGS)
El sistema permite comprar productos que no esten en stock, llegando incluso a descontar la tarjeta del cliente.

## INCIDENTES (ISSUES)
Si bien el sistema no calcula sub total ni costo total al incluir una cantidad inválida (decimales, negativos y extremos), el mismo igualmente permite proceder al pago final.
