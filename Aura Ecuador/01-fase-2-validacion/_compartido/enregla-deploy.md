# Deploy productivo de EnRegla — checklist Fase 2

> **Objetivo:** EnRegla en URL viva con una demo mostrable en discovery calls y videos. No es construir features nuevas — es **poner lo que ya existe en vivo** y prepararlo para demo.
> **Owner:** Danilo. **Plazo:** semana 1 (pico técnico aceptable según filtro F6).

## Checklist de deploy

- [ ] Repo de EnRegla (`C:\dev\enregla`) revisado: build productivo OK.
- [ ] Hosting elegido (Vercel/Netlify/VPS) + dominio o subdominio (p.ej. `app.auracompliance.ec` o similar).
- [ ] Variables de entorno productivas (sin secretos en repo).
- [ ] Base de datos productiva provisionada + migraciones aplicadas.
- [ ] HTTPS activo.
- [ ] Usuario demo con datos de ejemplo cargados (empresa ficticia con obligaciones y vencimientos).
- [ ] Smoke test: login, ver dashboard, ver vencimiento próximo, recibir recordatorio.

## Guion de demo (3 min, para discovery call / video)

1. **Dashboard:** "Aquí ves todas tus obligaciones de protección de datos en un solo lugar, con semáforo."
2. **Vencimiento:** "Esta obligación vence en X días — EnRegla te avisa antes, no te enteras tarde."
3. **Registro de tratamientos:** "Tu registro de actividades, siempre actualizado y exportable si la Superintendencia lo pide."
4. **Cierre:** "Esto es lo que incluye el retainer. Tu abogado externo + este sistema, por $190/mes."

## Datos demo a cargar
- 1 empresa ficticia (sector clínica, alto riesgo).
- 6–8 obligaciones con distintos estados (al día / por vencer / vencida).
- 1 recordatorio configurado para mostrar la notificación en vivo.

## Nota de seguridad
- No usar datos reales de nadie en la demo.
- La cuenta demo es de solo lectura o reseteo automático.
- Cumplir LOPDP en el propio formulario de la landing (predicar con el ejemplo): aviso de privacidad + base legal del contacto.
