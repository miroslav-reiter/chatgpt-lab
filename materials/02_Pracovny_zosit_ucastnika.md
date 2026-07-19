**Pracovný zošit účastníka | Praktické používanie AI ChatGPT**

# Pravidlá práce

- Každý placeholder v hranatých zátvorkách doplníme.
- Neúplný údaj označíme ako `CHÝBA`.
- Predpoklad označíme ako `PREDPOKLAD`.
- Dôležitý fakt označíme na manuálne overenie.
- Citlivé údaje v zadaniach nahradíme modelovými hodnotami.
- Výsledok hodnotíme podľa použiteľnosti, nie podľa toho, ako presvedčivo znie.

# LAB A: Kvalitný prompt

## Úloha A1: Diagnostika slabého promptu

Východiskový prompt:

```text
Napíš mi príspevok o našom kurze.
```

Doplňte, čo chýba:

| **Oblasť** | **Otázka** | **Naša odpoveď** |
|---|---|---|
| Cieľ | Čo má príspevok dosiahnuť? | |
| Publikum | Pre koho je určený? | |
| Kontext | Kde a prečo bude použitý? | |
| Vstupy | Aké fakty musí obsahovať? | |
| Tón | Ako má znieť? | |
| Rozsah | Aká má byť dĺžka? | |
| Formát | Akú má mať štruktúru? | |
| Obmedzenia | Čomu sa má vyhnúť? | |
| Kontrola | Čo sa nesmie vymyslieť? | |

## Úloha A2: Vytvorenie promptu

```text
Úloha:

Kontext:

Cieľová skupina:

Vstupy:

Pravidlá:

Formát:

Kontrola:
```

## Úloha A3: Iterácia

Po prvom výstupe zapíšte tri konkrétne zmeny:

1. 
2. 
3. 

Následný prompt:

```text
Zachovaj:

Zmeň:

Odstráň:

Doplň:
```

# LAB B: Placeholdery a šablóny

## Úloha B1: Premenné prvky

Jednorazový prompt:

```text
Navrhni mi päť tém pre blog o kybernetickej bezpečnosti pre malé firmy.
```

Označte meniteľné časti:

| **Placeholder** | **Význam** | **Príklad hodnoty** |
|---|---|---|
| `[počet]` | | |
| `[typ obsahu]` | | |
| `[oblasť]` | | |
| `[cieľová skupina]` | | |
| `[cieľ]` | | |
| `[formát]` | | |

## Úloha B2: Vlastná šablóna

```text
Navrhni [počet] [typ výstupu] pre [cieľová skupina] v oblasti [oblasť].
Cieľom je [cieľ].
Použi tieto vstupy: [vstupy].
Dodrž tieto pravidlá: [pravidlá].
Výstup vytvor vo formáte: [formát].
Nevymýšľaj: [zakázané údaje].
```

## Úloha B3: Test opakovateľnosti

| **Test** | **Vstup 1** | **Vstup 2** | **Fungovala šablóna?** |
|---|---|---|---|
| Oblasť | | | |
| Publikum | | | |
| Cieľ | | | |
| Výsledná štruktúra | | | |
| Potrebná oprava | | | |

# LAB C: Vlastné inštrukcie

## Úloha C1: Stabilné preferencie

Vyplňte iba informácie, ktoré majú platiť dlhodobo:

| **Oblasť** | **Naša požiadavka** |
|---|---|
| Jazyk | |
| Tón | |
| Úroveň detailu | |
| Formát | |
| Praktické príklady | |
| Práca s neistotou | |
| Upozornenia na riziká | |
| Čomu sa vyhýbať | |

## Úloha C2: Kontrola vhodnosti

Pri každom pravidle označte:

| **Pravidlo** | **Stabilné?** | **Konkrétne?** | **Overiteľné?** | **Bez citlivých údajov?** |
|---|---:|---:|---:|---:|
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |

## Úloha C3: Finálna verzia

```text
1. 
2. 
3. 
4. 
5. 
```

## Úloha C4: Test v novom chate

Testovacie zadanie:

```text
Navrhni postup, ako pripraviť interné školenie.
```

Kontrola výsledku:

- [ ] správny jazyk,
- [ ] požadovaný tón,
- [ ] požadovaná dĺžka,
- [ ] praktické kroky,
- [ ] uvedené predpoklady,
- [ ] upozornenie na riziká,
- [ ] bez vymyslených údajov.

# LAB D: Analýza PDF dokumentu

## Úloha D1: Príprava dokumentu

Pred nahratím skontrolujeme:

- [ ] dokument môžeme spracovať,
- [ ] neobsahuje heslá ani prístupové údaje,
- [ ] osobné údaje sú anonymizované,
- [ ] vieme, čo chceme z dokumentu získať,
- [ ] máme určený formát výsledku.

## Úloha D2: Naštudovanie

```text
Naštuduj si priložený PDF súbor. Zameraj sa na jeho účel, cieľovú skupinu, štruktúru, hlavné témy, dôležité údaje, tabuľky, vizuálne prvky, terminológiu a informačnú hierarchiu.

Nevypisuj analýzu. Po naštudovaní odpovedz iba:
OK, dokument som naštudoval.
```

## Úloha D3: Štruktúrovaný výstup

```text
Na základe priloženého PDF vytvor praktické zhrnutie.
Použi iba informácie, ktoré vyplývajú z dokumentu.

Výstup:
1. zhrnutie do piatich viet,
2. hlavné body,
3. kľúčové údaje v tabuľke,
4. praktický význam,
5. čo si má čitateľ zapamätať.

Ak potrebný údaj v dokumente nie je, napíš CHÝBA.
```

## Úloha D4: Audit výsledku

| **Tvrdenie** | **Je v dokumente?** | **Kde?** | **Fakt/PREDPOKLAD** | **Oprava** |
|---|---:|---|---|---|
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |

# Záverečné sebahodnotenie

| **Kritérium** | **Áno** | **Čiastočne** | **Nie** |
|---|---:|---:|---:|
| Viem vysvetliť rozdiel medzi promptom a vlastnými inštrukciami | | | |
| Viem vytvoriť prompt so šiestimi vrstvami | | | |
| Viem vytvoriť šablónu s placeholdermi | | | |
| Viem otestovať vlastné inštrukcie | | | |
| Viem označiť chýbajúci údaj | | | |
| Viem manuálne overiť dôležité tvrdenie | | | |
| Viem rozpoznať citlivé údaje | | | |
