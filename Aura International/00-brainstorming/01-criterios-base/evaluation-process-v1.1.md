# Proceso de evaluacion de ideas v1.1

> **Estado:** fuente para visual HTML  
> **Version:** Evaluation Process v1.1  
> **Proposito:** explicar el sistema que convierte objetivos del equipo en criterios de evaluacion, genera ideas, las puntua y produce una recomendacion accionable.

## Resumen ejecutivo

La version 1.1 sirvio para ordenar el brainstorming inicial y proponer una primera recomendacion: **Aura Compliance** como spearhead, con **MedCases EU** y **GrantOps** como alternativas o expansiones.

Esta version mejora el foco. Ya no se trata solo de encontrar la idea que mejor encaja con los 4 perfiles. Ahora el objetivo dominante es:

> Encontrar la idea que pueda generar mas dinero, mas rapido, con margen alto, riesgo controlado y suficiente encaje del equipo.

Para evitar confusion, el sistema separa cinco capas:

1. **Criterios base:** objetivos editables del equipo.
2. **40 criterios de evaluacion:** checklist completo para revisar cada idea.
3. **10 criterios ponderados:** sintesis ejecutiva para calcular score y ranking.
4. **Filtros de descarte:** reglas duras que pausan ideas con bloqueos criticos.
5. **Ideas evaluadas:** candidatos de negocio que reciben score, filtros, ranking y plan de validacion.

## Capa 1: criterios base

Los criterios base son la entrada del sistema. Viven en:

`../01-criterios-base/criterios-base-ideas.md`

Este archivo responde:

- que queremos maximizar;
- que estamos dispuestos a sacrificar;
- que riesgos no aceptamos;
- cuanto pesa el dinero rapido frente al largo plazo;
- cuanto importa el encaje con los 4 roles;
- que debe descartar una idea automaticamente.

El usuario puede editar ese archivo manualmente antes de pedir una nueva version del HTML.

## Capa 2: 40 criterios de evaluacion

Los 40 criterios son el checklist completo. Sirven para no olvidar dimensiones importantes antes de rankear:

| Area | Criterios incluidos |
|---|---|
| Problema y cliente | 1. Problema real, 2. Cliente objetivo, 3. Necesidad y dolor, 4. Poder adquisitivo, 5. Urgencia de compra |
| Mercado y demanda | 6. Tamano del mercado, 7. Demanda real, 8. Competencia, 9. Diferenciacion, 10. Propuesta de valor |
| Monetizacion | 11. Oferta inicial, 12. Modelo de negocio, 13. Precio, 14. Rentabilidad, 15. Coste de adquisicion |
| Ventas y ejecucion | 16. Canales de venta, 17. Ciclo de venta, 18. Capacidad de ejecucion, 19. Equipo y socios, 20. Credibilidad |
| Validacion y posicionamiento | 21. MVP, 22. Validacion de mercado, 23. Posicionamiento, 24. Marca y comunicacion, 25. Legal y administrativo |
| Riesgo y operaciones | 26. Riesgo regulatorio, 27. Propiedad intelectual, 28. Operaciones, 29. Escalabilidad, 30. Tesoreria |
| Entrada al mercado | 31. Riesgos principales, 32. Timing, 33. Estrategia de entrada, 34. Primeros clientes, 35. Prueba social |
| Recurrencia y vision | 36. Retencion y recurrencia, 37. Satisfaccion, 38. Metricas, 39. Compatibilidad personal, 40. Vision a largo plazo |

## Capa 3: 10 criterios ponderados

Los 10 criterios ponderados son la sintesis ejecutiva de los 40 criterios. Se usan para calcular score comparable entre ideas:

| # | Criterio | Peso |
|---:|---|---:|
| 1 | Potencial de ingresos rapidos | 18% |
| 2 | Urgencia y presupuesto del cliente | 14% |
| 3 | Velocidad de venta inicial | 13% |
| 4 | Margen y eficiencia operativa | 12% |
| 5 | Facilidad de MVP vendible | 10% |
| 6 | Riesgo controlado | 9% |
| 7 | Diferenciacion y defensibilidad | 8% |
| 8 | Encaje suficiente con el equipo | 6% |
| 9 | Potencial de expansion | 5% |
| 10 | Timing estrategico | 5% |

Total: **100%**.

Cada idea recibe una nota de 1 a 10 por criterio. El score ponderado se calcula asi:

`score final = suma(nota del criterio x peso del criterio)`

## Capa 4: filtros de descarte

Los filtros de descarte no son pesos. Son reglas duras. Una idea puede tener buen score, pero quedar pausada si falla en algo critico.

Filtros actuales:

- sin comprador claro;
- sin primera oferta vendible en menos de 60 dias;
- riesgo clinico alto;
- CAC incierto o alto;
- margen artesanal;
- capital inicial excesivo.

## Capa 5: analisis detallado de competencia

Obligatorio en cada iteracion para las ideas del top 5 y cualquier candidata a #1. Estructura por idea:

- competidores directos;
- competidores indirectos / sustitutos;
- alternativa interna del cliente;
- posicion de Aura frente a cada uno;
- defensibilidad concreta (que no se puede copiar en 3-6 meses);
- riesgo competitivo y mitigacion.

Este analisis justifica la nota del criterio 4.7 (Diferenciacion y defensibilidad). Sin evidencia concreta, la nota no puede ser alta.

## Capa 6: generacion de ideas

Las ideas se generan desde el contexto del equipo, los criterios base y los sectores donde puede haber ventaja:

- salud;
- oncologia;
- AI Act;
- RGPD;
- compliance;
- datos medicos;
- proyectos europeos;
- herramientas digitales;
- IA aplicada a operaciones.

Las ideas se agrupan para no comparar cosas incompatibles:

| Grupo | Tipo | Funcion |
|---|---|---|
| A | Servicio/consultoria vendible en menos de 60 dias | Buscar cashflow inmediato |
| B | Hibrido servicio + producto | Aprender vendiendo y construir activos |
| C | Plataforma/SaaS mas ambicioso | Mantener opciones de largo plazo |

## Capa 7: evaluacion

Cada idea se evalua en estos pasos:

1. Se describe la idea en una frase.
2. Se identifica comprador, presupuesto y urgencia.
3. Se define primera oferta vendible.
4. Se revisa contra los 40 criterios.
5. Se aplican filtros de descarte.
6. Si la idea entra al top 5, se produce su analisis detallado de competencia.
7. Se puntua con los 10 criterios ponderados.

El resultado no es solo un ranking. Tambien debe incluir:

- por que gana la idea #1;
- que haria fracasar esa idea;
- que evidencia falta;
- que hay que validar en 14-30 dias;
- que dato nos obligaria a pivotar.

## Lectura del ranking

| Score final | Decision |
|---:|---|
| 8.5-10 | Prioridad inmediata |
| 7.5-8.4 | Candidata fuerte |
| 6.5-7.4 | Backup o expansion posterior |
| < 6.5 | Pausar salvo evidencia nueva |

## Diferencia frente a v1.1

En v1.1, el ranking favorecia el encaje completo del equipo y la narrativa estrategica.

En esta version, el ranking favorece:

- cashflow temprano;
- ticket alto;
- margen;
- comprador claro;
- velocidad de cierre;
- MVP vendible sin construir demasiado;
- riesgo controlado;
- encaje suficiente, no perfecto.

## Hipotesis actual

**Aura Compliance** sigue siendo la hipotesis lider, pero ahora debe ganar bajo el nuevo scoring.

La pregunta central es:

> Puede Aura Compliance producir el primer contrato pagado mas rapido y con mayor margen que MedCases EU, GrantOps u otra idea nueva?

Si si, se mantiene como spearhead.

Si no, el ranking debe cambiar.

## Proximo entregable

Despues de aprobar este sistema visual, el siguiente paso es generar el ranking de ideas:

1. Releer criterios base.
2. Revisar las ideas contra los 40 criterios.
3. Aplicar filtros de descarte.
4. Re-evaluar las 18 ideas.
5. Agregar nuevas ideas si aparecen.
6. Producir analisis detallado de competencia del top 5.
7. Calcular scores ponderados con los 10 criterios ejecutivos.
8. Generar `ranking-ideas-v1.1.md`.
9. Generar `ranking-ideas-v1.1.html`.
