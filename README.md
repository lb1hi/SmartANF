# SmartANF

Konsept for et moderne Smart Automatic Notch Filter for SSB-mottak i amatørradio.

Prosjektet beskriver en ekstern DSP-lydprosessor som automatisk kan oppdage, følge og undertrykke smalbåndede forstyrrende toner.

Det publiserte dokumentet er skrevet på norsk (bokmål) og består av to deler:

- **Del I** – oversikt over problemet, eksisterende inline-DSP-produkter og SmartANF-konseptet. Krever ingen forkunnskaper i signalbehandling.
- **Del II** – teknisk fordypning: notchfilterteori, adaptiv filtrering, tonedeteksjon, fler-tone tracking, latens, sanntidsarkitektur og bruk av TinyML i beslutningsleddet.

Til slutt følger en referanseliste med fagfellevurdert DSP-litteratur, lærebøker, produsentdokumentasjon og nyere forskning.

Hovedregelen i dokumentet: klassisk DSP gjør selve filtreringen, mens maskinlæring eventuelt kan forbedre beslutningen om hva som skal filtreres bort.

## GitHub Pages

Prosjektsiden er tilgjengelig via GitHub Pages:

https://lb1hi.github.io/SmartANF/

## Innhold

- `index.html` — hele dokumentet om SmartANF, på norsk. Én selvstendig side uten eksterne avhengigheter.
