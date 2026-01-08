# Compliance Agent Builder

En specialiserad Claude Code agent för att skapa compliance-agenter från regelverk och standarder.

## Användning

```
Skapa en compliance-agent från GDPR-dokumentationen i /path/to/pdfs/
```

Agenten skapar automatiskt:
- Compliance-granskningsagent
- Skill med snabbreferens och checklistor
- Templates för gap-analyser och checklistor
- Markdown-kunskapsfiler

## Installation

```bash
cp -r compliance-agent-builder/.claude /ditt/projekt/
```

## Struktur

```
.claude/
├── agents/
│   └── compliance-agent-builder.md
└── skills/
    └── compliance-agent-builder/
        ├── SKILL.md
        └── templates/
            ├── compliance-agent-template.md
            └── gap-analysis-template.md
```

## Stöd för regelverkstyper

| Typ | Exempel | Konsolidering |
|-----|---------|---------------|
| EU-direktiv | NIS2, GDPR, AI Act | Per artikel |
| EU-förordningar | DORA, CRA | Per artikel |
| ISO-standarder | 27001, 27002 | Per kontrollområde |
| Branschregleringar | PCI-DSS, HIPAA | Per kravområde |

## Output

Agenten genererar:

```
[regelverk]-compliance-agent/
├── README.md
├── .claude/
│   ├── agents/
│   │   └── [regelverk]-compliance.md
│   └── skills/
│       └── [regelverk]-compliance/
│           ├── SKILL.md
│           └── templates/
│               ├── compliance-checklist.md
│               └── gap-analysis.md
└── markdown/
    ├── [REGELVERK]_COMPLETE.md
    └── [regelverk]_by_section/
```

## Features

- Identifierar automatiskt regelverkstyp
- Extraherar definitioner och krav
- Dokumenterar sanktioner och böter
- Skapar praktiska checklistor
- Genererar rapportformat

## Exempel

Se [nis2-compliance-agent](../nis2-compliance-agent) för ett komplett exempel.

## Licens

MIT
