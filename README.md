# PideYa — Sobrepedidos Cafetería CBTIS 89

Prototipo de una aplicación de pedidos anticipados ("sobrepedidos") para la cafetería del CBTIS 89, desarrollado como propuesta de solución para la materia de Desarrollo Sustentable.

## Problema que resuelve

El benchmarking del proceso de pedido y entrega mostró que la cafetería tarda entre 3 y 7 veces más que su competencia (pastes, puestos de comida cercanos, vendedores de botanas) en entregar un pedido, principalmente por depender de una sola fila presencial y por la saturación del espacio físico.

## Cómo funciona

1. El alumno elige su carrera y semestre (hay 8 carreras: E-commerce, Construcción, Arquitectura, Programación, Mecatrónica, Contabilidad, Recursos Humanos, Comercio Internacional y Aduanas), cada una con cupo de 55 alumnos por turno.
2. Arma su pedido eligiendo un platillo y/o una bebida del menú real de la cafetería; si elige ambos, obtiene un descuento por combo. También puede comprar un solo producto sin necesidad de combo.
3. Puede sumar el pedido de un compañero para recogerlo junto (pedido grupal).
4. Al confirmar, se le asigna una ventana de entrega específica según su carrera, y ve el impacto en tiempo de espera comparado con el sistema actual.
5. Recibe una notificación cuando su pedido está listo.
6. Gana puntos según lo que pagó, subiendo de nivel (Bronce, Plata, Oro, Diamante) para futuros descuentos.
7. Hay una vista de cocina/administración donde el personal puede ver los pedidos pendientes agrupados por ventana.
8. Un apartado de noticias muestra promociones vigentes (2x1, descuentos por día, festividades).

## Cómo verlo en vivo

Este repositorio está pensado para usarse con **GitHub Pages**:
1. Ve a **Settings → Pages** en este repositorio
2. En "Branch" elige `main` y la carpeta `/ (root)`
3. Guarda — GitHub te dará un link público para abrir la app desde cualquier navegador

## Nota

Es un prototipo funcional con fines de demostración académica: los datos (cupos, pedidos, puntos) se generan en el navegador y no se guardan de forma permanente ni se conectan a un sistema real de la cafetería.
