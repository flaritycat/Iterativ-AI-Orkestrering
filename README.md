# Iterativ AI-orkestrering

Dette repoet forklarer en praktisk metode for å bruke ChatGPT, Codex, GitHub og AI-SKILLS sammen i prosjektarbeid.

Metoden gjør hvert prosjekt til to ting samtidig:

1. en konkret leveranse
2. en læringsnode som forbedrer neste prosjekt

```text
Problemstilling
-> intervjurunder
-> prompt-destillering
-> ny operativ ChatGPT-chat
-> arkitektur, regler og struktur
-> Codex-handoff
-> GitHub som prosjektbase
-> reflection
-> AI-SKILLS-tilbakeføring
-> bedre startpunkt for neste prosjekt
```

## Kort sagt

Iterativ AI-orkestrering er en arbeidsmåte der AI ikke brukes som en løs svarmaskin, men som et koordinert sett med roller.

| Del | Rolle |
|---|---|
| ChatGPT | Utforsker problem, intervjuer, destillerer prompts og evaluerer metode. |
| Codex | Gjør konkret repo-arbeid med filer, kode, dokumentasjon og struktur. |
| GitHub | Holder prosjektets dokumentasjon, historikk, beslutninger og leveranser samlet. |
| AI-SKILLS | Samler prompts, regler, maler og læring som kan gjenbrukes. |
| Metodeeier | Styrer retning, prioritering, kvalitet og beslutninger. |

Poenget er ikke bare å få AI til å produsere raskere. Poenget er å bygge en arbeidsflyt som lærer.

## Start her

For å forstå metoden:

1. Les [hva metoden er](docs/01-hva-er-iterativ-ai-orkestrering.md).
2. Les [arbeidsflyten](docs/02-arbeidsflyt.md).
3. Les [AI-SKILLS som metodebase](docs/04-ai-skills-som-metodebase.md).

For å bruke metoden i et prosjekt:

1. Skriv et [problemnotat](templates/problemnotat-mal.md).
2. Kjør en intervjurunde med [intervjustartprompten](prompts/01-intervjurunde-startprompt.md).
3. Lag en destillert prompt med [prompt-destillering](prompts/02-prompt-destillering.md).
4. Start ny operativ chat med [ny operativ chat](prompts/03-ny-operativ-chat.md).
5. Velg relevante skills med [AI-SKILLS-rutekortet](templates/ai-skills-rutekort-mal.md).
6. Forbered Codex med [Codex-handoff](prompts/05-codex-handoff.md).
7. Dokumenter prosjektet med [prosjektcase-malen](templates/prosjektcase-mal.md).
8. Avslutt med [reflection og forbedring](prompts/06-reflection-og-forbedring.md).
9. Foreslå tilbakeføring med [AI-SKILLS-endringsforslag](templates/ai-skills-endringsforslag-mal.md).

## Repoets innhold

| Mappe | Bruk |
|---|---|
| `docs/` | Forklaring av metode, arbeidsflyt, roller, artefakter, risiko og AI-SKILLS-bruk. |
| `prompts/` | Promptmaler for intervju, destillering, ny chat, arkitektur, Codex, reflection og skill-ruting. |
| `templates/` | Maler for problemnotat, intervjunotat, prosjektcase, beslutningslogg, reflection og AI-SKILLS-forslag. |
| `examples/` | Korte eksempler som viser hvordan metoden brukes i praksis. |
| `codex/` | Startpunkt og prompts for videre Codex-arbeid. |
| `ai-skills/` | Lokale kandidater og backlog før eventuell tilbakeføring til felles AI-SKILLS. |
| `visuals/` | Visualiseringsliste og placeholders for figurer og presentasjon. |
| `source-documents/` | Underliggende metodedokument og kildemateriale. |

## Bruk av AI-SKILLS-SETS

`AI-SKILLS-SETS-main` brukes som kildemateriale, ikke som råinnhold som kopieres inn.

Riktig bruk:

- les og analyser relevante skills
- velg et lite sett som passer prosjektfasen
- oversett funnene til lokale forklaringer, prompts, maler eller eksempler
- dokumenter hvilke skill-slugs som inspirerte arbeidet
- tilbakefør bare konkrete og modne forslag

Ikke gjør dette:

- ikke kopier hele `skills/`-mappen inn hit
- ikke legg inn zip-pakker eller importmapper
- ikke gjør specialist-skills til standard for alle prosjekter
- ikke legg til regler uten forklaring av praktisk bruk

Se [AI-SKILLS-SETS som kildemateriale](docs/11-ai-skills-set-som-kildemateriale.md) og [eksempel på AI-SKILLS-ruting](examples/eksempel-ai-skills-ruting.md).

## Minste praktiske bruk

For et lite prosjekt holder dette:

1. problemnotat
2. intervjurunde
3. destillert prompt
4. AI-SKILLS-rutekort
5. Codex-handoff
6. repo-arbeid
7. reflection-notat
8. minst ett vurdert AI-SKILLS-forslag

Det viktigste er ikke å fylle ut alt perfekt. Det viktigste er at prosjektet etterlater spor som neste prosjekt kan bruke.

## Kvalitetsregel

Et godt prosjekt i denne metoden skal kunne svare på:

- Hva prøvde vi å løse?
- Hvilke prompts og skills brukte vi?
- Hva ble levert?
- Hva lærte vi?
- Hva bør forbedres i metoden?
- Hva bør tilbakeføres til AI-SKILLS?

## Kilde

Hovedkilden for repoet er `source-documents/iterativ_ai_orkestrering_metodedokument_v0_1.docx`.
