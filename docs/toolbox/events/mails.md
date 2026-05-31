---
title: Automatiske mails til deltagere
layout: default
parent: Opret event i Odoo
grand_parent: Værktøjskasse til projekter og produkter
nav_order: 20
has_toc: false
---

# Automatiske mails til deltagere 

Denne side viser, hvordan du opsætter **automatiske mails** til deltagere i et Odoo-event 📩

Du finder information om
- hvordan du bruger mailskabeloner korrekt
- hvordan du undgår at ændre noget for andre events
- hvordan du sikrer, at eventet bruger *din* mail (og ikke en [GLOBAL]-skabelon)

---

## ⚠️ Vigtigt (læs dette først)

Odoo er skabelon-baseret.

- 🚫 **[GLOBAL]-skabeloner må ikke rettes direkte**
- ♻️ Vil du bruge samme opsætning/udseende, skal du **duplikere skabelonen** og redigere din egen kopi

> Hvis du retter i en [GLOBAL]-skabelon, slår ændringen igennem på *alle* events, der bruger skabelonen. :contentReference[oaicite:0]{index=0}

---

## Overblik: sådan fungerer mails i Odoo

Der vil være tre forudoprettede mails på eventet (typisk ved tilmelding, 3 dage før og 1 time før).  
Vi anbefaler, at du **opretter dine egne mails** og **sletter [GLOBAL]-mails** på *dette* event bagefter. :contentReference[oaicite:1]{index=1}

---

## 1) Find fanen “Kommunikation”

1. Åbn dit event i Odoo
2. Gå til fanen **Kommunikation** (nederst på event-siden)
3. Klik **Tilføj linje**
4. Sørg for, at typen er **Mail** (ikke SMS) via dropdown-pilen 🔻

---

## 2) Vælg en skabelon og åbn den

1. Vælg en skabelon i dropdown-menuen
2. Hold musen over linjen
3. Klik på den lille pil **▶** (til højre)

Nu er du inde i selve skabelonen.

---

## 3) Duplikér skabelonen (så du må redigere)

1. Øverst til højre ser du **Ny**-knappen og stien, fx:  
   `Arrangementer / [event-titel]`
2. Under stien ser du navnet på mailskabelonen
3. Klik på **tandhjulet ⚙** til højre for skabelonnavnet
4. Vælg **Duplikér**

✅ Nu arbejder du i din egen kopi.

---

## 4) Ret mailens indhold

1. Klik på linjen med mailtitlen
2. Klik på pilen **▶** for at åbne mailen

Du ser typisk fanerne:
- **Indhold**
- **E-mail konfiguration**
- **Opsætning**

### Du skal kun rette i “Indhold”

- Skriv teksten til deltageren
- Brug `/` for formatering og dynamiske felter (fx deltagerens navn)

**Eksempel (dynamisk felt):**
- Skriv `/`
- Vælg **Dynamic Placeholder**
- Søg fx på “Navn” og vælg deltagerens navn-felt
- Tryk enter (standardværdi kan være tom)

### 🚫 Ret ikke i “E-mail konfiguration”

Her kan stå systemfelter, som ikke skal ændres (fx afsender-felt / flettefelt).

### 🚫 Ret ikke i “Opsætning”

Her kan stå systemfelter om sprog (flettefelt), som ikke skal ændres.

---

## 5) Vælg den rigtige mail på eventet (meget vigtigt)

Når du går tilbage til eventets backend:

⚠️ **Vigtigt:** Odoo kan have valgt en [GLOBAL]-skabelon i stedet for din nye mail.

1. Find dropdown-menuen med mails på eventet (klik på den lille trekant)
2. Find din nye mail i listen
3. Vælg **din** mail 

---

## 6) Indstil hvornår mailen sendes

På mail-linjen indstiller du:

- **Enhed**: Timer / Dage / Uger / Måneder / Omgående
- **Interval**: fx 0, 1, 3 osv.
- **Trigger**: Efter hver tilmelding / Før arrangementet / Efter arrangementet

📌 Hvis mailen skal sendes straks ved tilmelding:

- Interval: **0**
- Enhed: **Omgående**
- Trigger: **Efter hver tilmelding** :contentReference[oaicite:2]{index=2}

---

## 7) Slet [GLOBAL]-mails (hvis du har lavet dine egne)

Hvis du har oprettet dine egne mails, så slet de forudoprettede mails med **[GLOBAL]** på *dette event*.

- Brug skraldespands-ikonet 🗑 ude til venstre for linjen :contentReference[oaicite:3]{index=3}

---

## Særligt for online events

Ved online events skal du:
- oprette mødet (fx Teams) uden for Odoo
- indsætte mødelinket manuelt i dine mails 🔗
- sende en ekstra påmindelse tæt på start (fx 1–3 timer før) ⏰ :contentReference[oaicite:4]{index=4}

---

## Brug for hjælp?

Kontakt OS2-sekretariatet: **os2@os2.eu**
