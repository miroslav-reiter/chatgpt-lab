# 💶 Praktické príklady promptov pre granty a dotácie

Tento dokument obsahuje praktické prompty na analýzu grantových a dotačných výziev, posudzovanie oprávnenosti žiadateľov, zamestnancov, poskytovateľov a vzdelávacích programov, výpočet finančného príspevku, prípravu žiadosti, kontrolu rizík a následné vyúčtovanie projektu.

Príklady vychádzajú z dokumentu upravujúceho 2. kolo národného projektu **„Zvyšovanie zručností zamestnancov“**, najmä z pravidiel oprávnenosti, spôsobu výpočtu príspevku, elektronického podania žiadosti, refundácie oprávnených výdavkov a rozhodujúcich termínov.

Prompty sú pripravené na rýchle skopírovanie. Používajú placeholdery v hranatých zátvorkách, napríklad `[názov firmy]`, `[počet zamestnancov]`, `[názov programu]`, `[údaje]` alebo `[vložiť návrh projektu]`. Pred odoslaním ich nahradíme konkrétnymi údajmi.

> Pri grantových a dotačných výzvach vždy pracujeme s aktuálnym oficiálnym znením dokumentov. Ak bola výzva aktualizovaná, rozhodujúca je posledná účinná verzia.

---

## 🎯 Ciele cvičenia

Po absolvovaní cvičenia budeme vedieť:

- analyzovať grantový alebo dotačný dokument,
- overiť oprávnenosť žiadateľa a cieľovej skupiny,
- posúdiť oprávnenosť poskytovateľa a vzdelávacieho programu,
- vypočítať maximálnu výšku finančného príspevku,
- identifikovať povinné prílohy a formálne podmienky,
- pripraviť textovú časť žiadosti,
- vyhodnotiť projekt z pohľadu hodnotiacej komisie,
- zostaviť harmonogram a kontrolný zoznam,
- identifikovať riziká zamietnutia alebo nepreplatenia výdavkov,
- pripraviť podklady na refundáciu, kontrolu a archiváciu.

---

## 🧭 Základný princíp práce s dotačným dokumentom

Pri spracovaní grantovej alebo dotačnej výzvy používame tento postup:

```text
NAŠTUDOVAŤ → OVERIŤ OPRÁVNENOSŤ → IDENTIFIKOVAŤ PODMIENKY → VYPOČÍTAŤ ROZPOČET → PRIPRAVIŤ ŽIADOSŤ → SKONTROLOVAŤ RIZIKÁ
```

### Kontrolné otázky

Pred prípravou žiadosti si overíme:

- Je žiadateľ oprávneným subjektom?
- Sú zamestnanci alebo účastníci oprávnenou cieľovou skupinou?
- Je poskytovateľ zapísaný v požadovanom registri?
- Je vzdelávací program oprávnený podľa pravidiel výzvy?
- Je forma realizácie programu povolená?
- Sú všetky výdavky oprávnené a preukázateľné?
- Je potrebné predfinancovanie z vlastných zdrojov?
- Aké prílohy a elektronické podpisy sa vyžadujú?
- Aké lehoty nemožno zmeškať?
- Aké povinnosti vzniknú po schválení projektu?

---

# 📌 Univerzálna inštrukcia k promptom

Tento blok odporúčame vložiť na koniec každého promptu:

```text
Pracuj výlučne s priloženým PDF dokumentom. Pri každom dôležitom tvrdení uveď číslo strany. Presne odlišuj informácie uvedené v dokumente od vlastného odborného posúdenia. Nevymýšľaj chýbajúce údaje. Ak dokument určitú otázku neupravuje jednoznačne, výslovne to označ.
```

---

# 1. Komplexná analýza dokumentu

## Situácia

Potrebujeme získať úplný odborný prehľad o grantovej alebo dotačnej výzve bez vynechania rozhodujúcich podmienok.

## Cieľ

Identifikujeme právny rámec, oprávnenosť, finančné podmienky, termíny, spôsob podania, hodnotenie a riziká.

## Prompt

```text
Dôkladne analyzuj priložený PDF dokument „Oznámenie – Aktualizácia č. 5“.

Výstup rozdeľ na:

1. účel a právny rámec projektu,
2. oprávnených a neoprávnených žiadateľov,
3. oprávnených a neoprávnených zamestnancov,
4. podmienky poskytovateľa vzdelávania,
5. podmienky vzdelávacieho programu,
6. oprávnené a neoprávnené výdavky,
7. výšku a spôsob výpočtu príspevku,
8. termíny a lehoty,
9. spôsob podania žiadosti,
10. proces hodnotenia, refundácie a kontroly,
11. najväčšie riziká zamietnutia žiadosti,
12. praktické odporúčania pre žiadateľa.
```

---

# 2. Manažérske zhrnutie

## Situácia

Konateľ alebo manažér potrebuje rýchlo rozhodnúť, či má firma kapacitu a podmienky na zapojenie do projektu.

## Cieľ

Vytvoríme stručný rozhodovací prehľad bez nadbytočných právnych detailov.

## Prompt

```text
Vytvor manažérske zhrnutie priloženého PDF dokumentu pre konateľa malej alebo strednej firmy.

Zameraj sa iba na informácie potrebné na rozhodnutie:

- či sa firma môže zapojiť,
- ktorí zamestnanci môžu byť vzdelávaní,
- aké kurzy sú oprávnené,
- koľko možno získať,
- čo musí firma najskôr zaplatiť,
- aké sú rozhodujúce termíny,
- aké dokumenty a administratívne kapacity bude potrebovať,
- aké sú hlavné finančné a právne riziká.

Výstup obmedz na jednu stranu A4.
```

---

# 3. Overenie oprávnenosti zamestnávateľa

## Situácia

Potrebujeme preveriť, či konkrétna firma spĺňa podmienky oprávneného žiadateľa.

## Cieľ

Porovnáme údaje firmy s každou podmienkou výzvy a označíme chýbajúce dôkazy.

## Prompt

```text
Posúď, či je nasledujúci zamestnávateľ oprávneným žiadateľom podľa priloženého PDF dokumentu:

Názov: [názov firmy]
Právna forma: [právna forma]
Počet zamestnancov: [počet]
Hospodárska činnosť: [opis]
Sídlo a prevádzkarne: [údaje]
Verejné vlastníctvo: [áno/nie/podiel]
Konkurz, likvidácia alebo exekúcie: [údaje]
Daňové a odvodové nedoplatky: [údaje]
Čerpanie inej pomoci: [údaje]
Predchádzajúca účasť v projekte: [údaje]

Výstup priprav ako tabuľku:

- podmienka,
- stav žiadateľa,
- splnené/nesplnené/neoverené,
- dôkaz alebo potrebný doklad,
- číslo strany PDF.

Na konci uveď jednoznačný záver a zoznam údajov, ktoré ešte musíme overiť.
```

---

# 4. Overenie oprávnenosti zamestnancov

## Situácia

Firma potrebuje určiť, ktorých zamestnancov môže zaradiť do vzdelávania.

## Cieľ

Overíme pracovný pomer, úväzok, typ zmluvy, dôchodkový status, miesto výkonu práce a pracovný čas.

## Prompt

```text
Posúď oprávnenosť jednotlivých zamestnancov na zapojenie do projektu podľa priloženého PDF.

Pre každého zamestnanca vyhodnoť:

- existenciu pracovného pomeru ku dňu začatia vzdelávania,
- rozsah pracovného úväzku,
- typ pracovnoprávneho vzťahu,
- poberanie starobného dôchodku,
- výkon štátnej služby alebo práce vo verejnom záujme,
- miesto výkonu práce,
- súlad času vzdelávania s pracovným časom.

Údaje:
[vložiť anonymizovanú tabuľku zamestnancov]

Výstup priprav ako kontrolnú tabuľku s výsledkom „oprávnený“, „neoprávnený“ alebo „potrebné overiť“.
```

---

# 5. Overenie poskytovateľa vzdelávania

## Situácia

Zamestnávateľ si vybral vzdelávaciu organizáciu a potrebuje overiť jej oprávnenosť.

## Cieľ

Skontrolujeme právne postavenie, predmet činnosti, certifikáciu a zápis v požadovaných registroch.

## Prompt

```text
Vypracuj presný kontrolný zoznam na overenie, či je vzdelávacia organizácia oprávneným dodávateľom vzdelávania podľa priloženého PDF.

Zahrň najmä:

- právne postavenie vzdelávacej inštitúcie,
- predmet činnosti,
- certifikáciu podľa § 10 zákona č. 292/2024 Z. z.,
- zápis v príslušnom registri ISVD,
- prípadný zápis medzi poskytovateľmi digitálnych a zelených zručností,
- externý spôsob zabezpečenia vzdelávania,
- požadované dôkazy a dokumenty.

Pri každom bode uveď, kde a ako ho máme overiť.
```

---

# 6. Posúdenie oprávnenosti konkrétneho kurzu

## Situácia

Potrebujeme zistiť, či konkrétny kurz zodpovedá podmienkam oprávneného vzdelávacieho programu.

## Cieľ

Posúdime obsah, formu, ukončenie, doklad, register a riziko nesprávneho zaradenia programu.

## Prompt

```text
Posúď, či je nasledujúci vzdelávací program oprávnený podľa priloženého PDF dokumentu:

Názov programu: [názov]
Obsah: [obsah]
Rozsah: [počet hodín]
Forma: [učebňa/live online/hybrid/e-learning]
Miesto realizácie: [miesto]
Cieľové zručnosti: [zručnosti]
Spôsob ukončenia: [test/skúška/praktická ukážka]
Výstupný doklad: [osvedčenie/certifikát/potvrdenie]
Register programu: [AVP/NVP/digitálne a zelené zručnosti/iné]
Poskytovateľ: [údaje]

Vyhodnoť:

1. odborné zameranie,
2. formu realizácie,
3. spôsob overenia výsledkov,
4. výstupný doklad,
5. registráciu programu,
6. oprávnenosť poskytovateľa,
7. riziko, že bude program považovaný za mäkké zručnosti, základné zručnosti, povinné školenie, seminár alebo workshop.

Uveď výsledok „oprávnený“, „pravdepodobne oprávnený“, „rizikový“ alebo „neoprávnený“.
```

---

# 7. Výpočet maximálneho finančného príspevku

## Situácia

Firma potrebuje vypočítať maximálny príspevok a rozsah potrebného predfinancovania.

## Cieľ

Vypočítame náklady na vzdelávaciu službu, náklady zamestnancov a scenáre podľa skutočnej účasti.

## Prompt

```text
Na základe pravidiel v priloženom PDF vypočítaj maximálny finančný príspevok.

Vstupné údaje:

- počet zamestnancov: [počet],
- počet hodín vzdelávania na osobu: [počet],
- počet skutočne absolvovaných hodín: [počet],
- uplatnenie náhrady mzdy: [áno/nie],
- rok realizácie: [rok],
- prípadné absencie: [údaje].

Samostatne vypočítaj:

1. jednotkový náklad na vzdelávaciu službu pri sadzbe 17,33 EUR za hodinu,
2. náklady vzdelávaných zamestnancov pri sadzbe maximálne 7,16 EUR za hodinu pre rok 2026,
3. celkový maximálny príspevok,
4. sumu, ktorú musí zamestnávateľ najskôr financovať z vlastných zdrojov,
5. scenár pri 90 %, 80 % a 70 % účasti.

Uveď vzorce, medzivýpočty a upozornenia na obmedzenia refundácie.
```

---

# 8. Kontrolný zoznam pred podaním žiadosti

## Situácia

Žiadosť je pripravená na odoslanie a potrebujeme vykonať poslednú formálnu a vecnú kontrolu.

## Cieľ

Zabránime vynechaniu povinnej prílohy, nesprávnemu podpisu, podaniu na nepríslušný úrad alebo zmeškaniu termínu.

## Prompt

```text
Vytvor detailný checklist pre zamestnávateľa pred elektronickým podaním žiadosti podľa priloženého PDF.

Rozdeľ ho na:

1. oprávnenosť firmy,
2. oprávnenosť zamestnancov,
3. oprávnenosť poskytovateľa,
4. oprávnenosť programu,
5. rozpočet a de minimis,
6. povinné prílohy,
7. elektronickú schránku a kvalifikovaný elektronický podpis,
8. miestnu príslušnosť úradu,
9. termín podania,
10. internú kontrolu pred odoslaním.

Pri každom bode vytvor políčka:

- splnené,
- nesplnené,
- potrebné doplniť,
- zodpovedná osoba,
- termín.
```

---

# 9. Vypracovanie textovej časti žiadosti

## Situácia

Potrebujeme pripraviť vecný a konkrétny opis projektu do formulára žiadosti.

## Cieľ

Prepojíme potreby firmy, pracovné pozície, vzdelávací program a očakávanú zmenu po vzdelávaní.

## Prompt

```text
Na základe priloženého PDF a nasledujúcich údajov priprav odborný návrh textovej časti žiadosti:

Žiadateľ: [opis firmy]
Východisková situácia: [aktuálny stav]
Pracovné pozície: [pozície]
Identifikovaný problém: [problém]
Vzdelávací program: [program]
Rozvíjané zručnosti: [zručnosti]
Počet zamestnancov: [počet]
Očakávané výsledky: [výsledky]

Spracuj:

1. názov vzdelávacieho projektu,
2. stručný opis žiadateľa,
3. opis a cieľ projektu,
4. účel a očakávané výsledky,
5. východiskovú situáciu,
6. zdôvodnenie výberu programu,
7. spôsob realizácie,
8. situáciu po ukončení vzdelávania,
9. prepojenie na automatizáciu, digitalizáciu, zelenú transformáciu alebo adaptabilitu zamestnancov.

Nepoužívaj všeobecné frázy. Každé tvrdenie previaž s konkrétnou potrebou zamestnávateľa.
```

---

# 10. Hodnotenie kvality projektu očami komisie

## Situácia

Projekt chceme preveriť ešte pred podaním z pohľadu odborného hodnotiteľa.

## Cieľ

Odhalíme slabé tvrdenia, neprimeraný rozpočet, chýbajúce dôkazy a nedostatočné prepojenie na cieľ projektu.

## Prompt

```text
Vystupuj ako odborný hodnotiteľ Výboru pre otázky zamestnanosti a Hodnotiacej komisie. Posúď nasledujúci návrh projektu podľa podmienok priloženého PDF:

[vložiť návrh projektu]

Vyhodnoť:

- súlad s cieľom národného projektu,
- vierohodnosť východiskovej situácie,
- potrebu vzdelávania,
- väzbu na pracovné pozície,
- konkrétnosť očakávaných výsledkov,
- primeranosť rozsahu a rozpočtu,
- oprávnenosť programu,
- hospodárnosť, efektívnosť a účelnosť,
- riziká dvojitého financovania,
- slabé alebo nepreukázané tvrdenia.

Prideľ skóre od 0 do 100 bodov a navrhni konkrétne úpravy, ktoré zvýšia pravdepodobnosť schválenia.
```

---

# 11. Riziková analýza žiadosti

## Situácia

Potrebujeme identifikovať všetky okolnosti, ktoré môžu viesť k zamietnutiu žiadosti alebo nepreplateniu výdavkov.

## Cieľ

Vytvoríme register rizík s preventívnymi opatreniami a zodpovednosťami.

## Prompt

```text
Identifikuj všetky dôvody, pre ktoré môže byť žiadosť podľa priloženého PDF zamietnutá alebo môže dôjsť k nepreplateniu výdavkov.

Rozdeľ riziká na:

- formálne,
- personálne,
- programové,
- finančné,
- časové,
- právne,
- procesné,
- riziká pri vyúčtovaní,
- riziká pri následnej kontrole.

Pri každom riziku uveď:

- opis,
- pravdepodobnosť,
- závažnosť,
- preventívne opatrenie,
- zodpovednú osobu,
- príslušnú stranu PDF.
```

---

# 12. Harmonogram celého procesu

## Situácia

Projektový tím potrebuje chronologický plán od prípravy žiadosti až po archiváciu dokumentácie.

## Cieľ

Zostavíme prehľad lehôt, úloh, zodpovedností a následkov zmeškania termínu.

## Prompt

```text
Z priloženého PDF vytvor chronologický harmonogram od prípravy žiadosti až po archiváciu dokumentácie.

Zahrň:

- podanie žiadosti v 2. kole,
- kontrolu formálnej správnosti,
- prípadnú päťdňovú lehotu na odstránenie nedostatkov,
- hodnotenie žiadosti,
- lehotu na oznámenie výsledku,
- podpis dohody,
- vznik účinnosti dohody po zverejnení v CRZ,
- začatie a ukončenie vzdelávania,
- úhradu nákladov z vlastných zdrojov,
- podanie žiadosti o úhradu,
- refundáciu,
- kontrolu a archiváciu do roku 2036.

Výstup priprav ako tabuľku s termínom, úlohou, zodpovednou osobou, potrebným dokumentom a následkom zmeškania lehoty.
```

---

# 13. Povinnosti po schválení žiadosti

## Situácia

Žiadosť bola schválená a zamestnávateľ potrebuje poznať všetky povinnosti počas realizácie a po ukončení projektu.

## Cieľ

Zabránime porušeniu dohody, strate nároku na refundáciu alebo povinnosti vrátiť príspevok.

## Prompt

```text
Vypíš všetky povinnosti zamestnávateľa po schválení finančného príspevku podľa priloženého PDF.

Rozdeľ ich na:

1. podpis a účinnosť dohody,
2. realizáciu vzdelávania,
3. evidenciu účasti,
4. zmeny projektu,
5. úhradu dodávateľovi,
6. podanie žiadosti o úhradu,
7. povinné podporné doklady,
8. finančnú kontrolu a audit,
9. archiváciu dokumentácie,
10. dôsledky porušenia povinností.

Osobitne označ povinnosti, ktorých nesplnenie môže viesť k úplnému nepreplateniu alebo vráteniu príspevku.
```

---

# 14. FAQ pre zamestnávateľov

## Situácia

Potrebujeme pripraviť zrozumiteľné odpovede na najčastejšie otázky klientov alebo žiadateľov.

## Cieľ

Prevedieme odborný dokument do praktického FAQ s odkazmi na konkrétne strany.

## Prompt

```text
Na základe priloženého PDF vytvor 25 často kladených otázok a presných odpovedí pre zamestnávateľov.

Zahrň otázky o:

- oprávnenosti firmy,
- SZČO,
- pracovných úväzkoch,
- dohodároch a dôchodcoch,
- online vzdelávaní,
- e-learningu,
- digitálnych a mäkkých zručnostiach,
- certifikátoch,
- výške príspevku,
- náhrade mzdy,
- refundácii,
- de minimis,
- termínoch,
- elektronickom podpise,
- prílohách,
- absencii zamestnanca,
- viacerých programoch,
- kontrole a archivácii.

Každá odpoveď musí byť krátka, praktická a musí obsahovať číslo strany dokumentu.
```

---

# 15. Porovnanie s iným projektom alebo predchádzajúcou verziou

## Situácia

Máme viac verzií oznámenia alebo potrebujeme porovnať dve podobné dotačné schémy.

## Cieľ

Identifikujeme skutočné zmeny a ich praktický dopad na žiadateľa.

## Prompt

```text
Porovnaj priložený dokument „Aktualizácia č. 5“ s nasledujúcim dokumentom:

[priložiť predchádzajúcu aktualizáciu alebo iné oznámenie]

Identifikuj:

- nové ustanovenia,
- zrušené ustanovenia,
- zmenené termíny,
- zmeny oprávnených žiadateľov,
- zmeny cieľovej skupiny,
- zmeny oprávnených programov,
- zmeny sadzieb a financovania,
- zmeny príloh,
- nové riziká alebo povinnosti.

Výstup priprav ako tabuľku „pôvodné znenie – nové znenie – praktický dôsledok“. Ak predchádzajúci dokument chýba, nevytváraj domnelé zmeny.
```

---

# 16. Hlavný prompt pre praktické spracovanie projektu

## Situácia

Potrebujeme spracovať celý proces od overenia oprávnenosti až po záverečnú kontrolu žiadosti.

## Cieľ

Použijeme jeden komplexný prompt ako pracovný rámec pre projektového alebo dotačného konzultanta.

## Prompt

```text
Naštuduj celý priložený PDF dokument a vystupuj ako odborný konzultant pre prípravu žiadosti v národnom projekte „Zvyšovanie zručností zamestnancov“.

Na základe údajov o našej firme:
[vložiť údaje]

vykonaj tieto úlohy:

1. over oprávnenosť žiadateľa,
2. over oprávnenosť zamestnancov,
3. over oprávnenosť poskytovateľa a programu,
4. vypočítaj maximálny príspevok,
5. identifikuj chýbajúce údaje a dokumenty,
6. navrhni štruktúru projektu,
7. priprav texty požadované v žiadosti,
8. zostav rozpočet a harmonogram,
9. vytvor checklist podania,
10. vykonaj záverečnú simulovanú kontrolu žiadosti.

Najskôr polož iba otázky, bez ktorých nemožno oprávnenosť a rozpočet spoľahlivo posúdiť. Následne spracuj výsledok v podobe projektovej správy pripravenej na praktické použitie.
```

---

# ✅ Kontrolný zoznam pred použitím promptu

Pred odoslaním promptu si overíme:

- [ ] Používame aktuálnu a účinnú verziu výzvy alebo oznámenia.
- [ ] Priložili sme všetky relevantné prílohy a metodické dokumenty.
- [ ] Nahradili sme placeholdery konkrétnymi údajmi.
- [ ] Údaje o zamestnancoch sú anonymizované, ak nie je potrebná identifikácia.
- [ ] Poznáme právnu formu a vlastnícku štruktúru žiadateľa.
- [ ] Máme údaje o daňových, odvodových a iných záväzkoch.
- [ ] Overili sme poskytovateľa v požadovaných registroch.
- [ ] Poznáme presný názov, rozsah a formu vzdelávacieho programu.
- [ ] Rozlišujeme cenu programu od výšky oprávneného príspevku.
- [ ] Počítame s refundáciou a predfinancovaním z vlastných zdrojov.
- [ ] Evidujeme všetky rozhodujúce termíny a hmotnoprávne lehoty.
- [ ] Každý záver vyžadujeme podložiť konkrétnou stranou dokumentu.
- [ ] Nejasnosti nechávame označené na manuálne overenie.
- [ ] Výsledok kontroluje zodpovedná osoba pred podaním žiadosti.

---

# 📝 Praktické úlohy

## Úloha 1: Analýza oprávnenosti firmy

Pripravíme modelové údaje malej firmy a pomocou promptu č. 3 preveríme všetky podmienky oprávnenosti. Osobitne označíme údaje, ktoré nemožno potvrdiť bez výpisu z registra alebo interného účtovníctva.

## Úloha 2: Výber oprávnených zamestnancov

Vytvoríme anonymizovanú tabuľku zamestnancov s rôznymi úväzkami, pracovnými zmluvami a statusmi. Pomocou promptu č. 4 ich rozdelíme na oprávnených, neoprávnených a zamestnancov vyžadujúcich overenie.

## Úloha 3: Kontrola poskytovateľa

Vyberieme konkrétnu vzdelávaciu organizáciu a podľa promptu č. 5 pripravíme zoznam registrov, dokladov a overení potrebných na potvrdenie jej oprávnenosti.

## Úloha 4: Posúdenie kurzu

Porovnáme prezenčný kurz, živé online vzdelávanie, hybridný kurz a samoštúdium. Pomocou promptu č. 6 určíme, ktoré formy zodpovedajú podmienkam dokumentu.

## Úloha 5: Výpočet príspevku

Vypočítame príspevok pre 5 zamestnancov pri rozsahu 40 hodín. Následne pripravíme scenáre pri rôznej účasti a porovnáme výsledok s potrebným predfinancovaním.

## Úloha 6: Príprava textovej časti

Zostavíme modelovú východiskovú situáciu firmy a pomocou promptu č. 9 pripravíme konkrétny opis problému, cieľa, spôsobu realizácie a očakávanej zmeny.

## Úloha 7: Simulované hodnotenie

Pomocou promptu č. 10 ohodnotíme pripravený návrh projektu. Slabé časti následne prepracujeme a porovnáme pôvodné a nové skóre.

## Úloha 8: Register rizík

Pomocou promptu č. 11 vytvoríme rizikovú maticu. Každému riziku priradíme zodpovednú osobu, preventívne opatrenie a termín kontroly.

## Úloha 9: Harmonogram projektu

Pomocou promptu č. 12 vytvoríme harmonogram od podania žiadosti až po archiváciu. Zvlášť označíme lehoty, ktorých zmeškanie nemožno odpustiť.

## Úloha 10: Záverečná kontrola žiadosti

Použijeme prompt č. 16 a vykonáme kompletnú simuláciu spracovania projektu. Výstup porovnáme s kontrolným zoznamom a doplníme chýbajúce údaje.

---

# 🧠 Zhrnutie

Kvalitné spracovanie grantovej alebo dotačnej výzvy nezačína písaním žiadosti, ale dôkladným overením oprávnenosti žiadateľa, cieľovej skupiny, poskytovateľa, programu a výdavkov. Každý dôležitý záver musíme vedieť podložiť konkrétnym ustanovením alebo stranou oficiálneho dokumentu.

Najdôležitejšie pravidlá sú:

- pracujeme s aktuálnym oficiálnym znením výzvy,
- chýbajúce údaje nevymýšľame,
- oprávnenosť posudzujeme po jednotlivých podmienkach,
- rozpočet počítame zo skutočne oprávnených jednotkových nákladov,
- rozlišujeme schválený príspevok od skutočne refundovanej sumy,
- evidujeme všetky prílohy, termíny a podpisové povinnosti,
- zmeny projektu vykonávame iba podľa podmienok dohody,
- pri vyúčtovaní používame preukázateľné podporné doklady,
- riziká identifikujeme ešte pred podaním žiadosti,
- konečný dokument vždy podrobíme manuálnej kontrole.

---

## ✅ Čo by sme mali vedieť po dokončení cvičenia

Po dokončení cvičenia dokážeme:

- komplexne analyzovať dotačnú alebo grantovú výzvu,
- pripraviť manažérske zhrnutie pre vedenie firmy,
- overiť oprávnenosť zamestnávateľa a zamestnancov,
- preveriť poskytovateľa vzdelávania a konkrétny kurz,
- vypočítať maximálny finančný príspevok,
- zostaviť kontrolný zoznam pred podaním žiadosti,
- pripraviť odbornú textovú časť projektu,
- simulovať hodnotenie projektu odbornou komisiou,
- vytvoriť register rizík a harmonogram,
- riadiť povinnosti po schválení a pri refundácii,
- pripraviť FAQ pre zamestnávateľov,
- porovnať dve verzie výzvy,
- vykonať komplexnú záverečnú kontrolu projektu.
