---
title: Sådan bruger vi Nextcloud
layout: default
parent: Fildeling
grand_parent: Værktøjskasse til projekter og produkter
has_toc: false
nav_order: 50
---

# Sådan bruger vi Nextcloud

Du behøver ikke gøre alting perfekt fra dag ét. Små, konsekvente vaner gør den største forskel.

## Intern vs. åben/ekstern mappe – sådan skelner vi

- **Intern** – her arbejder vi: kladder, noter og dokumenter i proces  
- **Åben/ekstern** – her deler vi det, der er færdigt og må bruges af andre

**Hvorfor flytte til det åbne filarkiv, når noget er færdigt?**  

OS2 bygger på åbenhed som grundprincip i open source. Derfor skal dokumentation være åbent tilgængelig i videst muligt omfang.

- De **interne mapper** er til dokumenter, der er under udarbejdelse.  
- Når dokumentationen er **godkendt og skal bruges af andre**, flytter eller kopierer du den til produktets **offentlige mappe** i Nextcloud (det åbne filarkiv).

## Filformater (åbne formater / ODF)

**Kort forklaring:** ODF er åbne standarder, der kan åbnes i mange programmer.  
Vi bruger som udgangspunkt **.odt, .ods og .odp**. Når noget skal deles bredt, **eksportér til PDF**.

### Godt at vide, hvis du er ny i ODF

- **Programmer:**  
  Du kan arbejde i fx **LibreOffice** (gratis) eller **Microsoft Office**. I browseren kan du redigere via Nextcloud (OnlyOffice/Collabora), hvis det er slået til.

- **Kompatibilitet:**  
  Avanceret formatering kan nogle gange ændre sig lidt på tværs af programmer. Tjek gerne slutlayout i den PDF, du deler.

- **Skabeloner:**  
  Brug fælles skabeloner for et ens udtryk. Du finder skabeloner i **Værktøjskassen for produkter og projekter**.

- **Track changes:**  
  “Spor ændringer” findes også i ODF. Aftal gerne en enkel godkendelsespraksis i jeres gruppe.

## Navigér i filformater (hurtig guide)

- **Kan man åbne ODF i Microsoft Office?**  
  Ja. `.odt`, `.ods` og `.odp` kan åbnes i nyere versioner af Office.

- **Kan man åbne .odp i Word?**  
  Nej. `.odp` åbnes i **PowerPoint**. Word åbner `.odt`.

- **Er der behov for særlig software?**  
  Nej. Men vi anbefaler, at du bruger programmer, der understøtter ODF godt (fx LibreOffice eller nyere Microsoft Office).

- **Word-filer i Nextcloud?**  
  Ja. Nextcloud kan gemme alle almindelige filtyper. Browser-redigering afhænger af, hvilke apps der er slået til.  
  Vi anbefaler, at du så vidt muligt bruger **åbne filformater**.

## Mappestruktur og navngivning

Hold det enkelt og genkendeligt. Følg disse principper:

- brug klare og konsekvente filnavne, fx `2025-03-15_Referat_Bestyrelsesmoede.odt`  
- navngiv mapper, så det er tydeligt, hvad de indeholder  
- filer, der skal deles offentligt, placeres i produktets mappe under **“Offentlige filer til hjemmeside”** (eller tilsvarende offentlig mappe)  
- interne arbejdsfiler gemmes i produktets interne mappe i **OS2 Intern Nextcloud**  
- versionering (ændringshistorik) for dokumenter med offentlig relevans – fx governance, vejledninger, skabeloner – håndteres på **GitHub**  
- personlige noter og midlertidige arbejdsfiler kan godt ligge lokalt, men læg dem i fælles arkiv, når de får varig betydning for produktet

> 💡 **Lille vane, stor effekt:**  
> Sæt dato i filnavnet, når noget er endeligt (fx `2025-01-12_oplaeg_v1.pdf`).
