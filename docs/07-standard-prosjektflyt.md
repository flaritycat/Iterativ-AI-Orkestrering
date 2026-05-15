# Standard prosjektflyt

Denne flyten kan brukes som startpunkt for nye prosjekter. Skaler den ned når prosjektet er lite.

## 1. Opprett prosjektrom

Start i ChatGPT med en kort beskrivelse:

- hva prosjektet handler om
- hvorfor det trengs
- hva som er uklart
- hva som finnes fra før

Lag et enkelt problemnotat hvis prosjektet skal leve videre.

## 2. Kjør intervjurunde

Bruk `prompts/01-intervjurunde-startprompt.md`.

Målet er å hente ut:

- mål
- kontekst
- begrensninger
- tidligere erfaringer
- risiko
- kvalitetskriterier
- mulige AI-SKILLS-koblinger

## 3. Destiller prompt

Bruk `prompts/02-prompt-destillering.md`.

Prompten skal være presis nok til å starte en ny operativ chat uten hele den gamle samtalen.

## 4. Start ny operativ chat

Lim inn den destillerte prompten i en ny chat.

Bruk chatten til å lage:

- struktur
- regler
- arkitektur
- dokumentasjonsplan
- Codex-handoff

## 5. Opprett eller oppdater repo

Bruk GitHub som prosjektbase.

Minimum:

- README
- `docs/`
- relevante prompts
- templates eller eksempler
- reflection-notat

## 6. Gi Codex tydelig oppdrag

Codex-prompten bør si:

- hva repoet er
- hva som skal endres
- hvilke filer som er viktige
- hva som ikke skal gjøres
- hvordan arbeidet skal verifiseres

## 7. Evaluer og tilbakefør

Etter arbeidet:

- skriv reflection
- oppdater prosjektcase
- registrer AI-SKILLS-kandidater
- flytt modne forslag til backlog for felles metodebase
