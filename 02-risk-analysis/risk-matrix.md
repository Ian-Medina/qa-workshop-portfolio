# Risk Matrix
| ID | Riesgo | Probabilidad | Impacto | Nivel | Mitigación |
|----|--------|--------------|---------|-------|------------|
| R1 | Fallo de autenticación cuando el cliente intente acceder a su cuenta después de un cierre de sesión. (Fiabilidad) | 2 | 4 | 8 | Pruebas de login/logout, monitoreo en de la autenticación. |
| R2 | El sistema no logra identificar la disponibilidad de stock de uno o más productos o viceversa. (Fiabilidad) | 3 | 4 | 12 | Validación de stock, pruebas de API, monitoreo del inventario. |
| R3 | Enlentecimiento o caída del sistema ante un alto tráfico de usuarios. (Eficiencia de Desempeño) | 3 | 5 | 15 | Pruebas de escalabilidad, monitoreo. |
| R4 | Fallo en el checkout, impidiendo completar la compra. (Adecuacuón Funcional) | 3 | 5 | 15 | Pruebas end to end, pruebas automatizadas. |
| R5 | Cantidades inválidas de productos en el carrito. (Adecuación Funcional) | 2 | 3 | 6 | Pruebas automatizadas, pruebas API, monitoreo. |

Justificaciones
R1:  Al tratarse de una funcionalidad recurrente en cualquier web o app, no tendría que ser muy susceptible a errores, sin embargo, en el caso de que llegase a suceder, puede incurrir en frustración y pérdidas de clientes y, por ende, pérdidas financieras.

R2: Teniendo en cuenta que el canal principal de ventas es la página web, un fallo en la detección de la disponibilidad de uno o más productos puede recurrir en un malestar en los clientes y pérdida financiera. 

R3: Revelaría una debilidad en la infraestructura del sistema, lo que podría conllevar a un costoso análisis y retrabajo para descubrir el origen.

R4: Cualquier fallo que suceda en el punto final de una compra impactan gravemente en los ingresos y la fidelidad del cliente.

R5: Al permitir la compra de productos en cantidades negativas o excesivas, puede incurrir en la base de datos y el inventario.
