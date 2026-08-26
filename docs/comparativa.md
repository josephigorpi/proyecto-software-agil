# 📊 Comparación de Metodologías y Análisis de Casos

## 1. Comparativa: Enfoque Tradicional vs. Enfoque Ágil

| Aspecto | Metodologías Tradicionales (Cascada) | Metodologías Ágiles (Scrum) |
|---|---|---|
| **Enfoque** | Predictivo y secuencial. El proyecto se planifica desde el inicio y se sigue una secuencia de fases previamente establecida. | Iterativo e incremental. El producto se construye y mejora progresivamente a partir de ciclos cortos y retroalimentación constante. |
| **Manejo de requisitos** | Los requisitos se establecen principalmente al comienzo del proyecto, procurando evitar modificaciones posteriores. | Los requisitos pueden cambiar y ajustarse conforme se obtiene nueva información o cambian las necesidades. |
| **Ciclo de vida** | El trabajo avanza por etapas consecutivas: Análisis → Diseño → Codificación → Pruebas → Implantación. | El desarrollo se organiza en Sprints de corta duración, normalmente entre 1 y 4 semanas, repitiendo el ciclo de trabajo en cada uno. |
| **Entrega** | El producto completo suele entregarse una vez finalizadas todas las etapas del proyecto. | Se realizan entregas frecuentes de incrementos funcionales que aportan valor progresivamente. |
| **Documentación** | Se prioriza una documentación amplia y detallada desde las primeras fases. | Se mantiene la documentación necesaria, dando mayor importancia a disponer de software funcional. |
| **Rol del cliente** | Su participación suele concentrarse al inicio para definir necesidades y al final para validar el resultado. | Participa de manera continua, proporcionando comentarios y retroalimentación durante los ciclos de desarrollo. |
| **Ventajas** | Facilita la planificación y ofrece una estructura clara, ordenada y predecible. | Permite responder con rapidez a los cambios, entregar valor antes y reducir el riesgo de desarrollar un producto inadecuado. |
| **Desventajas** | Presenta dificultades cuando los requisitos cambian y el valor del producto se percibe principalmente al final. | Puede ofrecer menor previsibilidad a largo plazo y exige compromiso, organización y disciplina constante del equipo. |

## 2. Análisis de 3 Casos

### ✅ Caso 1: Sistema de Inventarios con Requisitos Estables

- **Características:** Funcionalidades conocidas, alcance definido y pocos cambios esperados en los requisitos.
- **Metodología recomendada:** Cascada (Tradicional).
- **Justificación:** Al tratarse de un sistema con necesidades claramente identificadas y relativamente estables, es posible definir y planificar las etapas desde el inicio. En este escenario, la capacidad de adaptación tiene menor importancia que contar con un proceso organizado y predecible.

### ✅ Caso 2: Plataforma de Comercio Electrónico en Constante Evolución

- **Características:** Cambios frecuentes en el mercado, competencia, nuevas necesidades de los usuarios e incorporación continua de funcionalidades.
- **Metodología recomendada:** Scrum (Ágil).
- **Justificación:** La plataforma necesita evolucionar progresivamente y adaptarse a nuevas condiciones. Scrum permite desarrollar funcionalidades por incrementos, recibir retroalimentación frecuente y realizar ajustes antes de finalizar todo el producto. De esta manera, se evita esperar hasta el final para descubrir que la solución ya no responde a las necesidades del mercado.

### ✅ Caso 3: Sistema Médico con Alta Regulación

- **Características:** Cumplimiento de normas estrictas, documentación obligatoria, certificaciones y necesidad de mantener trazabilidad.
- **Metodología recomendada:** Enfoque híbrido (Cascada + prácticas ágiles).
- **Justificación:** Las exigencias regulatorias requieren una planificación previa y documentación formal, características propias de enfoques tradicionales. Sin embargo, determinadas funcionalidades o módulos pueden desarrollarse mediante ciclos ágiles, permitiendo obtener mayor flexibilidad sin dejar de cumplir los requisitos normativos establecidos.

---

## 3. Aplicación de Principios Ágiles en el Proyecto de Comercio Electrónico

### Principio 1 — Entregar valor de forma frecuente

> El proyecto puede generar una versión funcional cada dos semanas. Al finalizar cada Sprint, el cliente revisa el incremento desarrollado y sus comentarios ayudan a definir las prioridades del siguiente ciclo.

### Principio 2 — Adaptarse a los cambios

> Cuando aparece una nueva necesidad del mercado o del cliente, esta se incorpora al Product Backlog para ser evaluada y priorizada. De este modo, los cambios se integran en futuros Sprints sin necesidad de reiniciar toda la planificación del proyecto.

### Principio 3 — Considerar el software funcionando como evidencia de progreso

> Cada Sprint debe finalizar con funcionalidades que puedan ejecutarse y demostrarse. La cantidad de documentos elaborados no representa por sí sola el avance del proyecto; el progreso principal se comprueba mediante software que realmente funciona.
