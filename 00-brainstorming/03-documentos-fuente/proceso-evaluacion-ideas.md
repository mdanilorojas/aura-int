# Proceso de generacion y evaluacion de ideas

> **Estado:** sintesis operativa  
> **Proposito:** explicar como se llego de un brainstorming amplio al ranking de ideas y como se debe regenerar una version futura.

## Resumen corto

El proceso original partio de una pregunta amplia: que negocio puede construir un equipo de 4 profesionales con perfiles complementarios, capital bootstrap limitado, ubicacion Quito-Barcelona y ambicion internacional.

El resultado inicial fue una lista de ideas en salud, IA, compliance, oncologia, datos, proyectos europeos y productos digitales. Luego esas ideas se filtraron con criterios de viabilidad, riesgo, mercado, equipo, monetizacion y timing. Finalmente, el HTML v1.1 presento una recomendacion: **Aura Compliance** como primera apuesta, con **MedCases EU** y **GrantOps** como alternativas o expansiones.

La version v2/v3 debe conservar el aprendizaje, pero recalibrar el scoring hacia **rentabilidad rapida y maxima con encaje suficiente del equipo**.

## Donde esta la informacion actual

| Archivo | Que contiene | Uso recomendado |
|---|---|---|
| `Kickoff doc v1.md` | Documento largo inicial con contexto, perfiles, ideas y prompts tempranos | Archivo historico |
| `Kickoff doc v1.1.md` | Version estructurada: contexto, equipo, gobernanza, 40 criterios, preguntas challenge y prompts | Fuente principal del brainstorming original |
| `Kickoff doc v1.1 - Parte II - Recomendacion.md` | Ranking de 18 ideas, framework de 5 lentes, top 3, roadmap y decision recomendada | Fuente principal del ranking v1.1 |
| `../02-visuales-generados/Kickoff doc v1.1.html` | Presentacion visual navegable del analisis | Base visual para regenerar HTML v2/v3 |
| `../01-criterios-base/criterios-base-ideas.md` | Criterios editables y pesos para recalibrar el scoring | Fuente principal para futuras regeneraciones |

## Proceso usado en v1/v1.1

### 1. Definir contexto del equipo

Se documento:

- quienes son los 4 participantes;
- habilidades principales;
- capital disponible;
- disponibilidad de tiempo;
- tolerancia al riesgo;
- ubicacion geografica;
- intereses y limitaciones personales.

Esto sirvio para evitar ideas genericas y enfocar oportunidades donde el equipo pudiera tener una ventaja real.

### 2. Definir filtros de entrada

Se establecio que el negocio ideal debia:

- ser realista;
- ser escalable;
- usar IA como multiplicador, no como gimmick;
- poder empezar pequeno;
- generar cashflow relativamente rapido;
- tener potencial internacional;
- aprovechar habilidades reales del equipo;
- operar parcialmente remoto;
- tener barreras competitivas.

Tambien se descartaron de entrada ideas como dropshipping, SaaS generico, agencias saturadas, marketplaces sin diferenciacion y negocios ultra regulados sin ventaja clara.

### 3. Generar ideas con prompts dirigidos

El documento v1.1 incluyo prompts para generar ideas usando el contexto del equipo. Esos prompts pedian ideas en tres grupos:

| Grupo | Tipo de idea | Objetivo |
|---|---|---|
| A | Servicios o consultoria con MVP en menos de 60 dias | Cashflow rapido |
| B | Hibridas servicio + producto digital | Aprender vendiendo y convertir en producto |
| C | SaaS o plataformas ambiciosas | Potencial mayor, pero mas lento |

### 4. Evaluar con 40 criterios

La version v1.1 definio 40 criterios amplios: problema, cliente, dolor, presupuesto, urgencia, mercado, demanda, competencia, diferenciacion, oferta inicial, modelo, precio, rentabilidad, CAC, canales, ciclo de venta, ejecucion, credibilidad, MVP, validacion, legal, operaciones, escalabilidad, tesoreria, riesgos, timing, retencion, metricas, compatibilidad personal y vision de largo plazo.

Estos 40 criterios sirven como checklist completo, pero no todos deben pesar igual.

### 5. Reducir a un framework de ranking

La Parte II redujo la evaluacion a 5 lentes:

| Lente v1.1 | Peso v1.1 | Observacion actual |
|---|---:|---|
| Encaje del equipo | 25% | Pesaba demasiado si el objetivo principal es dinero rapido |
| Cliente con presupuesto y urgencia | 25% | Sigue siendo critico |
| Defensibilidad | 20% | Importante, pero no debe bloquear ventas tempranas |
| Capital eficiente | 15% | Sigue siendo importante |
| IA como multiplicador real | 15% | Importante, pero no por encima de monetizacion |

Ese framework favorecio ideas que aprovechaban a los 4 perfiles y tenian buena narrativa estrategica. Fue util para ordenar el brainstorming, pero ahora debe recalibrarse hacia cashflow.

### 6. Seleccionar top 3

El ranking v1.1 dejo como top 3:

| Ranking | Idea | Razon principal |
|---:|---|---|
| 1 | Aura Compliance | AI Act + RGPD + salud, cliente B2B con urgencia, oferta consultiva vendible |
| 2 | MedCases EU | Expertise medico, farma/Medical Affairs, producto de conocimiento premium |
| 3 | GrantOps | Red europea, proyectos Horizon/IHI, posible retainer operativo |

La recomendacion fue lanzar primero Aura Compliance y luego activar MedCases EU o GrantOps segun traccion.

## Recalibracion v2/v3

El nuevo scoring debe cambiar la pregunta central.

Antes:

> Que idea aprovecha mejor los 4 perfiles y tiene una ventaja estrategica defendible?

Ahora:

> Que idea puede generar mas dinero, mas rapido, con margen alto, riesgo controlado y suficiente encaje del equipo?

## Nuevo flujo para regenerar HTML v2/v3

1. Editar `../01-criterios-base/criterios-base-ideas.md`.
2. Confirmar pesos y filtros de descarte.
3. Re-evaluar las 18 ideas existentes con esos pesos.
4. Si hace falta, agregar nuevas ideas candidatas.
5. Recalcular ranking.
6. Reescribir la recomendacion:
   - idea #1;
   - top 3;
   - razones de descarte;
   - plan de validacion de 14-30 dias;
   - criterios de pivot.
7. Regenerar el documento de ranking de ideas.
8. Regenerar el HTML visual de ranking en `../02-visuales-generados/`, usando el estilo visual de `../02-visuales-generados/Kickoff doc v1.1.html`.

## Regla de decision para la siguiente version

Una idea no debe ganar por ser elegante, completa o intelectualmente atractiva. Debe ganar porque:

- se puede vender pronto;
- alguien tiene presupuesto;
- el ticket justifica el esfuerzo;
- el margen es alto;
- el riesgo es manejable;
- el equipo puede ejecutarla sin contratar mucho;
- crea aprendizaje o activos que permitan escalar despues.

## Hipotesis a validar ahora

**Aura Compliance** sigue siendo la hipotesis lider, pero debe probarse contra el nuevo scoring. La pregunta no es "suena bien?", sino:

> Puede Aura Compliance producir el primer contrato pagado mas rapido y con mayor margen que MedCases EU, GrantOps u otra idea nueva?

Si la respuesta es si, se mantiene como spearhead. Si no, se reordena el ranking.
