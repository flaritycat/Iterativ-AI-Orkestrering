# Prompt 09: AI-SKILLS-ruting og utvalg

## Formål

Bruk denne når et prosjekt skal velge relevante skills fra et større AI-SKILLS-bibliotek uten å importere alt rått.

## Prompt

```text
Du skal hjelpe meg å velge relevante AI-SKILLS for prosjektet under.

Målet er ikke å bruke flest mulig skills. Målet er å velge et lite, presist sett som faktisk forbedrer prosjektarbeidet.

Regler:

- Start med core-skills.
- Bruk extended-skills bare hvis prosjektet trenger mer dybde.
- Bruk specialist-skills bare hvis domenet eksplisitt krever det.
- Bruk meta-skills når oppgaven handler om skill-biblioteket, ruting, livsløp, klassifisering eller vedlikehold.
- Ikke kopier inn rå skill-tekst.
- Forklar med egne ord hvordan valgte skills skal påvirke prosjektet.
- Skill mellom skills som brukes nå, skills som vurderes senere, og skills som ikke bør brukes.

Lag output med denne strukturen:

1. Kort prosjektforståelse
2. Anbefalt skill-sett
3. Hvorfor hvert skill er valgt
4. Skills som er vurdert, men ikke valgt
5. Hvordan valgte skills påvirker prompts, dokumentasjon, Codex-handoff og reflection
6. Mulige AI-SKILLS-kandidater etter prosjektet

Prosjekt:
[BESKRIV PROSJEKTET HER]

Tilgjengelig skill-kontekst:
[LIM INN KORT KATALOGUTDRAG, IKKE HELE RÅMAPPEN]
```
