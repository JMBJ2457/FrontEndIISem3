# Desafío: Layout Adaptativo (MQ + Flex)

Pequeño resumen de lo que se hizo:

- Separé los estilos del HTML y los pasé a `src/styles/styles.css`.
- Armé el breakpoint `@media (min-width: 768px)` para el modo escritorio.
- El layout pasa de móvil (columnas apiladas) a escritorio con 2 columnas: `sidebar` fija (~250px) + `contenido` flexible.
- Las tarjetas de noticias cambian a 2 por fila en escritorio.

Cómo probarlo rápido:

- Accede a la pagina a travez del link: 
- Abre el inspect de tu navegador.
- Reduce la ventana (<768px) para ver el modo móvil.
- Aumenta la ventana (>=768px)para ver el modo escritorio (2 columnas y tarjetas en 2 por fila).

