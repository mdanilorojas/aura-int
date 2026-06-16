# Aura Compliance Design System (ACDS) v1.0

> Sistema de diseño para todas las páginas de Aura Compliance EC.
> **Base:** IBM Carbon (dark). **Orientación:** cumplimiento, confianza, conversión.
> **Archivo:** [`aura-compliance.css`](aura-compliance.css). **Showcase:** [`showcase.html`](showcase.html).

## Principio rector

> **Lo único que importa es que las páginas conviertan.**

Cada componente existe para una de tres metas, en este orden:
1. **Credibilidad** — que un dueño de PYME crea que somos serios (abogado real, sistema real).
2. **Claridad** — que entienda el riesgo y la oferta en segundos.
3. **Acción** — que dé el siguiente paso (diagnóstico gratis).

## Identidad

- **Tono visual:** sobrio, técnico, "esto es legal y serio" — Carbon encaja: institucional sin ser aburrido.
- **Color de marca:** azul Carbon (`--blue-60` #0f62fe) para acción/confianza.
- **Firma del sistema:** el **semáforo de riesgo** (rojo/amarillo/verde) — es el lenguaje visual del cumplimiento y aparece en informe, landing y discovery.
- **Verde "tranquilidad"** (`--trust` #42be65) para señales positivas (✓, prueba social).
- **Rojo riesgo** (`--risk-high` #da1e28) solo para urgencia/multa — no abusar, pierde fuerza.
- **Tipografía:** IBM Plex Sans (UI) + IBM Plex Mono (cifras, código).

## Componentes (clases)

| Componente | Clase | Para qué (conversión) |
|---|---|---|
| Barra de alerta | `.alert-bar` | Urgencia inmediata arriba del fold |
| Hero + trust-row | `.hero`, `.trust-row` | Credibilidad en los primeros 3s |
| Botón CTA | `.btn--primary`, `.btn--lg`, `.btn--block` | Acción clara, repetida |
| Semáforo riesgo | `.risk--high/mid/low`, `.risk-list` | Lenguaje de cumplimiento, hace tangible el problema |
| Pasos | `.steps` | Bajar la fricción ("solo 3 pasos") |
| Precios | `.pricing`, `.plan.feat` | Precio claro = menos abandono |
| Calculadora de multa | `.calc` | Lead magnet: personaliza el dolor con su cifra |
| Formulario | `form.acds` | Captura; campos mínimos |
| Prueba social | `.quote`, `.logos` | Credibilidad (insertar casos fundadores) |
| Cupos fundadores | `.cupos` | Escasez real → urgencia |
| FAQ | `.faq details` | Resolver objeción antes de que frene |
| Sticky CTA móvil | `.sticky-cta` | El CTA siempre a la vista en celular |

## Reglas de conversión (aplican a toda landing)

1. **Un solo CTA primario**, repetido 3+ veces (hero, mitad, cierre, sticky móvil).
2. **El dolor antes que la solución**: multa → brechas → oferta.
3. **Prueba social arriba del precio** (credibilidad antes de pedir plata).
4. **Formulario corto**: nombre, empresa, sector, WhatsApp, correo. Nada más.
5. **Cifra concreta siempre**: "1% de tu facturación", no "multas altas".
6. **Móvil primero**: la mayoría llega desde TikTok en celular → sticky CTA obligatorio.
7. **Velocidad**: CSS único compartido, sin dependencias externas (CDN flaky = abandono).

## Uso

```html
<link rel="stylesheet" href="RUTA/_compartido/design-system/aura-compliance.css">
```
Ajustar `RUTA` según profundidad. Desde una landing en `B2-aura-compliance/`:
```html
<link rel="stylesheet" href="../_compartido/design-system/aura-compliance.css">
```

## Versión y cambios
- **v1.0** — tokens Carbon + componentes de cumplimiento/conversión. Landings A1/A2/B2 migran a este CSS (dejan de inline-stylear).
