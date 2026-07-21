# 🧪 Cvičenie 01: Praktické používanie AI ChatGPT

Toto cvičenie je zamerané na prípravu kvalitných promptov, ktoré môžeme okamžite skopírovať, doplniť o vlastné údaje a použiť v ChatGPT.

Prompty používajú placeholdery v hranatých zátvorkách, napríklad `[téma]`, `[produkt]`, `[cieľová skupina]` alebo `[dokument]`. Pred odoslaním ich nahradíme konkrétnymi údajmi.

---

## 🎯 Ciele cvičenia

Po absolvovaní cvičenia budeme vedieť:

- pripraviť prompt s jasným cieľom, kontextom, pravidlami a formátom,
- používať placeholdery na opakované použitie promptov,
- spracovať PDF dokumenty a dlhé texty,
- vytvárať obsah, e-maily, plány a pracovné podklady,
- nastaviť vlastné inštrukcie ChatGPT,
- rozlíšiť jednorazový prompt od trvalého pravidla,
- kontrolovať kvalitu a presnosť výstupu.

---

## 1. Základná štruktúra kvalitného promptu

Pri tvorbe promptu používame tento model:

```text
CIEĽ + KONTEXT + VSTUPY + PRAVIDLÁ + FORMÁT + KONTROLA
```

| Časť | Otázka, ktorú si položíme |
|---|---|
| Cieľ | Čo má ChatGPT vytvoriť alebo vyriešiť? |
| Kontext | Pre koho, prečo a v akej situácii výstup používame? |
| Vstupy | Aké údaje, texty, dokumenty alebo podmienky má spracovať? |
| Pravidlá | Aký tón, rozsah, jazyk a obmedzenia má dodržať? |
| Formát | Má ísť o tabuľku, zoznam, e-mail, článok alebo osnovu? |
| Kontrola | Ako má ChatGPT overiť úplnosť, logiku a riziká? |

### Univerzálna šablóna promptu

```text
Vytvor [typ výstupu] na tému [téma].

Kontext:
- cieľová skupina: [cieľová skupina],
- účel: [účel],
- situácia: [situácia].

Požiadavky:
- jazyk: slovenčina,
- tón: [tón],
- rozsah: [rozsah],
- zohľadni: [dôležité podmienky],
- vyhni sa: [nežiaduce prvky].

Výstup priprav vo formáte [formát výstupu].
Na konci skontroluj, či si splnil všetky požiadavky.
```

---

## 2. Príprava konverzácie pred hlavnou úlohou

Pri práci s dlhším dokumentom alebo zložitejšou úlohou môžeme najprv pripraviť kontext a až následne zadať konkrétnu úlohu.

### Prompt: naštudovanie priloženého PDF

```text
Naštuduj si priložený PDF súbor dôkladne a analyzuj jeho obsah, štruktúru, účel, cieľovú skupinu, hlavné témy, dôležité údaje, tabuľky, vizuálne prvky, opakujúce sa vzory, terminológiu a informačnú hierarchiu.

Nevypisuj mi analýzu ani dlhé vysvetlenie.
Po úspešnom naštudovaní odpovedz iba vetou:
OK, PDF súbor som úspešne naštudoval a zanalyzoval.
```

### Prompt: potvrdenie pripraveného kontextu

```text
Naštuduj si nasledujúce informácie a používaj ich ako pracovný kontext pre ďalšie úlohy.

[pracovný kontext]

Zatiaľ nič nevytváraj.
Odpovedz iba: OK.
```

### Prompt: spresnenie zadania pred spracovaním

```text
Pred vytvorením výstupu skontroluj, či máš dostatok informácií.

Ak niečo podstatné chýba, polož mi najviac 5 konkrétnych doplňujúcich otázok.
Ak je zadanie dostatočné, pokračuj priamo vo vytvorení výstupu.

Úloha:
[úloha]
```

---

## 3. Práca s PDF dokumentmi a dlhými textami

### Prompt: praktické zhrnutie PDF

```text
Na základe priloženého PDF súboru vytvor praktické a prehľadné zhrnutie.

Zameraj sa na:
- hlavný účel dokumentu,
- najdôležitejšie témy,
- kľúčové fakty, čísla a termíny,
- tabuľky a rozhodujúce údaje,
- odporúčané kroky,
- informácie dôležité pre čitateľa.

Výstup štruktúruj takto:
1. stručné zhrnutie do 5 viet,
2. hlavné body v odrážkach,
3. najdôležitejšie údaje v tabuľke,
4. praktický význam dokumentu,
5. čo si má čitateľ zapamätať.

Nepíš všeobecné frázy. Použi iba informácie, ktoré vyplývajú z PDF.
```

### Prompt: zhrnutie do troch hlavných bodov

```text
Zhrň priložený text alebo dokument do troch hlavných bodov.

Pri každom bode uveď:
- hlavnú myšlienku,
- stručné vysvetlenie,
- praktický dôsledok pre [cieľová skupina].

Nepoužívaj všeobecné formulácie a neopakuj rovnakú informáciu viackrát.
```

### Prompt: plusy a mínusy

```text
Analyzuj priložený článok alebo dokument a vytvor prehľad plusov a mínusov.

Výstup priprav v tabuľke so stĺpcami:
- oblasť,
- výhoda,
- nevýhoda alebo riziko,
- praktické odporúčanie.

Na konci pridaj stručný záver, pre koho je riešenie vhodné a pre koho nie.
```

### Prompt: extrakcia údajov z dokumentu

```text
Z priloženého dokumentu vyber všetky dôležité údaje, ktoré patria do týchto kategórií:

- dátumy a termíny,
- sumy a rozpočty,
- mená organizácií a osôb,
- povinnosti,
- podmienky,
- riziká,
- odporúčané kroky.

Výstup priprav v prehľadnej tabuľke.
Pri každom údaji uveď aj stranu alebo časť dokumentu, z ktorej pochádza.
Nevymýšľaj chýbajúce informácie.
```

### Prompt: kontrolný zoznam z dokumentu

```text
Na základe priloženého dokumentu vytvor praktický kontrolný zoznam.

Rozdeľ ho na:
1. čo musíme pripraviť,
2. čo musíme overiť,
3. čo musíme odovzdať alebo vykonať,
4. termíny,
5. možné chyby a riziká.

Každý bod formuluj ako konkrétnu kontrolovateľnú úlohu.
```

### Prompt: porovnanie dvoch dokumentov

```text
Porovnaj dokument A a dokument B.

Zameraj sa na:
- účel,
- cieľovú skupinu,
- hlavné požiadavky,
- termíny,
- finančné podmienky,
- rozdiely,
- riziká,
- praktické dôsledky.

Výstup priprav v porovnávacej tabuľke.
Na konci uveď 5 najdôležitejších rozdielov a odporúčanie, ktorý dokument je vhodnejší pre [situácia].
```

### Prompt: spätná väzba k dokumentu

```text
Posúď priložený dokument z pohľadu kvality, zrozumiteľnosti a praktickej použiteľnosti.

Vyhodnoť:
- logiku štruktúry,
- jasnosť formulácií,
- úplnosť informácií,
- konzistentnosť terminológie,
- opakovanie,
- nejasné alebo rizikové časti,
- vhodnosť pre cieľovú skupinu [cieľová skupina].

Výstup priprav v troch častiach:
1. čo je spracované dobre,
2. čo treba zlepšiť,
3. konkrétne návrhy úprav.
```

---

## 4. Copywriting a obsahový marketing

### Prompt: návrh SEO tém

```text
Navrhni mi 5 tém pre kvalitné SEO blogové články v oblasti [oblasť].

Pri každej téme uveď:
- pracovný názov článku,
- cieľové publikum,
- hlavné kľúčové slovo,
- 3 súvisiace kľúčové slová,
- vyhľadávací zámer,
- dôvod, prečo má téma SEO potenciál.

Témy nesmú byť všeobecné ani obsahovo duplicitné.
```

### Prompt: blogový článok

```text
Napíš blogový článok na tému [téma] pre cieľovú skupinu [cieľová skupina].

Použi:
- pútavý, ale vecný titulok,
- stručný úvod,
- logickú štruktúru H1, H2 a H3,
- krátke odseky,
- praktické príklady,
- konkrétne odporúčania,
- záver s jasnou hlavnou myšlienkou.

Rozsah: [počet slov] slov.
Tón: [tón].
Navrhni aj SEO titulok do 60 znakov a meta popis do 155 znakov.
Nevym