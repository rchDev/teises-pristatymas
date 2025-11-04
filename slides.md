---
# try also 'default' to start simple
theme: academic
# some information about your slides (markdown enabled)
colorSchema: light
fonts:
  mono: Roboto
themeConfig:
  paginationX: r
  paginationY: t
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
coverAuthor: PRIf-22/1 stud. Rizvan Chalilovas
coverAuthorUrl: https://github.com/rchDev
coverDate: 2025-11-04
---

# **Patrick McHardy vs GENIATECH**
### Riba tarp trolinimo ir autorių teisių gynimo


---
layout: figure-side
mdc: true
transition: view-transition
figureUrl: /multiple_trolls.png
figureCaption: John Bauer 1915
figureFootnoteNumber: 1
figureWidth: 90%
---

# **Trolių rūšys** {.vt-title}

- Folkloriniai / mitologiniai
- Socialiniai
  - Interneto
    - Provokuojantys
    - Įžeidinėjantys / Priekabiaujantys
    - „Rūpestingi“ (apsimetantys draugiškais)
    - Valstybiniai / Propagandiniai
  - Gatvės {.vt-item}
  - Dezinformacijos {.vt-item}
- <span v-mark.box.orange="{color: '#ffb347', strokeWidth: 3, animationDuration:400}">Teisiniai (Intelektinės Nuosavybės)</span> {.vt-item}
    - Patentų {.vt-item}
    - <span v-mark.highlight="{color: '#e63946', strokeWidth: 3, animationDuration:400}">Autorių teisių / Licencijų troliai</span> {.vt-item}
    - Prekių ženklų {.vt-item}

<Footnotes>
  <Footnote :number="1">
     Source: <a href="https://mythus.fandom.com/wiki/Troll/Gallery?file=John_Bauer_1915.jpg" target="_blank" rel="noopener noreferrer">
      Myth and Folklore Wiki
    </a>
  </Footnote>
</Footnotes>

---
mdc: true
transition: view-transition
layout: figure-side
figureUrl: /norgeillus.webp
figureCaption: Norgeillus
figureFootnoteNumber: 1
figureX: r
---

# **Teisiniai (Intelektinės Nuosavybės) troliai**

**Kas jie?**

Fiziniai ar juridiniai asmenys, kurie piktnaudžiauja teisine sistema (ypač intelektinės nuosavybės teise),
kad gautų finansinę naudą, o ne siektų teisingumo ar realaus teisių įgyvendinimo.

**Rūšys:**
- <span v-mark.box="{color: '#ffb347', strokeWidth: 3, animationDuration:400}">Patentų troliai</span>
- <span v-mark.box="{color: '#ffb347', strokeWidth: 3, animationDuration:400}">Autorių teisių / Licencijų troliai</span>
- Prekių ženklų troliai

<Footnotes>
  <Footnote :number="1">
     Source: <a href="https://mythus.fandom.com/wiki/Troll/Gallery?file=Norgelius_1-1.jpg" target="_blank" rel="noopener noreferrer">
      Myth and Folklore Wiki
    </a>
  </Footnote>
</Footnotes>

---
mdc: true
transition: view-transition
layout: figure-side
figureUrl: /two_trolls.webp
figureCaption: Du troliai
figureFootnoteNumber: 1
---

# **Patentų VS Licencijų**

### Pagrindiniai skirtumai

| | **Patentų** | **Licencijų** |
|-----------|-----------|------------|
| **Prigimtis** | Dažniausiai spec. įmonės | Dažniausiai kūrėjai |
| **Atakos objektas** | Aibė patentą pažeidusių technologijų | Konkreti PĮ ar jos dalis |
| **Labiausiai paplitę** | JAV | ES |
| **Erzinimo lygis** | <span style="color:#5B6236;">★★★★★</span> | <span style="color:#5B6236;">★★★★☆</span>|

<Footnotes>
  <Footnote :number="1">
     Source: <a href="https://mythus.fandom.com/wiki/Troll/Gallery?file=E8a2b9ecbd56e0b5e73ffe8c7c20aad8.jpg" target="_blank" rel="noopener noreferrer">
      Myth and Folklore Wiki
    </a>
  </Footnote>
</Footnotes>

---
mdc: true
transition: view-transition
layout: figure
figureUrl: /veikimo_principas_v2.svg
---

# **Veikimo principas**

---
layout: default
mdc: true
transition: view-transition
---

# **Žinomi IP troliai**

- VirnetX (Apple trolis) (JAV)
- Sable Networks Inc. (JAV)
- Uniloc Corporation (JAV)
- <span v-mark.box="{color: '#ffb347', strokeWidth: 3, animationDuration:400}">Patrick McHardy "GPL trolis" (ES)</span>
- Hans Reiser (JAV)
- Rothschild Patent Imaging (JAV)

---
layout: figure-side
figureUrl: /masked_villain.png
figureCaption: The Hooded Terror
figureFootnoteNumber: 1
mdc: true
transition: view-transition
---

# **Patrick McHardy**

<br/>

- 🇩🇪 Vokietijos pilietis
- Prisidėjo prie Linux branduolio ir "Netfilter" karkaso kūrimo 2006-2014 m.
- 2016–2018 m. vykdė General Public License (GPL) gynybos kampaniją, kurios metu iš kompanijų ir individualių kūrėjų išgavo apie 1.8 mln. eur.,
todėl buvo pramintas GPL trolio vardu.

<Footnotes>
  <Footnote :number="1">
     Source: <a href="https://en.wikipedia.org/wiki/Masked_villain#/media/File:Hooded_Terror.jpg" target="_blank" rel="noopener noreferrer">
         Wikipedia
    </a>
  </Footnote>
</Footnotes>

---
layout: default
mdc: true
transition: view-transition
---

# **Kaip veikė McHardis?**

<br/>

**Taikiniai:** smulkos ar vidutinio dydžio įmonės, padariusios daug neesminių GPLv2 pažeidimų.

**Schema:**
- Atsiunčiamas cease-and-desist laiškas, kuriame:
    - nurodoma sumokėti smulkią kontrakto pažeidimo baudą,
    - sutikti su svarbia sąlyga, jog pakartotinai pažeidus licenciją, auka turės mokėti nuolatos didėjančias baudas.
- Aukai sutikus su pirmosios sutarties sąlygomis, siunčiami nauji cease-and-desist laiškai, kuriuose pateikiami kiti GPL pažeidimai su reikalavimais mokėti vis didesnes baudas ir sutikti su papildomomis sąlygomis.


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

- <span v-mark.box="{color:'#ffb347', strokeWidth: 3, animationDuration:400}">Vokietijos teismai bylose, susijusiose su intelektine nuosavybe, dažnai neišklausę abiejų pusių, yra linkę skirti itin griežtas ir sunkiai (apeliacijomis) panaikinamas laikinąsias sankcijas atsakovams.</span>
- Atsakovo prieštaravimas nestabdo teismo sankcijos.
- Ieškovas laisvai renkasi teismą, kuriame bus nagrinėjama byla.
- Ieškovas gali, bet kada atsiimti prašymą dėl sankcijos skyrimo.
- Teismai yra sąlyginai uždari.
- Atsakovui nevykdant laikinojo arba nuolatinio teismo draudimo, ieškovas gali reikalauti finansinės baudos.

<div class="absolute bottom-4 left-8 text-xs text-gray-500">
  Šaltinis: Marcus v. Welser, <a href="https://www.vossius.eu/fileadmin/news_docs/Opposing_the_Monetization_of_Linux_McHardy_v.__Geniatech___Addressing_Copyright_%E2%80%9CTrolling%E2%80%9D_in__Germany.pdf" target="_blank" >
  “Opposing the Monetization of Linux: McHardy v. Geniatech &amp; Addressing Copyright ‘Trolling’ in Germany”
  </a>,
  Vossius &amp; Partner, Munich, Germany.

</div>

---
layout: top
transition: view-transition
---

# **Lemtinga byla**

<br/>

**Priešistorė:**

- 2006-2014 m. Patrick McHardy prisidėjo prie „Netfilter“ projekto.
- 2016-2017 m. McHardy siautėjo, puldinėdamas visų GPLv2 nuostatų nesilaikančių įmonių

---
layout: top
transition: view-transition
---

# **GENIATECH VS McHardy (1)**

<br/>

**Ginčas:**
- 2017 liepos 17 d. „Geniatech“ gavo susitarimo laišką iš Patrick McHardy, kuriame McHardis reikalavo, jog įmonė nutrauktų pažeidimą ir sumokėtų baudą.
- 2017 liepos 24 d. „Geniatech“ atsisakė sutikti su sutarties sąlygomis.
- 2017 liepos 26 d. Patrick McHardy nutraukė „Geniatech“ GPLv2.
- 2017 rugpjūčio 4 d. Patrick McHardy pasirašė priesaikos deklaraciją, kurioje, kartu su įrodymais, išdėstė esminius pažeidimo faktus.

---
layout: top
transition: view-transition
---

# **GENIATECH VS McHardy (2)**

<br/>

**Draudimas:**

- 2017 rugpjūčio 10 d. Patrick McHardis Kelno apygrados teismui pateikė prašymą dėl laikinosios priemonės suteikimo „Geniatech“.
- 2017 rugpjūčio 23 d. teismas įmonei „Geniatech“ išdavė laikinąjį draudimą platinti produkciją, turinčią McHardžio rašytą programinį kodą, nes McHardžiui pavyko įrodyti:
  - autorystę,
  - autorinių teisių pažeidimo egzistavimą,
  - skubumo svarbą,
  - įrodymų pakankamumą.

---
layout: top
transition: view-transition
---

# **GENIATECH VS McHardy (3)**

<br/>

**Pagrindiniai Geniatech argumentai:**

- 2017 m. rugpjūčio 30 d. „Geniatech“ pateikė prieštaravimą dėl laikinojo draudimo, kuriame teigė:
  - Laikinasis draudimas yra pernelyg abstraktus ir yra taikomas per plačiai.
  - Patrick McHardy piktnaudžiauja savo teisėmis ir siekia pasipelnyti.
  - Skubos nėra, nes McHardy seniai žinojo apie pažeidimą ir nesikreipė į teismą.
  - GPLv2 yra pernelyg abstrakti ir dviprasmiška, todėl negali būti taikoma Vokietijoje.
  - McHardy indėlis į Linux branduolį yra pernelyg menkas, kad jam būtų suteikta autorystės teisė.

---
layout: top
transition: view-transition
---

# **GENIATECH VS McHardy (4)**

<br/>

**Žodinis nagrinėjimas ir galutinis nutarimas:**

- 2017 m. spalio 12 d. Vokietijos Kelno apygardos teisme įvyko žodinis nagrinėjimas, kuriame abi šalys:
  - žodžiu išdėstė argumentus,
  - pristatė ekspertų išvadas.

- 2017 m. spalio 17 d. abi šalys Kelno apygardos teismui pateikė galutinius rašytinius paaiškinimus ir kitus procesinius dokumentus.

- 2017 m. spalio 21 d. Kelno apygardos teismas pateikė išvadas ir pateikė galutinį nutarimą.

---
layout: figure-side
figureUrl: /teismo_sprendimas.png
figureCaption: Teismo sprendimo antraštė
figureFootnoteNumber: 1
---

# **Teismo išvados ir nutarimas**

- **Bylos numeris:** 14 O 188/17
- **Vieta:** Kelno apygardos teismas
- **Ieškovas:** Patrick McHardy
- **Atsakovas:** „Geniatech“ Europe GmbH
- **Teisėjai:**
  - Dr. Koepsel
  - Hübeler-Brakat
  - Dr. Gryska
- **Esmė:** „Geniatech“ pažeidė autorines teises ir turi nutraukti su pažeidimu susijusią veiklą, bei sumokėti teismo išlaidoms skirtą 100 tūkst. EUR sumą.

<Footnotes>
  <Footnote :number="1">
     Source: <a href="http://docs.dpaq.de/13314-urteil_lg_k_ln.pdf" target="_blank" rel="noopener noreferrer">
         Teismo sprendimas
    </a>
  </Footnote>
</Footnotes>

---
layout: top
transition: view-transition
---

# **Kelno apygardos teismo išvados (1)**

### **McHardžio pusė:**

1. **McHardy** turi autorystės teisę į „Linux“ branduolio komponentą: „Netfilter“. <span class="font-bold text-[#1565c0]">PALANKU</span>
2. **McHardy** 2017 m. rūgpjūčio 4 d. priesaikos metu pateikti įrodymai laikomi pakankamais. <span class="font-bold text-[#1565c0]">PALANKU</span>
3. **GENIATECH** naudojoto McHardžio kodą savo įrenginiuose. <span class="font-bold text-[#1565c0]">PALANKU</span>
4. **GENIATECH** pažeidė GPLv2, nepaviešindama viso šaltinio kodo ir neįterpdama licencijos teksto. <span class="font-bold text-[#1565c0]">PALANKU</span>
5. **GENIATECH** GPLv2 buvo nutraukta teisėtai. <span class="font-bold text-[#1565c0]">PALANKU</span>
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
3. **McHardy** piktnaudžiavo savo teisėmis ir vykdė sistemingą GPL pažeidusiųjų persekiojimo kampaniją, tokiu būdu siekdamas pelno. <span class="font-bold text-[#e63946]">NEPALANKU</span>
4. **GPLv2** yra pernelyg abstrakti, todėl **nėra privaloma vykdyti.** <span class="font-bold text-[#e63946]">NEPALANKU</span>
5. **McHardy** neteisėtai nutraukė licenciją. <span class="font-bold text-[#e63946]">NEPALANKU</span>
6. **McHardy** nėra aktyvus „Netfilter“ projekto prižiūrėtojas, todėl neturi teisės reikšti pretenzijų. <span class="font-bold text-[#e63946]">NEPALANKU</span>
7. **GENIATECH** pateikė didžiają dali šaltinio kodo, todėl tenkina GPLv2 sąlygas. <span class="font-bold text-[#e63946]">NEPALANKU</span>
8. **McHardy** siekia financinės naudos. <span class="font-bold text-[#e63946]">NEPALANKU</span>

---
transition: view-transition
---

# **Kelno apygdardos teismo nutarimas**

- **Data:** 2017 m. spalio 21 d.
- **Nutarimas:** Atsakovui (GENIATECH) uždrausta platinti ar viešinti programinę įrangą, ar firmware, kurioje yra McHardžio sukurtas Linux kodas („Netfilter“), jei nėra visiškai laikomasi GPLv2 sąlygų.
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

- **Bylos numeris:** 6 U 193/17 (išgalvotas, nežinau ar toks)
- **Apeliantas:** „Geniatech“ Europe GmbH
- **Atsakovas:** Patrick McHardy
- **Nagrinėjo:** Aukštesnysis Kelno regioninis teismas.
- **Žodinio nagrinėjimo data:** 2018 kovo 7 d.
- **Tikslas:** Apeliacija dėl 2017 m. Kelno apygardos teismo (LG Köln) laikinojo draudimo sprendimo.
- **Rezultatas:**
  - Atsakovas (McHardy) atsiėmė prašymą išlaikyti laikinąjį draudimą,
  - apeliacijos byla nutraukta,
  - McHardžiui nurodyta sumokėti visas teismo išlaidas.

---
layout: top
transition: view-transition
---

# **Apeliacija (2)**

<br/>

### **Teismo nustatyti faktai:**

1. „Linux“ kūrėju yra laikomas Linus Torvalds (1991 m.)
2. Nėra bendraautorystės – prie projekto prisidėjo daugiau kaip 15 000 kūrėjų. Jie yra laikomi projekto perdirbėjais, o ne bendraautoriaus.
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
- McHardis gali taikyti GPLv2 tik savo kodo daliai, o ne visam „Linux“ branduoliui.
- McHardžio pateikti įkalčiai nėra pakankami, nes:
  - trūksta originalumo įrodymo,
  - McHardis nesugebėjo pateikti konkrečių savo darbo įrodymų, kuriuos būtų galima laikyti jo kūrybiniu darbu, todėl McHardžio indėlis yra laikomas techniniu, o ne kūrybiniu.
- McHardžio rolė „maintainter“ arba „head of Netfilter core team“ nesuteikia jam autorystės teisės.
- McHardžio prašoma laikinojo draudimo apimtis yra pernelyg didelė: ji neturėtų apimti visų „Linux“ versijų.

---
layout: top
transition: view-transition
layout: figure-side
figureUrl: /clara-stroebe-george-hood.webp
---

# **Apeliacija (4)**

<br/>

### **Rezultatas:**

- McHardis atsitraukia.
- Laikinasis draudimas GENIATECH platinti įrangą - panaikinamas.
- Teismas McHardžiui nurodo sumokėti visas teisines išlaidas.

<Footnotes>
  <Footnote>
     Image: <a href="https://mythus.fandom.com/wiki/Troll/Gallery?file=The-swedish-fairy-book-clara-stroebe-george-hood.jpg" target="_blank" rel="noopener noreferrer">
      Myth and Folklore Wiki
    </a>
  </Footnote>
</Footnotes>

---
layout: center
transition: view-transition
---

# **Trolis teisininkams,**
# **licencijos riteris OSS bendruomenei?**

---
layout: top
transition: view-transition
---

# **OSS bendruomenės sentimentas**

<div class="relative w-full h-[500px]">

  <img v-click class="absolute top-0 left-0 shadow-lg rounded-lg" src="/lwn_comment1.png" />

  <img v-click class="absolute top-[30px] left-[40px] shadow-lg rounded-lg" src="/lwn_comment2.png" />

  <img v-click class="absolute top-[100px] left-[-30px] shadow-lg rounded-lg" src="/lwn_comment3.png" />

  <img v-click class="absolute top-[20px] left-[10px] shadow-lg rounded-lg" src="/lwn_comment4.png" />

  <img v-click class="absolute top-[170px] left-[0px] shadow-lg rounded-lg" src="/lwn_comment6.png" />

</div>

---
layout: top
transition: view-transition
---

# **Herald Welte komentaras**

<br/>

- Pavieniai kūrėjai turi išlaikyti teisę ginti autorines teises.
- Versti įmones laikytis licencijos sąlygų nėra smerktina veikla.
- Siekiai turi būti atviri ir žinomi bendruomenei.
- Individualūs kūrėjai neturi pelnytis.
- Teismo rezultatas:
  - pernelyg griežtas draudimas įmonei buvo panaikintas - <span class="font-bold text-[#1565c0]">GERAI</span>,
  - nesukurtas precedentas, nes nėra galutinio sprendimo - <span class="font-bold text-[#e63946]">BLOGAI</span>.

---
layout: figure-side
transition: view-transition
figureUrl: /Trollet_som_grunner.webp
---

# **Išvados**

<br/>

- GPL nesilaikančios įmonės - <span class="font-bold text-[#e63946]">BLOGAI</span>
- Uždarbiaujantys, pavieniai projekto dalyviai - <span class="font-bold text-[#e63946]">IRGI BLOGAI</span>
- Didžioji dalis bylų baigiasi dvišaliais susitarimais - <span class="font-bold text-[#e63946]">IRGI BLOGAI</span>
- Trolį nuo licencijos riterio skiria:

|     | **Trolis**     | **Riteris**  |
| ------- | ------------ | ------- |
| **Pirminė motyvacija** |  finansinė nauda | atviro kodo įdėjų gynimas |
| **Sukurtas produktas** |  naudinga inovacija | butaforinis |

<Footnotes>
  <Footnote>
     Image: <a href="https://mythus.fandom.com/wiki/Troll/Gallery?file=Trollet_som_grunner_p%C3%A5_hvor_gammelt_det_er.jpg" target="_blank" rel="noopener noreferrer">
      Myth and Folklore Wiki
    </a>
  </Footnote>
</Footnotes>

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
1. [The rise of copyright trolls](https://lwn.net/Articles/721458/)
2. [Report from the Geniatech vs. McHardy GPL violation court hearing](https://laforge.gnumonks.org/blog/20180307-mchardy-gpl/)
3. [Welte: Report from the Geniatech vs. McHardy GPL violation court hearing](https://lwn.net/Articles/748761/)
4. [What makes the drivers unsalvageable? Proprietary blobs interacting with the Linux kernel?](https://news.ycombinator.com/item?id=30827779)
5. [Kelno apygardos teismo nuosprendis](http://docs.dpaq.de/13314-urteil_lg_k_ln.pdf)
6. [Opposing the Monetization of Linux: McHardy v.
Geniatech & Addressing Copyright “Trolling” in
Germany](https://www.vossius.eu/fileadmin/news_docs/Opposing_the_Monetization_of_Linux_McHardy_v.__Geniatech___Addressing_Copyright_%E2%80%9CTrolling%E2%80%9D_in__Germany.pdf)

<PoweredBySlidev mt-10 />
