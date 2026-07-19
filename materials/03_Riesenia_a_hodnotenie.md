**Vzorové riešenia a hodnotenie | Praktické používanie AI ChatGPT**

# Ako používať tento dokument

Vzorové riešenia nepredstavujú jedinú správnu formuláciu. Slúžia ako kontrola, či zadanie obsahuje potrebné prvky a či výsledok vieme objektívne vyhodnotiť.

# LAB A: Kvalitný prompt

## Vzorová diagnostika

Prompt „Napíš mi príspevok o našom kurze“ neobsahuje:

- platformu,
- cieľ príspevku,
- cieľovú skupinu,
- názov a obsah kurzu,
- tón,
- rozsah,
- štruktúru,
- výzvu na akciu,
- zakázané alebo neoverené údaje.

## Vzorový zlepšený prompt

```text
Napíš príspevok na LinkedIn o kurze Praktické používanie AI ChatGPT.

Cieľ:
Predstaviť kurz ľuďom, ktorí ChatGPT používajú iba na jednoduché otázky a chcú sa naučiť vytvárať kvalitné prompty, šablóny a vlastné inštrukcie.

Cieľová skupina:
Lektori, marketéri, administratívni pracovníci, manažéri a freelanceri.

Vstupy:
- kurz obsahuje praktické laboratóriá,
- venuje sa promptom, placeholderom, vlastným inštrukciám a analýze PDF,
- výstupom sú opakovateľné pracovné postupy.

Pravidlá:
- profesionálny a vecný tón,
- bez prehnaných sľubov,
- maximálne 170 slov,
- nepoužívaj frázy „revolučný“ ani „zmení vám život“,
- nevymýšľaj cenu, dátum, certifikát ani akreditáciu.

Formát:
1. problém používateľa,
2. tri praktické prínosy,
3. stručná výzva na získanie informácií.
```

## Prečo je riešenie kvalitné

- cieľ je merateľný,
- publikum je určené,
- model má fakty, ktoré môže použiť,
- formát je kontrolovateľný,
- obmedzenia znižujú riziko marketingových výmyslov.

# LAB B: Placeholdery

## Vzorová univerzálna šablóna

```text
Navrhni [počet] tém pre [typ obsahu] v oblasti [oblasť].

Cieľová skupina:
[cieľová skupina]

Cieľ obsahu:
[cieľ]

Pri každej téme uveď:
- pracovný názov,
- konkrétny problém publika,
- hlavný prínos,
- tri obsahové body,
- odporúčanú výzvu na akciu.

Pravidlá:
- nepoužívaj všeobecné témy,
- neuvádzaj štatistiky bez zdroja,
- prispôsob odbornú úroveň publiku,
- výstup vytvor v tabuľke.
```

## Kontrola opakovateľnosti

Šablóna je použiteľná, keď:

- každý placeholder má jasný význam,
- po doplnení nevznikajú gramatické alebo významové chyby,
- rovnaká štruktúra funguje pre rozdielne témy,
- stabilné pravidlá nemusíme opakovať mimo šablóny,
- výstup vieme porovnať medzi jednotlivými spusteniami.

# LAB C: Vlastné inštrukcie

## Zlá verzia

```text
Píš mi lepšie odpovede a pomáhaj mi s prácou.
```

Problémy:

- pojem „lepšie“ nie je definovaný,
- nevieme skontrolovať splnenie,
- nie je určený jazyk, tón ani formát,
- neobsahuje pravidlo pre neúplné vstupy,
- neobsahuje pravidlo pre riziká a overovanie.

## Dobrá verzia

```text
1. Odpovedaj po slovensky.
2. Používaj profesionálny, vecný a praktický tón.
3. Pri návodoch uvádzaj konkrétne kroky v logickom poradí.
4. Ak vstup nie je úplný, najprv uveď pracovný predpoklad alebo polož jednu nevyhnutnú otázku.
5. Pri odporúčaniach uveď hlavné riziko a vhodnú alternatívu.
6. Nevymýšľaj zdroje, čísla, citácie ani funkcie produktu.
7. Pri časovo citlivých informáciách upozorni, že ich treba overiť.
8. Nepoužívaj marketingové frázy bez vecného obsahu.
```

## Kontrola kvality

Každý bod je:

- dlhodobo použiteľný,
- konkrétny,
- pozorovateľný vo výsledku,
- bez citlivých údajov,
- oddelený od konkrétnej jednorazovej úlohy.

# LAB D: PDF dokument

## Vzorový dvojkrokový postup

### Krok 1

```text
Naštuduj si priložený PDF súbor. Analyzuj účel, cieľovú skupinu, štruktúru, hlavné témy, kľúčové údaje, tabuľky, vizuálne prvky a terminológiu.

Nevypisuj analýzu. Odpovedz iba:
OK, dokument som naštudoval.
```

### Krok 2

```text
Na základe priloženého PDF vytvor praktické zhrnutie.

Použi iba informácie z dokumentu.
Výstup rozdeľ na:
1. zhrnutie do piatich viet,
2. hlavné body,
3. najdôležitejšie údaje v tabuľke,
4. praktický význam,
5. čo si má čitateľ zapamätať.

Pri každom čísle alebo termíne uveď stranu dokumentu.
Ak údaj chýba, napíš CHÝBA.
Nevytváraj externé odporúčania, ktoré z dokumentu nevyplývajú.
```

### Krok 3: Audit

```text
Skontroluj svoje zhrnutie voči PDF.

Vytvor tabuľku:
- tvrdenie,
- číslo strany,
- priamy dôkaz,
- miera istoty,
- oprava.

Tvrdenie bez priamej podpory označ ako NEOVERENÉ.
```

# Hodnotiaca rubrika

| **Kritérium** | **0 bodov** | **1 bod** | **2 body** |
|---|---|---|---|
| Cieľ | chýba | všeobecný | jednoznačný a použiteľný |
| Kontext a publikum | chýbajú | čiastočné | presne určené |
| Vstupy | neurčené | niektoré údaje | úplné alebo medzery označené |
| Pravidlá a obmedzenia | chýbajú | všeobecné | konkrétne a overiteľné |
| Formát | neurčený | základný | presná štruktúra |
| Placeholdery | nepoužité | nejednoznačné | jasné a opakovateľné |
| Vlastné inštrukcie | jednorazové alebo všeobecné | čiastočne stabilné | stabilné a kontrolovateľné |
| Bezpečnosť | bez kontroly | základné upozornenie | anonymizácia a jasné hranice |
| Overovanie | bez overenia | všeobecná kontrola | audit tvrdení a zdrojov |
| Praktická použiteľnosť | vyžaduje úplné prepracovanie | použiteľné s úpravami | pripravené na použitie |

Maximum: **20 bodov**.

## Interpretácia výsledku

| **Body** | **Úroveň** | **Interpretácia** |
|---:|---|---|
| 0 - 7 | základná | zadania sú prevažne všeobecné alebo rizikové |
| 8 - 13 | použiteľná | výsledky fungujú, ale chýba konzistentnosť alebo kontrola |
| 14 - 17 | pokročilá | prompty sú dobre štruktúrované a opakovateľné |
| 18 - 20 | profesionálna | zadania, nastavenia a kontrola tvoria ucelený workflow |

# Kontrolný zoznam lektora

- [ ] Účastník vie vysvetliť rozdiel medzi promptom a vlastnými inštrukciami.
- [ ] V prompte je určený cieľ a publikum.
- [ ] Placeholdery majú jednoznačný význam.
- [ ] Vlastné inštrukcie sú stabilné a bez citlivých údajov.
- [ ] PDF výstup používa iba informácie z dokumentu.
- [ ] Aspoň jedno dôležité tvrdenie bolo manuálne overené.
- [ ] Účastník vie pomenovať situáciu, keď ChatGPT nemá byť jediným zdrojom rozhodnutia.
