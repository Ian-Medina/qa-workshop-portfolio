# Coverage Decisions
## Riesgos que se probarán primero
1. Enlentecimiento o caída del sistema ante un alto tráfico de usuarios.
2. Fallo en el checkout, impidiendo completar la compra.
3. El sistema no logra identificar la disponibilidad de stock de uno o más productos o viceversa.
## ¿Por qué esos riesgos son prioridad?
Influyen fuertemente en en los ingresos del negocio, todas estas funcionalidades son críticas para el funcionamiento del sistema.
## Qué se probará menos o quedará fuera por ahora
- Fallo de autenticación cuando el cliente intente acceder a su cuenta después de un cierre de sesión.
- Cantidades inválidas de productos en el carrito.
## Justificación de exclusiones
Ambas son funcionalidades importantes, sin embargo, un fallo en las mismas no necesariamente implica consecuencias graves para el negocio, aun mas si consideramos que son funcionalidads comúnmente implementadas y más estables.
