# Subagente C — Validación Externa (Pasada 1)

**Misión:** Validar ideas A1 (Aura Compliance), A4, A2, B5, B1 con evidencia pública.
**Fecha:** 2026-05-24
**Método:** WebSearch (rangos y URLs citadas; cuando no hay dato público se reporta "No encontrado").

> **Disclaimer:** Todos los rangos son referencias públicas a fecha de búsqueda; no proyecciones propias. Los engagements reales se cotizan a medida.

---

## 1. Benchmarks pricing AI Act compliance UE 2026

### Big 4 (Deloitte / EY / KPMG / PwC)
- **Floor estructural:** Ninguna de las Big 4 publica precios. Las plataformas de AI/governance (Deloitte Zora, PwC Agent OS, EY.ai) entran como parte de engagements de consultoría con **piso analista-estimado de ~$500k USD** y rangos típicos $500k–$3M el primer año; deployments enterprise habituales 7 cifras / 18 meses ([nextbestaction.ai](https://nextbestaction.ai/insights/big-four-pricing-audit/)).
- **Auditoría tradicional Big 4** (no AI Act): $100k+ piso incluso para empresas pequeñas; $250k–$500k+ para SaaS midmarket $150–250M revenue ([onlycfo.io](https://www.onlycfo.io/p/ai-is-coming-for-audit-fees-kpmg)).
- **Implicación:** Para una healthtech series A-B (10–50 empleados), Big 4 es estructuralmente inaccesible — la matemática de partner-track no cuadra debajo de ~$200k.

### Boutiques / plataformas AI governance
- **OneTrust** — Sin precio público; tiered por "admin users + AI inventory size"; quote-based ([onetrust.com/pricing](https://www.onetrust.com/pricing/)).
- **Credo AI** — Sin precio público; vendido vía sales; benchmarks industria describen contratos típicos en "six figures annually" (~$100k+ ARR) en AWS Marketplace 12/24/36 meses ([agentsindex.ai](https://agentsindex.ai/compare/credo-ai-vs-holistic-ai)).
- **Holistic AI** — Quote-based; orientado a auditorías rigurosas tipo banca regulada ([fronterio.com](https://fronterio.com/no/blog/ai-governance-platform-comparison-credo-fairly-holistic-fronterio)).
- **Fronterio** — Outlier: tier Free incluye baseline EU AI Act; Pro €199/mes flat. Competidores arrancan en €10k/año + ciclo de procurement ([fronterio.com](https://fronterio.com/no/blog/ai-governance-platform-comparison-credo-fairly-holistic-fronterio)).
- **Vanta / Drata** — ACV típico ~$13.5k según cohort de SOC2 (Sacra). Rango Drata $10–40k/año, Secureframe $10–50k/año ([sacra.com/c/drata](https://sacra.com/c/drata/), [silentsector.com](https://silentsector.com/blog/drata-vs-vanta-secureframe)).

### ¿Healthtech series A-B paga 25k€? Evidencia
- **Modelo CEPS / SME analysis 2026:** healthtech "high-risk provider" estimado **€200k–€600k inicial + €80k–€150k/año** (Q​MS, post-market monitoring, conformity assessment €9.5k–€14.5k por sistema, legal retainer €20–40k/año) ([ovidiusuciu.com](https://ovidiusuciu.com/eu-ai-act-compliance-costs-smes-2026-and-beyond/)).
- **Cost-bundle típico mid-market** desplegando AI bajo SOC2 + HIPAA + GDPR + AI Act conformity = **$120k–$350k año 1** combinado ([dev.to AI Compliance Checklist 2026](https://dev.to/korix/ai-compliance-checklist-2026-soc-2-hipaa-gdpr-guide-521f)).
- **Señal directa para 25k€:** Coincide con el rango "Deployer baseline" + "Phase 2" de SME ovidiusuciu (€10k–€20k Q1–Q2 2026) y con el ACV medio de Drata/Vanta (~$13.5k → €12k). **25k€ es un ticket realista para series A-B no-high-risk o early high-risk** — pero será percibido como caro frente a Vanta-class si no hay diferenciación healthtech/AI Act muy clara.
- **Riesgo:** Por debajo de 25k€, hay solución freemium emergente (Fronterio Free + €199/mes Pro) que pondrá presión a la baja.

---

## 2. Multas / sanciones AI Act + RGPD salud (2024-2026)

### AI Act — estado de enforcement
- **Fines provision aplica desde 2 agosto 2026** (Art. 99): hasta €35M / 7% turnover (prácticas prohibidas), €15M / 3% (otras obligaciones operador), €7.5M / 1% (info incorrecta) ([Art. 99](https://artificialintelligenceact.eu/article/99/)).
- **Status Q1 2026:** "No major fines had been issued under the AI Act through Q1 2026; enforcement focus to date has been compliance guidance, transparency obligation reviews, and prohibition violation investigations" ([presenc.ai tracker](https://presenc.ai/research/eu-ai-act-enforcement-tracker-2026)).
- ⚠️ **Una fuente (informedclearly.com) reporta "first fines" en marzo 2026** (€45M recruitment AI, €28M biometría no registrada, €12M credit scoring) pero **no encontré confirmación oficial EU AI Office** — tratar como no verificado.
- **Implicación para urgencia comercial:** El "miedo AI Act" en healthtech UE es **anticipatorio** (deadline 2 agosto 2026), no aún reactivo. Hay que vender ese deadline, no casos de multas.

### RGPD salud — multas verificadas
- **🇫🇷 CNIL vs CEGEDIM SANTÉ:** **€800.000** (5 sept 2024) — uso no autorizado de teleservicio HRi para almacén de datos de salud sin autorización CNIL ni base legal ([CNIL](https://www.cnil.fr/en/health-data-cegedim-sante-fined-eu800000), [EDPB](https://www.edpb.europa.eu/news/national-news/2024/commercial-prospecting-french-sa-fined-cegedim-sante-eur-800-000_en)). **Caso ancla: software healthtech (EHR) sancionado por flujo de datos por defecto.**
- **🇫🇷 CNIL — software gestión médicos:** **€800.000** (5 sept 2024, mismo registro) — falta de autorización CNIL para data warehouse de salud.
- **🇪🇸 AEPD vs FSEOM (fundación oncología médica):** **€70.000** (caso EXP202416691) — Art. 5(1)(f) GDPR, falta de medidas técnicas suficientes, responsabilidad del controller no transferible al processor ([ponsip.com](https://ponsip.com/en/ip-case-law/companies-cannot-transfer-responsibility-for-their-data-when-they-contract-services-from-a-provider-acting-as-a-processor/)).
- **🇪🇸 AEPD vs farmacias:** Resoluciones 2024–2025 de **€11k → reducidas a €6.6k** por reconocimiento; falta de base legal Art. 6 + transparencia Art. 14 ([cuatrecasas.com](https://www.cuatrecasas.com/en/spain/technology-digital-media/art/aepd-pharmacy-data-processing-en)).
- **🇫🇷 Sanciones simplificadas CNIL 2024 en healthcare:** Cirujano dental €5k, €4k; soporte regional e-health €20k; pharmaceutical wholesale €20k ([CNIL sanctions list](https://www.cnil.fr/en/investigation-powers-cnil/sanctions-issued-cnil)).
- 🇩🇪 Alemania específico healthtech: **No encontrado caso reciente público destacado** en esta búsqueda.

**Señal de urgencia real:** Tickets RGPD healthtech en UE concentrados en **€10k–€800k**, con foco DPA en bases legales para datos clínicos + ausencia de autorización formal cuando hay warehouse/SaaS. **Para una series A-B esto es existencial.**

---

## 3. Conferencias 2026 con compradores objetivo

| Conferencia | Fechas | Ciudad | Perfil asistente | Coste / acceso |
|---|---|---|---|---|
| **HIMSS26 Europe** | 19–21 May 2026 | Copenhague (Bella Center) | Health IT leaders, policymakers UE, hospital execs, digital health innovators | Pase: €599–€899 member / €699–€899 non-member; pase exec: €1.729–€2.499. **Coste exhibición: no público, vía prospectus a sales** ([himss.org](https://www.himss.org/events-overview/european-health-conference-and-exhibition/?iesrc=ctr), [vendelux.com](https://vendelux.com/insights/himss-europe-2026-attendee-list)) |
| **ESMO Gastrointestinal Cancers Congress 2026** | 1–4 July 2026 | Múnich | Oncólogos GI, investigadores, pharma — **menos directo para compliance**, más para data partners ([esmo.org](https://www.esmo.org/meeting-calendar/esmo-gastrointestinal-cancers-congress-2026), [releviumproject.eu](https://www.releviumproject.eu/conferences-events)) | No encontrado coste exhibición público |
| **ESMO Congress 2026** | No encontrado en fuentes consultadas | Berlin (per task brief, no confirmé en ESMO) | — | — |
| **BIO-Europe 2026** | 9–11 Nov 2026 | Colonia (Koelnmesse) | Biopharma partnering, 5.800+ asistentes / 3.200+ empresas / 60+ países | **Basic Exhibitor Package €5.670 (6sqm)**; pase delegate €795–€1.195 según ventana ([informaconnect.com booking](https://informaconnect.com/bioeurope/booking-options/), [exhibit](https://informaconnect.com/bioeurope/exhibit-opportunities/)) |
| **Frontiers Health 2026** | Búsqueda devolvió "10º aniversario 2025"; **fechas 2026 no encontradas confirmadas** en fuente directa | Berlín (histórico bcc) | Digital therapeutics, breakthrough tech, ecosystem; perfil VC + corporates ([frontiers.health](https://www.frontiers.health/)) | No encontrado coste exhibición |
| **EU R&I Days 2026** | No encontrado fechas confirmadas (edición 2025 fue 16–17 sept) | Bruselas + online | Policymakers EU, Comisión, ERA, EIC; **alto valor para narrativa policy / Horizon** ([ec.europa.eu R&I Days](https://research-and-innovation.ec.europa.eu/events/european-research-and-innovation-days_en)) | Generalmente gratuito |

**Prioridad recomendada para Aura:** HIMSS26 Europe (compradores directos) > BIO-Europe (data partnerships pharma) > EU R&I Days (relaciones reguladoras/policy). ESMO GI es nicho indirecto.

---

## 4. Partners referidores potenciales

### Despachos legales UE healthtech / AI Act (confirmados con práctica activa)
- **DLA Piper** — Práctica Digital Health dedicada (AI, telehealth, medical AI, ciber/privacy, cumplimiento regulatorio). Tiene **Prisca AI Compliance** (legal-tech propio para madurez AI vs estándares) y **Transfer** (TIA tool). Bien posicionado para referir software complementario ([dlapiper.com Digital Health](https://www.dlapiper.com/en-us/capabilities/industry/healthcare/digital-health), [Innovation Law Insights](https://www.dlapiper.com/en-us/insights/publications/innovation-law-insights/2026/innovation-law-insights-12-may-2026)).
- **Hogan Lovells** — Equipo 50+ life sciences cross-jurisdiccional. Práctica MedDevice AI específica (CE marking AI, FDA, MDR/IVDR vs AI Act). Publica activamente sobre EU AI Act health impact ([Digital Health](https://www.hoganlovells.com/en/aof/digital-health), [JDSupra](https://www.jdsupra.com/legalnews/global-impact-of-the-eu-ai-act-for-8072208/)). **Alto fit.**
- **Cuatrecasas** — Publica enforcement AEPD en healthcare (pharmacy data) ([artículo AEPD pharmacy](https://www.cuatrecasas.com/en/spain/technology-digital-media/art/aepd-pharmacy-data-processing-en)). **Fortaleza España + Portugal.** Práctica Technology, Digital Media + Life Sciences. No encontrada práctica AI Act dedicada en esta búsqueda pero alineamiento natural.
- **Bird & Bird** — No encontré nota directa en esta búsqueda; es conocido por tech+regulated industries en UE, validar en pasada 2.

### Consultoras GTM que necesiten complemento técnico
- Boutiques tipo **Holistic AI / Credo AI** son competencia + posible partner técnico para casos donde no quieran construir vertical healthtech.
- **No encontrado** en esta pasada un mapeo claro de consultoras GTM healthtech UE que busquen complemento de compliance software. Pendiente para pasada 2.

### Comisión típica
- **SaaS vendor partner programs (referencia legaltech "Irys"):** **10% first-year revenue share** affiliate / **20% margin** reseller / custom enterprise ([irys.ai/partners](https://www.irys.ai/partners)).
- **Attorney-to-attorney referral fees:** **30%+** común, varía por jurisdicción y reglas éticas locales ([smokeball.com](https://www.smokeball.com/blog/law-firm-guide-to-attorney-referral-fees)).
- **Implicación:** Ofrecer **15–20% año 1** a despachos UE como cliente-partner es competitivo; **revenue share recurrente 10%** durante vida del cliente es estándar SaaS.

---

## 5. Modelos "compliance sprint" / boutique con tracción

### Comparables con datos públicos
| Empresa | Modelo | Tracción / Valoración | Fuente |
|---|---|---|---|
| **Vanta** | SaaS compliance multi-framework (SOC2, ISO27001, HIPAA, GDPR, ahora ISO 42001 / AI Act) | **~$300M ARR (Abr 2026, +69% YoY)**, $4.15B valuation Series D, 16.000+ clientes | [Sacra](https://sacra.com/research/vanta-at-300m-year/) |
| **Drata** | SaaS compliance, 20+ frameworks (GDPR, HIPAA inc.) | **~$98M ARR (Ene 2025, +61% YoY)**, $2B valuation, 7.000+ clientes, ACV ~$13.5k | [Sacra Drata](https://sacra.com/c/drata/) |
| **Kertos** 🇩🇪 | "AI-first compliance" EU-first, GDPR + AI Act + certifications | **€14M Series A (Sept 2025)** Portage led | [tech.eu](https://tech.eu/2025/09/17/kertos-lands-eur14m-to-lead-europes-ai-first-compliance-shift/) |
| **Copla** 🇪🇺 | ICT compliance para regulated finance (DORA + AI Act + Cyber Resilience) | **€6M Series A (Feb 2026)** Iron Wolf Capital | [tech.eu](https://tech.eu/2026/02/19/copla-raises-eur6m-series-a-to-support-eu-regulatory-compliance/) |
| **Ketryx** | Infrastructure regulated AI **specifically life sciences / MedTech** | **$39M Series B**, $55M total, 3 of top 5 MedTech use it; afirma "50–80% del tiempo product dev en compliance" | [ketryx.com](https://www.ketryx.com/blog/building-the-infrastructure-for-regulated-ai-announcing-ketryx-39m-series-b) |
| **Noru** 🇸🇪 | "Agentic compliance" pre-seed | €560k pre-seed (Ampli Ventures + a16z Scout) | [techfront360.com](https://techfront360.com/noru-raises-e560k-to-build-agentic-compliance-inside-the-bet-on-ai-agents-as-regulatory-infrastructure/) |
| **Sprinto / TrustCloud** | Lower-cost / freemium para SMB | Mencionados como newcomers presionando ACV a la baja | [Sacra Drata](https://sacra.com/c/drata/) |
| **Fronterio** | EU AI Act free tier + €199/mes Pro flat | Posicionamiento "free baseline" disruptor | [fronterio.com](https://fronterio.com/no/blog/ai-governance-platform-comparison-credo-fairly-holistic-fronterio) |

### Lecciones para Aura Compliance
1. **El mercado YA está validado y compitiendo a varios precios.** Hay un peldaño claro de ARR a alcanzar ($10–100M en 3–5 años) sin tener que reinventar el modelo.
2. **Ketryx es el comparable más cercano al wedge healthtech** ($55M total raised, vertical regulated). Indica que **especializarse en healthtech UE** vs SaaS horizontal genérica (Vanta) es viable.
3. **El "AI-first / agentic" es el nuevo wedge.** Kertos (€14M), Copla (€6M), Noru (€560k) todos venden AI-native compliance en 2025–2026 → la ventana está abierta.
4. **Modelo "sprint" puro no es lo que tracciona** — los comparables son plataformas SaaS recurrentes. Un sprint inicial 25k€ como land + plataforma recurrente €1–2k/mes como expand es coherente con cómo Vanta/Drata convierten consultoría en ARR.
5. **Riesgo competitivo concreto:** Kertos (DE), Copla (regulated finance EU), Fronterio (free tier UE), todos pueden pivotar a healthtech UE antes que Aura escale.

---

## Resumen tactico para la hipótesis líder (A1 — Aura Compliance)

- ✅ **Mercado real y financiado** (€14M Kertos, $39M Ketryx, $300M Vanta).
- ✅ **Deadline 2 ago 2026 es palanca real** de urgencia comercial para healthtech UE.
- ⚠️ **Multas AI Act aún no materializadas** — el FUD se vende con deadline + multas RGPD ancla (CEGEDIM €800k es la mejor referencia).
- ⚠️ **25k€ ticket plausible pero presionado** por Fronterio Free + Vanta-class €10–40k. Diferenciación healthtech UE + EU AI Act es **obligatoria**, no opcional.
- ⚠️ **Ketryx ya hace esto mejor en MedTech regulado** — Aura debe definir si compite (segmento underserved: digital health SaaS no-device, biotech early) o complementa.
- ✅ **Partners legales accesibles** (DLA Piper, Hogan Lovells, Cuatrecasas) con prácticas activas; modelo de comisión 10–20% año 1 es estándar.
- ✅ **HIMSS26 Europe (Copenhague, 19–21 May 2026)** es el primer evento de exposición coste-eficiente — pase exec €2k–€2.5k, exhibición a cotizar.

**Recomendación de pasada 2:** Validar entrevistando 3–5 healthtech series A-B UE: ¿pagarían 25k€ + €1.5k/mes a Aura vs hacer Kertos/Vanta + abogado DLA/Hogan?
