# Log de Decisiones
- **Fecha:** 2026-02-23
- **Decisión:** Uso de DuckDB como motor analítico local.
- **Contexto:** Se necesita procesar datos (ej. exoplanetas) localmente de forma eficiente y sin depender de la infraestructura de un servidor externo.
- **Consecuencias:** Permite realizar consultas SQL analíticas (OLAP) muy rápidas sobre archivos locales, facilitando el modelado de datos entre las capas Raw, Silver y Gold.