# 🧪 Cvičenie 04: Projekty v AI ChatGPT

Toto cvičenie je zamerané na praktické používanie Projektov v ChatGPT pri dlhodobej, opakovanej a tímovej práci. Projekty používame na spoločné usporiadanie chatov, referenčných súborov, projektových inštrukcií, uložených výstupov a pracovného kontextu.

Prompty sú pripravené na rýchle skopírovanie. Používajú placeholdery v hranatých zátvorkách, napríklad `[názov projektu]`, `[cieľ]`, `[typické úlohy]`, `[zdroje]`, `[výstupy]`, `[členovia tímu]` alebo `[variant riešenia]`. Pred odoslaním promptu ich nahradíme konkrétnymi údajmi.

> Projekty, ich limity, dostupné nástroje a názvy ovládacích prvkov sa môžu meniť podľa tarify, pracovného priestoru, platformy a aktuálnej verzie ChatGPT. Pred školením alebo produkčným použitím ich overíme v rozhraní a v aktuálnej dokumentácii OpenAI.

---

## 🎯 Ciele cvičenia

Po absolvovaní cvičenia budeme vedieť:

- vysvetliť, čo sú Projekty v ChatGPT,
- rozhodnúť, kedy použijeme Projekt a kedy bežný chat,
- vytvoriť nový Projekt a vhodne ho pomenovať,
- navrhnúť organizačnú štruktúru projektu,
- rozdeliť prácu do samostatných projektových chatov,
- pridávať a spravovať projektové zdroje,
- ukladať dôležité odpovede ako projektové zdroje,
- vytvoriť projektové inštrukcie,
- rozlíšiť predvolenú a výhradne projektovú pamäť,
- presunúť existujúci chat do projektu,
- používať nástroje dostupné v projektoch,
- zdieľať projekt s ďalšími používateľmi,
- rozlíšiť roly vlastník, edit a chat,
- používať vetvenie konverzácií,
- zdieľať jeden chat bez sprístupnenia celého projektu,
- bezpečne opustiť alebo odstrániť projekt,
- rozlíšiť Projekt a vlastné GPT,
- vytvoriť opakovateľný pracovný postup pre dlhodobú činnosť.

---

## 📁 Čo sú Projekty v ChatGPT

Projekty sú inteligentné pracovné priestory pre dlhodobejšiu činnosť. Udržiavajú súvisiace chaty, súbory, vlastné pokyny a pracovný kontext na jednom mieste.

Projekt nám pomáha zachovať kontinuitu práce. Namiesto jedného veľmi dlhého chatu môžeme vytvoriť viac samostatných konverzácií, ktoré používajú spoločné zdroje a projektové inštrukcie.

### Základné prvky projektu

| Prvok | Účel |
|---|---|
| Chaty | Samostatné pracovné konverzácie venované konkrétnym úlohám |
| Projektové zdroje | Súbory, texty, odkazy z aplikácií a uložené odpovede |
| Projektové inštrukcie | Pravidlá, podľa ktorých má ChatGPT v projekte pracovať |
| Projektová pamäť | Kontext založený na chatoch a súboroch projektu |
| Nástroje | Canvas, obrázky, webové vyhľadávanie, Deep Research a ďalšie dostupné funkcie |
| Spolupráca | Zdieľanie projektu, prístupové roly a samostatné chaty členov |

### Základný pracovný princíp

```text
CIEĽ → PROJEKT → ZDROJE → INŠTRUKCIE → CHATY → VÝSTUPY → KONTROLA
```

---

## ⚖️ Projekt alebo bežný chat

Projekt používame najmä vtedy, keď potrebujeme udržiavať spoločný kontext, opakovane používať rovnaké zdroje a pokračovať vo viacerých súvisiacich chatoch.

| Kritérium | Bežný chat | Projekt |
|---|---|---|
| Trvanie | Jednorazová alebo krátka úloha | Opakovaná alebo dlhodobá činnosť |
| Kontext | Jeden chat a jeho prílohy | Viac chatov, spoločné zdroje a inštrukcie |
| Organizácia | Jedno vlákno | Samostatné tematické chaty |
| Opakovateľnosť | Obmedzená | Vhodná pre pravidelné workflow |
| Spolupráca | Zdieľanie jednotlivého chatu | Spoločný pracovný priestor s rolami |
| Pamäť | Kontext konkrétnej konverzácie | Projektový kontext naprieč chatmi a súbormi |

### Vhodné pracovné projekty

#### 💼 Marketingová kampaň

Uvedenie nového kurzu alebo služby na trh. Projekt môže obsahovať marketingový brief, cieľové skupiny, obsahový plán, harmonogram, rozpočet, komunikačné výstupy a vyhodnotenie kampane.

#### 📊 Projektový manažment

Implementácia nového interného systému. Projekt môže obsahovať projektový plán, míľniky, úlohy, zodpovednosti, riziká, zápisnice, zmenové požiadavky a pravidelné stavové reporty.

#### 💶 Dotácie a granty

Príprava žiadosti o finančný príspevok. Projekt môže obsahovať podmienky výzvy, oprávnenosť žiadateľa, aktivity, rozpočet, prílohy, termíny, pracovné verzie žiadosti a kontrolný zoznam.

---

## 🧪 Cvičenie 1: Posúdenie vhodnosti projektu

### Zadanie

Vyberieme jednu pracovnú činnosť a posúdime, či je vhodné spracovať ju ako Projekt v ChatGPT.

### Prompt: posúdenie vhodnosti projektu

```text
Posúď, či je nasledujúca činnosť vhodná pre Projekt v ChatGPT.

Činnosť: [opis činnosti]
Trvanie: [jednorazová / opakovaná / dlhodobá]
Vstupy: [súbory, odkazy, poznámky]
Očakávané výstupy: [výstupy]
Počet používateľov: [jeden používateľ / tím]

Vyhodnoť:
1. potrebu spoločného kontextu,
2. potrebu viacerých samostatných chatov,
3. potrebu projektových inštrukcií,
4. potrebu opakovaného používania zdrojov,
5. potrebu zdieľania a rolí,
6. odporúčanie: Projekt alebo bežný chat.

Odpoveď priprav v krátkej tabuľke.
Na konci uveď jednoznačné odporúčanie a dôvod.
```

---

## 🆕 Vytvorenie prvého projektu

Pri vytvorení projektu postupujeme v troch základných krokoch:

1. V bočnom paneli vyberieme možnosť **New project** alebo **Nový projekt**.
2. Zadáme stručný a jednoznačný názov projektu.
3. Vyberieme ikonu a farbu na rýchle vizuálne rozlíšenie.

Pri vytváraní projektu môžeme podľa dostupnosti zvoliť aj režim projektovej pamäte. Výber výhradne projektovej pamäte môže byť trvalý, preto ho posúdime ešte pred vytvorením projektu.

### Pravidlá pomenovania projektu

Dobrý názov projektu:

- jednoznačne označuje tému,
- odlišuje projekt od ostatných projektov,
- neobsahuje zbytočné všeobecné slová,
- môže obsahovať obdobie, klienta alebo fázu,
- neobsahuje citlivé údaje, ktoré nemajú byť viditeľné v bočnom paneli.

### Príklady názvov

| Nevhodný názov | Vhodnejší názov |
|---|---|
| Projekt | Implementácia CRM 2026 |
| Marketing | Kampaň Kurz ChatGPT Q4 2026 |
| Grant | Žiadosť Výzva 3792 |
| Klient | Klient ABC - obchodná príležitosť |
| Dokumenty | Interná smernica AI - revízia |

---

## 🧪 Cvičenie 2: Návrh organizačnej štruktúry

### Prompt: organizačná štruktúra projektu

```text
Navrhni organizačnú štruktúru Projektu v ChatGPT.

Téma: [téma]
Hlavný cieľ: [cieľ]
Trvanie: [obdobie]
Používatelia: [ja / tím]
Typické vstupy: [súbory, poznámky, odkazy]
Očakávané výstupy: [výstupy]

Navrhni:
- stručný názov projektu,
- vhodnú ikonu alebo kategóriu,
- odporúčané samostatné chaty,
- jednotné pomenovanie chatov,
- zdroje, ktoré máme pridať,
- výstupy vhodné na uloženie ako projektové zdroje,
- odporúčaný režim pamäte,
- základné pravidlá organizácie.

Nevytváraj samotný obsah projektu.
Výstup priprav ako implementačný plán.
```

### Odporúčané pomenovanie chatov

```text
01_Zadanie_a_ciele
02_Zdroje_a_analyza
03_Plan_a_harmonogram
04_Rizika_a_rozhodnutia
05_Pracovne_vystupy
06_Kontrola_kvality
07_Zaverecne_zhrnutie
```

---

## 📚 Projektové zdroje

Projektové zdroje poskytujú ChatGPT referenčný materiál pre prácu v projekte. Zdrojom môže byť:

- nahratý súbor,
- vložený text,
- podporovaný odkaz z pripojenej aplikácie,
- odpoveď uložená z projektového chatu.

### Typy projektových zdrojov

| Typ zdroja | Príklad | Vhodné použitie |
|---|---|---|
| PDF | výzva, metodika, správa | analýza pravidiel, podmienok a požiadaviek |
| Dokument | smernica, zmluva, projektový zámer | úprava, porovnanie a kontrola textu |
| Tabuľka | rozpočet, harmonogram, register rizík | výpočty, kontrola a sumarizácia |
| Obrázok | diagram, návrh, snímka obrazovky | interpretácia vizuálneho obsahu |
| Vložený text | poznámky, zápisnica, zadanie | rýchle doplnenie kontextu |
| Odkaz z aplikácie | Google Drive alebo Slack | použitie externého pracovného zdroja |
| Uložená odpoveď | rozhodnutie, zhrnutie, analýza | opakované použitie overeného výstupu |

### Dôležité pravidlá

- Do projektu pridávame iba relevantné a aktuálne zdroje.
- Pri každom zdroji evidujeme jeho pôvod, dátum a účel.
- Staré verzie dokumentov zreteľne označujeme.
- Dôležité odpovede môžeme uložiť pomocou funkcie **Save to project**.
- V zdieľanom projekte odstránenie súboru odstráni zdroj pre všetkých členov.
- Členovia zdieľaného projektu môžu vidieť a sťahovať pridané súbory.

---

## 🧪 Cvičenie 3: Katalóg projektových zdrojov

### Prompt: katalóg zdrojov

```text
Na základe zdrojov dostupných v tomto projekte vytvor katalóg.

Pri každom zdroji uveď:
- názov alebo identifikátor,
- typ zdroja,
- dátum alebo verziu, ak sú dostupné,
- hlavnú tému,
- na aké úlohy je vhodný,
- možné prekrytie s iným zdrojom,
- či môže byť zastaraný,
- otázky, ktoré z neho vieme zodpovedať,
- obmedzenia zdroja.

Výstup priprav v tabuľke.
Nevytváraj fakty, ktoré v zdrojoch nie sú.
Ak zdroj nevieme jednoznačne identifikovať, označ ho na manuálnu kontrolu.
```

---

## 🧪 Cvičenie 4: Záznam rozhodnutia

Dôležité projektové rozhodnutia uložíme ako samostatný zdroj. Získame tak opakovateľný a kontrolovateľný záznam, ku ktorému sa môžu vrátiť ďalšie chaty aj členovia tímu.

### Prompt: záznam rozhodnutia

```text
Zhrň doterajšiu diskusiu do záznamu rozhodnutia.

Použi štruktúru:
- názov rozhodnutia,
- dátum,
- riešený problém,
- posudzované možnosti,
- kritériá rozhodovania,
- prijaté rozhodnutie,
- dôvody rozhodnutia,
- zamietnuté možnosti a dôvody,
- otvorené otázky,
- zodpovednosti,
- ďalšie kroky a termíny.

Použi iba informácie z tohto chatu a projektových zdrojov.
Oddeľ potvrdené údaje od predpokladov.
Chýbajúce informácie nevymýšľaj.
```

---

## 📦 Limity súborov

Počet súborov v projekte závisí od plánu vlastníka projektu. V prezentácii sú uvedené tieto limity:

| Plán vlastníka | Súbory na projekt | Maximálny počet spolupracovníkov |
|---|---:|---:|
| Free | 5 | 5 |
| Go / Plus | 25 | 10 |
| Pro / Business | 40 | 100 |

Používatelia môžu podľa prezentácie vytvárať neobmedzený počet projektov. Pri dosiahnutí limitu môžeme:

- odstrániť nepotrebné alebo zastarané súbory,
- zlúčiť údaje do jedného riadeného dokumentu,
- rozdeliť prácu do viacerých projektov,
- uložiť dôležité zhrnutie namiesto viacerých duplicitných zdrojov.

> Prezentácia obsahuje rozdielne ukážky limitu jednorazového nahrávania súborov. Presný aktuálny limit preto overíme priamo v rozhraní ChatGPT. Limit počtu súborov v projekte a limit súborov nahraných v jednom kroku nie sú totožné obmedzenia.

### Prompt: optimalizácia projektových zdrojov

```text
Posúď aktuálnu zostavu projektových zdrojov a navrhni optimalizáciu.

Cieľ projektu: [cieľ]
Aktuálne zdroje: [zoznam alebo katalóg]
Limit súborov: [limit]

Identifikuj:
- duplicitné zdroje,
- zastarané verzie,
- zdroje s nízkou pridanou hodnotou,
- zdroje vhodné na zlúčenie,
- dôležité zdroje, ktoré chýbajú,
- zdroje, ktoré nesmieme odstrániť.

Výstup priprav v tabuľke:
- zdroj,
- odporúčanie ponechať / nahradiť / zlúčiť / odstrániť,
- dôvod,
- riziko odstránenia,
- navrhovaná náhrada.
```

---

## ⚙️ Projektové inštrukcie

Projektové inštrukcie definujú, ako má ChatGPT odpovedať a pracovať v konkrétnom projekte. Pridávame ich cez nastavenia projektu.

Projektové inštrukcie:

- platia iba v danom projekte,
- majú prednosť pred globálnymi vlastnými inštrukciami používateľa,
- používajú sa vo všetkých chatoch projektu,
- môžu určiť rolu, štýl, formát, pravidlá práce so zdrojmi a kontrolu kvality.

### Základné časti inštrukcií

| Časť | Účel | Príklad |
|---|---|---|
| Rola | Určí spôsob pomoci | Správaj sa ako projektový analytik. |
| Zdroje | Určí, z čoho má model vychádzať | Pracuj prednostne s projektovými zdrojmi. |
| Štýl | Nastaví jazyk, stručnosť a tón | Odpovedaj po slovensky, vecne a prakticky. |
| Formát | Určí podobu výstupu | Používaj tabuľky, kontrolné zoznamy a krátke odseky. |
| Interakcia | Určí prácu s nejasnosťami | Pri nejasnostiach polož presnú doplňujúcu otázku. |
| Kontrola kvality | Určí povinné overenie | Oddeľ fakty, predpoklady a odporúčania. |

---

## 🧪 Cvičenie 5: Návrh projektových inštrukcií

### Prompt: projektové inštrukcie

```text
Priprav návrh projektových inštrukcií.

Názov projektu: [názov]
Hlavný cieľ: [cieľ]
Typické úlohy: [úlohy]
Cieľová skupina výstupov: [skupina]
Používané zdroje: [zdroje]
Požadovaný štýl: [štýl]
Riziká: [riziká]

Pokyny rozdeľ na:
1. rolu ChatGPT,
2. pravidlá práce so zdrojmi,
3. požadovaný formát odpovedí,
4. prácu s nejasnosťami,
5. pravidlá kontroly kvality,
6. ochranu citlivých údajov,
7. zakázané domnienky alebo výpočty.

Výsledok napíš ako krátky blok pripravený na vloženie do Nastavení projektu.
```

---

## 💼 Príklad projektových pokynov pre obchodníka

```text
1. V tomto projekte spracúvaj obchodné príležitosti, klientsku komunikáciu, ponuky, stretnutia a následné kroky.
2. Vychádzaj prednostne zo súborov, chatov a informácií uložených v tomto projekte.
3. Pred vytvorením výstupu identifikuj klienta, jeho potreby, cieľ komunikácie a fázu obchodného prípadu.
4. Oddeľuj potvrdené fakty, predpoklady, otvorené otázky a odporúčané kroky.
5. Nevymýšľaj ceny, zľavy, termíny, funkcionality, referencie ani obchodné podmienky.
6. Obchodné e-maily píš stručne, profesionálne a s jasnou výzvou na ďalší krok.
7. Zo stretnutí vytváraj prehľad potrieb klienta, námietok, rozhodnutí, úloh, termínov a zodpovedností.
8. Pri každej obchodnej príležitosti navrhni ďalší krok, termín kontaktu a potrebné podklady.
9. Ak chýba dôležitá informácia, polož konkrétnu doplňujúcu otázku a nepracuj s domnienkou.
10. Chráň osobné a dôverné údaje klientov a nezobrazuj citlivé identifikátory ani prístupové údaje.
```

---

## 📊 Príklad projektových pokynov pre projektového manažéra

```text
1. V tomto projekte spracúvaj plánovanie, harmonogram, úlohy, míľniky, riziká, zmeny, zápisnice a stavové reporty.
2. Vychádzaj prednostne zo súborov, chatov a informácií uložených v tomto projekte.
3. Pred spracovaním identifikuj cieľ, rozsah, výstupy, termíny, rozpočet a zainteresované osoby.
4. Oddeľuj potvrdené údaje, predpoklady, otvorené otázky, rozhodnutia a odporúčania.
5. Nevymýšľaj termíny, rozpočty, zodpovednosti, stav úloh ani percento dokončenia.
6. Každú úlohu formuluj s názvom, zodpovednou osobou, termínom, prioritou, stavom a očakávaným výstupom.
7. Pri rizikách uvádzaj opis, pravdepodobnosť, dopad, úroveň rizika, vlastníka a navrhované opatrenie.
8. Upozorni na nejasný rozsah, chýbajúcu zodpovednosť, konfliktné závislosti a nereálne termíny.
9. Stavové reporty štruktúruj na celkový stav, dokončené úlohy, prebiehajúce úlohy, problémy, riziká, rozhodnutia a ďalšie kroky.
10. Návrhy označuj ako pracovné podklady, pokiaľ v projektových zdrojoch nie sú výslovne uvedené ako schválené.
```

---

## 🧠 Projektová pamäť

Projektová pamäť umožňuje ChatGPT nadviazať na predchádzajúcu prácu a zostať zameraný na projektový kontext.

### Predvolená pamäť

Pri predvolenej pamäti sa môžu používať uložené osobné pamäte. Použitie chatov mimo projektu závisí od plánu a nastavení. Tento režim je vhodný, keď chceme projekt prepojiť s bežnou personalizáciou.

### Výhradne projektová pamäť

Pri výhradne projektovej pamäti:

- osobné pamäte sa nepoužívajú,
- chaty môžu odkazovať iba na konverzácie v rovnakom projekte,
- projekt je oddelený od osobného kontextu,
- režim je vhodný pre jasné hranice a tímovú spoluprácu.

### Dôležité pravidlá

- Predtým uložené osobné pamäte sa vo výhradne projektovom režime nepoužívajú.
- Po zdieľaní projektu sa pamäť podľa prezentácie automaticky nastaví na výhradne projektovú.
- Zdieľaný projekt nemá prístup k osobnej pamäti členov mimo projektu.
- Projektová pamäť nezobrazuje samostatný zoznam zapamätaných položiek.
- Ak nechceme, aby ChatGPT používal konkrétnu konverzáciu, musíme ju odstrániť alebo presunúť.

---

## 🧪 Cvičenie 6: Rozhodovacia matica pamäte

### Prompt: výber pamäte

```text
Posúď, či má projekt používať predvolenú alebo výhradne projektovú pamäť.

Projekt: [opis projektu]
Používatelia: [ja / tím]
Citlivosť obsahu: [nízka / stredná / vysoká]
Potreba osobnej personalizácie: [áno / nie]
Potreba oddelenia od ostatných chatov: [áno / nie]
Potreba zdieľania: [áno / nie]
Dlhodobosť projektu: [krátkodobý / dlhodobý]

Porovnaj oba režimy podľa:
- dostupného kontextu,
- súkromia,
- rizika miešania informácií,
- tímovej spolupráce,
- možnosti neskoršej zmeny.

Výstup priprav v rozhodovacej tabuľke.
Na konci uveď jednoznačné odporúčanie.
```

---

## 🔄 Presúvanie a organizácia chatov

Existujúci chat môžeme presunúť do projektu:

- potiahnutím chatu na projekt v bočnom paneli,
- cez ponuku chatu a možnosť **Move to project**.

Presunutý chat zdedí projektové inštrukcie a kontext projektových súborov.

### Obmedzenia a odporúčania

- Chat vytvorený s vlastným GPT nemožno podľa prezentácie presunúť do projektu.
- Starší chat nájdeme pomocou vyhľadávania chatov.
- Ak sa možnosť **Move to project** nezobrazuje, vytvoríme nový chat priamo v projekte.
- Pred presunom skontrolujeme, či pôvodný chat neobsahuje informácie, ktoré do projektu nepatria.

### Prompt: posúdenie presunu chatu

```text
Posúď, či je vhodné presunúť nasledujúci chat do projektu.

Projekt: [názov a cieľ projektu]
Obsah chatu: [stručný opis]
Citlivé údaje: [áno / nie / nejasné]
Použité zdroje: [zdroje]
Očakávané ďalšie použitie: [použitie]

Vyhodnoť:
- tematický súlad,
- prínos pre projektový kontext,
- riziko neželaného miešania informácií,
- riziko sprístupnenia členom projektu,
- potrebu anonymizácie alebo vyčistenia chatu.

Výstup:
1. odporúčanie presunúť / nepresunúť,
2. dôvod,
3. potrebné úpravy pred presunom.
```

---

## 🛠️ Nástroje dostupné v projektoch

Dostupnosť nástrojov závisí od plánu, pracovného priestoru a administrátorských nastavení.

| Nástroj | Použitie v projekte |
|---|---|
| Canvas | Tvorba a úprava dokumentov alebo kódu |
| Generovanie obrázkov | Návrh vizuálnych nápadov a podkladov |
| Študijný režim | Interaktívne otázky a overovanie porozumenia |
| Hlasový režim | Konverzácia bez klávesnice |
| Webové vyhľadávanie | Aktuálne informácie s citáciami |
| Deep Research | Rozsiahlejší výskum vo vybraných plánoch |

Ak administrátor nástroj vypne, nebude dostupný ani v projektoch daného pracovného priestoru.

---

## 🧪 Cvičenie 7: Výber nástroja pre projektovú úlohu

### Prompt: odporúčanie nástroja

```text
Vyber najvhodnejší nástroj ChatGPT pre nasledujúcu projektovú úlohu.

Úloha: [opis úlohy]
Požadovaný výstup: [výstup]
Potreba aktuálnych údajov: [áno / nie]
Potreba vizuálneho výstupu: [áno / nie]
Potreba práce s dokumentom alebo kódom: [áno / nie]
Rozsah výskumu: [malý / stredný / veľký]

Posúď použitie:
- bežného chatu,
- Canvas,
- webového vyhľadávania,
- Deep Research,
- generovania obrázkov,
- hlasového režimu.

Výstup priprav v tabuľke:
- nástroj,
- vhodnosť,
- dôvod,
- obmedzenia,
- odporúčaný postup.
```

---

## 👥 Zdieľané projekty

Projekt môžeme zdieľať:

- pozvaním konkrétnej osoby e-mailom,
- pozvaním skupiny v podporovanom pracovnom priestore,
- zdieľateľným odkazom podľa dostupného nastavenia.

Pri zdieľaní projektu kontrolujeme:

- kto môže projekt otvoriť,
- akú rolu dostane každý člen,
- aké súbory a chaty budú viditeľné,
- či projekt obsahuje dôverné alebo osobné údaje,
- či má projekt vhodne oddelenú pamäť.

### Prístupové roly

| Rola | Môže | Nemôže alebo typické obmedzenie |
|---|---|---|
| Vlastník | Spravovať projekt vrátane jeho odstránenia | Vlastník nesie zodpovednosť za projekt a prístup |
| Edit | Meniť inštrukcie, pridávať a upravovať súbory, pozývať členov | Nemusí mať oprávnenie odstrániť existujúcich členov |
| Chat | Vidieť a používať chaty, súbory a inštrukcie | Nemôže pozývať ďalších členov ani meniť nastavenia |

Používateľom prideľujeme najnižšiu rolu, ktorá postačuje na ich úlohu.

---

## 🧪 Cvičenie 8: Návrh prístupových rolí

### Prompt: matica prístupov

```text
Navrhni prístupové roly pre zdieľaný Projekt v ChatGPT.

Projekt: [názov a cieľ]
Členovia tímu: [zoznam rolí alebo osôb]
Typy údajov: [verejné / interné / dôverné]
Typické činnosti členov: [činnosti]

Pre každého člena odporuč rolu:
- vlastník,
- edit,
- chat,
- bez prístupu.

Pri každom odporúčaní uveď:
- potrebné oprávnenia,
- nepotrebné oprávnenia,
- hlavné riziko,
- odporúčané obmedzenie,
- potrebu pravidelnej kontroly prístupu.

Použi princíp najnižších potrebných oprávnení.
Výstup priprav v tabuľke.
```

---

## 👁️ Viditeľnosť obsahu v zdieľanom projekte

Pri tímovej práci platia tieto pravidlá:

- členovia môžu vidieť a sťahovať súbory pridané do projektu,
- chat môže byť spojený s profilovou ikonou autora,
- odpovede môžu využiť obsah pridaný iným členom,
- informácia pridaná jedným členom sa môže objaviť v odpovedi viditeľnej ostatným,
- členovia nepracujú súčasne v jednom chate ako v spoločnom editore dokumentu.

Pred pridaním súboru alebo správy preto počítame s tým, že obsah môže ovplyvniť ďalšie odpovede v projekte.

### Prompt: kontrola obsahu pred pridaním

```text
Skontroluj nasledujúci obsah pred pridaním do zdieľaného projektu.

Obsah: [text alebo opis súboru]
Projekt: [cieľ projektu]
Členovia: [typy používateľov]

Posúď:
- relevantnosť pre projekt,
- osobné údaje,
- dôverné údaje,
- interné názvy a identifikátory,
- riziko nesprávnej interpretácie,
- riziko použitia v odpovediach pre ostatných členov,
- potrebu anonymizácie,
- potrebu obmedziť prístup.

Výstup:
1. pridať bez úpravy,
2. pridať po úprave,
3. nepridávať,
4. presný zoznam potrebných úprav.
```

---

## 🌿 Vetvenie chatov

Vetvenie umožňuje pokračovať z existujúceho chatu novým smerom bez zmeny pôvodného vlákna. Vetvený chat sa zobrazí ako samostatná konverzácia a môže byť označený ako **Branch**.

Vetvenie používame napríklad pri:

- porovnávaní dvoch variantov riešenia,
- skúšaní alternatívneho harmonogramu,
- príprave viacerých verzií textu,
- hodnotení rozdielnych stratégií,
- rozdelení práce medzi členov tímu.

### Základný postup

1. Otvoríme existujúci chat.
2. Pri vybranej odpovedi otvoríme ponuku ďalších možností.
3. Zvolíme vetvenie v novom chate.
4. V novej vetve zadáme alternatívny smer.
5. Pôvodný chat zostane nezmenený.

---

## 🧪 Cvičenie 9: Porovnanie dvoch vetiev

### Prompt pre vetvu A

```text
Pokračuj z pôvodného chatu a rozpracuj variant A.

Variant A: [opis]

Zachovaj:
- pôvodný cieľ,
- potvrdené fakty,
- projektové inštrukcie,
- obmedzenia zo zdrojov.

Uveď:
- hlavné rozhodnutia,
- výhody,
- nevýhody,
- potrebné zdroje,
- náklady alebo náročnosť, ak sú známe,
- riziká,
- otvorené otázky.

Nemeň pôvodný chat a nevymýšľaj chýbajúce údaje.
```

### Prompt pre vetvu B

```text
Pokračuj z pôvodného chatu a rozpracuj variant B.

Variant B: [opis]

Použi rovnaké hodnotiace kritériá ako vo variante A.
Uveď:
- hlavné rozhodnutia,
- výhody,
- nevýhody,
- potrebné zdroje,
- náklady alebo náročnosť, ak sú známe,
- riziká,
- otvorené otázky.

Nemeň pôvodný chat a nevymýšľaj chýbajúce údaje.
```

### Prompt: porovnanie vetiev

```text
Porovnaj výsledky vetvy A a vetvy B.

Kritériá:
- súlad s cieľom projektu,
- náročnosť realizácie,
- potrebné zdroje,
- riziká,
- očakávané prínosy,
- otvorené otázky,
- reverzibilita rozhodnutia.

Výstup priprav v porovnávacej tabuľke.
Na konci uveď odporúčanie, ale jasne označ predpoklady a chýbajúce údaje.
```

---

## 🔗 Zdieľanie jedného chatu

Z osobného projektu môžeme zdieľať samostatný chat cez unikátny odkaz. Príjemca vidí iba daný chat, nie ostatné chaty, súbory, projektové inštrukcie ani celú históriu projektu.

Zdieľanie jedného chatu používame, keď:

- nechceme sprístupniť celý projekt,
- potrebujeme poslať konkrétny výsledok,
- príjemca nepotrebuje pokračovať v projektovej práci,
- obsah chatu neodhaľuje citlivý projektový kontext.

Pred zdieľaním skontrolujeme, či chat neobsahuje údaje prevzaté zo súborov alebo správ, ktoré nemá príjemca vidieť.

---

## 🧪 Cvičenie 10: Kontrola pred zdieľaním

### Prompt: audit zdieľaného chatu

```text
Skontroluj tento chat pred zdieľaním externému príjemcovi.

Príjemca: [typ príjemcu]
Účel zdieľania: [účel]

Identifikuj:
- osobné údaje,
- dôverné informácie,
- interné názvy,
- citácie alebo údaje prevzaté z projektových súborov,
- neoverené tvrdenia,
- otvorené interné diskusie,
- informácie, ktoré môžu byť vytrhnuté z kontextu.

Výstup:
1. bezpečné časti,
2. problematické časti,
3. odporúčané odstránenia alebo anonymizácia,
4. konečné rozhodnutie: zdieľať / zdieľať po úprave / nezdieľať.
```

---

## 🚪 Odchod zo zdieľaného projektu

Člen môže zdieľaný projekt opustiť cez bočný panel. Pred odchodom môže podľa dostupnej funkcie vytvoriť kópiu vlastných chatov. Kópie sa môžu presunúť do nového projektu s označením **Copy**.

Pred odchodom overíme:

- či potrebujeme vlastné chaty zachovať,
- či máme odovzdané úlohy a rozhodnutia,
- či sme odstránili osobný alebo nepotrebný obsah,
- či zmena členstva neovplyvní prebiehajúcu prácu.

---

## 🗑️ Mazanie projektu

Voľba **Delete project** natrvalo odstráni súbory, chaty a projektové inštrukcie. Akcia je nevratná a členovia stratia prístup k obsahu, ktorý si predtým neskopírovali.

Podľa prezentácie sa odstránené projekty, chaty a súbory zo systémov odstránia do 30 dní, ak ich OpenAI nemusí uchovať z právnych alebo bezpečnostných dôvodov.

### Kontrolný zoznam pred odstránením projektu

- [ ] Overili sme, že ide o správny projekt.
- [ ] Skontrolovali sme vlastníka projektu.
- [ ] Uložili sme potrebné výstupy.
- [ ] Rozhodli sme, ktoré chaty potrebujeme kopírovať.
- [ ] Exportovali sme potrebné rozhodnutia a dokumenty.
- [ ] Informovali sme členov projektu.
- [ ] Overili sme, že neexistuje aktívna úloha závislá od projektu.
- [ ] Rozumieme tomu, že odstránenie je nevratné.

---

## 🧪 Cvičenie 11: Plán ukončenia projektu

### Prompt: kontrola ukončenia

```text
Priprav plán bezpečného ukončenia Projektu v ChatGPT.

Projekt: [názov]
Dôvod ukončenia: [dôvod]
Členovia: [členovia]
Dôležité chaty: [zoznam]
Dôležité súbory: [zoznam]
Otvorené úlohy: [zoznam]

Navrhni:
1. čo musíme archivovať,
2. čo musíme exportovať,
3. čo musíme odovzdať členom,
4. ktoré rozhodnutia musíme zaznamenať,
5. ktoré riziká musíme uzavrieť,
6. koho musíme informovať,
7. kontrolný zoznam pred odstránením.

Nevykonávaj žiadne odstránenie.
```

---

## 🤖 Projekty verzus vlastné GPT

Projekty a vlastné GPT poskytujú dodatočný kontext, ale používame ich na odlišné účely.

| Kritérium | Vlastné GPT | Zdieľaný projekt |
|---|---|---|
| Hlavný účel | Opakovateľná vlastná verzia ChatGPT | Spoločný priestor pre priebežnú prácu |
| Charakter obsahu | Väčšinou stabilný a kurátorovaný | Priebežne sa vyvíja cez chaty a súbory |
| Spolupráca | Štandardizovaný spôsob používania | Viacerí členovia vidia projektový obsah |
| Škálovanie | Prenos pravidiel a znalostí | Zladenie tímu a onboarding |
| Typický príklad | Interný HR asistent | Projekt plánovania štvrtého kvartálu |

Vlastné GPT možno podľa prezentácie použiť v správach existujúceho projektového chatu. Ak však prvá správa vznikne s vlastným GPT, konverzácia sa môže zobraziť mimo projektu.

---

## 🧪 Cvičenie 12: Rozhodnutie Projekt alebo vlastné GPT

### Prompt: výber riešenia

```text
Posúď, či je pre nasledujúcu potrebu vhodnejší Projekt v ChatGPT alebo vlastné GPT.

Potreba: [opis]
Používatelia: [jeden používateľ / tím / organizácia]
Obsah: [stabilný / priebežne sa meniaci]
Zdroje: [zdroje]
Typické úlohy: [úlohy]
Potreba zdieľania priebežnej práce: [áno / nie]
Potreba jednotného správania naprieč úlohami: [áno / nie]

Porovnaj:
- hlavný účel,
- spôsob správy znalostí,
- spoluprácu,
- opakovateľnosť,
- správu zdrojov,
- riziká a obmedzenia.

Výstup priprav v tabuľke.
Na konci odporuč:
- Projekt,
- vlastné GPT,
- alebo kombináciu oboch.
```

---

## 🛡️ Údaje, trénovanie a administrátorské ovládanie

Podľa prezentácie sa pravidlá používania údajov líšia podľa typu účtu a nastavení.

| Typ účtu alebo projektu | Používanie údajov na zlepšovanie modelov |
|---|---|
| Business / Enterprise / Edu | Štandardne sa nepoužívajú |
| Free / Plus / Pro | Môžu sa použiť, ak je zapnuté príslušné nastavenie |
| Zdieľané projekty | Podľa prezentácie iba pri zapnutí príslušného nastavenia vlastníkmi a prispievateľmi |

Administrátori pracovného priestoru môžu riadiť:

- dostupnosť nástrojov,
- retenčné intervaly,
- dátovú rezidenciu,
- nastavenia pamäte,
- prístupové roly,
- bezpečnostné a auditné pravidlá.

Projekty používajú rovnaké základné bezpečnostné mechanizmy ako štandardné chaty, napríklad šifrovanie, prístupové riadenie a auditné logovanie podľa typu pracovného priestoru.

---

# 💼 Praktické projektové workflow

## Workflow 1: Týždenný výskum

Každý týždeň pridáme nové zdroje, vytvoríme samostatný výskumný chat, porovnáme nové zistenia s predchádzajúcim obdobím a záverečné zhrnutie uložíme ako projektový zdroj.

### Prompt: týždenný výskumný report

```text
Priprav týždenný výskumný report na základe zdrojov pridaných do projektu od [dátum].

Téma: [téma]
Predchádzajúce zhrnutie: [názov zdroja alebo chatu]

Postup:
1. identifikuj nové zdroje,
2. zhrň nové zistenia,
3. porovnaj ich s predchádzajúcim zhrnutím,
4. označ zmeny, rozpory a nové riziká,
5. uveď, ktoré tvrdenia treba overiť,
6. navrhni ďalšie výskumné otázky,
7. priprav odporúčané ďalšie kroky.

Výstup:
- exekutívne zhrnutie,
- tabuľka nových zistení,
- zmeny oproti minulému obdobiu,
- otvorené otázky,
- odporúčané kroky.

Nevytváraj fakty, ktoré nie sú v zdrojoch.
```

---

## Workflow 2: Jednotný obsahový štýl

Do projektových inštrukcií vložíme pravidlá tónu, terminológie a formátu. Samostatný kontrolný chat použijeme na audit výstupov bez automatického prepisovania textu.

### Prompt: audit štýlu

```text
Skontroluj nasledujúci text podľa projektových inštrukcií a zdrojov.

Text:
[text]

Kontroluj:
- tón komunikácie,
- terminológiu,
- štruktúru,
- opakovanie,
- nejasné formulácie,
- rozpory so zdrojmi,
- neoverené tvrdenia,
- súlad s cieľovou skupinou.

Výstup priprav v tabuľke:
- miesto v texte,
- problém,
- pravidlo projektu,
- závažnosť,
- odporúčaná úprava.

Text zatiaľ neprepisuj.
```

---

## Workflow 3: Projektový manažment

Projekt rozdelíme na samostatné chaty pre zadanie, harmonogram, úlohy, riziká, zápisnice, rozhodnutia a reporting.

### Prompt: stavový report

```text
Priprav stavový report projektu na základe dostupných chatov a zdrojov.

Obdobie: [obdobie]
Dátum reportu: [dátum]

Štruktúra:
1. celkový stav projektu,
2. dokončené úlohy,
3. prebiehajúce úlohy,
4. oneskorené úlohy,
5. dosiahnuté míľniky,
6. problémy a blokátory,
7. riziká a opatrenia,
8. prijaté rozhodnutia,
9. otvorené otázky,
10. ďalšie kroky, zodpovednosti a termíny.

Pravidlá:
- nevymýšľaj stav úloh,
- neodhaduj percento dokončenia bez podkladu,
- označ chýbajúce údaje,
- oddeľ potvrdený stav od návrhov.
```

---

## Workflow 4: Dotácie a granty

Projekt môže obsahovať výzvu, príručky, oprávnenosť, rozpočet, harmonogram, prílohy, návrhy textov a kontrolný zoznam.

### Prompt: kontrola úplnosti žiadosti

```text
Skontroluj úplnosť pripravovanej žiadosti podľa projektových zdrojov.

Výzva alebo program: [názov]
Žiadateľ: [typ žiadateľa]
Projektový zámer: [stručný opis]

Skontroluj:
- oprávnenosť žiadateľa,
- oprávnenosť aktivít,
- oprávnenosť výdavkov,
- povinné prílohy,
- termíny,
- merateľné ukazovatele,
- súlad rozpočtu a aktivít,
- konzistentnosť názvov a čísel,
- otvorené otázky,
- chýbajúce podklady.

Výstup priprav ako kontrolný zoznam:
- požiadavka,
- zdroj a miesto v zdroji,
- stav splnenia,
- dôkaz,
- problém,
- odporúčaný krok.

Nevymýšľaj požiadavky, ktoré nie sú v projektových zdrojoch.
```

---

## Workflow 5: Interné vzdelávanie

Do projektu môžeme nahrať interné metodiky, školiteľské materiály a pracovné dokumenty. Samostatné chaty použijeme na plán učenia, otázky, precvičovanie a kontrolu výsledkov.

### Prompt: plán učenia podľa projektových zdrojov

```text
Vytvor plán interného vzdelávania podľa zdrojov v tomto projekte.

Cieľová skupina: [skupina]
Cieľ vzdelávania: [cieľ]
Časový rozsah: [rozsah]
Úroveň účastníkov: [začiatočník / mierne pokročilý / pokročilý]

Navrhni:
- tematické celky,
- logické poradie,
- odporúčané zdroje ku každej téme,
- praktické úlohy,
- kontrolné otázky,
- míľniky,
- záverečné overenie.

Označ témy, ktoré projektové zdroje nepokrývajú.
Nevymýšľaj chýbajúci odborný obsah.
```

---

# 🚀 Univerzálny superprompt pre návrh projektu

```text
Navrhni kompletný Projekt v ChatGPT pre nasledujúcu pracovnú činnosť.

Názov alebo téma:
[téma]

Hlavný cieľ:
[cieľ]

Trvanie:
[obdobie]

Používatelia:
[jeden používateľ / tím]

Typické vstupy:
[zdroje]

Očakávané výstupy:
[výstupy]

Citlivosť údajov:
[nízka / stredná / vysoká]

Navrhni:

### 1. Posúdenie vhodnosti
- prečo použiť Projekt alebo bežný chat,
- hlavné prínosy,
- hlavné riziká.

### 2. Základné nastavenie
- názov projektu,
- ikonu alebo kategóriu,
- odporúčaný režim pamäte.

### 3. Organizačnú štruktúru
- samostatné chaty,
- jednotné pomenovanie,
- účel každého chatu.

### 4. Projektové zdroje
- potrebné súbory,
- potrebné odkazy alebo texty,
- výstupy vhodné na uloženie cez Save to project,
- pravidlá verziovania.

### 5. Projektové inštrukcie
- rolu ChatGPT,
- prácu so zdrojmi,
- štýl a formát,
- prácu s nejasnosťami,
- kontrolu kvality,
- ochranu údajov.

### 6. Spoluprácu
- členov,
- odporúčané roly,
- pravidlá viditeľnosti,
- schvaľovanie výstupov.

### 7. Workflow
- opakované kroky,
- míľniky,
- rozhodovacie záznamy,
- kontrolné mechanizmy.

### 8. Riziká
- nesprávne zdroje,
- zastarané údaje,
- miešanie kontextu,
- nadmerné oprávnenia,
- nechcené zdieľanie,
- nevratné odstránenie.

Výstup priprav ako praktický implementačný plán.
Nevytváraj samotný obsah projektu ani chýbajúce fakty.
```

---

# ✅ Kontrolný zoznam projektu

## Pred vytvorením projektu

- [ ] Máme jasný cieľ projektu.
- [ ] Ide o dlhodobejšiu alebo opakovanú činnosť.
- [ ] Potrebujeme viac súvisiacich chatov.
- [ ] Poznáme typy vstupných zdrojov.
- [ ] Rozhodli sme o režime pamäte.
- [ ] Skontrolovali sme citlivosť údajov.
- [ ] Vieme, kto bude vlastníkom projektu.

## Po vytvorení projektu

- [ ] Projekt má jednoznačný názov.
- [ ] Má vhodnú ikonu a farbu.
- [ ] Vytvorili sme základné tematické chaty.
- [ ] Pridali sme iba relevantné zdroje.
- [ ] Nastavili sme projektové inštrukcie.
- [ ] Vytvorili sme katalóg zdrojov.
- [ ] Určili sme pravidlá pomenovania chatov a výstupov.

## Pred zdieľaním projektu

- [ ] Skontrolovali sme všetky súbory a chaty.
- [ ] Odstránili alebo anonymizovali sme nepotrebné citlivé údaje.
- [ ] Každému členovi sme pridelili najnižšiu potrebnú rolu.
- [ ] Rozumieme viditeľnosti obsahu v projekte.
- [ ] Overili sme režim projektovej pamäte.
- [ ] Určili sme pravidlá schvaľovania zmien.

## Počas práce

- [ ] Udržiavame aktuálny katalóg zdrojov.
- [ ] Označujeme verzie dokumentov.
- [ ] Dôležité rozhodnutia ukladáme ako samostatné záznamy.
- [ ] Kontrolujeme fakty, zdroje a výpočty.
- [ ] Používame vetvy na alternatívne riešenia.
- [ ] Pravidelne kontrolujeme členov a oprávnenia.
- [ ] Odstraňujeme zastarané a duplicitné zdroje.

## Pred odstránením projektu

- [ ] Ukončili sme otvorené úlohy.
- [ ] Exportovali sme potrebné výstupy.
- [ ] Zachovali sme potrebné chaty a rozhodnutia.
- [ ] Informovali sme členov.
- [ ] Rozumieme nevratnosti odstránenia.

---

# 📝 Praktické úlohy

## Úloha 1: Vytvorenie pracovného projektu

Vyberieme jednu pracovnú tému:

- marketingová kampaň,
- implementácia interného systému,
- príprava dotácie alebo grantu.

Vytvoríme projekt, zvolíme názov, ikonu a pamäť.

---

## Úloha 2: Organizačná štruktúra

Pomocou promptu z Cvičenia 2 navrhneme minimálne päť samostatných chatov. Následne ich vytvoríme a pomenujeme jednotným spôsobom.

---

## Úloha 3: Projektové zdroje

Do projektu pridáme najmenej tri rôzne typy zdrojov. Vytvoríme katalóg zdrojov a označíme:

- aktuálne zdroje,
- zastarané zdroje,
- duplicitné zdroje,
- chýbajúce zdroje.

---

## Úloha 4: Projektové inštrukcie

Pripravíme vlastné projektové inštrukcie a otestujeme ich v dvoch rôznych chatoch. Skontrolujeme, či sú odpovede konzistentné.

---

## Úloha 5: Pamäť projektu

Porovnáme predvolenú a výhradne projektovú pamäť. Pre vybraný pracovný príklad vytvoríme rozhodovaciu maticu.

---

## Úloha 6: Zdieľanie a roly

Navrhneme modelový tím s minimálne tromi členmi. Každému členovi pridelíme vhodnú rolu a zdôvodníme ju.

---

## Úloha 7: Vetvenie chatu

Z jedného pôvodného chatu vytvoríme dve vetvy. Každá vetva rozpracuje iný variant riešenia. Výsledky porovnáme v samostatnom chate.

---

## Úloha 8: Záznam rozhodnutia

Na základe porovnania vetiev vytvoríme záznam rozhodnutia a uložíme ho ako projektový zdroj.

---

## Úloha 9: Stavový report

Z dostupných chatov a zdrojov vytvoríme stavový report projektu. Označíme chýbajúce údaje a nebudeme odhadovať neznáme hodnoty.

---

## Úloha 10: Ukončenie projektu

Pripravíme plán ukončenia modelového projektu vrátane archivácie výstupov, odovzdania úloh a kontrolného zoznamu pred odstránením.

---

# 🧠 Zhrnutie cvičenia

Projekt v ChatGPT používame ako dlhodobý pracovný priestor, ktorý spája chaty, súbory, inštrukcie, pamäť a nástroje. Najväčší prínos získame vtedy, keď projekt navrhneme systematicky a nerozvíjame všetku prácu v jednom neprehľadnom chate.

Projektové zdroje poskytujú spoločný referenčný materiál. Projektové inštrukcie zabezpečujú konzistentný spôsob práce. Projektová pamäť pomáha nadväzovať na predchádzajúce konverzácie a výhradne projektový režim vytvára jasnejšie hranice medzi projektom a osobným kontextom.

Pri tímovej práci osobitne kontrolujeme prístupové roly, viditeľnosť obsahu, zdieľanie súborov a spôsob používania pamäte. Vetvenie chatov používame na skúmanie alternatív bez zmeny pôvodnej konverzácie. Pred odstránením projektu vždy archivujeme potrebné výstupy, pretože odstránenie je nevratné.

---

## ✅ Čo by sme mali vedieť po dokončení cvičenia

Po dokončení cvičenia dokážeme:

- rozhodnúť, či je úloha vhodná pre Projekt,
- vytvoriť a pomenovať Projekt v ChatGPT,
- navrhnúť štruktúru samostatných chatov,
- pridávať a katalogizovať projektové zdroje,
- ukladať dôležité odpovede ako zdroje,
- vytvoriť kvalitné projektové inštrukcie,
- vybrať vhodný režim projektovej pamäte,
- presúvať existujúce chaty,
- vybrať vhodný nástroj pre projektovú úlohu,
- nastaviť zdieľanie a prístupové roly,
- používať vetvenie konverzácií,
- zdieľať samostatný chat bez celého projektu,
- pripraviť záznam rozhodnutia a stavový report,
- rozlíšiť Projekt a vlastné GPT,
- bezpečne ukončiť alebo odstrániť projekt.

---

## 📚 Zdroj a aktuálna dokumentácia

Dokument bol spracovaný podľa priloženej prezentácie **Projekty ChatGPT**. Aktuálnosť funkcií a limitov overujeme v oficiálnej dokumentácii OpenAI:

- Projects in ChatGPT: https://help.openai.com/en/articles/10169521-projects-in-chatgpt
