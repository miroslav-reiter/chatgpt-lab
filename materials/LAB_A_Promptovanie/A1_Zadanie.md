# LAB A: Kvalitný prompt a riadená iterácia

## Cieľ

Prepracujeme všeobecné zadanie na presný prompt, ktorý vieme objektívne vyhodnotiť.

## Východiskový prompt

```text
Napíš mi príspevok o našom kurze.
```

## Úloha 1: Diagnostika

Identifikujte najmenej osem chýbajúcich informácií. Použite kategórie:

- cieľ,
- cieľová skupina,
- platforma,
- vstupné fakty,
- tón,
- rozsah,
- štruktúra,
- výzva na akciu,
- zakázané údaje,
- kontrola výsledku.

## Úloha 2: Prvý zlepšený prompt

Vytvorte prompt podľa šablóny:

```text
ÚLOHA:

KONTEXT:

CIEĽOVÁ SKUPINA:

VSTUPY:

PRAVIDLÁ:

FORMÁT:

KONTROLA:
```

## Úloha 3: Spustenie a audit

Po získaní odpovede vyhodnoťte:

| **Kritérium** | **Splnené?** | **Dôkaz vo výstupe** | **Oprava promptu** |
|---|---:|---|---|
| Správne publikum | | | |
| Správny tón | | | |
| Dodržaný rozsah | | | |
| Použité vstupné fakty | | | |
| Bez vymyslených údajov | | | |
| Správna štruktúra | | | |
| Použiteľná výzva na akciu | | | |

## Úloha 4: Riadená iterácia

Nevkladajte iba pokyn „sprav to lepšie“. Vytvorte následný prompt:

```text
Zachovaj tieto prvky:
- [prvok 1]
- [prvok 2]

Zmeň tieto prvky:
- [konkrétna zmena 1]
- [konkrétna zmena 2]

Odstráň:
- [čo nemá byť vo výstupe]

Doplň:
- [čo vo výstupe chýba]

Ostatné fakty a obmedzenia zachovaj.
```

## Úloha 5: Porovnanie verzií

| **Oblasť** | **Prvá odpoveď** | **Druhá odpoveď** | **Zlepšenie?** |
|---|---|---|---:|
| Presnosť | | | |
| Relevantnosť | | | |
| Štruktúra | | | |
| Tón | | | |
| Praktická použiteľnosť | | | |

## Kritériá úspechu

- prompt obsahuje minimálne šesť vrstiev,
- cieľ a publikum sú jednoznačné,
- formát výsledku je kontrolovateľný,
- obmedzenia sú konkrétne,
- druhá iterácia rieši presne pomenované nedostatky,
- finálny výstup neobsahuje vymyslené fakty.
