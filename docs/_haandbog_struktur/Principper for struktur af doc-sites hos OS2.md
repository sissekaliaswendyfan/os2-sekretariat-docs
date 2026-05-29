# Principper for struktur og formidling i OS2’s håndbog og doc-sites

Dette dokument samler de vigtigste principper for struktur og formidling i arbejdet med OS2’s håndbog og OS2’s doc-sites.

Principperne er lavet for at gøre dokumentationen lettere at:

* forstå
* bruge
* udbygge
* vedligeholde
* overdrage til andre

De gælder både, når vi arbejder med OS2’s fælles håndbog, og når vi hjælper produkter med at lave egne doc-sites.

## Kort version

Brug disse principper:

1. Tag udgangspunkt i brugerens situation og opgave.
2. Byg indhold i tre lag: **Overblik → Handling → Baggrund**.
3. Giv hver side ét tydeligt formål.
4. Svar kort først og læg detaljer bagefter.
5. Skriv klart, konkret og venligt.
6. Gør navigation og næste skridt tydelige.
7. Brug få, stabile links.
8. Hold forskellige typer dokumentation adskilt.

Den vigtigste huskeregel er:

> Dokumentation skal hjælpe læseren med at forstå, hvor de er, hvad der forventes af dem, og hvad de kan gøre som næste skridt.

## Hvorfor er principperne nødvendige?

OS2’s dokumentation dækker komplekse emner:

* produkter
* projekter
* governance
* roller og ansvar
* samarbejde
* arbejdsgange
* skabeloner
* GitHub
* doc-sites
* filarkiver
* brugermanualer
* fælles beslutninger

Det er let at komme til at blande det hele sammen.

Når overblik, vejledning, baggrund, skabeloner og links ligger blandet på samme side, bliver det svært for læseren at finde ud af:

* hvad siden egentlig skal bruges til
* hvad der er vigtigt nu
* hvad der bare er baggrund
* hvad der er en fælles regel
* hvad der er en praktisk vejledning
* hvor detaljerne egentlig hører hjemme

Derfor bygger principperne på én enkel idé:

> Gør indgangen enkel, og placér kompleksiteten dér, hvor den hører hjemme.

## 1. Tag udgangspunkt i brugerens situation og opgave

Alt indhold skal kunne svare på:

> Hvem er du – og hvad er det, du prøver at løse lige nu?

God dokumentation starter ikke med vores interne struktur.

Den starter med læserens situation.

Spørg derfor altid:

* Hvem er læseren?
* Hvad prøver læseren at finde ud af?
* Hvad skal læseren kunne gøre efter at have læst siden?
* Er læseren ny, erfaren, presset, undersøgende eller i gang med en konkret opgave?
* Har læseren OS2 som helhed i hovedet – eller et bestemt projekt/produkt?

Eksempler på brugeropgaver:

* “Jeg er ny produktkoordinator. Hvad forventes der af mig?”
* “Vi har et produkt. Skal vi have et doc-site?”
* “Jeg skal finde en skabelon til governance.”
* “Jeg skal forstå forskellen på produktside, doc-site og GitHub-repo.”
* “Jeg skal vide, hvem der har ansvar for hvad.”

Kort fortalt:

> Skriv ikke først ud fra, hvad OS2 gerne vil fortælle. Skriv først ud fra, hvad læseren prøver at løse.

## 2. Byg indhold i tre lag: Overblik → Handling → Baggrund

Indhold bør bygges i tre lag:

1. **Overblik**
   Hvad er det? Hvorfor er det vigtigt? Hvem er det relevant for? Hvad er næste skridt?

2. **Handling**
   Hvordan gør jeg? Hvilke trin skal jeg følge? Hvem gør hvad? Hvilken skabelon bruger jeg?

3. **Baggrund**
   Hvorfor gør vi det sådan? Hvilke regler, beslutninger, principper eller historik ligger bag?

Det betyder ikke, at alt skal være langt.

Det betyder, at læseren ikke skal tvinges gennem baggrundsstof for at kunne handle.

Eksempel:

* Overbliksside: “Dokumentation og doc-sites”
* Handlingsside: “Dokumentationsside til dit produkt”
* Baggrundsside: “Principper for doc-sites i OS2”

Kort fortalt:

> Forklar først rammen. Hjælp derefter læseren med at handle. Læg begrundelser og detaljer til sidst.

## 3. Giv hver side ét tydeligt formål

En side skal helst have ét hovedformål.

Når du har læst en side, skal du kunne sige:

> “Den her side hjalp mig med X.”

Hvis siden prøver at være tre ting på én gang, skal den som regel deles op.

Brug denne sortering:

| Hvis læseren skal…          | Så er siden typisk en… | Typisk indhold                                                                       |
| --------------------------- | ---------------------- | ------------------------------------------------------------------------------------ |
| forstå et område            | Overbliksside          | Hvad er det? Hvorfor er det vigtigt? Hvem er det relevant for? Hvad er næste skridt? |
| gøre noget konkret          | Vejledning             | Trin for trin, rækkefølge, ansvar og praktiske handlinger                            |
| kopiere eller udfylde noget | Skabelon               | Tekstskabelon, formular, eksempel eller tjekliste                                    |
| vælge mellem muligheder     | Beslutningshjælp       | Kriterier, anbefaling, fordele/ulemper og “vælg dette hvis…”                         |
| forstå hvorfor noget gælder | Baggrund/princip       | Begrundelse, regler, beslutningsgrundlag og historik                                 |
| finde videre                | Ressource-/linkside    | Få, stabile links til centrale dokumenter, repos eller systemer                      |

En side må gerne linke videre til andre sidetyper.

Men den skal ikke selv være alle sidetyper på én gang.

Kort fortalt:

> Én side = ét hovedformål.

## 4. Svar kort først og læg detaljer bagefter

Mange læser ikke dokumentation fra ende til anden.

De scanner først.

Derfor skal det vigtigste stå øverst i en kort, klar form.

Start gerne sider med:

* en kort forklaring
* hvem siden er relevant for
* hvad læseren kan bruge siden til
* de vigtigste næste skridt

Derefter kan I uddybe.

En god standardstruktur kan være:

```md
# Titel

Kort forklaring på 2-4 linjer.

## Hvornår bruger du denne side?

- Situation 1
- Situation 2
- Situation 3

## Det vigtigste kort

- Punkt 1
- Punkt 2
- Punkt 3

## Sådan gør du

1. Trin
2. Trin
3. Trin

## Baggrund og detaljer

Længere forklaring, principper, historik eller beslutningsgrundlag.
```

Kort fortalt:

> Giv læseren en landingsbane, før I giver dem hele lufthavnen.

## 5. Skriv klart, konkret og venligt

Vi skriver til kloge mennesker med travlt.

Derfor skal sproget være:

* klart
* konkret
* venligt
* kort, hvor det kan være kort
* præcist, hvor det skal være præcist

Forklar fagord og forkortelser første gang, de optræder.

Eksempel:

> Governance betyder styring: altså de aftaler, roller, krav og beslutninger, der rammer et produkt ind.

Undgå at skrive for internt, hvis siden også skal kunne læses af nye i OS2-fællesskabet.

Skriv hellere:

> Brug denne side, når du skal finde ud af, hvem der har ansvar for hvad.

end:

> Siden beskriver ansvarsplacering i relation til den organisatoriske governance-model.

Kort fortalt:

> Vi forenkler ikke fagligheden. Vi forenkler adgangen til fagligheden.

## 6. Gør navigation og næste skridt tydelige

Brugeren skal altid kunne se:

* hvor de er
* hvad siden handler om
* hvad de kan gøre bagefter
* hvor de kan læse mere
* hvor de kan finde et konkret værktøj, hvis de skal handle

I håndbogen arbejder vi derfor med en kobling mellem overblikssider og værktøjssider.

**Overblikssider** forklarer rammer, begreber og sammenhæng.

**Værktøjssider** hjælper læseren med at gøre noget konkret.

Eksempel:

* En overbliksside om “Dokumentation og doc-sites” forklarer, hvad et OS2-doc-site er, hvorfor det er vigtigt, og hvilke forventninger der gælder.
* En værktøjsside om “Dokumentationsside til dit produkt” viser, hvordan man konkret kommer i gang.

Overblikssider kan derfor have CTA’er til Værktøjskassen.

CTA betyder “call to action” – altså en tydelig henvisning til næste relevante handling.

Værktøjssider kan have CTA’er tilbage til det relevante overblik.

Kort fortalt:

> Læseren skal kunne vælge mellem “jeg skal forstå det først” og “jeg skal bare i gang”.

## 7. Brug få, stabile links

Links er nyttige, men de skaber også vedligehold.

Hvert link er:

* et valg for læseren
* en mulig blindgyde
* noget, der kan blive forældet
* noget, nogen skal huske at rette

Brug derfor få og stabile links.

Gode links går typisk til:

* centrale sektioner
* faste repos
* faste skabeloner
* centrale systemer
* officielle sider

Undgå at en forside eller overbliksside bliver en lang linkliste.

Menuen viser hele strukturen.

Forsiden eller overblikssiden skal kun pege på de vigtigste døre.

Kort fortalt:

> Færre links giver mindre støj og mindre vedligehold.

## 8. Forsiden er en velkomst – ikke en indholdsfortegnelse

En forside skal ikke gentage hele menuen.

Der er forskel på:

* **Menu/indholdsfortegnelse**: viser hele strukturen.
* **Forside/landingsside**: hjælper læseren med at forstå, hvad sitet er, og hvor de kan starte.

Hvis forsiden bliver en lang liste over alle sider, får vi ofte:

* dobbeltarbejde
* for mange valg
* mere vedligehold
* en oplevelse af overload
* uklare indgange for nye læsere

En god forside skal i stedet svare kort på tre spørgsmål:

1. **Hvad er det her?**
2. **Hvem er det til – og hvornår er du det rigtige sted?**
3. **Hvad kan du gøre herfra?**

Eksempel:

```md
Dette site samler dokumentation om [X].
Det bruges til [formål].

Du er det rigtige sted, hvis du fx er:

- [rolle] og skal [situation]
- [rolle] og skal [situation]

Her kan du:

- få overblik over [tema]
- se, hvordan du gør [proces]
- læse, hvilke krav der gælder for [noget]
```

Kort fortalt:

> Menuen er oversigten. Forsiden er den hjælpsomme person, der tager imod dig i døren.

## 9. Adskil håndbog, doc-site, produktside, filarkiv og GitHub

En vigtig del af arbejdet er at gøre det tydeligt, hvad der hører hjemme hvor.

Ellers kommer håndbogen og produkternes dokumentation hurtigt til at blande sig sammen.

Brug denne enkle skelnen:

| Sted                  | Bruges især til                                                        |
| --------------------- | ---------------------------------------------------------------------- |
| OS2’s håndbog         | Fælles rammer, principper, arbejdsgange og vejvisning                  |
| Produktets doc-site   | Produktets egen dokumentation, roller, drift, governance og vejledning |
| Produktside på os2.eu | Offentlig præsentation/salgsside for produktet                         |
| GitHub-repo           | Kode, tekniske filer, issues og skabeloner                             |
| Filarkiv/Nextcloud    | Dokumenter, bilag og arbejdsfiler                                      |
| Brugermanual          | Konkret hjælp til slutbrugere eller administratorer                    |

Håndbogen må gerne linke videre.

Men håndbogen skal ikke prøve at samle alt.

Kort fortalt:

> Håndbogen er indgangen og vejviseren. Den er ikke hele arkivet.

## 10. Særligt om doc-sites

Der ligger en del materiale om OS2-doc-sites i arbejdet med håndbogen.

Det er med, fordi arbejdet med håndbogen viste et beslægtet behov:

Flere OS2-produkter er begyndt at etablere egne doc-sites, og der har samtidig været uklarhed om forskellen på:

* produktsider
* doc-sites
* brugermanualer
* GitHub-repos
* governance-skabeloner
* filarkiver

Der har også været behov for at gøre det lettere for produkterne at tage OS2’s GitHub-baserede skabeloner og styringsmodel i brug.

Derfor blev doc-site-materialet udviklet som en afløber af håndbogsarbejdet.

Det skal ikke forstås som om håndbogen primært handler om doc-sites.

Det skal forstås sådan:

> Håndbogen skal forklare de fælles rammer for dokumentation i OS2, mens doc-site-materialet skal hjælpe de enkelte produkter med at lave og vedligeholde deres egen dokumentation.

### Hvad er et OS2-doc-site?

Et OS2-doc-site er produktets fælles håndbog og beslutningsgrundlag i OS2-fællesskabet.

Det er ikke produktets salgsside.

Det er heller ikke nødvendigvis den fulde tekniske dokumentation eller en komplet brugermanual.

Et doc-site er den fælles indgang, hvor man kan forstå:

* hvad produktet er
* hvem der har ansvar
* hvordan man kommer i gang
* hvordan drift, support og udvikling foregår
* hvilke krav, aftaler og beslutninger der gælder
* hvor man finder mere detaljeret hjælp

Doc-sitet må gerne linke videre til salgsside, brugermanual, GitHub, Nextcloud og andre systemer.

Men doc-sitet skal gøre det tydeligt, hvad der ligger hvor.

Kort fortalt:

> Et OS2-doc-site er produktets fælles referencepunkt – ikke produktets salgsside, filarkiv eller brugermanual.

## 11. Praktisk tjekliste, når I opretter eller flytter en side

Brug denne tjekliste, når I arbejder med sider i håndbogen eller på et doc-site.

### 1. Hvad er sidens formål?

Siden skal især hjælpe læseren med at:

* forstå noget
* gøre noget
* vælge noget
* kopiere noget
* finde noget
* forstå baggrunden for noget

Vælg én primær funktion.

### 2. Hvem er siden til?

Skriv gerne for jer selv:

> Denne side er især til [målgruppe], når de skal [opgave].

Eksempel:

> Denne side er især til produktkoordinatorer, når de skal finde ud af, hvordan produktets doc-site skal bygges op.

### 3. Hvor hører siden hjemme?

Brug hovedsporene i håndbogen:

* **Sekretariatet** = hvordan OS2-sekretariatet arbejder
* **Projekter og produkter** = når læseren har et konkret projekt eller produkt
* **Samarbejde i OS2-fællesskabet** = community, relationer og fælles arbejde
* **Værktøjskassen** = guides, skabeloner og tjeklister

### 4. Skal noget flyttes ud?

Hvis siden indeholder både overblik, trin-for-trin, historik, links og skabeloner, så overvej at dele den op.

Spørg:

* Er noget af dette en vejledning?
* Er noget af dette en skabelon?
* Er noget af dette baggrund?
* Er noget af dette kun et link videre?

### 5. Er næste skridt tydeligt?

Når læseren har læst siden, skal de kunne se, hvad de kan gøre bagefter.

Det kan fx være:

* gå til en vejledning
* bruge en skabelon
* læse baggrund
* kontakte en bestemt rolle
* gå til produktets doc-site
* finde en fil i et andet system

Kort fortalt:

> En god side efterlader ikke læseren med “okay, men hvad gør jeg så?”

## Kilder og inspiration

Principperne bygger bl.a. på praksis fra content design, plain language og web-brugervenlighed.

Relevante kilder:

* Nielsen Norman Group: *How Users Read on the Web*
* Nielsen Norman Group: *How People Read Online*
* GOV.UK: *Content design: planning, writing and managing content*
* Digital.gov: *Principles of plain language*
* WHO: *Use plain language*
* Microsoft Writing Style Guide
