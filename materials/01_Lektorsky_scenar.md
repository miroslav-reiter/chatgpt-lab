**Lektorský scenár | 90 minút | začiatočník až mierne pokročilý**

# Charakter kurzu

Kurz je postavený na štyroch praktických laboratóriách. Účastníci nepíšu iba jednotlivé otázky. Vytvárajú opakovateľný systém práce s ChatGPT: kvalitný prompt, šablóny s placeholdermi, vlastné inštrukcie a kontrolovaný postup pri práci s dokumentmi.

Výstup každého laboratória musí byť použiteľný a kontrolovateľný.

| **Vstupná podmienka:** Účastník vie otvoriť ChatGPT, vytvoriť nový chat, odoslať prompt a skopírovať odpoveď. |
|---|

# Ciele

- Vysvetlíme rozdiel medzi promptom, vlastnými inštrukciami, osobnosťou a pamäťou.
- Zostavíme prompt s cieľom, kontextom, vstupmi, pravidlami, formátom a kontrolou.
- Prepracujeme všeobecné zadania na opakovateľné šablóny s placeholdermi.
- Navrhneme vlastné inštrukcie, ktoré opisujú konkrétne a overiteľné správanie.
- Použijeme dvojkrokový postup pri analýze PDF dokumentu.
- Overíme, či výstup neobsahuje nepodložené, citlivé alebo neaktuálne informácie.

# Časový plán

| **Čas** | **Blok** | **Výstup** |
|---|---|---|
| 0 - 8 min | Úvod, rozhranie a pravidlá | spoločný pracovný rámec |
| 8 - 28 min | LAB A: kvalitný prompt | prompt v šiestich vrstvách |
| 28 - 45 min | LAB B: placeholdery | dve opakovateľné šablóny |
| 45 - 65 min | LAB C: vlastné inštrukcie | sada stabilných pravidiel |
| 65 - 84 min | LAB D: PDF a kontrola | zhrnutie a audit odpovede |
| 84 - 90 min | Záver | kontrolné otázky a odovzdanie |

# Pravidlo proti generickému výstupu

- Každý prompt musí pomenovať cieľový výsledok.
- Pri pracovnom výstupe určujeme cieľovú skupinu a účel.
- Ak je dôležitá forma, uvedieme štruktúru, rozsah a tón.
- Ak informácia chýba, model ju nemá dopĺňať bez označenia predpokladu.
- Kritické fakty overujeme mimo modelu.
- Účastník musí vedieť vysvetliť, ktorá časť promptu spôsobila konkrétnu vlastnosť odpovede.

# Úvod: rozhranie a základné ovládanie

Lektor ukáže:

1. nový chat,
2. vstupné pole promptu,
3. možnosť pridať prílohu,
4. výber dostupného modelu,
5. nastavenia prispôsobenia,
6. vlastné inštrukcie,
7. dočasný chat, ak je v účte dostupný,
8. klávesové správanie Enter a Shift + Enter.

## Krátka demonštrácia

Napíšeme dvojriadkový prompt. Najskôr ukážeme, že **Enter** odosiela správu. Potom použijeme **Shift + Enter** na vloženie nového riadka.

Lektor upozorní, že názvy položiek, modelov, taríf a dostupnosť funkcií sa môžu meniť.

# LAB A: Kvalitný prompt a iterácie

## Východiskový problém

Účastníci dostanú príliš všeobecný prompt:

> Napíš mi príspevok o našom kurze.

## Krok 1: Diagnostika

Účastníci označia, čo chýba:

- cieľ,
- cieľová skupina,
- kontext,
- hlavné informácie,
- tón,
- rozsah,
- formát,
- výzva na akciu,
- obmedzenia,
- kontrola faktov.

## Krok 2: Šesťvrstvový prompt

> Napíš príspevok na sociálnu sieť [sieť] o kurze [názov kurzu]. Cieľom je [cieľ]. Príspevok je určený pre [cieľová skupina]. Použi tieto informácie: [vstupy]. Tón má byť [tón]. Rozsah maximálne [počet] slov. Výstup rozdeľ na pútavý úvod, tri prínosy a nenásilnú výzvu na akciu. Nevymýšľaj cenu, termín ani akreditáciu. Ak údaj chýba, označ ho ako CHÝBA.

## Krok 3: Kontrolovaná iterácia

Po prvom výsledku účastník nevysloví iba „sprav to lepšie“. Použije konkrétnu spätnú väzbu:

> Zachovaj fakty. Skráť text o 30 %, odstráň všeobecné frázy, zvýrazni praktický výsledok kurzu a uprav prvú vetu tak, aby pomenovala problém cieľovej skupiny.

## Debrief

- Kvalitný prompt neurčuje iba tému.
- Slovo „kvalitný“ alebo „lepší“ bez kritérií nepomáha.
- Formát výstupu môžeme riadiť presnejšie než obsah ručne opravovať.
- Kontrolný pokyn znižuje riziko vymyslených údajov, ale nezaručuje úplnú správnosť.

# LAB B: Placeholdery a opakovateľné šablóny

## Cieľ

Z jednorazového promptu vytvoríme šablónu, ktorú vieme použiť pre viac klientov, produktov alebo tém.

## Krok 1: Rozpoznanie meniteľných častí

Príklad:

> Navrhni mi päť tém pre blog o kybernetickej bezpečnosti pre malé firmy.

Meniteľné časti:

- `[počet tém]`,
- `[obsahová oblasť]`,
- `[cieľová skupina]`,
- `[cieľ obsahu]`,
- `[jazyk]`,
- `[formát výsledku]`.

## Krok 2: Vytvorenie šablóny

> Navrhni [počet] tém pre [typ obsahu] v oblasti [oblasť]. Obsah je určený pre [cieľová skupina] a jeho cieľom je [cieľ]. Pri každej téme uveď názov, problém publika, hlavný prínos, tri kľúčové body a odporúčanú výzvu na akciu. Nepoužívaj témy, ktoré vyžadujú údaje, ktoré sme neposkytli.

## Krok 3: Test dvoch variantov

Každý účastník použije rovnakú šablónu s dvoma rozdielnymi sadami vstupov. Sleduje, či:

- šablóna funguje bez ďalšieho vysvetľovania,
- placeholdery nie sú nejednoznačné,
- výstup má vždy rovnakú štruktúru,
- obmedzenia zostávajú zachované.

## Debrief

- Placeholder nie je iba technická značka. Je to pomenovanie premenného vstupu.
- Dobrá šablóna oddelí stabilné pravidlá od meniteľného obsahu.
- Ak musí používateľ po každom spustení dopĺňať ďalšie vysvetlenia, šablóna ešte nie je hotová.

# LAB C: Vlastné inštrukcie a prispôsobenie

## Vysvetlenie vrstiev

Lektor porovná:

- prompt ako aktuálne zadanie,
- vlastné inštrukcie ako dlhodobú pracovnú dohodu,
- osobnosť ako základný tón a spôsob vyjadrovania,
- pamäť ako zapamätané informácie použiteľné naprieč chatmi.

## Krok 1: Zlá inštrukcia

> Píš mi lepšie odpovede a pomáhaj mi s prácou.

Problém: správanie nie je konkrétne ani overiteľné.

## Krok 2: Dobrá inštrukcia

> Odpovedaj po slovensky. Pri pracovných úlohách najskôr uveď predpoklady, ak vstup nie je úplný. Používaj vecný profesionálny tón. Pri návodoch uvádzaj konkrétne kroky. Pri odporúčaniach pridaj riziká a lepšie alternatívy. Neuvádzaj vymyslené čísla, zdroje ani citácie.

## Krok 3: Test v novom chate

Účastník otvorí nový chat a zadá neutrálne zadanie:

> Navrhni postup, ako pripraviť interné školenie.

Kontroluje, či odpoveď rešpektuje:

- jazyk,
- tón,
- štruktúru,
- praktickosť,
- upozornenie na riziká,
- prácu s neúplným kontextom.

## Krok 4: Oprava

Nefunkčný alebo príliš všeobecný bod prepíšeme na konkrétne správanie. Jednorazové požiadavky odstránime.

## Debrief

- Vlastná inštrukcia nemá obsahovať aktuálnu úlohu.
- Nepíšeme do nej heslá, osobné čísla, dôverné údaje ani citlivé profily.
- Osobnosť nemení schopnosti ani bezpečnostné pravidlá ChatGPT.
- Stabilný pracovný štýl vzniká kombináciou vlastných inštrukcií, osobnosti, pamäte a kvalitného aktuálneho promptu.

# LAB D: PDF dokument a kontrola výstupu

## Cieľ

Ukážeme dvojkrokový postup: najskôr dokument naštudovať, potom vytvoriť presne definovaný výstup.

## Krok 1: Naštudovanie dokumentu

> Naštuduj si priložený PDF súbor. Zameraj sa na jeho účel, cieľovú skupinu, štruktúru, hlavné témy, dôležité údaje, tabuľky, vizuálne prvky, terminológiu a informačnú hierarchiu. Nevypisuj analýzu. Po naštudovaní odpovedz iba: OK, dokument som naštudoval.

Lektor vysvetlí, že potvrdenie samo osebe nedokazuje správne pochopenie. Slúži na oddelenie prípravy od finálnej úlohy.

## Krok 2: Štruktúrované zhrnutie

> Na základe priloženého PDF vytvor praktické zhrnutie. Použi iba informácie, ktoré z dokumentu vyplývajú. Výstup rozdeľ na: 1. zhrnutie do piatich viet, 2. hlavné body, 3. kľúčové údaje v tabuľke, 4. praktický význam, 5. čo si má čitateľ zapamätať. Ak dokument neobsahuje potrebný údaj, napíš CHÝBA.

## Krok 3: Audit

> Skontroluj predchádzajúci výstup. Vytvor tabuľku so stĺpcami: tvrdenie, miesto v dokumente, typ podpory, miera istoty a potrebná oprava. Označ tvrdenia, ktoré nie sú priamo podložené dokumentom.

## Debrief

- Dlhý dokument spracúvame po krokoch.
- Nežiadame naraz analýzu, interpretáciu, odporúčanie a finálny marketingový text.
- Tabuľky a obrázky môžu obsahovať informácie, ktoré textová extrakcia nezachytí dokonale.
- Výstup musí zostať oddelený od externých domnienok.

# Záverečný audit

Každý účastník vyberie jeden svoj prompt a odpovie:

1. Je cieľ výsledku jednoznačný?
2. Je zadaná cieľová skupina a účel?
3. Sú vstupy úplné alebo označujeme medzery?
4. Je formát výsledku kontrolovateľný?
5. Sú obmedzenia konkrétne?
6. Vieme rozlíšiť fakt, predpoklad a odporúčanie?
7. Neobsahuje zadanie citlivé údaje?
8. Ktorý fakt musíme manuálne overiť?

# Hodnotenie

| **Kritérium** | **0 bodov** | **1 bod** | **2 body** |
|---|---|---|---|
| Cieľ a kontext | chýbajú | čiastočné | presné a relevantné |
| Vstupy | nejasné | použiteľné s medzerami | úplné alebo medzery označené |
| Formát a obmedzenia | bez kontroly | základné | konkrétne a merateľné |
| Opakovateľnosť | jednorazové zadanie | čiastočná šablóna | funkčné placeholdery |
| Bezpečnosť a overenie | bez kontroly | základné upozornenie | systematický audit |

Maximum: **10 bodov**.
