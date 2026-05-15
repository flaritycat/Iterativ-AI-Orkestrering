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

## Hvem repoet er for

Repoet er laget for arbeid der AI skal brukes systematisk, ikke bare som hjelp til enkeltoppgaver.

Det passer særlig når du vil:

- starte nye prosjekter med bedre problemforståelse
- bruke ChatGPT til intervjurunder og prompt-destillering
- overføre modent arbeid til Codex og GitHub
- dokumentere prosjektcase på en måte som kan gjenbrukes
- bygge en felles metodebase gjennom AI-SKILLS
- gjøre erfaringer fra ett prosjekt nyttige i neste prosjekt

## Start her

For å forstå metoden:

1. Les [hva metoden er](docs/01-hva-er-iterativ-ai-orkestrering.md).
2. Les [arbeidsflyten](docs/02-arbeidsflyt.md).
3. Les [AI-SKILLS enkelt forklart](docs/12-ai-skills-enkelt-forklart.md).
4. Les [AI-SKILLS som metodebase](docs/04-ai-skills-som-metodebase.md).

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

## Hva er en AI-SKILL?

En AI-SKILL er en liten, gjenbrukbar arbeidsregel for AI-assistert arbeid.

Den kan beskrive:

- når en bestemt arbeidsmåte bør brukes
- hvilke spørsmål AI bør stille
- hvilke regler AI bør følge
- hvilke feil AI bør passe på
- hvordan resultatet bør vurderes

En AI-SKILL er altså ikke bare en prompt. Den er mer som en liten metodebit som kan brukes igjen i flere prosjekter.

Se [AI-SKILLS enkelt forklart](docs/12-ai-skills-enkelt-forklart.md) for en mer pedagogisk forklaring med små eksempler.

## Små eksempler

| Situasjon | Relevant AI-SKILL | Hvordan den hjelper |
|---|---|---|
| Du starter et uklart prosjekt. | Intervjubasert kartlegging | ChatGPT stiller ett spørsmål om gangen og henter ut mål, kontekst og risiko. |
| Du har en lang samtale som må brukes videre. | Syntese og destillering | ChatGPT gjør samtalen om til en kort, presis arbeids-prompt. |
| Codex skal jobbe i repoet. | AI-assistert utvikling | Codex får tydelig mål, avgrensning, filkontekst og krav til sjekk. |
| Prosjektet er ferdig. | Feedback loop / reflection | Erfaringer gjøres om til forbedringer for neste prosjekt. |
| Du har laget en bedre prompt. | Skill-tilbakeføring | Prompten vurderes som kandidat til felles AI-SKILLS. |

## Hvordan AI-SKILLS brukes her

I Iterativ AI-orkestrering brukes AI-SKILLS på to måter:

1. Som inngang til prosjektet: eksisterende skills hjelper prosjektet å starte bedre.
2. Som utgang fra prosjektet: ny læring kan bli forslag til forbedrede skills.

```text
AI-SKILLS
-> bedre prosjektstart
-> prosjektarbeid med ChatGPT, Codex og GitHub
-> reflection
-> forslag til forbedrede AI-SKILLS
```

Bruk [AI-SKILLS-rutekortet](templates/ai-skills-rutekort-mal.md) når et prosjekt skal velge hvilke skills som er relevante, og se [eksempel på AI-SKILLS-ruting](examples/eksempel-ai-skills-ruting.md) for en konkret modell.

## Iterasjon som arbeidsmotor

Metoden bygger på flere runder, ikke én perfekt gjennomføring.

I hver runde prøver du å:

1. finne hva som er uklart, svakt eller uferdig
2. gå løs på det med riktig prompt, skill, dokumentasjon eller Codex-arbeid
3. reflektere over hva som faktisk ble bedre
4. analysere hva som fortsatt skurrer
5. forbedre metode, prompt, repo eller AI-SKILLS-forslag

```text
Finn
-> bearbeid
-> reflekter
-> analyser
-> forbedre
-> ny runde
```

Dette gjør det mulig å følge med på tidligere arbeid systematisk. Gamle prompts, beslutninger, dokumentasjon, Codex-handoff og reflection-notater blir ikke bare historikk. De blir materiale som kan vurderes på nytt og forbedres.

## Små og store iterasjoner

Iterasjon kan brukes på flere nivåer:

| Nivå | Eksempel | Hva forbedres |
|---|---|---|
| Liten runde | Forbedre én prompt etter en intervjurunde. | Bedre spørsmål og klarere output. |
| Prosjektrunde | Gå gjennom repoet etter Codex-arbeid. | Bedre dokumentasjon, struktur og handoff. |
| Metoderunde | Sammenligne flere prosjektcase. | Bedre felles regler, maler og AI-SKILLS. |
| Porteføljerunde | Se mønstre på tvers av mange prosjekter. | Bedre startpunkt for nye prosjekter. |

Den lille konteksten handler om å forbedre noe konkret nå. Den store konteksten handler om å se mønstre over tid og justere hele arbeidsmåten.

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

## Første praktiske leveranse

Når du bruker repoet på et nytt prosjekt, er en god første leveranse:

- ett utfylt problemnotat
- ett intervjunotat eller en kort oppsummering av intervjurunden
- én destillert ChatGPT-prompt
- ett AI-SKILLS-rutekort
- én Codex-handoff
- ett reflection-notat
- ett konkret forslag til AI-SKILLS-tilbakeføring eller en begrunnelse for at ingenting bør tilbakeføres ennå

Dette er nok til at prosjektet blir mer enn en samtale. Det blir et sporbart læringspunkt.

## Kvalitetsregel

Et godt prosjekt i denne metoden skal kunne svare på:

- Hva prøvde vi å løse?
- Hvilke prompts og skills brukte vi?
- Hva ble levert?
- Hva lærte vi?
- Hva bør forbedres i metoden?
- Hva bør tilbakeføres til AI-SKILLS?

## Vedlikehold av repoet

Når repoet oppdateres, bruk disse reglene:

- legg til forklaringer, prompts, maler eller eksempler som faktisk kan brukes
- oppdater `CHANGELOG.md` når metodebasen endres vesentlig
- legg usikre ideer i `ai-skills/backlog.md`
- legg modne forslag i `ai-skills/kandidater.md`
- hold README kort nok til å være en inngang, og flytt detaljer til `docs/`
- ikke legg inn råmateriale uten at det er analysert, forklart og gjort anvendbart

## Kilde

Hovedkilden for repoet er `source-documents/iterativ_ai_orkestrering_metodedokument_v0_1.docx`.
