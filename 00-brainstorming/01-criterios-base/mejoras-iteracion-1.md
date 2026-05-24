# Mejoras Iteracion 1

> **Estado:** versión final · loop de 5 pasadas completado  
> **Fecha:** 2026-05-24  
> **Proceso:** entrada = sistema actual (criterios + 40 criterios + 10 ponderados + filtros + competencia + ranking v1.1) · salida = palancas y ajustes accionables  
> **Archivos crudos de subagentes:** [`_subagentes-pasada-1/`](../_subagentes-pasada-1/)

## Resumen ejecutivo

El sistema de evaluación es sólido para elegir ideas, pero no responde la pregunta operativa siguiente: **cómo cerrar al primer cliente del top 5 en menos de 60 días, sin empresa constituida**. Esta iteración añade tres capas: palancas comerciales (12), ajustes al proceso (8) y assets fundacionales (lista de clientes, playbook venta sin empresa, validación externa). Tras priorizar por impacto sobre ingresos del primer trimestre, el plan inmediato cabe en un paquete de 14 días que combina tres palancas de pricing y pitch sobre la idea líder A1 Aura Compliance.

## Recomendación #1: plan de 14 días

Combinar palancas #12 + #2 + #1 sobre A1 Aura Compliance. Todo se ejecuta en el mismo deck, MSA y landing.

| Día | Acción | Owner |
|---:|---|---|
| 1-2 | Bastien inicia alta autónomo ES + ROI (modelo 036 casilla 582) | Bastien |
| 1-3 | Compra dominios `aura-int.eu` y `aura-international.com` + Google Workspace 4 cuentas | Danilo |
| 1-4 | Reescritura oferta A1: Audit Sprint 25k€ + Post-Audit Support obligatorio 3 meses (4.5k€) = ticket base 29.5k€ | Bastien + Danilo |
| 3-5 | Deck v0 (8 slides): anchor Big4 en slide 1, tier-pricing en slide 6 (Lite 15k€ / Standard 29.5k€ / Premium 55k€) | Danilo + Bastien |
| 4-6 | MSA + NDA + SOW base con cláusula de novation a NewCo | Joseph + abogado mercantil ES |
| 5-7 | Landing minimalista publicada en `aura-int.eu` | Danilo |
| 7-10 | Pre-engagement case study sobre una healthtech UE pública (Tucuvi, IOMED o Ada Health) | Bastien + Mariam |
| 7-14 | Outbound a primeros 30 prospects nominales (lista D) con cadencia diaria por fundador | Bastien + Danilo + Joseph + Mariam (sólo conversaciones científicas, sin facturación) |
| 10-14 | Founders' Pre-Inc Agreement firmado entre los 4 | Joseph + revisión externa |
| 12-14 | Primer LOI firmado con prospect tibio para usar como prueba social | Bastien |

Métrica de éxito de los 14 días: deck + landing + MSA listos + 5 conversaciones de descubrimiento abiertas + 1 LOI firmada.

Si al día 14 no hay LOI: revisar pitch antes de seguir; no avanzar a deals sin validación externa mínima.

## Top 3 palancas comerciales

### Palanca #12 - Retainer obligatorio post-audit (score 36.0)

- **Problema:** A1 termina mes 2 y el cliente queda sin contacto regular. El cross-sell a B5 mes 4-6 reabre presupuesto desde cero, compite con el pipeline interno del cliente y alarga o mata la conversión.
- **Propuesta:** incluir en cada SOW de A1 un Post-Audit Support de 3 meses (1.5k€/mes = 4.5k€ embebidos en el ticket). Cubre Q&A regulatorio + 1 update review trimestral. Convierte B5 en parte estructural del producto A1.
- **Métrica:** % de contratos A1 que incluyen el Post-Audit Support (objetivo: 100% desde día 1) + tasa de conversión a Watch anual al final del trimestre (objetivo: ≥60%).
- **Acción 14-30 días:** reescribir SOW template de A1 con la cláusula del Post-Audit como deliverable fijo. No es opcional, no se factura aparte.
- **Verificación:** al cierre del primer trimestre con A1 firmado, ≥1 cliente convierte automáticamente a Watch anual sin nuevo proceso de venta.
- **Riesgo y mitigación:** cliente puede rechazar el componente obligatorio. Mitigación: si rechaza Post-Audit, ofrecer Audit Sprint Lite 15k€ sin extras como alternativa, no negociar quitar el Post-Audit del Standard.

### Palanca #2 - Tier-pricing tres niveles con decoy (score 32.0)

- **Problema:** sin tier premium visible, el standard 25k€ funciona como techo. No hay upgrade orgánico ni efecto decoy.
- **Propuesta:** tres tiers desde día 1:
  - **Lite 15k€** (audit acotado, sin Post-Audit) - rara vez se vende, sirve para sostener el ancla bajo.
  - **Standard 29.5k€** (audit completo + Post-Audit 3 meses) - el target real, 70-80% de cierres.
  - **Premium 55k€** (audit + Post-Audit + sesión con abogado externo UE + dossier regulator-ready + 6 meses Watch incluidos) - decoy ofensivo; vende 1 de cada 5.
- **Métrica:** distribución de ventas por tier (target: 70% Standard, 20% Premium, 10% Lite) + ticket promedio (target: ≥30k€).
- **Acción 14-30 días:** producir 3 SOWs templates diferenciados + slide de pricing con los 3 lado a lado + decisión clara de "qué tier recomendamos para tu caso" en la conversación de cierre.
- **Verificación:** primeros 3 deals firmados tienen ticket promedio ≥30k€ y al menos 1 cierra Premium.
- **Riesgo y mitigación:** Premium puede asustar y matar la conversación si se presenta primero. Mitigación: presentar siempre en orden Lite → Standard → Premium, con Standard como recomendación verbal explícita.

### Palanca #1 - Anchor Big4 al inicio del pitch (score 31.5)

- **Problema:** el prospecto evalúa 25k€ sin referencia y lo percibe caro. Sin ancla explícito, la negociación arranca a la baja y el ciclo se alarga.
- **Propuesta:** convertir los benchmarks de Big4 (80-300k€) y de boutiques (Holistic AI/Credo AI 30-80k€) en la **slide 1** de cada deck y en la **primera frase** del cold email. Frase tipo: *"Big4 cotiza esto en 80-300k€ con plazo 4-6 meses. Boutiques sin verticalidad salud lo cotizan en 30-80k€. Nosotros entregamos en 4 semanas a 29.5k€ porque combinamos médico + abogado + PM Horizon + AI."*
- **Métrica:** % de propuestas que incluyen anchor explícito (target: 100%) + tiempo de cierre desde primera reunión hasta firma (target: ≤30 días).
- **Acción 14-30 días:** preparar slide ancla con datos de [`_subagentes-pasada-1/C-validacion-externa.md`](../_subagentes-pasada-1/C-validacion-externa.md) sección 1 + reescribir cold email template con el anchor en línea 1.
- **Verificación:** comparar tiempo de cierre con anchor versus sin anchor en próximos 3 deals. Objetivo: ≥30% más rápido con anchor.
- **Riesgo y mitigación:** prospecto puede contra-anchor con freemium (Fronterio €199/mes) o Vanta-class. Mitigación: añadir segundo anchor "para healthtech UE con dato clínico, Vanta y freemium no cubren AI Act ni MDR" + multa CEGEDIM €800k como recordatorio de coste real de no cumplir.

## Bonus: palanca #11 - Outbound LinkedIn multi-fundador (score 24.0)

Alimenta el funnel diario que las palancas anteriores requieren. Sin volumen top-of-funnel, no hay clientes a quienes aplicar pricing nuevo.

- **Problema:** el ranking trata la red como activo estático ("red Bastien Horizon", "red Mariam clínica"). No hay operación diaria distribuida ni scripts por nicho.
- **Propuesta:** asignación diaria por fundador:
  - **Mariam:** 5 jefes de innovación digital hospital UE o oncólogos GI clave por día - solo conversación científica, sin pitch comercial.
  - **Bastien:** 5 coordinadores Horizon Europe / EIT Health / IHI por día - pitch directo GrantOps + Aura Compliance.
  - **Joseph:** 5 in-house counsels healthtech UE por día - pitch como referido de Aura legal team.
  - **Danilo:** 5 CTOs / Heads of AI series A-B healthtech UE por día - pitch técnico AI Act + audit.
- **Métrica:** mensajes enviados/semana (target: 80) + tasa de respuesta (target: ≥10%) + reuniones agendadas/semana (target: ≥4).
- **Acción 14-30 días:** scripts por nicho (4 templates), CRM básico (Notion o Hubspot Free), reuniones semanales de 30 min para revisar pipeline.
- **Verificación:** al final del mes 1, ≥15 conversaciones de descubrimiento y ≥3 LOIs.
- **Riesgo y mitigación:** Mariam puede ser tildada de hacer publicidad médica si pitch comercial directo. Mitigación: solo conversaciones científicas/exploratorias, derivar comercial a Bastien.

## Top 2 ajustes al sistema

### Ajuste #3 - Leading indicators semanales (score 24.0)

- **Problema:** todos los pivots actuales del ranking son lagging (mes 2, mes 6). Si los leading van mal en semana 3, no hay mecanismo para reaccionar.
- **Propuesta:** añadir capa de monitoreo semanal con 5 indicadores:
  - mensajes outbound enviados/semana (objetivo: 80);
  - tasa de respuesta cold outreach (objetivo: ≥10%);
  - reuniones de descubrimiento celebradas/semana (objetivo: ≥4);
  - propuestas enviadas/mes (objetivo: ≥3);
  - LOIs/contratos firmados/mes (objetivo: ≥1 LOI mes 1, ≥1 contrato mes 2).
- **Métrica:** dashboard semanal del equipo con los 5 KPIs en Notion/Sheets.
- **Acción 14-30 días:** crear template Notion con tabla semanal + responsable: Bastien actualiza cada viernes.
- **Verificación:** durante 4 semanas, los KPIs muestran tendencia ascendente. Si 2 KPIs caen por debajo del 50% del objetivo dos semanas seguidas, se dispara ajuste de pitch o canal.
- **Riesgo y mitigación:** el dashboard se convierte en burocracia si nadie lo usa. Mitigación: revisión 15 min los viernes, con acción concreta al dejar la reunión.
- **Dónde se inserta:** nueva sección "Capa 8: monitoreo semanal" en `evaluation-process-v1.1.md` + ampliación de la sección "Criterios de pivot" en `ranking-ideas-v1.1.md` con umbrales semanales.

### Ajuste #4 - Cadencia de re-evaluación del ranking (score 22.5)

- **Problema:** el ranking está fechado como evento único. Sin calendario, queda estático y se descalibra frente al mercado.
- **Propuesta:** cadencia explícita en 3 niveles:
  - **Semanal:** revisión del dashboard de leading indicators (incluido en ajuste #3).
  - **Mensual:** re-validación de scoring por cambios en evidencia externa (ejecutar primer lunes de cada mes). 30 min.
  - **Trimestral:** re-ranking completo con re-puntuación de las 18 ideas + apertura formal a candidatos nuevos. Genera nuevo ranking versionado.
- **Métrica:** cada ciclo termina con archivo versionado (`ranking-ideas-v1.2.md`, `v1.3.md`, etc.) con commit en git.
- **Acción 14-30 días:** crear sección 9 en `criterios-base-ideas.md` titulada "Gobierno del modelo" con la cadencia + responsable + checklist.
- **Verificación:** primer re-ranking mensual ejecutado antes del 1 de julio 2026.
- **Riesgo y mitigación:** la cadencia se vuelve ceremonia sin tracción. Mitigación: cada cadencia requiere output (commit en git con archivo nuevo).
- **Dónde se inserta:** nueva capa en `evaluation-process-v1.1.md` + sección de gobierno del modelo en `criterios-base-ideas.md`.

## Assets fundacionales

Estos tres entregables habilitan todas las palancas anteriores. Existen como archivos crudos en [`_subagentes-pasada-1/`](../_subagentes-pasada-1/).

### Asset D - Lista de clientes potenciales

Archivo: [`_subagentes-pasada-1/D-clientes-potenciales.md`](../_subagentes-pasada-1/D-clientes-potenciales.md) (243 líneas, fuentes con URL).

Contenido aprovechable directo:

- **22 organizaciones Barcelona / Cataluña** (10 hospitales con dolor AI Act demostrado en prensa 2026 + 12 healthtechs con rondas confirmadas + ecosistema Biocat / BHH / CataloniaBio).
- **~30 organizaciones europeas** en 6 ciudades clave (Madrid, Berlín, Amsterdam, París, Bruselas, Estocolmo, Helsinki).
- **50 nominales segmentados** por idea del top 5 (10 por A1, A4, A2, B5, B1) con dolor específico y prioridad.

**Convocatoria activa relevante:** HORIZON-MISS-2026-02-CANCER, deadline 15 sep 2026, encaja con A2 GrantOps + B1 MedCases.

**Decisión inmediata:** los 30 prospects de la palanca #11 salen de esta lista. Empezar por los 5 hospitales BCN top (Clínic, Vall d'Hebron, Bellvitge, Sant Joan de Déu, Sant Pau).

### Asset E - Playbook venta sin empresa

Archivo: [`_subagentes-pasada-1/E-playbook-venta-sin-empresa.md`](../_subagentes-pasada-1/E-playbook-venta-sin-empresa.md) (695 líneas con fuentes).

Decisiones aprobables hoy:

- **Vehículo de facturación:** Bastien autónomo ES con tarifa plana ~88€/mes + alta ROI. Emite factura única al cliente UE con inversión sujeto pasivo (Art. 196 Directiva 2006/112/CE). Danilo y Joseph facturan a Bastien desde RUC Ecuador con IVA 0% (exportación de servicios).
- **Mariam NO factura** ni aparece como cofundadora públicamente hasta tener autorización de compatibilidad por escrito de su hospital. Framing seguro mientras tanto: "Scientific Advisor" o "Medical Advisor". Validación obligatoria con Metges de Catalunya antes de cualquier paso.
- **Contratos:** MSA persona-física + NDA + SOW con cláusula de novation a NewCo (clave para migrar contratos a la SL futura sin renegociar).
- **Trigger para constituir SL:** cumplir 2 de 3 - ≥2 contratos firmados con ≥60k€ facturados / 3 meses sin pivote / prospect exige proveedor societario.
- **Jurisdicción ganadora:** SL exprés en España vía CIRCE 2.0 (~500€ total, NIF en 48-72h, IS bonificado al 15% los 2 primeros ejercicios).
- **Coste estructural pre-empresa 12 meses:** ~3.890€ sin abogado UE retainer, ~9.890€ con retainer parcial - holgado dentro del bootstrap 21-31k USD.

**8 puntos marcados como VALIDAR con asesor local** antes de ejecutar - listados en el archivo crudo.

### Asset C - Validación externa

Archivo: [`_subagentes-pasada-1/C-validacion-externa.md`](../_subagentes-pasada-1/C-validacion-externa.md) (121 líneas con URLs).

Datos accionables para integrar al deck:

- **Big4 inaccesibles:** floor estructural ~$500k USD. Deals típicos $500k-$3M primer año. Refuerza palanca #1 (anchor).
- **Comparables públicos:** Vanta ~$300M ARR, Drata ~$98M ARR, Kertos €14M Series A, Copla €6M Series A, **Ketryx $39M (regulated AI en MedTech)**. El mercado está validado y financiado.
- **Multa ancla:** CNIL vs CEGEDIM Santé **€800.000** (sept 2024) por uso no autorizado de teleservicio para datos de salud sin autorización. Caso ancla en cada propuesta para vender urgencia.
- **AI Act enforcement:** fines provision aplica desde 2 agosto 2026. Sin multas mayores confirmadas a Q1 2026. Se vende el deadline, no los castigos.
- **Conferencias prioritarias 2026:** HIMSS26 Europe (Copenhague, 19-21 mayo 2026, pase exec €1.7k-€2.5k), BIO-Europe (Colonia, 9-11 nov, exhibitor package €5.670), EU R&I Days (Bruselas, gratuito).
- **Partners legales referidores:** DLA Piper, Hogan Lovells, Cuatrecasas. Comisión estándar 10-20% año 1.
- **Riesgo competitivo:** Ketryx ya cubre MedTech regulado mejor; segmento underserved donde Aura puede ganar es **digital health SaaS no-device + biotech early**.

## Ajustes recomendados al sistema (para iteraciones futuras)

Se levantan aquí pero **no se ejecutan en esta iteración** (restricción explícita del plan de pasada 1). Pendiente decisión del usuario sobre aplicar después.

### En `criterios-base-ideas.md`

- Reforzar criterio 4.8 "Encaje suficiente con el equipo" con sub-criterio "Concentración de riesgo de entrega" (% de horas requeridas a un solo fundador).
- Añadir filtro de descarte 5.7: "jurisdicción del comprador exige vehículo legal o licencia profesional que el equipo no posee".
- Añadir filtro 5.8: "sin lista de prospectos nombrada ≥10 antes de iniciar".
- Añadir sección 9 "Gobierno del modelo" con cadencia semanal/mensual/trimestral.
- Añadir estado "muerta" en la sección de lectura del resultado con criterios para descartar definitivamente.

### En `evaluation-process-v1.1.md`

- Nueva capa 8: monitoreo semanal con 5 KPIs.
- Nueva capa 9: cadencia de re-evaluación (mensual + trimestral).

### En `ranking-ideas-v1.1.md` (próxima versión `v1.2`)

- Sección "Criterios de pivot" ampliada con triggers de escalado además de los de abandono.
- Sección "Estrategia recomendada" reescrita con umbrales numéricos para activación de cada idea (no "mes 4-6 si bandwidth", sino "activar B5 cuando A1 tenga ≥2 contratos firmados").

## Próximos pasos

1. **Aprobar la recomendación #1** (plan de 14 días) y empezar a ejecutar.
2. **Revisar archivos crudos** [`_subagentes-pasada-1/D-clientes-potenciales.md`](../_subagentes-pasada-1/D-clientes-potenciales.md) y [`_subagentes-pasada-1/E-playbook-venta-sin-empresa.md`](../_subagentes-pasada-1/E-playbook-venta-sin-empresa.md) con los 4 fundadores; señalar discrepancias.
3. **Decidir si los ajustes al sistema se aplican ahora o en iteración 2.** Recomendación: aplicar #3 (leading indicators) + #4 (cadencia) antes de la próxima venta para que el dashboard ya esté operando durante la palanca #11.
4. **Definir si se ejecuta iteración 2** (`mejoras-iteracion-2.md`) o se valida iteración 1 antes con primer cliente real.

## Bitácora de las 5 pasadas

| Pasada | Acción | Resultado |
|---:|---|---|
| 1 | Diagnóstico amplio con 5 subagentes paralelos | 12 palancas (A) + 8 gaps (B) + validación externa (C) + lista de clientes (D) + playbook venta sin empresa (E) |
| 2 | Validación contra criterios + ponderados + filtros + competencia + ranking | 0 redundantes; 2 reclasificados como PARCIALMENTE CUBIERTO; los 20 candidatos sobreviven |
| 3 | Priorización por impacto / esfuerzo / probabilidad / encaje | Top 3 palancas (#12, #2, #1) + bonus #11 + top 2 ajustes (#3, #4) |
| Checkpoint | Aprobación del usuario para seguir | Usuario aprobó sin ajustes |
| 4 | Concreción accionable: métrica + ubicación + acción 14-30 días + verificación + riesgo | 9 items concretados (4 palancas + 2 ajustes + 3 assets) |
| 5 | Pulido final: reescritura sin discurso, foco en evidencia + acción | Documento final con recomendación #1 + plan de 14 días |

---

**Fin de iteración 1.** Decisión pendiente del usuario sobre aplicar mejoras al sistema o validar primero con cliente real.
