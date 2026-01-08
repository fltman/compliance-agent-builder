---
name: compliance-agent-builder
description: Kunskap om att skapa compliance-agenter från regelverk och standarder
---

# Compliance Agent Builder Skill

## Regelverkstyper

| Typ | Struktur | Nyckelbegrepp |
|-----|----------|---------------|
| EU-direktiv | Artiklar, punkter | "ska", sanktioner, tillämpningsområde |
| EU-förordning | Artiklar, bilagor | Direkt tillämplig, böter |
| ISO-standard | Kontroller, annexer | "shall", certifiering |
| Branschstandard | Krav, kategorier | Compliance levels |

## Checklista: Compliance-agent

### Dokumentanalys
- [ ] Identifiera regelverkstyp
- [ ] Extrahera definitioner
- [ ] Mappa kravstruktur
- [ ] Notera sanktioner/böter
- [ ] Identifiera tillämpningsområde

### Agent-komponenter
- [ ] Granskningskapacitet mot alla krav
- [ ] Gap-identifiering med referenser
- [ ] Checklistgenerering
- [ ] Rapportformat definierat

### Skill-innehåll
- [ ] Snabbreferens alla krav
- [ ] Checklistor per område
- [ ] Tidsgränser/deadlines
- [ ] Sanktionsnivåer
- [ ] Tillämpningsområde

### Templates
- [ ] Compliance checklist
- [ ] Gap analysis report
- [ ] Audit evidence template

## Vanliga EU-regelverk

| Regelverk | Fokus | Artikel för krav |
|-----------|-------|------------------|
| NIS2 | Cybersäkerhet | Art. 21 (10 krav) |
| GDPR | Dataskydd | Art. 5, 6, 32 |
| DORA | Finansiell resiliens | Art. 5-16 |
| AI Act | AI-system | Art. 8-15 |
| CRA | Cybersäkerhet produkter | Bilaga I |

## Vanliga ISO-standarder

| Standard | Fokus | Struktur |
|----------|-------|----------|
| 27001 | ISMS | Annex A kontroller |
| 27002 | Säkerhetskontroller | Detaljerade kontroller |
| 9001 | Kvalitet | Kapitel 4-10 |
| 22301 | Kontinuitet | Kapitel 4-10 |

## Rapportformat

```markdown
## [Regelverk] Compliance Status

### Uppfyllda krav ✅
- [Art. X] - [Implementation]

### Gaps ⚠️
- [Art. Y] - [Saknas] - [Åtgärd]

### Kritiskt 🚨
- [Art. Z] - [Risk] - [Omedelbart]
```

## Sanktionsnivåer (exempel)

| Regelverk | Max böter |
|-----------|-----------|
| NIS2 Essential | €10M / 2% |
| NIS2 Important | €7M / 1.4% |
| GDPR | €20M / 4% |
| DORA | Varierande |
