# !! DRAFT - Må godkjennes av TLG !!

# Retningslinjer for åpen kildekode i Statens pensjonskasse

## Introduksjon

Statens pensjonskasse er en offentlig virksomhet finansiert av fellesskapets midler.
Produkter og tjenester utviklet av SPK bør derfor være fritt tilgjengelige. Ifølge [offentleglova](https://lovdata.no/dokument/NL/lov/2006-05-19-16) – Lov om rett til innsyn i dokument i offentleg verksemd – skal offentlige virksomheter være åpne og gjennomsiktige. Åpen kildekode er en utmerket måte å støtte dette lovverket på.

## Åpenkildekode

Åpen kildekode har mange fordeler, for eksempel:

- Økt kvalitet på koden i våre løsninger.
- Bedre samarbeid og større synlighet av koden.
- Fremmer deling av kompetanse og løsninger gjennom fellesskapet.

## Krav til åpne repoer

Alle åpne repositorier må opprettes gjennom [self-service-repo](https://github.com/statens-pensjonskasse/self-service-repo).

### Før publisering

All kode må gjennom en dokumentert sikkerhetssjekk før den gjøres offentlig.
Koden skal ikke inneholde sensitiv informasjon eller interne systemdetaljer.
Ansvarlig team og kontaktperson må være definert.
Retningslinjene for publisering må godkjennes av rett instans – f.eks. Sikkerhetssenteret, IT-ledelse eller jurist.

### Ved mottak av sårbarhetsrapport

Eksterne må ha en tydelig kanal for å rapportere sikkerhetsfunn se [SIKKERHET](SIKKERHET.md)
SPK bekrefter mottak innen 3 virkedager og vurderer innen 10 virkedager.

### Etter publisering – forvaltning og oppfølging

Hvert team må ha ansvar for videre vedlikehold og sårbarhetsoppfølging.
Det må være krav til hvor raskt sårbarheter skal håndteres – maks 10 virkedager.
Sikkerhetssenteret skal kunne følge opp team som ikke håndterer svakheter som rapporteres.

### Lisens

Alle repositorier må ha en MIT License.

### README

Alle repositorier må ha en forklarende README-fil som beskriver hensikten med repositoriet.

### Etiske regler

Statens pensjonskasse [etiske regler](CODE_OF_CONDUCT.md) er basert på og oversatt fra [Contributor Covenant](https://www.contributor-covenant.org/)

## Hvordan komme i gang?

All informasjon du trenger for å komme i gang finner du i vår [utvikler håndbok](https://handbok.utv.spk.no/plattform/github/).

# Referanser

Kilde som brukes til inspirasjon:

- [NAV offentlig](https://github.com/navikt/offentlig)
- [DigDir overordnede arkitekturprinsipper ](https://www.digdir.no/digital-samhandling/overordnede-arkitekturprinsipper/1065)
- [Altinn](https://github.com/Altinn/.github/blob/main/profile/README.md)
- [Offentleglova](https://lovdata.no/dokument/NL/lov/2006-05-19-16)
- [Contributor covenant](https://www.contributor-covenant.org/)
