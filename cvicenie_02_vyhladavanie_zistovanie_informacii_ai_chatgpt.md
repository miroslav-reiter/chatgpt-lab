# 🧪 Cvičenie 02: Vyhľadávanie a zisťovanie informácií pomocou AI ChatGPT

Toto cvičenie je zamerané na praktické používanie ChatGPT pri vyhľadávaní, overovaní, porovnávaní a spracovaní informácií. ChatGPT nepoužívame iba ako nástroj na vytvorenie textovej odpovede, ale ako analytického asistenta, ktorý nám pomáha pripraviť rešerš, porovnať zdroje, identifikovať nejasnosti a vytvoriť praktický výstup.

Prompty sú pripravené na rýchle skopírovanie. Používajú placeholdery v hranatých zátvorkách, napríklad `[téma]`, `[meno osoby]`, `[názov firmy]`, `[web firmy]`, `[odvetvie]` alebo `[účel analýzy]`. Pred odoslaním promptu ich nahradíme konkrétnymi údajmi.

---

## 🎯 Ciele cvičenia

Po absolvovaní cvičenia budeme vedieť:

- používať ChatGPT na vyhľadávanie aktuálnych informácií,
- rozlíšiť základný režim, štandardné vyhľadávanie a podrobné vyhľadávanie,
- vybrať vhodný režim podľa náročnosti úlohy,
- pripraviť kvalitný prompt na vyhľadávanie informácií,
- vyžadovať zdroje, dátumy a odkazy na pôvodné informácie,
- nastaviť povolenia webov a cloudový prehliadač,
- používať placeholdery vo vyhľadávacích promptoch,
- pracovať so znakom `@` na označenie dostupného zdroja alebo objektu,
- vytvoriť z výsledkov vyhľadávania praktický briefing,
- pripraviť podklady pred stretnutím, pohovorom alebo obchodným kontaktom,
- analyzovať verejne dostupné informácie o osobe alebo firme,
- porovnať viacero firiem, produktov alebo riešení,
- identifikovať riziká, nejasnosti a chýbajúce informácie,
- rozlišovať medzi overeným faktom, tvrdením zdroja a interpretáciou AI,
- skontrolovať výstup pred jeho ďalším použitím.

---

## 🔎 Základný princíp vyhľadávania pomocou ChatGPT

Namiesto náhodného otvárania veľkého množstva výsledkov vyhľadávania používame ChatGPT na systematické získavanie a spracovanie informácií. ChatGPT nám môže pomôcť informácie vyhľadať, usporiadať, sumarizovať, porovnať, vysvetliť a premeniť na praktický pracovný výstup.

ChatGPT však nie je neomylný zdroj. Môže nesprávne interpretovať stránku, použiť zastaranú informáciu, zameniť dve osoby alebo vytvoriť tvrdenie, ktoré v citovanom zdroji nie je uvedené. Kľúčové fakty preto vždy overujeme v pôvodných a dôveryhodných zdrojoch.

Pri vyhľadávaní dodržiavame tento postup:

```text
VYHĽADAŤ → POROVNAŤ → OVERIŤ → INTERPRETOVAŤ → POUŽIŤ
```

### Čo môže ChatGPT pri vyhľadávaní robiť

- vyhľadávať aktuálne informácie na internete,
- získať informácie z viacerých webových stránok,
- porovnať rozdielne tvrdenia,
- zhrnúť rozsiahle texty,
- vytvoriť časovú os,
- pripraviť porovnávaciu tabuľku,
- označiť možné rozpory,
- identifikovať chýbajúce informácie,
- pripraviť otázky na ďalšie preverenie,
- vytvoriť briefing pred stretnutím,
- pripraviť odporúčanie na základe zistení.

### Čo ChatGPT nemusí vedieť urobiť spoľahlivo

- potvrdiť pravdivosť každého tvrdenia,
- rozpoznať všetky neaktuálne informácie,
- správne rozlíšiť osoby s rovnakým menom,
- získať údaje z neprístupných alebo platených zdrojov,
- posúdiť neverejné skutočnosti,
- nahradiť právne, finančné alebo bezpečnostné preverenie,
- garantovať, že našiel všetky relevantné zdroje.

---

## ⚖️ Porovnanie režimov ChatGPT

ChatGPT môžeme pri práci s informáciami používať v troch základných režimoch:

1. základný režim,
2. štandardné vyhľadávanie na webe,
3. podrobné vyhľadávanie, teda Deep Research.

| Oblasť | Základný režim | Štandardné vyhľadávanie | Podrobné vyhľadávanie |
|---|---|---|---|
| Spôsob práce | Odpovedá z modelových znalostí, kontextu a poskytnutých podkladov | Vyhľadáva aktuálne informácie na webe | Vykonáva viacstupňový výskum z viacerých zdrojov |
| Aktuálnosť | Nemusí obsahovať najnovšie informácie | Pracuje s aktuálnymi webovými zdrojmi | Pracuje s aktuálnymi aj rozsiahlejšími odbornými zdrojmi |
| Zdroje | Nemusia byť uvedené | Zvyčajne uvádza citácie a odkazy | Pripravuje rozsiahlejšiu správu s citáciami |
| Rýchlosť | Najrýchlejší režim | Rýchly až stredne rýchly | Najpomalší režim |
| Rozsah | Stručná odpoveď, vysvetlenie alebo návrh | Súhrnná odpoveď z viacerých stránok | Štruktúrovaná analytická správa |
| Vhodné použitie | Brainstorming, vysvetlenie, práca s dodaným textom | Aktuality, ceny, produkty, rýchle overenie faktu | Rešerše, stratégie, analýzy trhu a komplexné porovnania |
| Hlavné riziko | Neaktuálne alebo neoverené informácie | Vyhľadávanie nemusí byť vyčerpávajúce | Výsledok stále vyžaduje kontrolu zdrojov |

---

## ⚡ Kedy použijeme základný režim

Základný režim používame vtedy, keď nepotrebujeme aktuálne údaje z internetu. Je vhodný najmä pri vysvetľovaní pojmov, brainstormingu, tvorbe textov alebo práci s obsahom, ktorý sme priamo vložili do konverzácie.

### Vhodné úlohy

- vysvetlenie odborného pojmu,
- návrh štruktúry dokumentu,
- brainstorming tém,
- spracovanie vloženého textu,
- úprava štýlu,
- príprava otázok,
- vytvorenie šablóny promptu.

### Prompt: rozhodnutie, či potrebujeme web

```text
Posúď nasledujúcu úlohu a rozhodni, či ju môžeme spoľahlivo vyriešiť bez aktuálneho vyhľadávania na internete.

Úloha:
[úloha]

Odpovedz v štruktúre:
1. Je potrebné vyhľadávanie na webe: áno alebo nie.
2. Zdôvodnenie.
3. Aké informácie môžu byť časovo premenlivé.
4. Aké zdroje by sme mali použiť.
5. Odporúčaný režim ChatGPT.
```

---

## 🌐 Kedy použijeme štandardné vyhľadávanie

Štandardné vyhľadávanie používame pri rýchlom získaní aktuálnej informácie. ChatGPT vyhľadá relevantné stránky, pripraví odpoveď a doplní odkazy alebo citácie.

Je vhodné najmä vtedy, keď potrebujeme rýchlo overiť konkrétny fakt, dátum, cenu, parameter produktu, zmenu pravidiel alebo aktuálnu udalosť.

### Vhodné úlohy

- aktuálne ceny,
- nové produkty,
- zmeny v legislatíve,
- aktuálne štatistiky,
- dostupnosť služby,
- termíny podujatí,
- rýchle porovnanie možností,
- overenie konkrétneho tvrdenia.

### Prompt: rýchle overenie aktuálneho faktu

```text
Vyhľadaj aktuálne informácie o nasledujúcom tvrdení:

[tvrdenie]

Požiadavky:
- používaj aktuálne a dôveryhodné zdroje,
- uprednostni oficiálne webové stránky,
- uveď dátum platnosti informácie,
- pri každom dôležitom tvrdení uveď zdroj,
- upozorni na prípadné rozdiely medzi zdrojmi,
- nevytváraj domnienky.

Výstup:
1. stručná odpoveď,
2. overené fakty,
3. zdroje,
4. nejasnosti alebo obmedzenia.
```

---

## 🔬 Kedy použijeme podrobné vyhľadávanie

Podrobné vyhľadávanie používame pri komplexných otázkach, ktoré vyžadujú viacstupňový výskum. ChatGPT môže naplánovať postup, prehľadať väčší počet zdrojov, porovnať ich a vytvoriť štruktúrovanú analytickú správu.

Deep Research je vhodné najmä na odborné rešerše, analýzu trhu, porovnanie viacerých firiem, prípravu stratégie, hodnotenie rizík alebo preverenie komplexnej témy.

### Vhodné úlohy

- analýza trhu,
- odborná rešerš,
- konkurenčná analýza,
- porovnanie viacerých riešení,
- príprava stratégie,
- komplexný profil firmy,
- analýza reputácie,
- príprava podkladov pre manažment.

### Dôležité upozornenie

V ukážke v priloženom PDF trvalo podrobné vyhľadávanie približne 6 až 10 minút. Skutočné trvanie, počet použitých zdrojov a dostupné funkcie však závisia od tarify, pracovného priestoru, náročnosti úlohy a aktuálnej konfigurácie ChatGPT.

### Prompt: rozhodnutie medzi Search a Deep Research

```text
Posúď nasledujúcu výskumnú úlohu:

[úloha]

Rozhodni, či máme použiť:
- štandardné vyhľadávanie,
- podrobné vyhľadávanie,
- alebo kombináciu oboch režimov.

Pri rozhodnutí zohľadni:
- aktuálnosť informácií,
- počet potrebných zdrojov,
- zložitosť porovnania,
- potrebu odbornej analýzy,
- riziko nepresného výsledku,
- časovú náročnosť.

Výstup priprav v tabuľke:
- kritérium,
- vyhodnotenie,
- odporúčanie.

Na konci navrhni konkrétny prompt pre odporúčaný režim.
```

---

## ⚙️ Nastavenie vyhľadávania a cloudového prehliadača

Pred prácou s aktuálnymi informáciami skontrolujeme, či má ChatGPT povolené používanie webového vyhľadávania. V závislosti od účtu a pracovného priestoru môžeme mať dostupné nastavenia pre prehliadanie webu, hľadanie v pripojených zdrojoch a cloudový prehliadač.

Cloudový prehliadač môže umožniť ChatGPT otvárať stránky nezávisle od prehliadača, ktorý používame na svojom zariadení. Pri firemných účtoch môžu byť tieto možnosti upravené administrátorom.

### Čo kontrolujeme

- či je povolené prehliadanie webu,
- či je povolené hľadanie v pripojených zdrojoch,
- či pracovný priestor neobmedzuje konkrétne funkcie,
- ktoré webové stránky môže ChatGPT otvárať,
- či sa má ChatGPT pred otvorením stránky opýtať,
- či máme povolené dôveryhodné weby.

---

## 🔐 Povolenia webových stránok

Povolenia webov používame na určenie, ktoré stránky môže ChatGPT otvoriť. Pri práci s firmami môžeme medzi dôveryhodné zdroje zaradiť napríklad oficiálny web firmy, Obchodný register Slovenskej republiky, Register účtovných závierok alebo ďalšie relevantné registre.

Povolenie konkrétnej stránky neznamená, že každá informácia na nej je automaticky správna. Stále musíme kontrolovať aktuálnosť, kontext a to, či sa údaj vzťahuje na správnu osobu alebo firmu.

### Príklady zdrojov

- oficiálny web organizácie,
- obchodný register,
- register účtovných závierok,
- FinStat,
- verejné databázy,
- partnerské weby,
- odborné portály,
- stránky regulačných orgánov.

### Prompt: vyhľadávanie iba v určených zdrojoch

```text
Preskúmaj tému [téma].

Použi iba nasledujúce zdroje:
- [zdroj 1],
- [zdroj 2],
- [zdroj 3].

Pravidlá:
- nepoužívaj iné zdroje bez môjho súhlasu,
- pri každom tvrdení uveď konkrétny zdroj,
- uveď dátum alebo obdobie, ku ktorému údaj platí,
- označ informácie, ktoré nie je možné potvrdiť,
- nepíš domnienky ako fakty.

Výstup priprav v štruktúre:
1. hlavné zistenia,
2. tabuľka overených údajov,
3. rozpory medzi zdrojmi,
4. chýbajúce informácie,
5. odporúčané manuálne overenie.
```

---

## @ Používanie označenia v promptoch

Znak `@` môže v podporovaných rozhraniach slúžiť na označenie dostupného zdroja, aplikácie, projektu, používateľa, objektu alebo iného pripojeného prvku. Pomocou označenia môžeme presnejšie určiť, s ktorým zdrojom má ChatGPT pracovať.

Dostupné možnosti sa môžu líšiť podľa tarify, pracovného priestoru, pripojených aplikácií a aktuálnej verzie ChatGPT.

### Všeobecná šablóna

```text
Použi zdroj @[zdroj alebo aplikácia] a spracuj nasledujúcu úlohu:

[úloha]

Zameraj sa na:
- [oblasť 1],
- [oblasť 2],
- [oblasť 3].

Pri každom dôležitom tvrdení uveď pôvod informácie.
```

---

## 🧩 Ako pracovať s promptami

Pri vyhľadávacích promptoch používame štyri základné kroky:

1. doplníme kontext,
2. vyžiadame zdroje,
3. vykonáme kritickú kontrolu,
4. vytvoríme praktický výstup.

### 1. Doplnenie kontextu

Hranaté zátvorky nahradíme konkrétnym menom, názvom firmy, webovou adresou, odvetvím alebo účelom analýzy.

### 2. Vyžiadanie zdrojov

Pri aktuálnych, citlivých alebo dôležitých informáciách žiadame:

- zdroj,
- dátum,
- odkaz na pôvodnú stránku,
- odlíšenie faktu od interpretácie,
- označenie neoverených tvrdení.

### 3. Kritická kontrola

Necháme ChatGPT označiť:

- neisté tvrdenia,
- možné rozpory,
- riziko zámeny,
- chýbajúce informácie,
- údaje, ktoré musíme overiť manuálne.

### 4. Praktický výstup

Výsledok môžeme premeniť na:

- briefing,
- porovnávaciu tabuľku,
- kontrolný zoznam,
- otázky na stretnutie,
- e-mail,
- predajný scenár,
- zoznam rizík,
- odporúčanie pre manažment.

---

## 📌 Placeholdery vo vyhľadávacích promptoch

| Placeholder | Význam | Príklad |
|---|---|---|
| `[meno osoby]` | osoba, ktorú preverujeme | Jana Nováková |
| `[názov firmy]` | názov organizácie | ABC Consulting s. r. o. |
| `[web firmy]` | webová stránka | https://example.com |
| `[odvetvie]` | oblasť podnikania | vzdelávanie |
| `[účel analýzy]` | dôvod vyhľadávania | príprava na stretnutie |
| `[časové obdobie]` | sledované obdobie | posledných 12 mesiacov |
| `[krajina]` | geografické obmedzenie | Slovensko |
| `[zdroje]` | požadované stránky | ORSR, RÚZ, oficiálny web |
| `[produkt]` | analyzovaný produkt | online kurz |
| `[cieľová skupina]` | skupina používateľov | malé firmy |
| `[konkurenti]` | porovnávané firmy | firma A, firma B |
| `[výstup]` | požadovaný formát | tabuľka, briefing |

### Prompt: kontrola nenahradených placeholderov

```text
Skontroluj nasledujúci prompt a nájdi všetky placeholdery v hranatých zátvorkách.

Prompt:
[prompt]

Výstup:
1. zoznam placeholderov,
2. vysvetlenie, čo máme doplniť,
3. upozornenie na chýbajúci kontext,
4. upravená verzia promptu pripravená na použitie.
```

---

# 👤 Prompty pre vyhľadávanie informácií o osobe

Pri vyhľadávaní informácií o osobe pracujeme iba s verejne dostupnými a profesijne relevantnými údajmi. Nevytvárame citlivé osobné profily, nezhromažďujeme súkromné údaje a neuvádzame nepotvrdené tvrdenia ako fakty.

---

## Prompt č. 1: Rýchly základný profil osoby

```text
Vyhľadaj verejne dostupné profesijné informácie o osobe:

Meno: [meno osoby]
Organizácia alebo oblasť: [organizácia alebo odvetvie]
Krajina: [krajina]

Zameraj sa na:
1. profesijné pozadie,
2. aktuálnu pracovnú rolu alebo podnikanie,
3. hlavné odborné témy,
4. verejné vystúpenia, články, podcasty alebo rozhovory,
5. profesijné projekty a organizácie,
6. dôveryhodné zdroje informácií,
7. možné nejasnosti alebo riziko zámeny s inou osobou.

Pravidlá:
- pracuj iba s verejne dostupnými informáciami,
- odlišuj oficiálne zdroje od vlastných profilov osoby,
- nepíš domnienky ako fakty,
- pri každom dôležitom tvrdení uveď zdroj,
- uveď dátum alebo obdobie platnosti informácie,
- označ informácie, ktoré sa nepodarilo overiť.

Výstup priprav takto:
1. identifikácia osoby,
2. profesijné zhrnutie,
3. hlavné odborné oblasti,
4. verejné aktivity,
5. možné nejasnosti,
6. stručné zhrnutie v 5 bodoch.
```

---

## Prompt č. 2: Profil osoby pred obchodným stretnutím

```text
Priprav verejný profesijný briefing o osobe:

Meno: [meno osoby]
Firma: [firma]
Pozícia: [pozícia]
Účel stretnutia: [účel stretnutia]
Naša ponuka alebo téma: [ponuka alebo téma]

Vyhľadaj a spracuj:
- aktuálnu rolu osoby,
- pravdepodobnú oblasť zodpovednosti podľa verejných zdrojov,
- odborné témy, ktorým sa venuje,
- verejne komunikované priority,
- projekty alebo iniciatívy, na ktorých pracuje,
- problémy alebo potreby relevantné pre našu ponuku,
- možné rozhodovacie právomoci, iba ak ich vieme podložiť zdrojom,
- vhodný štýl komunikácie podľa verejných vystúpení,
- témy, ktorým sa máme vyhnúť,
- odporúčané otázky na stretnutie.

Výstup:
1. stručný profil osoby,
2. čo môže byť pre osobu dôležité,
3. možné potreby a problémy,
4. 10 otázok na stretnutie,
5. odporúčaná úvodná veta,
6. otvorené otázky a informácie na manuálne overenie.

Nevytváraj psychologický profil. Neodhaduj osobné vlastnosti bez dôveryhodných podkladov.
```

---

## Prompt č. 3: Analýza verejného profilu LinkedIn

```text
Analyzuj verejne dostupný profesijný profil osoby:

Meno: [meno osoby]
LinkedIn alebo iný profesijný profil: [URL]
Firma: [firma]
Účel analýzy: [účel]

Zameraj sa na:
- aktuálnu pracovnú pozíciu,
- predchádzajúce pracovné skúsenosti,
- deklarované kompetencie,
- odborné príspevky a témy,
- verejne komunikované obchodné priority,
- projekty, certifikácie a vzdelanie,
- možné spoločné odborné témy,
- vhodný dôvod na kontaktovanie.

Výstup:
1. profesijné zhrnutie,
2. hlavné kompetencie,
3. relevantné témy na oslovenie,
4. možné obchodné potreby, označené ako hypotézy,
5. návrh personalizovanej LinkedIn správy do 500 znakov,
6. návrh následnej správy,
7. zdroje a nejasnosti.

Nepoužívaj osobné alebo súkromné informácie. Hypotézy jasne označ.
```

---

## Prompt č. 4: Overenie verejnej dôveryhodnosti osoby

```text
Vykonaj predbežnú kontrolu verejnej profesijnej dôveryhodnosti osoby:

Meno: [meno osoby]
Firma alebo organizácia: [firma]
Oblasť činnosti: [oblasť]
Účel preverenia: [účel]

Skontroluj:
- verejné profesijné informácie,
- prepojenia na firmy alebo organizácie,
- verejné referencie a hodnotenia,
- odborné články, rozhovory a vystúpenia,
- konzistentnosť pracovných údajov naprieč zdrojmi,
- možné kontroverzie alebo negatívne zmienky,
- možné varovné signály,
- riziko zámeny s inou osobou.

Výstup rozdeľ na:
1. overené fakty,
2. tvrdenia pochádzajúce z vlastných profilov osoby,
3. nezávislé verejné zdroje,
4. otvorené otázky,
5. možné varovné signály,
6. odporúčané ďalšie preverenie.

Pravidlá:
- pracuj iba s verejnými informáciami,
- nehodnoť súkromný život,
- nepoužívaj citlivé osobné údaje,
- neuvádzaj obvinenia bez dôveryhodného zdroja,
- pri každom významnom tvrdení uveď zdroj a dátum.
```

---

# 🏢 Prompty pre vyhľadávanie informácií o firme

Pri firemnej analýze kombinujeme informácie z oficiálneho webu, verejných registrov, účtovných údajov, odborných portálov, referencií a mediálnych zdrojov. Rozlišujeme medzi tým, čo firma tvrdí sama o sebe, a tým, čo uvádzajú nezávislé zdroje.

---

## Prompt č. 5: Rýchly profil firmy

```text
Vyhľadaj a spracuj základný profil firmy:

Názov firmy: [názov firmy]
IČO: [IČO, ak je známe]
Web: [web firmy]
Krajina: [krajina]
Odvetvie: [odvetvie]

Zisti:
1. oficiálny názov a identifikačné údaje,
2. predmet činnosti,
3. hlavné produkty alebo služby,
4. cieľových zákazníkov,
5. geografické pôsobenie,
6. veľkosť firmy, ak je verejne dostupná,
7. vedenie a verejne uvedené kontaktné osoby,
8. hlavné referencie,
9. konkurentov,
10. možné riziká alebo nejasnosti.

Pri slovenskej firme uprednostni:
- oficiálny web,
- Obchodný register SR,
- Register účtovných závierok,
- dôveryhodné ekonomické databázy.

Výstup:
1. profil firmy,
2. produkty a zákazníci,
3. pozícia na trhu,
4. dôveryhodnosť zdrojov,
5. možné riziká,
6. záver: Čo by sme mali vedieť pred prvým kontaktom?
```

---

## Prompt č. 6: Firma pred obchodnou ponukou

```text
Priprav obchodný briefing o firme:

Firma: [názov firmy]
Web: [web firmy]
Odvetvie: [odvetvie]
Naša služba alebo produkt: [naša ponuka]
Cieľ ponuky: [cieľ]

Vyhľadaj:
- čo firma ponúka,
- komu predáva,
- aké problémy pravdepodobne rieši,
- aké aktuálne projekty alebo zmeny komunikuje,
- aké technológie, procesy alebo partnerstvá používa,
- ktoré oddelenia môžu byť relevantné,
- kto môže rozhodovať o podobnej ponuke,
- aké argumenty môžu byť relevantné,
- aké námietky môžu vzniknúť,
- aké informácie nám chýbajú.

Výstup:
1. stručný profil firmy,
2. pravdepodobné potreby,
3. vhodná hodnotová ponuka,
4. 5 relevantných argumentov,
5. 5 možných námietok a reakcií,
6. 10 otázok na zistenie potrieb,
7. návrh prvého e-mailu,
8. návrh ďalšieho kroku.

Odlišuj overené fakty od obchodných hypotéz.
```

---

## Prompt č. 7: Analýza webovej stránky firmy

```text
Analyzuj webovú stránku firmy:

URL: [web firmy]
Účel analýzy: [účel]
Cieľová skupina firmy: [cieľová skupina, ak je známa]

Posúď:
- čo firma ponúka,
- komu sú služby alebo produkty určené,
- akú hodnotu firma komunikuje,
- zrozumiteľnosť hlavnej ponuky,
- dôveryhodnosť webu,
- referencie a sociálne dôkazy,
- kvalitu výziev na akciu,
- kontaktné možnosti,
- konzistentnosť komunikácie,
- silné a slabé stránky,
- možné informačné medzery.

Výstup:
1. stručné zhrnutie webu,
2. ponuka a cieľová skupina,
3. silné stránky,
4. slabé stránky,
5. nejasnosti,
6. otázky pred spoluprácou,
7. 10 konkrétnych návrhov na zlepšenie komunikácie,
8. prioritizácia návrhov podľa dopadu a náročnosti.

Nevymýšľaj funkcie, služby ani referencie, ktoré na webe nie sú uvedené.
```

---

## Prompt č. 8: Porovnanie viacerých firiem

```text
Porovnaj nasledujúce firmy:

Firma A: [firma A]
Web A: [web A]

Firma B: [firma B]
Web B: [web B]

Firma C: [firma C]
Web C: [web C]

Účel porovnania: [účel]

Porovnaj ich podľa kritérií:
- hlavná ponuka,
- cieľová skupina,
- positioning,
- cenový model, ak je verejne dostupný,
- geografické pôsobenie,
- referencie,
- dôveryhodnosť,
- kvalita webovej komunikácie,
- silné stránky,
- slabé stránky,
- reputačné riziká,
- obchodné riziká,
- odlišujúce prvky.

Výstup priprav v porovnávacej tabuľke.

Na konci uveď:
1. hlavné rozdiely,
2. najväčšie výhody každej firmy,
3. najväčšie riziká,
4. chýbajúce informácie,
5. odporúčanie podľa účelu [účel],
6. zdroje použité pri porovnaní.
```

---

## Prompt č. 9: Hľadanie rozhodovacích osôb

```text
Identifikuj verejne dostupné profesijné kontakty relevantné pre B2B oslovenie.

Firma: [názov firmy]
Web: [web firmy]
Oblasť ponuky: [oblasť]
Naša služba: [naša služba]

Hľadaj osoby zodpovedné za:
- [obchod],
- [marketing],
- [IT],
- [ľudské zdroje],
- [vzdelávanie],
- [nákup],
- [logistiku],
- [inú oblasť].

Pre každú osobu uveď:
- meno,
- verejne uvedenú pozíciu,
- pravdepodobnú oblasť zodpovednosti,
- dôveryhodný zdroj,
- dátum alebo obdobie platnosti informácie,
- vhodný profesionálny dôvod na kontaktovanie,
- mieru istoty.

Pravidlá:
- používaj iba verejné profesijné informácie,
- nezískavaj súkromné kontaktné údaje,
- neodhaduj e-mailové adresy,
- označ neaktuálne alebo neisté pracovné pozície,
- rozlišuj medzi rozhodovacou osobou a kontaktnou osobou.

Výstup priprav v tabuľke.
```

---

## ⚠️ Prompt č. 10: Kontrola rizík pred spoluprácou

```text
Vykonaj predbežné reputačné a obchodné preverenie firmy.

Firma: [názov firmy]
IČO: [IČO]
Web: [web firmy]
Krajina: [krajina]
Účel spolupráce: [účel]

Skontroluj:
- konzistentnosť identifikačných údajov,
- aktívny stav firmy,
- vlastnícke a riadiace väzby,
- dostupné účtovné a finančné signály,
- verejné referencie,
- recenzie,
- negatívne zmienky,
- možné právne problémy,
- dlhy alebo iné verejne dostupné rizikové signály,
- rozdiely medzi webom a registrami,
- profesionalitu verejnej komunikácie.

Rozdeľ zistenia do kategórií:

### Nízke riziko
Konzistentné informácie, jasné identifikačné údaje, pozitívne referencie a profesionálna komunikácia.

### Stredné riziko
Čiastočne nejasné informácie, obmedzené referencie, jednotlivé sťažnosti alebo chýbajúce údaje.

### Vysoké riziko
Významné rozpory, právne problémy, podozrivé praktiky alebo závažné negatívne zistenia.

### Manuálne overiť
Informácie, ktoré nie je možné spoľahlivo potvrdiť pomocou dostupných zdrojov.

Výstup:
1. exekutívne zhrnutie,
2. tabuľka zistení,
3. klasifikácia rizík,
4. otvorené otázky,
5. odporúčané manuálne overenie,
6. predbežné odporúčanie pokračovať, pokračovať s podmienkami alebo nepokračovať.

Upozorni, že ide iba o predbežné informačné preverenie, nie právny alebo finančný audit.
```

---

# 💼 Príprava na pohovor a obchodný kontakt

---

## Prompt č. 11: Príprava na pracovný pohovor

```text
Priprav ma na pracovný pohovor vo firme:

Firma: [názov firmy]
Web: [web firmy]
Pozícia: [pracovná pozícia]
Pracovná ponuka: [text alebo URL ponuky]
Moje skúsenosti: [stručný profil kandidáta]

Vyhľadaj a spracuj:
- činnosť firmy,
- produkty a služby,
- kultúru a verejne komunikované hodnoty,
- aktuálne projekty alebo zmeny,
- očakávania od kandidáta,
- kľúčové kompetencie pre pozíciu,
- možné otázky na pohovore,
- oblasti, ktoré mám zdôrazniť,
- možné riziká alebo nejasnosti,
- otázky, ktoré mám položiť zamestnávateľovi.

Výstup:
1. briefing o firme,
2. požiadavky na pozíciu,
3. prepojenie mojich skúseností s požiadavkami,
4. 15 možných otázok a návrhy odpovedí,
5. 10 otázok pre zamestnávateľa,
6. krátke predstavenie kandidáta do 60 sekúnd,
7. kontrolný zoznam pred pohovorom.

Odlišuj verejné fakty od odhadov.
```

---

## Prompt č. 12: Príprava na predajný hovor

```text
Priprav podklady na predajný hovor.

Potenciálny zákazník: [firma]
Web: [web firmy]
Odvetvie: [odvetvie]
Naša služba alebo produkt: [služba]
Cieľ hovoru: [cieľ]

Vyhľadaj:
- profil firmy,
- hlavné produkty a služby,
- cieľových zákazníkov,
- možné obchodné potreby,
- aktuálne projekty alebo zmeny,
- možné problémy relevantné pre našu ponuku,
- pravdepodobné námietky,
- chýbajúce informácie.

Priprav:
1. stručný briefing,
2. úvod hovoru do 30 sekúnd,
3. 10 otázok na zistenie potrieb,
4. 5 relevantných argumentov,
5. 5 možných námietok a odpovedí,
6. návrh hodnotovej ponuky,
7. návrh ďalšieho kroku,
8. krátky následný e-mail.

Neprezentuj nepotvrdené potreby firmy ako fakty. Označ ich ako hypotézy na overenie.
```

---

# 📊 Konkurencia a mediálny obraz

---

## Prompt č. 13: Analýza konkurencie

```text
Priprav konkurenčný briefing.

Naša firma: [naša firma]
Náš web: [náš web]
Konkurent: [konkurent]
Web konkurenta: [web konkurenta]
Trh: [trh]
Cieľ analýzy: [cieľ]

Zisti:
- čo konkurent ponúka,
- komu predáva,
- ako komunikuje hodnotu,
- aký používa positioning,
- produkty a služby,
- ceny, ak sú verejne dostupné,
- obchodný model,
- hlavné referencie,
- komunikačné kanály,
- silné a slabé stránky,
- možné konkurenčné výhody,
- možné riziká,
- informačné medzery.

Výstup:
1. exekutívne zhrnutie,
2. porovnávacia tabuľka,
3. SWOT analýza konkurenta,
4. rozdiely oproti našej firme,
5. príležitosti na odlíšenie,
6. odporúčania pre manažment,
7. zoznam zdrojov a dátum analýzy.

Nepoužívaj neverejné alebo nepodložené údaje.
```

---

## Prompt č. 14: Mediálny obraz osoby alebo firmy

```text
Analyzuj verejný mediálny obraz:

Subjekt: [osoba alebo firma]
Časové obdobie: [obdobie]
Krajina alebo jazyk: [krajina alebo jazyk]
Účel analýzy: [účel]

Vyhľadaj:
- pozitívne zmienky,
- neutrálne zmienky,
- negatívne zmienky,
- hlavné mediálne témy,
- opakujúce sa tvrdenia,
- významné udalosti,
- zdroje s najväčším dosahom,
- možné reputačné riziká,
- rozpory medzi zdrojmi,
- vývoj mediálneho obrazu v čase.

Výstup:
1. stručný reputačný profil,
2. tabuľka zmienok,
3. hlavné pozitívne témy,
4. hlavné negatívne témy,
5. neutrálne alebo faktické témy,
6. časová os,
7. reputačné riziká,
8. odporúčané reakcie alebo ďalšie preverenie.

Pri negatívnych tvrdeniach uveď presný zdroj a nepoužívaj nepodložené obvinenia.
```

---

# 🔄 Porovnanie vyhľadávacích prístupov

---

## Prompt č. 15: Google verzus ChatGPT

```text
Správaj sa ako analytik a porovnaj dva spôsoby zisťovania informácií o téme:

Téma: [téma]
Účel: [účel]

Porovnaj:
1. čo získame bežným vyhľadávaním Google,
2. čo získame analytickou sumarizáciou pomocou ChatGPT,
3. čo dokáže lepšie Google,
4. čo dokáže lepšie ChatGPT,
5. aké informácie musíme overiť manuálne,
6. aké riziká má každý prístup,
7. aké informácie pravdepodobne chýbajú.

Výstup priprav v tabuľke:
- oblasť,
- Google,
- ChatGPT,
- odporúčaný postup.

Na konci vytvor kombinovaný pracovný postup:
1. čo vyhľadáme v Google,
2. čo spracujeme v ChatGPT,
3. čo overíme v pôvodnom zdroji,
4. aký praktický výstup vytvoríme.
```

---

# 🚀 Komplexné superprompty

---

## Prompt č. 16: Superprompt pre verejný profil osoby

```text
Vykonaj komplexnú analýzu verejne dostupných profesijných informácií o osobe.

Meno: [meno osoby]
Firma alebo organizácia: [firma]
Pozícia alebo oblasť: [pozícia]
Krajina: [krajina]
Kontext použitia: [stretnutie, pohovor, obchod, spolupráca alebo iný účel]
Naša téma alebo ponuka: [téma]

Cieľ:
Pripraviť presný, praktický a zdrojmi podložený briefing bez zásahu do súkromia osoby.

Preskúmaj:

### 1. Identifikácia
- správna identifikácia osoby,
- organizácia a pozícia,
- možné riziko zámeny s inou osobou.

### 2. Profesijné pozadie
- aktuálna rola,
- predchádzajúce pracovné skúsenosti,
- vzdelanie a certifikácie,
- odborné oblasti,
- verejné projekty.

### 3. Verejná komunikácia
- články,
- rozhovory,
- konferencie,
- podcasty,
- sociálne siete,
- opakujúce sa odborné témy.

### 4. Profesijná reputácia
- verejné referencie,
- odborné uznania,
- nezávislé zmienky,
- možné kontroverzie,
- konzistentnosť informácií.

### 5. Kontext spolupráce
- možné profesijné priority,
- relevantné potreby,
- možné problémy,
- rozhodovacia rola,
- vhodné témy na rozhovor.

### 6. Riziká
- neaktuálne údaje,
- rozpory,
- nepotvrdené tvrdenia,
- zámennosť mena,
- chýbajúce informácie.

### 7. Praktická príprava
- 10 otázok na stretnutie,
- odporúčané témy,
- nevhodné alebo citlivé témy,
- návrh úvodného oslovenia,
- návrh e-mailu alebo LinkedIn správy.

Pravidlá:
- používaj iba verejne dostupné profesijné informácie,
- nepoužívaj súkromné alebo citlivé údaje,
- odlišuj fakt, tvrdenie zdroja a vlastnú interpretáciu,
- pri každom významnom tvrdení uveď zdroj,
- uveď dátum alebo obdobie platnosti,
- označ nízku mieru istoty,
- nevytváraj psychologický profil.

Výstup:
1. exekutívne zhrnutie,
2. profil osoby,
3. tabuľka zdrojov,
4. reputačné zistenia,
5. relevantné profesijné priority,
6. riziká a nejasnosti,
7. otázky na stretnutie,
8. návrh oslovenia,
9. informácie na manuálne overenie.
```

---

## Prompt č. 17: Superprompt pre komplexnú analýzu firmy

```text
Vykonaj komplexnú analýzu firmy.

Názov firmy: [názov firmy]
IČO: [IČO]
Web: [web firmy]
Krajina: [krajina]
Odvetvie: [odvetvie]
Účel analýzy: [obchodná spolupráca, investícia, dodávateľ, konkurencia alebo iný účel]
Naša firma alebo ponuka: [naša firma alebo ponuka]

Cieľ:
Vytvoriť zdrojmi podložený briefing, ktorý môžeme použiť pri rozhodovaní alebo príprave na obchodný kontakt.

Preskúmaj:

### 1. Identifikácia firmy
- oficiálny názov,
- právna forma,
- IČO,
- sídlo,
- dátum vzniku,
- stav firmy,
- verejne dostupné registračné údaje.

### 2. Vedenie a vlastnícke väzby
- konatelia,
- štatutárne orgány,
- vlastníci alebo spoločníci, ak sú verejne dostupní,
- prepojené firmy,
- významné zmeny.

### 3. Produkty a služby
- hlavná ponuka,
- zákaznícke segmenty,
- obchodný model,
- cenový model, ak je verejný,
- geografické pôsobenie,
- hlavné distribučné kanály.

### 4. Trh a konkurencia
- odvetvie,
- významní konkurenti,
- positioning,
- konkurenčné výhody,
- slabé stránky,
- trhové príležitosti a hrozby.

### 5. Verejná reputácia
- referencie,
- recenzie,
- mediálne zmienky,
- pozitívne a negatívne témy,
- konzistentnosť verejnej komunikácie.

### 6. Finančné signály
- dostupné účtovné výsledky,
- vývoj tržieb,
- zisk alebo strata,
- zadlženosť alebo iné verejné ukazovatele,
- zmeny v čase,
- obmedzenia dostupných údajov.

### 7. Riziká
- právne problémy,
- negatívne záznamy,
- nekonzistentné identifikačné údaje,
- nejasné vlastnícke väzby,
- chýbajúce účtovné údaje,
- reputačné riziká,
- riziká spolupráce.

### 8. Obchodný kontext
- možné potreby firmy,
- relevantnosť našej ponuky,
- vhodné oddelenia a rozhodovacie roly,
- možné argumenty,
- možné námietky,
- otázky na prvé stretnutie.

### 9. Odporúčanie
- pokračovať,
- pokračovať s podmienkami,
- manuálne preveriť,
- nepokračovať.

Pravidlá:
- uprednostni oficiálne a primárne zdroje,
- pri každom dôležitom tvrdení uveď zdroj,
- uveď dátum platnosti údajov,
- odlišuj fakty od interpretácií,
- označ chýbajúce informácie,
- nevytváraj finančné alebo právne závery bez dôkazov,
- upozorni, že analýza nenahrádza právny alebo finančný audit.

Výstup:
1. exekutívne zhrnutie,
2. identifikačný profil firmy,
3. produkty, zákazníci a trh,
4. vedenie a vlastnícke väzby,
5. finančné signály,
6. reputácia,
7. konkurencia,
8. riziká,
9. obchodné príležitosti,
10. odporúčané otázky,
11. odporúčanie ďalšieho postupu,
12. zoznam zdrojov,
13. informácie na manuálne overenie.
```

---

# 🛠️ Prompty na spracovanie výsledkov vyhľadávania

---

## Prompt: oddelenie faktov od interpretácií

```text
Skontroluj nasledujúci výsledok vyhľadávania:

[výsledok]

Rozdeľ tvrdenia do kategórií:
1. overený fakt podložený zdrojom,
2. tvrdenie konkrétneho zdroja,
3. interpretácia ChatGPT,
4. hypotéza,
5. neoverené alebo nejasné tvrdenie.

Výstup priprav v tabuľke:
- tvrdenie,
- kategória,
- zdroj,
- miera istoty,
- potrebné ďalšie overenie.

Na konci vypíš tvrdenia, ktoré nesmieme použiť bez manuálneho overenia.
```

---

## Prompt: kontrola zdrojov

```text
Skontroluj kvalitu zdrojov použitých v nasledujúcej odpovedi:

[odpoveď]

Pri každom zdroji vyhodnoť:
- typ zdroja,
- autoritu,
- aktuálnosť,
- nezávislosť,
- relevantnosť,
- možné konflikty záujmov,
- či zdroj skutočne podporuje dané tvrdenie.

Výstup priprav v tabuľke:
- zdroj,
- podporované tvrdenie,
- hodnotenie kvality,
- problém,
- odporúčanie.

Na konci uveď, ktoré tvrdenia musíme overiť v lepšom zdroji.
```

---

## Prompt: kontrola rizika zámeny osoby alebo firmy

```text
Skontroluj, či pri nasledujúcej analýze nehrozí zámena osoby alebo firmy:

Analyzovaný subjekt:
[názov alebo meno]

Dostupné identifikátory:
- firma alebo organizácia: [firma],
- pozícia: [pozícia],
- mesto alebo krajina: [lokalita],
- IČO: [IČO],
- web: [web],
- ďalšie údaje: [údaje].

Preskúmaj:
- podobné mená alebo názvy,
- rozdielne firmy s rovnakým alebo podobným názvom,
- rozdielne osoby s rovnakým menom,
- nezhody v pracovných pozíciách,
- nezhody v lokalite,
- nezhody v dátumoch.

Výstup:
1. miera rizika zámeny,
2. identifikované možné zámeny,
3. údaje potrebné na jednoznačné rozlíšenie,
4. odporúčané manuálne overenie.
```

---

## Prompt: vytvorenie briefingu

```text
Premeň nasledujúce výsledky vyhľadávania na praktický briefing:

[výsledky]

Účel briefingu:
[účel]

Cieľová skupina:
[cieľová skupina]

Výstup:
1. exekutívne zhrnutie do 7 viet,
2. hlavné overené fakty,
3. dôležité súvislosti,
4. príležitosti,
5. riziká,
6. otvorené otázky,
7. odporúčané ďalšie kroky,
8. zdroje,
9. informácie na manuálne overenie.

Nepoužívaj všeobecné formulácie. Uprednostni konkrétne a rozhodovacie informácie.
```

---

## Prompt: vytvorenie otázok na stretnutie

```text
Na základe nasledujúcej analýzy priprav otázky na stretnutie:

[analýza]

Kontext stretnutia:
[kontext]

Rozdeľ otázky na:
1. úvodné otázky,
2. otázky na aktuálnu situáciu,
3. otázky na problémy,
4. otázky na potreby,
5. otázky na rozhodovanie,
6. otázky na rozpočet a termín,
7. otázky na ďalší krok.

Pri každej otázke uveď:
- cieľ otázky,
- čo sa z odpovede môžeme dozvedieť,
- vhodnú doplňujúcu otázku.

Nevytváraj manipulatívne otázky.
```

---

## Prompt: vytvorenie porovnávacej tabuľky

```text
Premeň nasledujúce informácie na porovnávaciu tabuľku:

[informácie]

Porovnávané možnosti:
[možnosti]

Kritériá:
[kritériá]

Pri každom kritériu uveď:
- zistenie,
- zdroj,
- dátum,
- mieru istoty,
- chýbajúce informácie.

Na konci vytvor:
1. hlavné rozdiely,
2. výhody každej možnosti,
3. riziká každej možnosti,
4. odporúčanie podľa účelu [účel].
```

---

# ✅ Kontrolný zoznam pred použitím AI výstupu

Pred použitím výsledku vyhľadávania si overíme:

- [ ] Je jasné, ktoré tvrdenia sú fakty?
- [ ] Je jasné, ktoré tvrdenia sú interpretácie?
- [ ] Sú pri dôležitých tvrdeniach uvedené zdroje?
- [ ] Sú zdroje dôveryhodné a aktuálne?
- [ ] Podporuje zdroj skutočne uvedené tvrdenie?
- [ ] Nie je informácia vytrhnutá z kontextu?
- [ ] Nevyskytuje sa riziko zámeny osoby?
- [ ] Nevyskytuje sa riziko zámeny firmy?
- [ ] Sú uvedené dátumy platnosti údajov?
- [ ] Nie sú použité citlivé alebo súkromné údaje?
- [ ] Je výstup prispôsobený konkrétnemu účelu?
- [ ] Sú označené chýbajúce informácie?
- [ ] Sú označené hypotézy?
- [ ] Vieme, čo musíme manuálne overiť?
- [ ] Nezamieňame AI rešerš za právny alebo finančný audit?
- [ ] Nevykonávame závažné rozhodnutie iba na základe AI odpovede?

---

## Prompt: záverečná kontrola AI výstupu

```text
Vykonaj kritickú kontrolu nasledujúceho AI výstupu:

[výstup]

Skontroluj:
- presnosť tvrdení,
- aktuálnosť údajov,
- kvalitu zdrojov,
- súlad tvrdení so zdrojmi,
- možné rozpory,
- riziko zámeny osoby alebo firmy,
- rozdiel medzi faktmi a interpretáciami,
- chýbajúce informácie,
- citlivé alebo nevhodné údaje,
- vhodnosť pre účel [účel].

Výstup priprav v štruktúre:
1. použiteľné časti,
2. problematické časti,
3. tvrdenia na manuálne overenie,
4. chýbajúce zdroje,
5. opravená verzia záveru,
6. odporúčanie, či môžeme výstup použiť.
```

---

# 📝 Praktické úlohy

## Úloha 1: Rýchle overenie aktuálnej informácie

Vyberieme jednu aktuálnu tému a pripravíme prompt na štandardné vyhľadávanie.

**Téma:**

```text
[téma]
```

**Čo skontrolujeme:**

- aktuálnosť,
- zdroje,
- dátumy,
- rozdiely medzi zdrojmi,
- nejasnosti.

---

## Úloha 2: Porovnanie režimov

Rovnakú otázku spracujeme:

1. v základnom režime,
2. pomocou štandardného vyhľadávania,
3. pomocou Deep Research.

Následne porovnáme:

- rýchlosť,
- rozsah,
- aktuálnosť,
- kvalitu zdrojov,
- praktickú použiteľnosť.

---

## Úloha 3: Profil osoby

Vyberieme verejne známu osobu z profesijnej oblasti a použijeme prompt č. 1.

Skontrolujeme:

- správnu identifikáciu,
- zdroje,
- riziko zámeny,
- oddelenie faktov od interpretácií,
- chýbajúce informácie.

---

## Úloha 4: Profil firmy

Vyberieme firmu a použijeme prompt č. 5.

Porovnáme informácie z:

- oficiálneho webu,
- verejného registra,
- účtovných údajov,
- nezávislých zdrojov.

---

## Úloha 5: Analýza konkurencie

Vyberieme našu firmu a jedného konkurenta. Použijeme prompt č. 13 a vytvoríme konkurenčný briefing.

Výsledok musí obsahovať:

- porovnávaciu tabuľku,
- silné a slabé stránky,
- príležitosti na odlíšenie,
- zdroje,
- informácie na manuálne overenie.

---

## Úloha 6: Príprava na stretnutie

Vyberieme osobu alebo firmu, s ktorou plánujeme stretnutie. Použijeme prompt č. 2 alebo prompt č. 6.

Pripravíme:

- briefing,
- 10 otázok,
- možné potreby,
- možné námietky,
- návrh ďalšieho kroku.

---

## Úloha 7: Kontrola rizík

Vyberieme firmu a použijeme prompt č. 10.

Zistenia rozdelíme na:

- nízke riziko,
- stredné riziko,
- vysoké riziko,
- manuálne overiť.

---

# 📋 Univerzálna šablóna promptu na vyhľadávanie

```text
Vyhľadaj a analyzuj informácie o téme:

[téma]

Kontext:
- účel: [účel],
- cieľová skupina: [cieľová skupina],
- krajina alebo región: [krajina],
- časové obdobie: [obdobie].

Použi prednostne:
- [zdroj 1],
- [zdroj 2],
- [zdroj 3].

Zameraj sa na:
- [oblasť 1],
- [oblasť 2],
- [oblasť 3],
- [oblasť 4].

Pravidlá:
- používaj aktuálne a dôveryhodné zdroje,
- pri každom dôležitom tvrdení uveď zdroj,
- uveď dátum platnosti informácie,
- rozlišuj fakty, tvrdenia zdrojov a interpretácie,
- označ neisté informácie,
- upozorni na rozpory,
- nevymýšľaj chýbajúce údaje,
- uveď, čo musíme overiť manuálne.

Výstup:
1. exekutívne zhrnutie,
2. hlavné zistenia,
3. tabuľka údajov,
4. rozpory a nejasnosti,
5. príležitosti,
6. riziká,
7. odporúčané kroky,
8. zdroje,
9. informácie na manuálne overenie.
```

---

# 🧠 Zhrnutie cvičenia

Pri vyhľadávaní pomocou ChatGPT nepoužívame jeden všeobecný prompt na všetky situácie. Najskôr si určíme cieľ, vyberieme vhodný režim, stanovíme zdroje a pripravíme požadovanú štruktúru výstupu.

Kvalitný výsledok nevzniká iba vyhľadaním informácií. Musíme skontrolovať zdroje, dátumy, možné rozpory, riziko zámeny a rozdiel medzi faktom a interpretáciou.

ChatGPT používame ako analytického asistenta. Konečné rozhodnutie, odborné posúdenie a zodpovednosť za použitie informácií zostávajú na používateľovi.

---

## ✅ Čo by sme mali vedieť po dokončení cvičenia

Po dokončení cvičenia dokážeme:

- vybrať správny režim vyhľadávania,
- pripraviť prompt s jasným cieľom,
- určiť dôveryhodné zdroje,
- vyhľadávať aktuálne informácie,
- pracovať s podrobným vyhľadávaním,
- analyzovať verejné profesijné informácie,
- pripraviť firemný briefing,
- porovnať konkurentov,
- identifikovať rozhodovacie osoby,
- pripraviť sa na pohovor alebo predajný hovor,
- klasifikovať obchodné a reputačné riziká,
- kontrolovať kvalitu AI výstupu,
- vytvoriť praktické podklady pre ďalšie rozhodovanie.
