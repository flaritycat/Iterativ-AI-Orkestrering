# AI-SKILLS-SETS som kildemateriale

`AI-SKILLS-SETS-main` er ikke en mappe som bør lastes rått inn i dette repoet.

Den bør brukes som et strukturert kildelag for å velge, forklare og forbedre metodegrep i Iterativ AI-orkestrering.

## Hva mappen inneholder

Gjennomgangen viser et modent skill-bibliotek med:

- 254 aktive skills
- 136 `core`-skills
- 63 `extended`-skills
- 46 `specialist`-skills
- 9 `meta`-skills
- kataloger, collections, metadata, importnotater, valideringsskript og tester

Biblioteket har også en tydelig rutingmodell:

- start med `core`
- bruk `extended` når prosjektet trenger mer dybde
- bruk `specialist` bare når domenet faktisk krever det
- bruk `meta` når selve skill-biblioteket, klassifisering, livsløp eller vedlikehold er tema

Dette passer godt med metoden i dette repoet, fordi Iterativ AI-orkestrering trenger både prosjektflyt og tverrprosjektlig metodeforbedring.

## Bruksregel i dette repoet

Bruk `AI-SKILLS-SETS-main` slik:

1. Les og analyser relevante skills.
2. Velg et lite sett som passer prosjektfasen.
3. Oversett dem til forklaring, arbeidsregel, prompt eller eksempel.
4. Dokumenter hvilke skills som inspirerte endringen.
5. Ikke kopier inn hele skill-filer, zip-pakker, kataloger eller rå imports.

Kort sagt:

```text
AI-SKILLS-SETS -> utvalg -> tolkning -> lokal forklaring -> eksempel -> eventuell tilbakeføring
```

## Hvorfor ikke råimport?

Råimport gir et større repo, men ikke nødvendigvis bedre metode.

Risikoen er at repoet blir:

- vanskeligere å lese
- vanskeligere å vedlikeholde
- uklart på hva som er metode og hva som bare er kildemateriale
- fullt av overlappende regler uten lokal forklaring

Dette repoet skal forklare hvordan skills brukes i Iterativ AI-orkestrering. Det skal ikke være en kopi av hele skill-biblioteket.

## Anbefalt kobling mot arbeidsflyten

| Fase i Iterativ AI-orkestrering | Relevante skill-typer fra AI-SKILLS-SETS | Hvordan brukes de her |
|---|---|---|
| Problemåpning | prosjektoppstart, kravkvalitet, prioritering | Styrker problemnotat, scope og første beslutninger. |
| Intervjurunder | intervjubasert discovery, antakelser, evidens | Gjør intervjuer mer presise og mindre tilfeldige. |
| Prompt-destillering | syntese, distillering, human-to-AI-oversettelse | Gjør samtale om til presis operativ prompt. |
| Ny operativ chat | moden AI-atferd, AI-assistert utvikling | Gir klarere rolle, grenser, usikkerhet og ansvar. |
| Arkitektur og regler | beslutningslogg, arkitekturdokumentasjon, guardrails | Gjør struktur og valg sporbare. |
| Codex-handoff | AI-assistert utvikling, testing, vedlikeholdbarhet | Gir Codex bedre rammer og bedre verifikasjon. |
| GitHub som prosjektbase | versjonering, changelog, dokumentasjonskvalitet | Holder repoet ryddig og forståelig. |
| Reflection | feedback loop, postmortem, læringsreview | Gjør erfaringer om til konkrete forbedringer. |
| AI-SKILLS-tilbakeføring | skill-ruting, lifecycle, deduplisering, relasjonskart | Gjør forbedringsforslag vurderbare og ryddige. |

## Første anbefalte shortlist

For dette repoet er disse skill-områdene spesielt relevante som inspirasjon:

- `mature-ai-skillset`: overordnet AI-atferd og ansvarlig arbeidsform
- `interview-driven-discovery`: intervjurunder som ekstraksjonsmotor
- `synthesis-and-distillation`: prompt-destillering og kondensering av innsikt
- `human-to-ai-translation`: oversette menneskelig metode til AI-brukbare regler
- `project-startup-guardrails`: minimumsregler ved prosjektstart
- `ai-assisted-development`: bruk av AI uten å outsource vurdering
- `source-backed-documentation`: sporbar dokumentasjon
- `documentation-quality`: dokumentasjon som fortsatt er nyttig senere
- `decision-record-documentation`: beslutninger med begrunnelse og konsekvens
- `success-feedback-loop`: læring tilbake til senere prosjekter
- `skillset-selection-and-routing`: velge riktig skill-nivå
- `skillset-authoring-and-update-governance`: skrive og endre skills kontrollert
- `skillset-lifecycle-and-status`: skille kandidater, aktive forslag, arkiv og avviste forslag
- `skillset-deduplication-and-merge`: unngå at metodebasen får mange nesten-like regler
- `skillset-relationship-mapping`: gjøre sammenhenger mellom skills eksplisitte

## Praktisk arbeidsmåte

Når et prosjekt starter, legg inn et kort skill-rutekort:

1. Hvilken fase er prosjektet i?
2. Hvilke 3 til 7 skills er mest relevante?
3. Hvorfor velges akkurat disse?
4. Hvordan skal de påvirke prompt, dokumentasjon eller Codex-handoff?
5. Hvilke skills er vurdert, men ikke valgt?
6. Hva bør tilbakeføres hvis prosjektet gir ny læring?

Bruk `templates/ai-skills-rutekort-mal.md` som mal.

## Eksempel på god bruk

God bruk:

- "Vi bruker `interview-driven-discovery` til å forbedre intervjuprompten, men skriver vår egen norske forklaring og vårt eget eksempel."
- "Vi bruker `skillset-selection-and-routing` til å forklare hvorfor prosjektet starter med core-skills og ikke specialist-skills."
- "Vi bruker `success-feedback-loop` som inspirasjon for reflection-malen."

Dårlig bruk:

- å kopiere hele `skills/`-mappen inn i dette repoet
- å legge inn zip-pakker som ikke forklares
- å importere 20 skills uten å forklare hvorfor de trengs
- å presentere specialist-skills som standard for alle prosjekter

## Neste forbedring

Neste naturlige steg er å bruke `AI-SKILLS-SETS-main` som testgrunnlag for et konkret prosjektcase:

1. velg et lite prosjekt
2. fyll ut skill-rutekort
3. kjør intervjurunde
4. destiller prompt
5. gjennomfør Codex-handoff
6. skriv reflection
7. vurder hvilke lokale forbedringer som bør bli AI-SKILLS-kandidater
