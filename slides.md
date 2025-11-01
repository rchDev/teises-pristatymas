---
# try also 'default' to start simple
theme: academic
# some information about your slides (markdown enabled)
colorSchema: light
fonts:
  mono: Roboto
themeConfig:
  paginationX: r
  paginationY: b
  paginationPagesDisabled: [3, 7]
title: Patrick McHardy vs GENIATECH
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
layout: cover
figureUrl: Old Mountain Troll.webp
coverAuthor: Rizvan Chalilovas
coverAuthorUrl: https://github.com/rchDev
coverDate: 2025-11-04
---

# **Patrick McHardy vs GENIATECH**
### Riba tarp trolinimo ir vykdymo kontrolės


---
layout: figure-side
mdc: true
transition: view-transition
figureUrl: /multiple_trolls.png
figureWidth: 90%
---

# **Trolių rūšys** {.vt-title}

- Folkloriniai / mitologiniai {.vt-item}
- Socialiniai {.vt-item}
  - Interneto {.vt-item}
    - Provokuojantys {.vt-item}
    - Įžeidinėjantys / Priekabiaujantys {.vt-item}
    - „Rūpestingi“ (apsimetantys draugiškais) {.vt-item}
    - Valstybiniai / Propagandiniai {.vt-item}
  - Gatvės {.vt-item}
  - Dezinformacijos {.vt-item}
- <span v-mark.box.orange="{color: '#ffb347', animationDuration:800}">Teisiniai (Intelektinės Nuosavybės)</span> {.vt-item}
    - Patentų {.vt-item}
    - <span v-mark.highlight="{color: '#e63946', animationDuration:800}">Autorių teisių / Licencijų troliai</span> {.vt-item}
    - Prekių ženklų {.vt-item}

---
mdc: true
transition: view-transition
layout: figure-side
figureUrl: public/Norgeillus 1-1.webp
figureX: r
---

# **Teisiniai (Intelektinės Nuosavybės) troliai**

**Kas jie?**

Fiziniai ar juridiniai asmenys, kurie piktnaudžiauja teisine sistema (ypač intelektinės nuosavybės teise),
kad gautų finansinę naudą, o ne siektų teisingumo ar realaus teisių įgyvendinimo.

**Rūšys:**
- <span v-mark.box="{color: '#ffb347', animationDuration:800}">Patentų troliai</span>
- <span v-mark.box="{color: '#ffb347', animationDuration:800}">Autorių teisių / Licencijų troliai</span>
- Prekių ženklų troliai

---
mdc: true
transition: view-transition
layout: figure-side
figureUrl: public/two_trolls.webp
figureX: r
---

# **Patentų VS Licencijų**

### Pagrindiniai skirtumai

| | **Patentų** | **Licencijų** |
|-----------|-----------|------------|
| **Prigimtis** | Dažniausiai spec. įmonės | Dažniausiai kūrėjai |
| **Atakos objektas** | Aibė patentą pažeidusių technologijų | Konkreti PĮ ar jos dalis |
| **Labiausiai paplitę** | JAV | ES |
| **Erzinimo lygis** | <span style="color:#5B6236;">★★★★★</span> | <span style="color:#5B6236;">★★★★☆</span>|

---
mdc: true
transition: view-transition
layout: figure
figureUrl: /public/Informatikos teisės pristatymas-2.svg
---

# **Veikimo principas**

---
layout: top
mdc: true
transition: view-transition
---

# **Žinomi IP troliai**

<br/>

**Patentų:**
- VirnetX (Apple trolis) (JAV)
- Sable Networks Inc. (JAV)
- Uniloc Corporation (JAV)

<br/>

**Licencijų:**
- <span v-mark.box="{color: '#ffb347', animationDuration:800}">Patrick McHardy "GPL trolis" (ES)</span>
- Open Source Security, Inc. (JAV)
- Hans Reiser / Namesys (JAV)

---
layout: figure-side
figureUrl: public/masked_villain.png
mdc: true
transition: view-transition
---

# **Patrick McHardy**
- 🇩🇪 Vokietijos pilietis
- Prisidėjo prie Linux branduolio ir "Netfilter" karkaso kūrimo 2006-2014 m.
- 2016-2018 m. vykdė GPL licencijos atitikties užtikrinimo kampaniją, kurios metu iš kompanijų ir individualių kūrėjų išgavo apie 3 mln. eur.,
todėl buvo pramintas GPL trolio vardu.

---
layout: default
mdc: true
transition: view-transition
---

# **Kaip veikė McHardis?**

**Taikiniai:** smulkos ar vidutinio dydžio įmonės, padariusios daug neesminių GPLv2 licencijos pažeidimų.

**Schema:**
1. Atsiunčiamas cease-and-desist laiškas, kuriame:
    - nurodoma sumokėti smulkią kontrakto pažeidimo baudą,
    - sutikti su svarbia sąlyga, jog pakartotinių licencijos pažeidimo atvejų metu, sutarties dalyvis turės sumokėti didėjančią baudą.
2. Aukai sutikus su pirmosios sutarties sąlygomis, siunčiami nauji cease-and-desist laiškai, kuriuose minimi kiti GPL licencijos pažeidimai su reikalavimais mokėti vis didesnes baudas
    ir sutikti su papildomomis sąlygomis.


---
layout: center
transition: view-transition
---

# **Kas lėmė schemos veiksmingumą?**

### Vokietijos teisinė sistema ir teismų praktika

---
layout: top
transition: view-transition
---

# **Vokietijos teisinė sistema**
<br/>

- Teismas gali be žodinio nagrinėjimo išduoti laikiną teismo draudimą, kurį panaikinti iki jo termino pabaigos yra sunku.
- Atsakovo prieštaravimas nestabdo teismo draudimo
- Laisvas teismo vietos pasirinkimas
- Ieškovas gali bet kada atsiimti prašymą dėl draudimo
- Teismų uždarumas
- Ieškovas gali iš atsakovo reikalauti sumokėti baudą savo naudai


---
layout: top
transition: view-transition
---

# **Lemtinga byla**

<br/>

**Priešistorė:**

- 2006-2014 m. Patrick McHardy prisidėjo prie „Netfilter“ projekto.
- 2016-2017 m. McHardy siautėjo, puldinėdamas visų GPLv2 licencijos nuostatų nesilaikančių įmonių

---
layout: top
transition: view-transition
---

# **„Geniatech“ VS McHardy (1)**

<br/>

**Ginčas:**

- „Geniatech“ iš McHardy gavo perspėjimo laišką apie GPLv2 pažeidimą.
- „Geniatech“ 2017 liepos 17 d. gauna susitarimo laišką iš Patrick McHardy, kuriame McHardy prašo įmonės nutraukti pažeidimą ir sumokėti baudą.
- 2017 liepos 24 d. „Geniatech“ atsisako sutikti su sutarties sąlygomis.
- 2017 liepos 26 d. Patrick McHardy nutraukia „Geniatech“ GPLv2 licenciją.
- 2017 rugpjūčio 4 d. Patrick McHardy pasirašo priesaikos deklaraciją, kurioje išdėsto esminius pažeidimo faktus kartu su įrodymais.

---
layout: top
transition: view-transition
---

# **„Geniatech“ VS McHardy (2)**

<br/>

**Draudimas:**

- 2017 rugpjūčio 10 d. Patrick McHardis Kelno apygrados teismui pateikė prašymą dėl laikinojo draudimo.
- 2017 rugpjūčio 24 d. įmonei „Geniatech“ išdavė laikinąjį draudimą platinti produkciją, turinčią McHardžio rašytą programinį kodą, nes McHardžiui pavyko įrodyti:
  - autorystę,
  - autorinių teisių pažeidimo egzistavimą,
  - skubumo svarbą,
  - įrodymų pakankamumą.

---
layout: top
transition: view-transition
---

# **Geniatech VS McHardy (3)**

<br/>

**Pagrindiniai Geniatech argumentai:**

- 2017 m. rugpjūčio 30 d. „Geniatech“ pateikė prieštaravimą dėl laikinojo draudimo, kuriame teigė:
  - Laikinasis draudimas yra pernelyg abstraktus ir yra taikomas per plačiai.
  - Patrick McHardy piktnaudžiauja savo teisėmis ir siekia pasipelnyti.
  - Skubos nėra, nes McHardy seniai žinojo apie pažeidimą ir nesikreipė į teismą.
  - GPLv2 licencija yra pernelyg abstrakti ir dviprasmiška, todėl negali būti taikoma Vokietijoje.
  - McHardy indėlis į Linux branduolį yra pernelyg menkas, kad jam būtų suteikta autorystės teisė.

---
layout: top
transition: view-transition
---

# **Geniatech VS McHardy (4)**

- 2017 m. spalio 12 d. Vokietijos Kelno apygardos teisme įvyko žodinis nagrinėjimas, kuriame abi šalys:
  - pateikė žodinius argumentus
  - pristatė ekspertų išvadas

- 2017 m. spalio 17 d. abi šalys Kelno apygardos teismui pateikė galutinius rašytinius paaiškinimus.

- 2017 m. spalio 21 d. Kelno apygardos teismas pateikė išvadas ir pateikė galutinį nutarimą.

---
layout: figure-side
figureUrl: public/teismo_sprendimas.png
---

# **Teismo išvados ir nutarimas**

- **Bylos numeris:** 14 O 188/17
- **Vieta:** Kelno apygardos teismas
- **Ieškovas:** Patrick McHardy
- **Atsakovas:** Geniatech Europe GmbH
- **Teisėjai:**
  - Dr. Koepsel
  - Hübeler-Brakat
  - Dr. Gryska
- **Esmė:** „Geniatech“ pažeidė autorines teises ir turi nutraukti su pažeidimu susijusią veiklą, bei ieškovui (Patrick McHardy) išmokėti kompensaciją.

---
layout: top
transition: view-transition
---

# **Kelno apygardos teismo išvados (1)**

### **McHardžio pusė:**

1. **McHardy** turi autorystės teisę į „Linux“ branduolio komponentą: „Netfilter“. <span class="font-bold text-[#1565c0]">PALANKU</span>
2. **McHardy** 2017 m. rūgpjūčio 4 d. priesaikos metu pateikti įrodymai laikomi pakankamais. <span class="font-bold text-[#1565c0]">PALANKU</span>
3. **GENIATECH** naudojoto McHardžio kodą savo įrenginiuose. <span class="font-bold text-[#1565c0]">PALANKU</span>
4. **GENIATECH** pažeidė GPLv2 licenciją, nepaviešindama viso šaltinio kodo ir neįterpdama licencijos teksto. <span class="font-bold text-[#1565c0]">PALANKU</span>
5. **GENIATECH** GPLv2 licencija buvo nutraukta teisėtai. <span class="font-bold text-[#1565c0]">PALANKU</span>
6. **McHardy** turi teisę reikalauti laikinosios drausminės priemonės. <span class="font-bold text-[#1565c0]">PALANKU</span>
7. Skubos reikalavimas tenkinamas, nes McHardy į teismą kreipėsi anksčiau, nei per mėnesį nuo žinios apie pažeidimą.<span class="font-bold text-[#1565c0]">PALANKU</span>
8. **McHardy** nepiktnaudžiavo savo teisėmis. <span class="font-bold text-[#1565c0]">PALANKU</span>
9. Teismo išlaidos, kurias turės padengti **GENIATECH**, sumažintos nuo 200 tūkst. EUR iki 100 tūkst. EUR. <span class="font-bold text-[#ff9800]">IŠ DALIES</span>

---
layout: top
transition: view-transition
---

# **Kelno apygardos teismo išvados (2)**

### **GENIATECH pusė:**

1. Prašymas dėl drausminės priemonės yra pernelyg platus. <span class="font-bold text-[#e63946]">NEPALANKU</span>
2. **McHardy** neturi autorių teisių „Linux“ branduoliui. <span class="font-bold text-[#e63946]">NEPALANKU</span>
3. **McHardy** piktnaudžiavo savo teisėmis ir vykdė sistemingą GPL licenciją pažeidusiųjų persekiojimo kampaniją, tokiu būdu siekdamas pelno. <span class="font-bold text-[#e63946]">NEPALANKU</span>
4. **GPLv2** licencija yra pernelyg abstrakti, todėl **nėra privaloma vykdyti.** <span class="font-bold text-[#e63946]">NEPALANKU</span>
5. **McHardy** neteisėtai nutraukė licenciją. <span class="font-bold text-[#e63946]">NEPALANKU</span>
6. **McHardy** nėra aktyvus „Netfilter“ projekto prižiūrėtojas, todėl neturi teisės reikšti pretenzijų. <span class="font-bold text-[#e63946]">NEPALANKU</span>
7. **GENIATECH** pateikė didžiają dali šaltinio kodo, todėl tenkina GPLv2 licencijos sąlygas. <span class="font-bold text-[#e63946]">NEPALANKU</span>
8. **McHardy** siekia financinės naudos. <span class="font-bold text-[#e63946]">NEPALANKU</span>

---
transition: view-transition
---

# **Kelno apygdardos teismo nutarimas**

- **Data:** 2017 m. spalio 21 d.
- **Nutarimas:** Atsakovui („Geniatech“) uždrausta platinti ar viešinti programinę įrangą, ar firmware, kurioje yra McHardžio sukurtas Linux kodas („Netfilter“), jei nėra visiškai laikomasi GPLv2 licencijos sąlygų.
- **Teisėjai:**
  - Dr. Koepsel (pirmininkaujantis teisėjas)
  - Hübeler-Brakat (teisėja)
  - Dr. Gryska (nedalyvavo dėl atostogų)
- **Ginčo vertė:** ~~200 000 EUR~~ &rarr; 100 000 EUR
- **Vykdyti nedelsiant:** Taip

---
layout: center
transition: view-transition
---

# **Nepabaiga**

---
layout: top
transition: view-transition
---

# **Apeliacija (1)**

<br/>

### **Apžvalga:**

1. **Bylos numeris:** 6 U 193/17
2. **Nagrinėjo:** Aukštesnysis Kelno regioninis teismas.
3. **Žodinio nagrinėjimo data:** 2018 kovo 7 d.
4. **Tikslas:** Apeliacija dėl 2017 m. Kelno apygardos teismo (LG Köln) laikinojo draudimo.
5. **Rezultatas:** McHardy atsiėmė prašymą dėl laikinojo draudimo;. Byla nutraukta, visos bylos išlaidos priteistos McHardy.

---
layout: top
transition: view-transition
---

# **Apeliacija (2)**

<br/>

### **Teismo nustatyti faktai:**

1. „Linux“ kūrėju yra laikomas Linus Torvalds (1991 m.)
2. **Nėra bendraautorystės** – prie projekto prisidėjo daugiau kaip 15 000 kūrėjų. Jie yra laikomi projekto perdirbėjais, o ne bendraautoriaus.
3. „Maintainer“ ar „core team member“ statusas nesuteikia autorių teisės.
4. Ne visos „Linux“ versijos turi McHardžio rašytą kodą.
5. Kodo dalies peržvalga (angl. code review) nesuteikia autorinės teisės į peržiūrimą kodo dalį.

---
layout: top
transition: view-transition
---
# **Apeliacija (3)**

<br/>

### **Pirminės teismo išvados:**

- McHardis nėra bendraautorius.
- McHardis gali taikyti GPLv2 licenciją tik savo kodo daliai, o ne visam „Linux“ branduoliui.
- McHardžio pateikti įkalčiai nėra pakankami:
  - trūksta originalumo įrodymo,
  - nėra aiškaus įrodymo apie.
- McHardžio rolė „maintainter“ arba „head of Netfilter core team“ nesuteikia jam autorystės teisės.
- McHardžio prašoma laikinojo draudimo apimtis yra pernelyg didelė: ji neturėtų apimti visų „Linux“ versijų.

---
layout: top
transition: view-transition
layout: figure-side
figureUrl: /public/clara-stroebe-george-hood.webp
---

# **Apeliacija (4)**

<br/>

### **Rezultatas:**

1. McHardis atsitraukia.
2. Laikinasis draudimas platinti įrangą panaikinamas.
3. Teismas McHardžiui nurodo sumokėti visas teisines išlaidas.

---
layout: center
transition: view-transition
---

# **Trolis teisininkams,**
# **didvyris OSS bendruomenei?**

---
layout: top
transition: view-transition
---

# **OSS bendruomenės sentimentas**

<div class="relative w-full h-[500px]">

  <img v-click class="absolute top-0 left-0 shadow-lg rounded-lg" src="/public/lwn_comment1.png" />

  <img v-click class="absolute top-[30px] left-[40px] shadow-lg rounded-lg" src="/public/lwn_comment2.png" />

  <img v-click class="absolute top-[100px] left-[-30px] shadow-lg rounded-lg" src="/public/lwn_comment3.png" />

  <img v-click class="absolute top-[20px] left-[10px] shadow-lg rounded-lg" src="/public/lwn_comment4.png" />

  <img v-click class="absolute top-[170px] left-[0px] shadow-lg rounded-lg" src="/public/lwn_comment6.png" />

</div>

---
layout: top
transition: view-transition
---

# **Herald Welte komentaras**

- GPL vykdymas – būtinas, bet turi būti bendruomeninis
- Atskiri kūrėjai turi turėti teisę ginti licenciją
- Pelnas – negali būti tikslu.
- Slaptas ar individualus vykdymas – blogai, nes neatspindi bendruomenės nuomonės
- Teismo rezultatas – mišrus: per plati sankcija panaikinta (gerai), bet teismo precedento nėra (blogai)

---
layout: figure-side
transition: view-transition
figureUrl: public/Trollet_som_grunner.webp
---

# **Išvados**
- GPL licencijos nesilaikančios įmonės - <span class="font-bold text-[#e63946]">BLOGAI</span>
- Uždarbiaujantys, pavieniai projekto dalyviai - <span class="font-bold text-[#e63946]">IRGI BLOGAI</span>

---
layout: center
transition: view-transition
---

# **Pabaiga**

---
layout: top
transition: view-transition
---

# **Šaltiniai**
1. [Netfilter project: Settlement with Patrick McHardy](https://lwn.net/Articles/882397/)
2. [The rise of copyright trolls](https://lwn.net/Articles/721458/)
3. [Report from the Geniatech vs. McHardy GPL violation court hearing](https://laforge.gnumonks.org/blog/20180307-mchardy-gpl/)
4. [Welte: Report from the Geniatech vs. McHardy GPL violation court hearing](https://lwn.net/Articles/748761/)
5. [What makes the drivers unsalvageable? Proprietary blobs interacting with the Linux kernel?](https://news.ycombinator.com/item?id=30827779)
6. [Kelno apygardos teismo nuosprendis](http://docs.dpaq.de/13314-urteil_lg_k_ln.pdf)
7. [Opposing the Monetization of Linux: McHardy v.
Geniatech & Addressing Copyright “Trolling” in
Germany](https://www.vossius.eu/fileadmin/news_docs/Opposing_the_Monetization_of_Linux_McHardy_v.__Geniatech___Addressing_Copyright_%E2%80%9CTrolling%E2%80%9D_in__Germany.pdf)

<PoweredBySlidev mt-10 />
