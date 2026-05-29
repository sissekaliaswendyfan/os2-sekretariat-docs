# Niveauer og sidetyper i håndbogen

Dette dokument forklarer, hvordan OS2’s håndbog kan inddeles i niveauer.

Det er lavet til dem, der skal oprette, flytte eller omskrive sider i håndbogen.

Formålet er at gøre det lettere at vurdere:

* hvad der skal være en hovedsektion
* hvad der skal være en underside
* hvornår noget skal ligge i Værktøjskassen
* hvordan overblik, vejledninger og baggrund holdes adskilt

### Se eksempel (docs/_haandbog_struktur/eksempel-aarshjul.md)

## Kort version

## TL;DR

Brug niveauerne sådan her:

- **N1** = de store hovedområder i håndbogen  
  Fx *Projekter og produkter i OS2*.

- **N2** = større emner under et hovedområde  
  Fx *Dokumentation og doc-sites*.

- **N3** = konkrete undersider under et emne  
  Fx *Hvad er et OS2-doc-site?* eller *Roller og ansvar for doc-sites*.

- **Værktøjskassen** = alt det, der hjælper læseren med at gøre noget konkret  
  Fx guides, tjeklister, skabeloner og trin-for-trin-vejledninger. 

Huskereglen er:

> **Overblik forklarer. Værktøj hjælper læseren med at gøre noget.**

Når du er i tvivl, så spørg:

> Skal læseren forstå noget, eller skal læseren gøre noget?

Hvis læseren skal forstå et område, hører det typisk hjemme som N1, N2 eller N3.  
Hvis læseren skal gøre noget konkret, hører det typisk hjemme i Værktøjskassen.


Brug denne tommelfingerregel:

| Niveau       | Bruges til                      | Eksempel                           |
| ------------ | ------------------------------- | ---------------------------------- |
| N1           | Hovedområde i håndbogen         | Projekter og produkter i OS2       |
| N2           | Emne under et hovedområde       | Dokumentation og doc-sites         |
| N3           | Konkret underside under et emne | Hvad er et OS2-doc-site?           |
| Værktøjsside | Guide, skabelon eller tjekliste | Dokumentationsside til dit produkt |

Husk:

> Overblik forklarer. Værktøj hjælper læseren med at gøre noget.

## Hvad betyder N1, N2 og N3?

N står for niveau.

Det handler om, hvor en side ligger i håndbogens struktur.

### N1: Hovedområder

N1 er de øverste hovedområder i håndbogen.

En N1-side skal give læseren et overblik over et helt område.

I udgangspunktet bør der ikke skabes flere N1-sider dvs. hovedområdesider. Indholdet skal inddeles i N2-emner. Se eksempel med [årshjul](docs/_haandbog_struktur/eksempel-aarshjul.md)

Eksempler på N1:

* OS2-sekretariatet: Sådan arbejder vi
* Projekter og produkter i OS2
* Samarbejde i OS2-fællesskabet
* Værktøjskasse til projekter og produkter

En N1-side skal svare på:

* Hvad finder du i denne del af håndbogen?
* Hvem er området især relevant for?
* Hvilke undersider eller næste skridt er vigtigst?

N1-sider bør ikke indeholde lange vejledninger.

Hvis der kommer trin-for-trin-indhold, skal det som regel flyttes til en vejledning eller Værktøjskassen.

### N2: Emner under et hovedområde

N2 er undersider under et N1-område.

En N2-side bruges til et større emne inden for hovedområdet.

Eksempel:

* N1: Projekter og produkter i OS2

  * N2: Dokumentation og doc-sites

En N2-side skal svare på:

* Hvad handler emnet om?
* Hvorfor er det relevant?
* Hvem er det relevant for?
* Hvad skal læseren forstå, før de går videre?
* Hvilke konkrete værktøjer eller undersider findes der?

N2-sider er ofte overblikssider.

De kan pege videre til:

* N3-sider med mere specifik forklaring
* værktøjssider med trin-for-trin-hjælp
* skabeloner
* relevante systemer eller repos

### N3: Konkrete undersider

N3 er undersider under et N2-emne.

En N3-side bruges, når et emne bliver for stort til at ligge på én side.

Eksempel:

* N1: Projekter og produkter i OS2

  * N2: Dokumentation og doc-sites

    * N3: Hvad er et OS2-doc-site?
    * N3: Minimumskrav til doc-sites
    * N3: Roller og ansvar for doc-sites
    * N3: Hvor ligger hvilken dokumentation?

En N3-side skal helst have ét tydeligt formål.

Eksempler:

* Forklare ét begreb
* Uddybe ét krav
* Beskrive ét ansvarsområde
* Samle baggrund om ét konkret emne

Hvis N3-siden bliver en praktisk guide, skal den måske i Værktøjskassen i stedet.

## Hvornår skal noget ligge i Værktøjskassen?

Værktøjskassen er til indhold, som hjælper læseren med at gøre noget konkret.

Værktøjssider hjælper læseren med at gøre noget konkret. Labels viser, hvem værktøjet er relevant for.

Brug Værktøjskassen til:

* guides
* trin-for-trin-vejledninger
* tjeklister
* skabeloner
* praktiske arbejdsredskaber

Eksempler:

* Dokumentationsside til dit produkt
* Fildeling
* Skabelon til beslutningsoplæg
* Tjekliste til mødeforberedelse
* Guide til opstart af et produktfællesskab

En god test er:

> Skal læseren gøre noget nu?

Hvis ja, hører indholdet ofte hjemme i Værktøjskassen.

## Overblik og værktøj skal hænge sammen

Overblikssider og værktøjssider skal gerne pege på hinanden.

Eksempel:

* Overbliksside: Dokumentation og doc-sites
  Forklarer hvad doc-sites er, hvorfor de findes, og hvilke rammer der gælder.

* Værktøjsside: Dokumentationsside til dit produkt
  Hjælper produktet med at oprette eller forbedre sit eget doc-site.

Overblikssiden kan have en CTA til værktøjet:

> 🛠️ Skal du gøre noget nu? Brug værktøjet **Dokumentationsside til dit produkt** i Værktøjskassen.

Værktøjssiden kan have en CTA tilbage til overblikket:

> 📚 Har du brug for overblik først? Læs **Dokumentation og doc-sites** under *Projekter og produkter i OS2*.

CTA betyder “call to action” – altså en tydelig henvisning til næste relevante handling.

## Sådan vælger du niveau

Brug disse spørgsmål, når du er i tvivl.

### 1. Er det et stort hovedområde?

Hvis siden handler om et helt område i håndbogen, er det sandsynligvis N1.

Eksempler:

* Hvordan sekretariatet arbejder
* Hvordan OS2 arbejder med projekter og produkter
* Hvordan OS2-fællesskabet samarbejder
* Hvor man finder guides og skabeloner

### 2. Er det et emne under et hovedområde?

Hvis siden handler om et større emne inden for et hovedområde, er det sandsynligvis N2.

Eksempler:

* Dokumentation og doc-sites
* Produktfællesskaber
* Sekretariatets rolle
* Fildeling

### 3. Er det en konkret uddybning?

Hvis siden forklarer ét konkret spørgsmål under et emne, er det sandsynligvis N3.

Eksempler:

* Hvad er et OS2-doc-site?
* Minimumskrav til doc-sites
* Roller og ansvar for doc-sites
* Hvad ligger på GitHub, og hvad ligger i Nextcloud?

### 4. Er det noget, læseren skal gøre?

Hvis siden hjælper læseren med at gøre noget konkret, er det sandsynligvis en værktøjsside.

Eksempler:

* Opret et doc-site
* Udfyld governance-template
* Del filer i Nextcloud
* Brug en skabelon

## Eksempelinddeling med placeholdertekst

Her er et eksempel på, hvordan en del af håndbogen kan bygges op.

### N1: Projekter og produkter i OS2

**Formål:**
Denne del af håndbogen er til dig, der arbejder med et konkret projekt eller produkt i OS2.

Her kan du få overblik over, hvad et OS2-produkt er, hvordan projekter bliver til produkter, hvilke roller der findes, og hvordan dokumentation, governance og samarbejde hænger sammen.

**Typiske undersider:**

* Hvad er et OS2-produkt?
* Hvad er et OS2-projekt?
* Fra projekt til OS2-produkt
* Dokumentation og doc-sites
* Roller og ansvar omkring produkter

### N2: Dokumentation og doc-sites

**Formål:**
Denne side giver overblik over, hvordan OS2 arbejder med dokumentation for produkter.

Her kan du læse, hvad et OS2-doc-site er, hvad det skal bruges til, og hvordan det hænger sammen med produktsider, GitHub, Nextcloud, governance og brugermanualer.

**Typiske undersider:**

* Hvad er et OS2-doc-site?
* Minimumskrav til doc-sites
* Roller og ansvar for doc-sites
* Hvor ligger hvilken dokumentation?
* Governance og doc-sites

**CTA til værktøj:**

> 🛠️ Skal du lave eller opdatere et doc-site nu? Brug værktøjet **Dokumentationsside til dit produkt** i Værktøjskassen.

### N3: Hvad er et OS2-doc-site?

**Formål:**
Denne side forklarer, hvad et OS2-doc-site er, og hvad det ikke er.

Et OS2-doc-site er produktets fælles håndbog og beslutningsgrundlag i OS2-fællesskabet.

Det er ikke en salgsside, ikke en ren brugermanual, ikke et nyhedssite og ikke et filarkiv.

**Typisk indhold:**

* Kort definition
* Hvad doc-sitet bruges til
* Hvad doc-sitet ikke bruges til
* Hvordan doc-sitet hænger sammen med andre steder

### Værktøjsside: Dokumentationsside til dit produkt

**Placering:**
Værktøjskasse til projekter og produkter

**Formål:**
Denne side hjælper produktet med at komme i gang med sit eget doc-site.

**Typisk indhold:**

* Hvad produktet skal afklare først
* Hvilke sider doc-sitet bør indeholde
* Hvordan governance-template kan bruges
* Hvad der skal linkes til
* Tjekliste før doc-sitet deles

**CTA tilbage til overblik:**

> 📚 Har du brug for rammer og minimumskrav først? Læs **Dokumentation og doc-sites** under *Projekter og produkter i OS2*.

## Eksempel på samlet struktur

```text
docs/
├─ projekter_produkter/
│  ├─ index.md
│  ├─ dokumentation-og-doc-sites.md
│  └─ doc-sites/
│     ├─ hvad-er-et-os2-doc-site.md
│     ├─ minimumskrav-til-doc-sites.md
│     ├─ roller-og-ansvar-for-doc-sites.md
│     └─ hvor-ligger-hvilken-dokumentation.md
│
├─ toolbox/
│  └─ doc_site_tool.md
```

Forklaring:

* `projekter_produkter/index.md` er N1-overblik.
* `dokumentation-og-doc-sites.md` er N2-overblik.
* filerne i `doc-sites/` er N3-undersider.
* `toolbox/doc_site_tool.md` er værktøjssiden.

## YAML-skabeloner

YAML er sidens metadata øverst i markdown-filen.

Det er her, man styrer titel, placering i menuen og rækkefølge.

### 1. N1-overblik

Filsti:

```text
docs/mappe_navn/index.md
```

Skabelon:

```md
---
title: TITEL HER
layout: default
nav_order: 10
has_children: true
---

# TITEL HER <span class="label label-purple">Overblik</span> <span class="label">DOMÆNE HER</span>

{: .cta}
🛠️ **Leder du efter værktøjer, guides eller skabeloner?** Gå til **[Værktøjskassen](../product_toolbox)**

(Introtekst)
```

Bruges til fx:

* OS2-sekretariatet: Sådan arbejder vi
* Projekter og produkter i OS2
* Samarbejde i OS2-fællesskabet

Bemærk:

Juster linket til Værktøjskassen, hvis siden ligger et andet sted.

Hvis siden ligger direkte i `docs/`, kan linket fx være:

```md
[ Værktøjskassen ](./product_toolbox)
```

Hvis siden ligger i en undermappe, kan linket fx være:

```md
[ Værktøjskassen ](../product_toolbox)
```

### 2. N2-overblik

Eksempel:

```text
docs/projekter_produkter/dokumentation-og-doc-sites.md
```

Skabelon:

```md
---
title: TITEL HER
layout: default
parent: Projekter og produkter i OS2
nav_order: 20
has_children: true
---

# TITEL HER <span class="label label-purple">Overblik</span> <span class="label">Projekter &amp; produkter</span>

{: .cta}
🛠️ **Skal du gøre noget nu?** Brug værktøjet **[RELATERET VÆRKTØJ](../toolbox/filnavn_her)** i Værktøjskassen.

(Introtekst)
```

Bruges til emner under et hovedområde.

Eksempler:

* Dokumentation og doc-sites
* Produktfællesskaber
* Sekretariatets rolle og opgaver

### 3. N3-side

Eksempel:

```text
docs/projekter_produkter/doc-sites/hvad-er-et-os2-doc-site.md
```

Skabelon:

```md
---
title: TITEL HER
layout: default
parent: Dokumentation og doc-sites
grand_parent: Projekter og produkter i OS2
nav_order: 10
---

# TITEL HER

(Kort forklaring på 2-4 linjer)

## Hvornår bruger du denne side?

- Situation 1
- Situation 2
- Situation 3

## Det vigtigste kort

- Punkt 1
- Punkt 2
- Punkt 3

## Uddybning

(Indhold)
```

Bruges til konkrete undersider under et N2-emne.

### 4. Værktøjsside i Værktøjskassen

Eksempel:

```text
docs/toolbox/doc_site_tool.md
```

Skabelon:

```md
---
title: TITEL HER
layout: default
parent: Værktøjskasse til projekter og produkter
nav_order: 20
has_toc: false
---

# TITEL HER <span class="label">Værktøj · Projekter &amp; produkter</span>

{: .cta}
📚 **Har du brug for overblik først?** Læs **[RELATERET OVERBLIK](../projekter_produkter/filnavn_her)** under *Projekter og produkter i OS2*.

(Beskrivelse, trin for trin, tjekliste osv.)
```

Bruges til konkrete guides, tjeklister og skabeloner.

## Når du kopierer en skabelon

Når du kopierer en af skabelonerne, skal du som minimum rette:

* `title`
* label i overskriften
* `parent`
* `grand_parent`, hvis siden er N3
* `nav_order`
* links i CTA’er
* intro- og brødtekst

## Hurtig beslutningsregel

Brug denne, når du er i tvivl:

| Spørgsmål                                       | Placering                             |
| ----------------------------------------------- | ------------------------------------- |
| Handler det om et helt hovedområde?             | N1                                    |
| Handler det om et emne under et hovedområde?    | N2                                    |
| Uddyber det ét konkret spørgsmål under et emne? | N3                                    |
| Hjælper det læseren med at gøre noget konkret?  | Værktøjskassen                        |
| Er det baggrund, regler eller historik?         | Ofte underside/baggrund – ikke øverst |
| Er det bare links?                              | Ressourceside eller kort linkafsnit   |
