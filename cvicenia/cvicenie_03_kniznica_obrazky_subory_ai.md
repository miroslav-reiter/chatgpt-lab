# 🧪 Cvičenie 03: Knižnica, obrázky a súbory v ChatGPT

Toto cvičenie je zamerané na praktickú prácu s Knižnicou, obrázkami a súbormi v ChatGPT. Naučíme sa vyhľadávať a opakovane používať uložené súbory, vytvárať a upravovať obrázky, analyzovať dokumenty, pracovať s tabuľkami a prepájať informácie z viacerých zdrojov.

Prompty sú pripravené na rýchle skopírovanie. Obsahujú placeholdery v hranatých zátvorkách, napríklad `[téma]`, `[názov súboru]`, `[cieľová skupina]`, `[požadovaná úprava]` alebo `[účel analýzy]`. Pred odoslaním ich nahradíme konkrétnymi údajmi.

---

## 🎯 Ciele cvičenia

Po absolvovaní cvičenia budeme vedieť:

- vysvetliť, na čo slúži Knižnica v ChatGPT,
- rozlíšiť Knižnicu od histórie chatov,
- vyhľadávať a filtrovať uložené súbory,
- opakovane použiť rovnaký súbor v rôznych konverzáciách,
- pracovať s nahratými aj vygenerovanými obrázkami,
- pripraviť kvalitný prompt na vytvorenie obrázka,
- presne opísať požadovanú úpravu existujúceho obrázka,
- rozlíšiť syntézu, transformáciu a extrakciu,
- analyzovať PDF, Word, Excel, CSV a PowerPoint súbory,
- porovnať dva dokumenty,
- vytvoriť spoločnú syntézu z viacerých súborov,
- identifikovať chýbajúce informácie, neistoty a rozpory,
- kontrolovať kvalitu a presnosť výstupu,
- chrániť citlivé a dôverné údaje.

---

# 📚 Knižnica v ChatGPT

## Čo je Knižnica

Knižnica je centrálne miesto na vyhľadávanie a opakované používanie súborov, ktoré sme nahrali do ChatGPT alebo vytvorili pomocou ChatGPT. Umožňuje nám pracovať s dokumentmi, tabuľkami, prezentáciami, PDF súbormi a obrázkami bez toho, aby sme ich museli pri každej novej úlohe opakovane nahrávať.

Knižnica je dostupná vo webovej verzii ChatGPT. Jej úložisko je oddelené od denných limitov príloh v jednotlivých konverzáciách. Dostupnosť Knižnice a jednotlivých funkcií sa môže líšiť podľa tarify, pracovného priestoru a aktuálneho nasadenia služby.

### Čo sa môže ukladať do Knižnice

**Dokumenty:**

- PDF dokumenty,
- Microsoft Word súbory DOCX,
- textové súbory TXT,
- Markdown súbory MD,
- výstupy z podrobného vyhľadávania,
- dokumenty vytvorené pomocou ChatGPT.

**Tabuľky a dáta:**

- Microsoft Excel súbory XLSX a XLS,
- CSV a TSV súbory,
- JSON súbory,
- exportované analýzy,
- vytvorené tabuľky a grafy.

**Vizuálny obsah:**

- nahraté obrázky,
- vygenerované obrázky,
- prezentácie Microsoft PowerPoint PPTX.

> Súbory nahraté v Dočasnom chate sa do účtu ani do Knižnice neukladajú.

---

## Práca s Knižnicou

V Knižnici môžeme súbory nahrávať, vyhľadávať, filtrovať, sťahovať, opakovane používať a odstraňovať. Pri väčšom počte dokumentov používame konkrétne názvy súborov, aby sme ich vedeli rýchlo nájsť podľa projektu, klienta, témy alebo obdobia.

### Základné činnosti

1. Otvoríme položku **Knižnica** v ľavom bočnom paneli.
2. Vyberieme zobrazenie **Všetky**, **Obrázky** alebo **Súbory**.
3. Použijeme vyhľadávacie pole alebo filtre.
4. Otvoríme náhľad súboru.
5. Súbor stiahneme, odstránime alebo pridáme do novej konverzácie.

### Vyhľadávanie

V Knižnici môžeme vyhľadávať podľa názvu, obsahu alebo typu súboru. V používateľskom rozhraní môžeme použiť aj vyhľadávanie cez klávesovú skratku `Ctrl + K`, pričom konkrétne správanie skratky sa môže líšiť podľa aktívnej časti rozhrania.

### Filtrovanie

Súbory môžeme filtrovať napríklad podľa:

- zdroja: nahraté alebo vygenerované,
- typu: obrázky, dokumenty, tabuľky, prezentácie alebo PDF,
- zobrazenia: mriežka alebo zoznam,
- stavu: aktívne alebo nedávno odstránené.

---

## Limity úložiska Knižnice

Limity úložiska sa líšia podľa tarify. Hodnoty sa môžu časom meniť, preto ich pred školením alebo produkčným použitím kontrolujeme v aktuálnej dokumentácii a priamo v účte.

| Tarifa | Úložisko |
|---|---:|
| Free | 500 MB |
| Go | 4 GB |
| Plus / Business | 20 GB |
| Pro | 100 GB |

---

## Knižnica verzus história chatov

Knižnica a história chatov nie sú rovnaká funkcia. Knižnica spravuje súbory a vytvorené výstupy, zatiaľ čo história chatov spravuje jednotlivé konverzácie.

| Oblasť | Knižnica | História chatov |
|---|---|---|
| Hlavný obsah | Súbory a vytvorené výstupy | Konverzácie |
| Vyhľadávanie | Podľa súboru, typu alebo obsahu | Podľa názvu alebo obsahu chatu |
| Opakované použitie | Súbor pripojíme do nového chatu | Pokračujeme v pôvodnej konverzácii |
| Odstránenie chatu | Súbor môže zostať v Knižnici | Konverzácia sa odstráni |
| Dočasný chat | Súbory sa neukladajú | Chat sa nezobrazuje v histórii |

Odstránenie konverzácie automaticky neodstráni súbor uložený v Knižnici. Súbor musíme odstrániť priamo z Knižnice. Po odstránení sa môže presunúť do časti **Nedávno odstránené**, kde ho môžeme dočasne obnoviť. Odstránené súbory sú naplánované na trvalé vymazanie do 30 dní.

---

## 🧪 Cvičenie 1: Orientácia v Knižnici

### Zadanie

1. Otvoríme Knižnicu.
2. Skontrolujeme dostupné kategórie súborov.
3. Vyfiltrujeme iba PDF dokumenty.
4. Vyhľadáme dokument podľa názvu.
5. Otvoríme jeho náhľad.
6. Pripojíme ho do nového chatu.

### Prompt: identifikácia súboru

```text
Analyzuj priložený súbor z Knižnice.

Najskôr identifikuj:
- názov súboru,
- typ súboru,
- hlavnú tému,
- pravdepodobný účel,
- cieľovú skupinu,
- základnú štruktúru,
- počet hlavných častí.

Zatiaľ nevytváraj podrobné zhrnutie.

Výstup priprav v krátkej tabuľke:
- položka,
- zistenie,
- miera istoty.

Ak niečo nevieš spoľahlivo určiť, označ to ako nejasné.
```

---

## 🧪 Cvičenie 2: Opakované použitie jedného súboru

Rovnaký dokument použijeme v troch samostatných konverzáciách. V každej konverzácii vytvoríme iný typ výstupu.

### Prompt A: stručné zhrnutie

```text
Na základe priloženého súboru vytvor praktické zhrnutie.

Výstup:
1. účel dokumentu,
2. hlavná téma,
3. päť najdôležitejších zistení,
4. kľúčové čísla, dátumy a pojmy,
5. praktické odporúčania,
6. informácie, ktoré treba overiť.

Používaj iba informácie zo súboru.
Nevymýšľaj chýbajúce údaje.
```

### Prompt B: otázky a odpovede

```text
Na základe priloženého súboru vytvor 10 odborných otázok a odpovedí.

Požiadavky:
- otázky nesmú byť všeobecné,
- každá odpoveď má mať 2 až 4 vety,
- otázky majú pokryť celý dokument,
- neopakuj rovnakú tému,
- používaj iba informácie zo súboru,
- pri nejasnej informácii upozorni na obmedzenie.
```

### Prompt C: osnova prezentácie

```text
Na základe priloženého súboru priprav osnovu prezentácie.

Parametre:
- cieľová skupina: [cieľová skupina],
- maximálny počet slajdov: [počet slajdov],
- maximálne trvanie: [počet minút] minút,
- jazyk: slovenčina,
- tón: odborný a zrozumiteľný.

Pri každom slajde uveď:
1. názov slajdu,
2. hlavné body,
3. odporúčaný vizuálny prvok,
4. poznámky pre prezentujúceho,
5. odhadovaný čas.

Na konci skontroluj celkový počet slajdov a trvanie.
```

---

# 🖼️ Obrázky v ChatGPT

## Vytváranie obrázkov

ChatGPT umožňuje vytvárať nové obrázky na základe textového zadania priamo v konverzácii. Kvalita výsledku závisí od presnosti promptu, jasne definovaného objektu, prostredia, kompozície, štýlu, svetla, farieb, formátu a obmedzení.

Pri tvorbe obrázka môžeme definovať:

- objekty a postavy,
- prostredie,
- kompozíciu,
- uhol pohľadu,
- pomer strán,
- vizuálny štýl,
- svetelnú atmosféru,
- farebnú paletu,
- text v obrázku,
- priehľadné pozadie,
- prvky, ktoré sa nesmú objaviť.

---

## Štruktúra kvalitného promptu na obrázok

Používame túto štruktúru:

```text
OBJEKT + PROSTREDIE + KOMPOZÍCIA + ŠTÝL + SVETLO + FARBY + FORMÁT + OBMEDZENIA
```

| Časť | Príklad |
|---|---|
| Objekt | Lektor pri interaktívnej tabuli |
| Prostredie | Moderná školiaca miestnosť |
| Kompozícia | Lektor vpravo, priestor na text vľavo |
| Štýl | Realistická firemná fotografia |
| Svetlo | Mäkké denné osvetlenie |
| Farby | Neutrálne modré a sivé odtiene |
| Formát | 16:9, 16:10 alebo 4:3 |
| Obmedzenia | Bez loga, bez textu, bez vodoznaku |

---

## Prompt: univerzálny obrázok

```text
Vytvor obrázok na tému [téma].

Hlavný objekt:
[objekt]

Prostredie:
[prostredie]

Kompozícia:
- hlavný objekt umiestni [umiestnenie],
- ponechaj voľný priestor na [ľavej alebo pravej] strane,
- použi prirodzenú perspektívu,
- zachovaj prehľadnú vizuálnu hierarchiu.

Vizuálny štýl:
[štýl]

Osvetlenie:
[typ osvetlenia]

Farby:
[farebná paleta]

Formát:
[pomer strán]

Obmedzenia:
- bez loga,
- bez vodoznaku,
- bez náhodného textu,
- bez deformovaných objektov,
- bez vizuálneho chaosu,
- profesionálny a realistický výsledok.
```

---

## Prompt: titulný obrázok pre prezentáciu

```text
Vytvor titulný obrázok pre prezentáciu na tému:

[téma prezentácie]

Cieľová skupina:
[cieľová skupina]

Hlavný vizuálny motív:
[motív]

Požiadavky:
- pomer strán 16:9,
- profesionálny moderný vzhľad,
- hlavný vizuálny motív umiestni vpravo,
- ľavú tretinu obrázka ponechaj jednoduchú pre nadpis,
- nepoužívaj žiadny text,
- nepoužívaj logá ani vodoznaky,
- obraz nesmie byť preplnený,
- používaj realistické objekty,
- zachovaj prirodzené osvetlenie.
```

---

## Prompt: obrázok pre online kurz

```text
Vytvor titulný obrázok pre online kurz.

Téma kurzu:
[téma kurzu]

Cieľová skupina:
[cieľová skupina]

Na obrázku zobraz:
[hlavný motív]

Požiadavky:
- realistická profesionálna fotografia,
- pomer strán 16:9,
- hlavný objekt vpravo,
- ľavá strana voľná pre názov kurzu,
- moderné pracovné alebo školiace prostredie,
- prirodzené osvetlenie,
- bez textu,
- bez loga,
- bez vodoznaku,
- bez rušivých prvkov.
```

---

## Prompt: produktový obrázok

```text
Vytvor profesionálny produktový obrázok produktu:

[produkt]

Prostredie:
[prostredie alebo neutrálne štúdio]

Kompozícia:
- produkt umiestni do stredu,
- zobraz celý produkt,
- zachovaj prirodzené proporcie,
- použi čisté pozadie,
- pridaj jemný realistický tieň.

Štýl:
[realistická produktová fotografia / minimalistická reklama]

Formát:
[pomer strán]

Obmedzenia:
- bez loga, ak nie je súčasťou produktu,
- bez vodoznaku,
- bez ďalších náhodných predmetov,
- bez deformácií,
- bez textu.
```

---

## Prompt: obrázok s priehľadným pozadím

```text
Vytvor samostatný objekt:

[objekt]

Požiadavky:
- priehľadné pozadie,
- celý objekt musí byť viditeľný,
- čisté a ostré okraje,
- prirodzené proporcie,
- bez textu,
- bez loga,
- bez ďalších predmetov,
- bez tieňa mimo objektu,
- vhodné na vloženie do prezentácie alebo dokumentu.
```

---

## Prompt: infografika

```text
Vytvor prehľadnú infografiku na tému:

[téma]

Obsah infografiky:
- [bod 1],
- [bod 2],
- [bod 3],
- [bod 4].

Cieľová skupina:
[cieľová skupina]

Požiadavky:
- jasná informačná hierarchia,
- krátke texty,
- čitateľná typografia,
- jednoduché ikony,
- dostatok bieleho priestoru,
- jednotná farebná paleta,
- vertikálny formát 4:5,
- bez vodoznaku,
- bez prebytočných dekorácií.

Použi presne zadané texty a nepridávaj ďalšie tvrdenia.
```

---

# ✏️ Úprava existujúceho obrázka

Existujúci obrázok môžeme nahrať a opísať požadovanú zmenu. Môžeme upravovať celý obrázok alebo označiť konkrétnu oblasť. Pri úprave musíme presne uviesť, čo sa má zmeniť, kde sa zmena nachádza, čo sa má zachovať a čo ChatGPT nesmie meniť.

Výber oblasti nemusí byť úplne presný. Úprava môže zasiahnuť aj okolie označenej časti, preto pri dôležitých prvkoch jasne uvedieme požiadavku na ich zachovanie.

---

## Prompt: univerzálna úprava obrázka

```text
Uprav priložený obrázok.

Zmeň:
[požadovaná zmena]

Umiestnenie zmeny:
[časť obrázka]

Zachovaj bez zmeny:
- hlavný objekt,
- tvár a identitu osoby,
- kompozíciu,
- perspektívu,
- osvetlenie,
- farebný štýl,
- rozmery a pomer strán.

Nepridávaj žiadne ďalšie objekty.
Výsledok musí pôsobiť prirodzene a realisticky.
```

---

## Prompt: odstránenie objektu

```text
Odstráň z priloženého obrázka nasledujúci objekt:

[objekt]

Objekt sa nachádza:
[umiestnenie]

Po odstránení:
- prirodzene doplň pozadie,
- zachovaj perspektívu,
- zachovaj tiene a osvetlenie,
- nemeň ostatné objekty,
- nemeň pomer strán,
- nepridávaj nový obsah,
- zachovaj pôvodný vizuálny štýl.
```

---

## Prompt: zmena pozadia

```text
Nahraď pozadie priloženého obrázka.

Nové pozadie:
[opis nového pozadia]

Zachovaj:
- hlavný objekt,
- tvar a proporcie objektu,
- tvár a identitu osoby,
- oblečenie,
- pózu,
- ostrosť hlavného objektu,
- pôvodný pomer strán.

Prispôsob nové pozadie pôvodnému osvetleniu a perspektíve.
Výsledok musí pôsobiť ako prirodzená fotografia.
```

---

## Prompt: zmena formátu obrázka

```text
Uprav priložený obrázok na pomer strán [pomer strán].

Zachovaj:
- hlavný objekt,
- identitu osoby,
- pôvodnú perspektívu,
- farebný štýl,
- osvetlenie,
- všetky dôležité prvky.

Ak je potrebné doplniť okraje:
- prirodzene rozšír pozadie,
- nepridávaj nové hlavné objekty,
- nevytváraj náhodný text,
- zachovaj realistický vzhľad.
```

---

## 🧪 Cvičenie 3: Vytvorenie a úprava obrázka

### Časť A: vytvorenie

Vytvoríme titulný obrázok pre kurz, prezentáciu alebo článok. Použijeme štruktúru objekt, prostredie, kompozícia, štýl, svetlo, farby, formát a obmedzenia.

### Časť B: úprava

Na vytvorenom obrázku vykonáme tri zmeny:

1. odstránime rušivý objekt,
2. zmeníme pozadie,
3. zachováme hlavný objekt bez zmeny.

### Prompt

```text
Uprav priložený obrázok v troch krokoch:

1. Odstráň [rušivý objekt].
2. Nahraď pôvodné pozadie prostredím [nové prostredie].
3. Zachovaj hlavný objekt, jeho proporcie, farby a pozíciu.

Ďalšie podmienky:
- zachovaj pôvodný pomer strán,
- zachovaj prirodzené osvetlenie,
- nemeň tvár ani identitu osoby,
- nepridávaj text,
- nepridávaj logo,
- výsledok musí pôsobiť realisticky.
```

---

# 📄 Súbory v ChatGPT

## Podporované typy súborov

ChatGPT podporuje bežné formáty dokumentov, tabuliek, prezentácií a textových súborov.

| Kategória | Formáty |
|---|---|
| Tabuľky | XLSX, XLS, CSV, TSV |
| Dokumenty | DOCX, PDF, TXT |
| Prezentácie | PPTX |

Formát Google Docs `.gdoc` nie je priamo podporovaný. Dokument pred nahratím exportujeme napríklad ako PDF alebo DOCX.

---

## Tri hlavné typy práce so súbormi

### 1. Syntéza

Pri syntéze spájame informácie a vytvárame nový výstup. Môžeme porovnať dokumenty, analyzovať tabuľky, spojiť viacero zdrojov alebo vytvoriť spoločné zhrnutie.

### 2. Transformácia

Pri transformácii meníme formu obsahu bez zásadnej zmeny významu. Patrí sem zjednodušenie článku, sumarizácia jedného dokumentu, premena prezentácie na dokument, prepis do iného štýlu alebo vytvorenie osnovy.

### 3. Extrakcia

Pri extrakcii vyberáme konkrétne existujúce údaje. Môžeme vybrať dátumy, mená, sumy, povinnosti, citácie, nadpisy, riadky tabuľky alebo výskyty určitého pojmu.

### Praktické pravidlo

```text
Jeden zdroj a zmena formy -> Transformácia
Viac zdrojov spojených do nového výstupu -> Syntéza
Výber konkrétnych existujúcich údajov -> Extrakcia
```

| Úloha | Zaradenie |
|---|---|
| Zhrň tento jeden PDF dokument | Transformácia |
| Zjednoduš tento odborný článok | Transformácia |
| Vytvor manažérsky sumár prezentácie | Transformácia |
| Spoj poznatky z piatich dokumentov do jedného záveru | Syntéza |
| Porovnaj dve správy a vytvor spoločné zhrnutie | Syntéza |
| Vyber existujúcu kapitolu Zhrnutie | Extrakcia |
| Vypíš iba dátumy a sumy | Extrakcia |

---

## Limity súborov

| Typ obmedzenia | Limit |
|---|---:|
| Maximálna veľkosť jedného súboru | 512 MB |
| Textové a dokumentové súbory | 2 milióny tokenov |
| CSV a tabuľky | približne 50 MB |
| Obrázok | 20 MB |

Limity sa môžu meniť podľa typu účtu, formátu a aktuálnych pravidiel služby.

---

# 📑 Práca s PDF dokumentmi

Pri väčšine plánov ChatGPT spracúva z PDF predovšetkým digitálny text. Obrázky, grafy a diagramy vložené v PDF nemusia byť automaticky analyzované. Ak je vizuálny obsah dôležitý, príslušnú stranu exportujeme ako obrázok a nahráme ju samostatne.

---

## Prompt: podrobné zhrnutie PDF

```text
Analyzuj priložený PDF dokument.

Zameraj sa na:
- účel dokumentu,
- cieľovú skupinu,
- hlavnú tému,
- štruktúru,
- kľúčové pojmy,
- najdôležitejšie tvrdenia,
- čísla a dátumy,
- závery,
- odporúčania,
- riziká a obmedzenia.

Výstup:
1. exekutívne zhrnutie do 7 viet,
2. hlavné témy,
3. najdôležitejšie údaje v tabuľke,
4. praktické dôsledky,
5. otvorené otázky,
6. informácie, ktoré treba overiť.

Používaj iba obsah dokumentu.
Nevymýšľaj chýbajúce informácie.
Pri dôležitých zisteniach uveď stranu alebo sekciu.
```

---

## Prompt: stručný manažérsky sumár

```text
Vytvor manažérsky sumár priloženého dokumentu.

Cieľová skupina:
[manažment / vedenie / klient]

Rozsah:
maximálne [počet] slov.

Zameraj sa na:
- hlavný problém,
- kľúčové zistenia,
- čísla a termíny,
- riziká,
- príležitosti,
- odporúčané rozhodnutia,
- nasledujúce kroky.

Nepoužívaj všeobecné frázy.
Oddeľ fakty od interpretácií.
```

---

## Prompt: extrakcia údajov z PDF

```text
Z priloženého PDF vyber všetky informácie patriace do týchto kategórií:

- mená osôb,
- organizácie,
- dátumy,
- termíny,
- sumy,
- povinnosti,
- podmienky,
- riziká,
- odporúčané kroky.

Výstup priprav v tabuľke so stĺpcami:
- kategória,
- údaj,
- význam,
- strana alebo sekcia,
- miera istoty.

Ak sa údaj v dokumente nenachádza, uveď: Nenájdené.
Nevymýšľaj chýbajúce informácie.
```

---

## Prompt: kontrolný zoznam z dokumentu

```text
Na základe priloženého dokumentu vytvor praktický kontrolný zoznam.

Rozdeľ ho na:
1. čo musíme pripraviť,
2. čo musíme overiť,
3. čo musíme vykonať,
4. čo musíme odovzdať,
5. termíny,
6. možné chyby,
7. riziká.

Každý bod formuluj ako konkrétnu a kontrolovateľnú úlohu.
Použi Markdown checkboxy:
- [ ] úloha

Pri každom bode uveď stranu alebo sekciu dokumentu.
```

---

# 📝 Práca s dokumentmi Microsoft Word

## Prompt: odborná kontrola dokumentu

```text
Skontroluj priložený Word dokument z pohľadu:

- logickej štruktúry,
- zrozumiteľnosti,
- gramatiky,
- konzistentnosti terminológie,
- opakovania,
- úplnosti,
- vhodnosti pre cieľovú skupinu [cieľová skupina],
- praktickej použiteľnosti.

Výstup rozdeľ na:
1. silné stránky,
2. slabé stránky,
3. konkrétne chyby,
4. odporúčané úpravy,
5. ukážku prepracovanej časti.

Nemeň odborný význam dokumentu.
```

---

## Prompt: premena dokumentu na študijné poznámky

```text
Premeň priložený dokument na študijné poznámky.

Použi:
- hlavné nadpisy,
- stručné definície,
- odrážky,
- praktické príklady,
- upozornenia na časté chyby,
- kontrolné otázky.

Na konci vytvor:
1. 10 otázok a odpovedí,
2. 10 kľúčových pojmov,
3. stručný kontrolný zoznam,
4. zhrnutie do 5 viet.
```

---

## Prompt: zjednodušenie odborného textu

```text
Zjednoduš priložený odborný text pre cieľovú skupinu:

[cieľová skupina]

Požiadavky:
- zachovaj odborný význam,
- vysvetli odborné pojmy jednoduchým jazykom,
- používaj krátke odseky,
- pridaj praktické príklady,
- odstráň zbytočné opakovanie,
- nevypúšťaj dôležité podmienky ani obmedzenia.

Výstup:
1. zjednodušený text,
2. slovník pojmov,
3. tri praktické príklady,
4. upozornenia na možné nesprávne pochopenie.
```

---

# 📊 Práca s tabuľkami

## Prompt: základná analýza tabuľky

```text
Analyzuj priloženú tabuľku.

Najskôr skontroluj:
- názvy stĺpcov,
- počet riadkov a stĺpcov,
- dátové typy,
- chýbajúce hodnoty,
- duplicity,
- neobvyklé alebo chybné hodnoty,
- nekonzistentné formáty.

Následne vytvor:
1. stručný popis datasetu,
2. základné štatistiky,
3. hlavné zistenia,
4. možné problémy s kvalitou údajov,
5. odporúčané úpravy,
6. návrhy ďalších analýz.

Pred výpočtami nevytváraj predpoklady o význame nejasných stĺpcov.
```

---

## Prompt: vyhľadanie konkrétnych riadkov

```text
V priloženej tabuľke nájdi všetky riadky, ktoré spĺňajú tieto podmienky:

[podmienky]

Výstup priprav v tabuľke.

Uveď:
- počet nájdených riadkov,
- vybrané záznamy,
- použité podmienky,
- chýbajúce alebo nejasné hodnoty,
- upozornenie na možné duplicity.

Nemeň pôvodné hodnoty.
```

---

## Prompt: kontrola kvality dát

```text
Vykonaj kontrolu kvality priloženej tabuľky.

Skontroluj:
- prázdne bunky,
- duplicity,
- neplatné dátumy,
- nečíselné hodnoty v číselných stĺpcoch,
- rozdielne formáty rovnakého údaja,
- extrémne hodnoty,
- nejednotné názvy kategórií,
- chýbajúce identifikátory.

Výstup:
1. tabuľka nájdených problémov,
2. počet problémov podľa typu,
3. návrh opravy,
4. riziko nesprávnej opravy,
5. kroky, ktoré vyžadujú manuálne rozhodnutie.
```

---

## Prompt: návrh vizualizácií

```text
Analyzuj priloženú tabuľku a navrhni vhodné vizualizácie.

Pri každej vizualizácii uveď:
- názov grafu,
- typ grafu,
- údaje na osi X,
- údaje na osi Y,
- prípadné skupiny alebo filtre,
- otázku, na ktorú graf odpovedá,
- dôvod výberu daného typu grafu,
- možné riziko nesprávnej interpretácie.

Navrhni maximálne 7 vizualizácií.
Nevytváraj graf, ak naň údaje nie sú vhodné.
```

---

# 📽️ Práca s prezentáciami

## Prompt: kontrola obsahu prezentácie

```text
Analyzuj priloženú prezentáciu.

Pri každom slajde skontroluj:
- jasnosť názvu,
- množstvo textu,
- logiku obsahu,
- nadväznosť na predchádzajúci slajd,
- vhodnosť pre cieľovú skupinu,
- opakovanie informácií,
- chýbajúce vysvetlenia,
- možné faktické nejasnosti,
- vhodnosť vizuálnych prvkov.

Výstup:
1. celkové hodnotenie,
2. tabuľka pripomienok ku každému slajdu,
3. návrhy na skrátenie,
4. návrhy na doplnenie,
5. odporúčané poradie slajdov,
6. odhadované trvanie prezentácie.
```

---

## Prompt: premena prezentácie na scenár videa

```text
Premeň priloženú prezentáciu na scenár vzdelávacieho videa.

Parametre:
- cieľová skupina: [cieľová skupina],
- maximálna dĺžka: [počet minút] minút,
- tón: odborný a zrozumiteľný,
- jazyk: slovenčina.

Pri každom slajde priprav:
1. názov témy,
2. hlavné vysvetlenie,
3. praktický príklad,
4. upozornenie na častú chybu,
5. prechod na ďalšiu časť,
6. odhadovaný čas.

Na konci:
- spočítaj celkové trvanie,
- označ slajdy, ktoré treba skrátiť,
- navrhni záverečné zhrnutie.
```

---

## Prompt: premena prezentácie na dokument

```text
Premeň priloženú prezentáciu na súvislý odborný dokument.

Cieľová skupina:
[cieľová skupina]

Požiadavky:
- zachovaj logické poradie tém,
- rozviň stručné body do úplných viet,
- doplň prechody medzi kapitolami,
- zachovaj odbornú terminológiu,
- nevytváraj nové fakty,
- označ miesta, kde prezentácia neposkytuje dostatok informácií.

Výstup:
1. názov dokumentu,
2. úvod,
3. kapitoly a podkapitoly,
4. praktické príklady,
5. záver,
6. zoznam chýbajúcich podkladov.
```

---

# 🔄 Kombinovanie viacerých súborov

## Prompt: porovnanie dvoch dokumentov

```text
Porovnaj priložený dokument A a dokument B.

Zameraj sa na:
- účel,
- cieľovú skupinu,
- rozsah,
- štruktúru,
- hlavné tvrdenia,
- rozdiely,
- protirečenia,
- chýbajúce informácie,
- praktické dôsledky.

Výstup:
1. stručné zhrnutie dokumentu A,
2. stručné zhrnutie dokumentu B,
3. porovnávacia tabuľka,
4. 10 najdôležitejších rozdielov,
5. rozpory,
6. chýbajúce informácie,
7. odporúčanie podľa účelu [účel].

Pri každom zistení uveď, z ktorého dokumentu pochádza.
Nevytváraj tvrdenia, ktoré sa nenachádzajú v žiadnom dokumente.
```

---

## Prompt: syntéza viacerých zdrojov

```text
Analyzuj všetky priložené súbory a vytvor spoločnú syntézu.

Cieľ:
[cieľ analýzy]

Postup:
1. samostatne identifikuj obsah každého súboru,
2. vytvor krátke zhrnutie každého súboru,
3. nájdi spoločné témy,
4. identifikuj rozdiely,
5. označ rozpory,
6. spoj dopĺňajúce sa informácie,
7. označ chýbajúce údaje.

Výstup:
1. zoznam analyzovaných súborov,
2. hlavné zistenia,
3. porovnávacia tabuľka,
4. rozpory medzi súbormi,
5. spoločné závery,
6. odporúčania,
7. informácie na manuálne overenie.

Nevytváraj tvrdenia, ktoré sa nenachádzajú v žiadnom súbore.
```

---

## Prompt: spojenie PDF, tabuľky a obrázka

```text
Analyzuj všetky priložené súbory:

- dokument: [názov PDF],
- tabuľka: [názov XLSX alebo CSV],
- obrázok: [názov obrázka].

Cieľ analýzy:
[cieľ]

Postupuj v tomto poradí:

1. Identifikuj typ a obsah každého súboru.
2. Zhrň hlavné informácie z dokumentu.
3. Z tabuľky vyber najdôležitejšie údaje a trendy.
4. Navrhni tri vhodné vizualizácie.
5. Opíš relevantný obsah obrázka.
6. Prepoj informácie zo všetkých troch zdrojov.
7. Označ rozpory a chýbajúce informácie.
8. Vytvor praktické odporúčania.

Výstup:
1. exekutívne zhrnutie,
2. samostatná analýza každého súboru,
3. spoločné zistenia,
4. tabuľka kľúčových údajov,
5. návrhy vizualizácií,
6. riziká a obmedzenia,
7. odporúčané kroky,
8. osnova prezentácie do 10 slajdov,
9. kontrolný zoznam.

Pravidlá:
- nevymýšľaj chýbajúce informácie,
- jasne označ predpoklady,
- pri dokumente uvádzaj strany alebo sekcie,
- pri tabuľke uvádzaj názvy stĺpcov,
- pri obrázku neopisuj obsah, ktorý nie je viditeľný,
- oddeľ fakty od interpretácií.
```

---

# 🛡️ Bezpečnosť a ochrana údajov

Pred nahratím súboru skontrolujeme, či neobsahuje údaje, ktoré do ChatGPT nesmieme vložiť. Pri firemných, školských alebo klientskych dokumentoch sa riadime internými pravidlami organizácie a platnými pravidlami ochrany údajov.

Nenahrávame najmä:

- heslá,
- prístupové tokeny,
- prihlasovacie údaje,
- čísla platobných kariet,
- zdravotné údaje bez oprávnenia,
- osobné identifikačné čísla,
- obchodné tajomstvá,
- dôverné zmluvy,
- údaje klientov bez súhlasu alebo oprávnenia,
- interné informácie, ktoré nesmieme zdieľať.

---

## Prompt: kontrola citlivých údajov

```text
Skontroluj priložený dokument a identifikuj možné citlivé údaje.

Hľadaj:
- osobné údaje,
- kontaktné údaje,
- finančné údaje,
- prihlasovacie údaje,
- identifikačné čísla,
- zdravotné údaje,
- dôverné firemné informácie,
- obchodné tajomstvá.

Výstup priprav v tabuľke:
- typ citlivého údaja,
- miesto v dokumente,
- úroveň rizika,
- odporúčaná anonymizácia.

Nevypisuj celé citlivé hodnoty.
Zobraz iba maskovanú podobu.
```

---

# ✅ Kontrolný zoznam pred prácou so súborom

Pred odoslaním promptu si overíme:

- [ ] Pripojili sme správny súbor.
- [ ] Súbor nie je poškodený.
- [ ] Používame aktuálnu verziu dokumentu.
- [ ] Dokument neobsahuje nepovolené citlivé údaje.
- [ ] Jasne sme definovali cieľ úlohy.
- [ ] Určili sme požadovaný formát výstupu.
- [ ] Uviedli sme, či má ChatGPT pracovať iba so súborom.
- [ ] Požiadali sme o označenie chýbajúcich informácií.
- [ ] Požiadali sme o uvedenie strán alebo častí dokumentu.
- [ ] Pri tabuľke sme vysvetlili nejasné stĺpce.
- [ ] Pri obrázku sme uviedli, čo sa má zachovať.
- [ ] Výsledok pred použitím manuálne skontrolujeme.

---

# 🧪 Záverečné praktické cvičenie

## Zadanie

Pripravíme kompletný pracovný postup z jedného PDF dokumentu, jednej tabuľky XLSX alebo CSV a jedného obrázka.

### Vstupy

- jeden PDF dokument,
- jedna tabuľka XLSX alebo CSV,
- jeden obrázok.

### Požadované výstupy

1. zhrnutie PDF,
2. extrakcia kľúčových údajov,
3. analýza tabuľky,
4. návrh troch grafov,
5. analýza obrázka,
6. spoločná syntéza všetkých súborov,
7. návrh prezentácie,
8. kontrolný zoznam ďalších krokov.

### Superprompt

```text
Analyzuj všetky priložené súbory:

- PDF dokument: [názov dokumentu],
- tabuľka: [názov tabuľky],
- obrázok: [názov obrázka].

Cieľ:
[cieľ analýzy]

Cieľová skupina výstupu:
[cieľová skupina]

Postup:

1. Identifikuj každý súbor a opíš jeho účel.
2. Vytvor stručné zhrnutie PDF dokumentu.
3. Z PDF vyber kľúčové pojmy, čísla, dátumy, závery a riziká.
4. Skontroluj štruktúru tabuľky, dátové typy, duplicity a chýbajúce hodnoty.
5. Z tabuľky identifikuj hlavné trendy a odchýlky.
6. Navrhni tri vhodné vizualizácie.
7. Opíš iba viditeľný a relevantný obsah obrázka.
8. Prepoj informácie zo všetkých troch zdrojov.
9. Označ rozpory, neistoty a chýbajúce údaje.
10. Vytvor praktické odporúčania.

Výstup priprav v štruktúre:
1. exekutívne zhrnutie,
2. identifikácia súborov,
3. analýza PDF,
4. analýza tabuľky,
5. analýza obrázka,
6. spoločné zistenia,
7. tabuľka kľúčových údajov,
8. návrhy grafov,
9. rozpory a chýbajúce informácie,
10. odporúčané kroky,
11. osnova prezentácie do 10 slajdov,
12. kontrolný zoznam.

Pravidlá:
- nevymýšľaj chýbajúce informácie,
- jasne označ predpoklady,
- oddeľ fakty od interpretácií,
- pri PDF uvádzaj strany alebo sekcie,
- pri tabuľke uvádzaj názvy stĺpcov,
- pri obrázku neopisuj nič, čo nie je viditeľné,
- upozorni na všetky obmedzenia analýzy.
```

---

# 🧠 Kľúčové poznatky

Knižnica nám umožňuje dlhodobo uchovávať a opakovane používať pracovné súbory. Časť Obrázky slúži na vytváranie, správu a úpravu vizuálneho obsahu. Nahrávanie súborov umožňuje vykonávať syntézu, transformáciu a extrakciu informácií.

Najlepší výsledok dosiahneme, keď:

- použijeme správny a aktuálny súbor,
- jasne definujeme cieľ,
- určíme požadovaný formát výstupu,
- požiadame o označenie neistôt,
- nevymýšľame chýbajúce informácie,
- oddeľujeme fakty od interpretácií,
- manuálne kontrolujeme výsledok,
- nenahrávame nepovolené citlivé údaje.

---

## ✅ Čo by sme mali vedieť po dokončení cvičenia

Po dokončení cvičenia dokážeme:

- orientovať sa v Knižnici,
- vyhľadať a filtrovať súbory,
- opakovane použiť uložený dokument,
- pripraviť kvalitný prompt na obrázok,
- upraviť existujúci obrázok bez neželaných zmien,
- pracovať s PDF, Word, Excel, CSV a PowerPoint súbormi,
- rozlíšiť syntézu, transformáciu a extrakciu,
- porovnať viacero dokumentov,
- vytvoriť syntézu viacerých zdrojov,
- identifikovať chýbajúce údaje a rozpory,
- kontrolovať citlivé údaje,
- pripraviť kompletný pracovný postup z viacerých súborov.
