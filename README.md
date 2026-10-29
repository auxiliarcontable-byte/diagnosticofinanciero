# Diagnóstico Financiero

Sistema de Diagnóstico Financiero para MiPyMES, publicado con Cloudflare Workers (recursos estáticos).

- **En línea:** https://diagnosticofinanciero.auxiliarcontable.workers.dev
- **Versión publicada:** v3.3 (`public/index.html`), versión estable con la que se cierra la Fase 1. Proyecto completo, historial de versiones y pruebas: [GEMELO-DIGITAL-FIANCIERO](https://github.com/auxiliarcontable-byte/GEMELO-DIGITAL-FIANCIERO).
- **Versiones anteriores** (fuera de `public/`, no se publican): v3.1 en `archivo/index_v3.1_2026-10-29.html` y la anterior en `archivo/index_anterior_2026-10-12.html`.

Cada commit a `main` se despliega automáticamente. Los datos que captura cada usuario se guardan solo en su navegador; la v3.3 usa el mismo almacenamiento que la v3.1, así que conserva empresas, periodos, historial, plan y escenarios sin migración.

**Novedades de la v3.3 frente a la v3.1:** los datos de ejemplo ya no entran al motor ni al historial; fechas invertidas e importes negativos se marcan como error de captura; cada campo distingue cero real, sin dato, no aplica, ejemplo y error; y la regla de solvencia R-01 limita el veredicto general a REGULAR cuando el capital contable es negativo, con una alerta de deterioro patrimonial.
