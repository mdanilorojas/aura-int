# Pricing y margen — B2 / A1 / A2

> **Propósito:** validar que el precio resiste el análisis de margen real y definir cuántos clientes hacen falta para cubrir el tiempo de Danilo (10–15h/sem, único desarrollador) y pagar al abogado.
> **Moneda:** USD (Ecuador usa USD). Cifras de trabajo, ajustar con datos reales.

## 1. Tabla de precios

| Oferta | Precio | Anticipo | Recurrencia |
|---|---:|---|---|
| Diagnóstico (A1 / entrada de B2) | $390 (fundador $290) | 50% | — |
| Retainer "Cumplimiento al día" (B2) | $190/mes (fundador $140) | 1er mes | mensual, mín. 6 m |
| Implementación (A2) Básico | $1.500 | 50% | → termina en B2 |
| Implementación (A2) Estándar | $2.500 | 50% | → termina en B2 |
| Implementación (A2) Completo | $3.500 | 50% | → termina en B2 |

## 2. Costo de entrega (estimado por unidad)

| Concepto | Diagnóstico | Retainer/mes | Implementación Est. |
|---|---:|---:|---:|
| Horas abogado | 4h | 1h | 16h |
| Horas Danilo (producto/automatización) | 0.5h | 0.25h | 4h |
| Costo IA + EnRegla (infra prorrateada) | $5 | $8 | $15 |
| **Costo directo aprox.** (abogado $35/h, Danilo $0 oport.) | ~$145 | ~$43 | ~$575 |
| **Margen bruto** | **~63%** | **~77%** | **~77%** |

> El retainer es el de mayor margen porque EnRegla automatiza el seguimiento: la hora del abogado baja con cada mes. Confirma la tesis del ranking (recurrencia + apalancamiento EnRegla).

## 3. Punto de equilibrio (¿cuántos clientes?)

**Supuesto de costos fijos mensuales del negocio en Fase 2:** ~$300 (infra EnRegla productivo, dominio, herramientas, ads mínimos). El abogado y Danilo no se pagan sueldo aún (reinversión).

| Escenario | Retainers activos | MRR | Diagnósticos/mes | Ingreso total/mes |
|---|---:|---:|---:|---:|
| Supervivencia | 3 | $570 | 2 ($780) | ~$1.350 |
| Tracción | 8 | $1.520 | 4 ($1.560) | ~$3.080 |
| Meta 90 días | ≥3 retainers + flujo de diagnósticos | $570+ | 4–6 | $2.000–3.500 |

**Lectura:** con **3 retainers + 2 diagnósticos/mes** ya se cubre el costo fijo y queda margen. La meta de 90 días del ranking (≥3 retainers) es el umbral de viabilidad, no de éxito.

## 4. Límite de capacidad (cuello de botella = horas)

- **Abogado** (más horas disponibles): a 4h/diagnóstico + 1h/retainer/mes, con ~60h/mes puede sostener ~8 retainers (8h) + ~12 diagnósticos (48h). Techo de entrega antes de contratar: **~12 clientes activos**.
- **Danilo** (10–15h/sem ≈ 50h/mes): la entrega recurrente le toma poco (EnRegla automatiza); su tiempo va a producto, landing, automatización. **No es el cuello de botella en la operación** mientras no haya que construir features nuevas (filtro F6 respetado).

**Implicación:** el límite es el tiempo de venta+entrega del abogado, no el de Danilo. Cuando se llegue a ~10 clientes, el siguiente paso es **productizar más** (plantillas por sector) o sumar un paralegal, no más horas de Danilo.

## 5. Sensibilidad de precio (para el gate)

Si el precio frena el cierre, palancas en orden:
1. Diagnóstico fundador a **$290** (ya contemplado).
2. Retainer fundador a **$140/mes** (margen aún ~68%).
3. Diagnóstico **gratis a cambio de compromiso de retainer** (el diagnóstico como CAC del MRR) — solo si el MRR cierra.
4. **Nunca** bajar de $120/mes en retainer: por debajo el margen no cubre la hora del abogado a escala.

## 6. Qué validar en Fase 2 sobre pricing
- ¿$390 frena el diagnóstico? (medir % cierre tras discovery)
- ¿$190/mes frena el retainer? (medir % diagnóstico→retainer, meta ≥30%)
- ¿El cliente percibe el retainer como caro o barato vs la multa? (escuchar objeciones)
- Margen real tras las primeras 3 entregas (¿las horas estimadas se cumplen?).
