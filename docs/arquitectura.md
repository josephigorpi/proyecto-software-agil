# Arquitectura del Proyecto y Relación con el Enfoque Ágil

La arquitectura propuesta separa el sistema en tres componentes principales:
frontend, backend y base de datos. Esta separación permite desarrollar,
probar y mejorar cada componente de manera incremental.

El frontend desarrollado con Next.js puede evolucionar mediante la entrega
progresiva de nuevas interfaces y funcionalidades. Por su parte, FastAPI
permite incorporar nuevos servicios y endpoints conforme aparecen nuevos
requisitos en el Backlog. PostgreSQL centraliza la persistencia de los datos
y permite que las nuevas funcionalidades se integren sobre una base de datos
común.

Esta arquitectura se beneficia de un enfoque ágil porque facilita dividir el
desarrollo en incrementos pequeños y funcionales. Por ejemplo, en un Sprint
se puede implementar la gestión de productos; en el siguiente, el carrito de
compras; y posteriormente, los pedidos y pagos.

La separación entre frontend y backend también facilita que los equipos puedan
trabajar en diferentes funcionalidades de forma paralela. Además, los cambios
en los requisitos pueden incorporarse progresivamente sin necesidad de
rediseñar todo el sistema desde el inicio, permitiendo obtener
retroalimentación continua y entregar valor de manera incremental.
