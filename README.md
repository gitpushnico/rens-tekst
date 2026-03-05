# Rens tekst ✨

Et lille browserværktøj til at rense tekst kopieret fra Word, Google Docs, PDF'er og emails — for skjulte Unicode-tegn, homoglypfer og andre usynlige problemer.

🔗 **[Åbn værktøjet](https://rens-tekst.vercel.app)**

---

## Hvad gør det?

- Fjerner zero-width characters (U+200B, U+FEFF m.fl.)
- Erstatter non-breaking spaces og bløde bindestreger
- Normaliserer typografiske anførselstegn til ASCII
- Fjerner WordMat/matematik-symboler
- Fjerner kontroltegn og bidi-overrides
- Detekterer og erstatter homoglypfer (kyrilliske/græske bogstaver der ligner latinske)

## Tilstande

**Normal** — hurtig rensning til daglig brug  
**Avanceret** — diff-visning, fjernet tegn log, Unicode-normalisering, uregelmæssigheder, batch-behandling og eksport af rapporter

## Privatliv

100% klient-side. Ingen tekst forlader din browser. Ingen cookies, ingen tracking, ingen ekstern server.

Værktøjet hostes på Vercel, som kan logge IP-adresser og basistrafikdata som en del af deres infrastruktur. Se [Vercels privatlivspolitik](https://vercel.com/legal/privacy-policy).

## Teknologi

Ren HTML, CSS og JavaScript — ingen frameworks, ingen dependencies.

## Licens

[MIT](./LICENSE) © [@gitpushnico](https://github.com/gitpushnico)
