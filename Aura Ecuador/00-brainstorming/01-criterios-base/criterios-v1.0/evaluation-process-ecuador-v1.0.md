# Proceso de evaluación de ideas — Aura Ecuador v1.0

> **Estado:** fuente para visual HTML
> **Versión:** Evaluation Process Ecuador v1.0 · 2026-06-12
> **Propósito:** explicar cómo el sistema convierte el documento V2 del socio abogado + el activo EnRegla + el canal TikTok en un ranking de ideas con una recomendación accionable para Ecuador.
> **Relación con Aura International:** mismo motor de cinco capas. Las diferencias (pesos, filtros, gobierno) están documentadas en `criterios-base-ecuador-v1.0.md` y resumidas abajo.

## Resumen ejecutivo

El documento `01 Proyecto_Compliance_Ecuador_V2.md` del socio describe una visión grande: una plataforma de 12 capas (LOPDP, UAFE, gobierno corporativo, gestión documental, contratos inteligentes, etc.). Esa visión es el **destino**, no el primer producto.

Este proceso descompone esa visión —más el activo EnRegla y los servicios que el abogado ya puede prestar— en ideas vendibles, las puntúa con un objetivo dominante (dinero rápido + recurrencia + canal propio), aplica filtros duros, y produce un top 5 con una recomendación de #1.

El objetivo no es construir la plataforma completa antes de vender. Es **encontrar la primera oferta que cobra en menos de 90 días y se vuelve recurrente**, usando lo que ya tenemos.

## Las cinco capas del sistema

| Capa | Qué es | Archivo |
|---|---|---|
| 1. Criterios base | Objetivos editables del equipo | `criterios-base-ecuador-v1.0.md` §1-3 |
| 2. Criterios ponderados | 10 criterios con peso para calcular score | `criterios-base-ecuador-v1.0.md` §4 |
| 3. Filtros de descarte | Reglas duras que pausan ideas con bloqueos | `criterios-base-ecuador-v1.0.md` §5 |
| 4. Análisis de competencia | Obligatorio para el top 5 | `criterios-base-ecuador-v1.0.md` §6 |
| 5. Ideas evaluadas | Candidatos con score, filtros, ranking, plan | `ranking-ideas-ecuador-v1.0.md` |

## Qué cambió frente a Aura International

El motor es el mismo; el contexto es distinto. Cuatro cambios estructurales:

1. **Dos criterios nuevos con peso:** Recurrencia/MRR (12%) y Encaje con canal propio TikTok+red (8%). En Ecuador el ticket es menor, así que retener importa más que cerrar grande, y el canal propio redefine el CAC.
2. **"Encaje con el equipo" deja de ser peso.** Con dos personas casi siempre es alto, no discrimina. Lo crítico se vuelve filtro duro.
3. **Filtro de jurisdicción eliminado.** En la UE nadie del equipo podía emitir dictamen legal; aquí el socio es abogado colegiado en Ecuador. La razón de ser del filtro desaparece.
4. **Concentración de riesgo pasa de peso a filtro duro:** si la entrega depende >70% de las horas de Danilo (part-time, único dev), la idea se pausa.

La tabla completa de mapeo de filtros está en `criterios-base-ecuador-v1.0.md` §5b.

## Las tres fuentes de ideas

| Fuente | Qué aporta |
|---|---|
| **Documento V2 del abogado** | Las 12 capas; cada una puede ser un producto/servicio independiente vendible hoy |
| **EnRegla** (activo construido) | Producto SaaS reutilizable: vender tal cual, mejorar, o white-label a estudios/contadores |
| **Servicios del abogado + canal TikTok** | Lo que el socio ya puede prestar (LOPDP, UAFE, societario) empaquetado y distribuido por su audiencia de 25k |

## Cómo se agrupan las ideas

| Grupo | Tipo | Función |
|---|---|---|
| A | Servicio vendible en <60 días | Cashflow inmediato (diagnósticos, manuales, implementaciones) |
| B | Híbrido servicio + producto | Aprender vendiendo y monetizar EnRegla como recurrente |
| C | Plataforma ambiciosa (visión V2) | Mantener el largo plazo; activar tras el primer cashflow |

## Los siete pasos de evaluación de cada idea

1. Describir la idea en una frase.
2. Identificar comprador, presupuesto y urgencia.
3. Definir la primera oferta vendible (y si admite preventa).
4. Revisar contra los 10 criterios ponderados.
5. Aplicar los filtros de descarte.
6. Si entra al top 5, producir el análisis de competencia.
7. Calcular el score ponderado.

El resultado incluye, además del ranking: por qué gana la #1, qué la haría fracasar, qué evidencia falta, qué validar en 14-30 días, qué dato obligaría a pivotar, lista/segmento de clientes y playbook de preventa.

## Gobierno simplificado (2 personas)

- **Semanal (15 min):** dashboard de leading indicators — videos TikTok + leads, outbound del abogado, reuniones, propuestas, preventas firmadas.
- **Mensual (30 min):** nota de cambios materiales (resoluciones de la Superintendencia de Protección de Datos, sujetos obligados UAFE, competidores, objeciones).
- **Re-ranking:** solo cuando la evidencia lo justifica (sin cadencia trimestral rígida).

## Próximo entregable

Después de aprobar este sistema:

1. Generar las ideas desde las tres fuentes.
2. Puntuar con los 10 criterios.
3. Aplicar filtros.
4. Producir top 5 con análisis de competencia.
5. Producir lista/segmento de clientes y playbook de preventa.
6. Generar `ranking-ideas-ecuador-v1.0.md` y `.html`.
7. **El equipo (Danilo + abogado) elige la idea.**
8. Solo entonces: plan de negocio de la idea elegida.
