# Casos de estudio de ingeniería

**Problemas reales. Diagnóstico basado en evidencias. Decisiones técnicas claras.**

Colección pública y bilingüe de casos técnicos de **Juan Herbozo**. El objetivo no es mostrar únicamente *qué* se implementó, sino **cómo se comprendió, investigó, resolvió y validó cada problema** en sistemas empresariales, ERP, inteligencia artificial, integraciones cloud y datos.

**English:** [Read this README in English](README.md)

## Casos publicados

| ID | Área | Caso | Estado | Idiomas |
|---|---|---|---|---|
| ECS-001 | Cloud e integraciones | [Cuando SMTP funciona, pero el formulario serverless devuelve HTTP 502](cloud-architecture/cloudflare-workers-smtp/README.es.md) | Resuelto · validado | [ES](cloud-architecture/cloudflare-workers-smtp/README.es.md) · [EN](cloud-architecture/cloudflare-workers-smtp/README.md) |

## Áreas de conocimiento

- **[Business Central y ERP](business-central/README.es.md):** análisis funcional, finanzas, almacén, ventas, integraciones, actualizaciones y migraciones. Los futuros casos se generalizarán y reconstruirán con datos ficticios.
- **[IA y sistemas inteligentes](ai-intelligent-systems/README.es.md):** IA generativa, IA en ERP, agentes, recuperación de conocimiento, evaluación y arquitectura.
- **[Cloud e integraciones](cloud-architecture/README.es.md):** compatibilidad de runtimes, despliegue, API, mensajería y fiabilidad.
- **[Datos y analítica](data-analytics/README.es.md):** modelado, calidad, informes y paneles operativos.

## Plantillas

Utiliza la [plantilla en español](templates/case-study-template.es.md) o en [inglés](templates/case-study-template.md) para documentar un caso nuevo.

## Metodología de documentación

1. **Contexto y comportamiento observado:** distinguir síntomas de suposiciones.
2. **Impacto y límites del problema:** qué falló y qué continuó funcionando.
3. **Hipótesis y pruebas:** evidencias que respaldan o descartan explicaciones.
4. **Decisión y alternativas:** qué se modificó y qué se decidió conservar.
5. **Validación:** criterios comprobables y resultados.
6. **Aprendizajes y limitaciones:** conclusiones transferibles y aspectos no demostrados.

## Confidencialidad y publicación

Los casos son **reconstrucciones educativas y anonimizadas**, no exportaciones de tickets ni repositorios privados de clientes. No se publican deliberadamente nombres de clientes, contratos, credenciales, tokens, endpoints internos, logs productivos, código propietario ni registros empresariales reales. Los diagramas y ejemplos son generalizados; cualquier futuro ejemplo ejecutable requerirá datos sintéticos y revisión previa a su publicación.

Solo se presenta un resultado como **verificado** cuando existe evidencia de validación. Las hipótesis se identifican como tales y los casos sin solución confirmada no se anuncian como resueltos. Las obligaciones de confidencialidad y propiedad intelectual prevalecen sobre la publicación.

## Artículos relacionados

- Web personal: [juanherbozo.com](https://juanherbozo.com/)
- Artículo en español: [Cuando una integración SMTP falla en Serverless](https://juanherbozo.com/es/blog/cloudflare-smtp-integration/)
- Article in English: [When an SMTP Integration Fails in Serverless](https://juanherbozo.com/en/blog/cloudflare-smtp-integration/)

*Conviene verificar las URL de los artículos al publicar. El caso de GitHub contiene la explicación necesaria por sí mismo.*

## Alcance y licencia

Documentación orientada al aprendizaje profesional. **Por ahora no se concede ninguna licencia de código abierto.** Si se publican ejemplos de código o diagramas reutilizables, se seleccionará una licencia expresamente.
