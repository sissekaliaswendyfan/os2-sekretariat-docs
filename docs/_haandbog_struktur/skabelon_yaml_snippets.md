

# 1. N1-overblik (i undermappe under docs/)

Filsti: docs/mappe_navn/index.md

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


Bruges til fx sekretariat, projekter & produkter, samarbejde i fællesskabet.

Juster ../product_toolbox til ./product_toolbox, hvis siden ligger direkte i docs/.


---

# 2. N2-overblik under “Projekter og produkter i OS2”

Filsti: fx docs/projekter_produkter/doc_sites.md

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


---

# 3. Værktøjsside i Værktøjskassen

Filsti: fx docs/toolbox/doc_site_tool.md

---
title: TITEL HER
layout: default
parent: Værktøjskasse til projekter og produkter
nav_order: 20
has_toc: false
---

---

# TITEL HER <span class="label">Værktøj · Projekter &amp; produkter</span>

{: .cta}
📚 **Har du brug for overblik først?** Læs **[RELATERET OVERBLIK](../projekter_produkter/doc_sites)** under *Projekter og produkter i OS2*.

(Beskrivelse, trin for trin, tjekliste osv.)


---

Hvis du bare gemmer de tre blokke et sted (lokalt eller i én markdown-fil), kan du copy/paste og kun rette:

title

labels

parent

nav_order

og stierne i CTA’erne.
