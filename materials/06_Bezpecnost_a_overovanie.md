# Bezpečnosť, súkromie a overovanie výstupov

## Základné pravidlo

ChatGPT používame ako pracovný nástroj, nie ako automatický zdroj pravdy. Plynulá a profesionálne znejúca odpoveď môže byť neúplná, neaktuálna alebo nesprávna.

## Čo nevkladáme do promptov ani nastavení

- heslá,
- API kľúče a prístupové tokeny,
- čísla platobných kariet,
- rodné čísla a osobné identifikátory,
- interné obchodné tajomstvá,
- zdravotné alebo personálne údaje bez oprávnenia,
- zmluvy a dokumenty, ktoré nemáme právo spracovať,
- údaje klientov bez anonymizácie.

## Anonymizácia

Pred vložením pracovného materiálu:

1. nahradíme mená neutrálnymi označeniami,
2. odstránime e-mailové adresy a telefónne čísla,
3. nahradíme identifikátory modelovými hodnotami,
4. odstránime interné URL a prihlasovacie údaje,
5. znížime rozsah dokumentu na nevyhnutné minimum.

Príklad:

```text
Nevhodné:
Ján Novák, j.novak@firma.sk, zákazník č. 583917, dlhuje 4 230 eur.

Vhodnejšie:
Zákazník A, modelový prípad, neuhradená suma 4 230 eur.
```

## Kedy používame dočasný chat

Dočasný chat môžeme použiť pri jednorazovej úlohe, keď nechceme, aby sa konverzácia využila na dlhodobú personalizáciu. Ani dočasný chat však nie je dôvodom vkladať údaje, ktoré nemáme právo spracovať.

Dostupnosť a správanie tejto funkcie sa môže líšiť podľa účtu a aktuálnej verzie produktu.

## Päť úrovní kontroly odpovede

### 1. Kontrola zadania

- Bol cieľ jednoznačný?
- Dostala AI potrebné vstupy?
- Určili sme formát a obmedzenia?
- Nevytvorili sme konflikt medzi pokynmi?

### 2. Kontrola obsahu

- Odpoveď rieši otázku?
- Neobsahuje nevyžiadané domnienky?
- Sú čísla, dátumy a mená správne?
- Nezamenila odporúčanie za fakt?

### 3. Kontrola zdrojov

- Máme autoritatívny zdroj?
- Je zdroj aktuálny?
- Podporuje zdroj celé tvrdenie alebo iba jeho časť?
- Nejde o sekundárnu interpretáciu bez dôkazu?

### 4. Kontrola rizika

- Môže nesprávna odpoveď spôsobiť finančnú, právnu, zdravotnú alebo reputačnú škodu?
- Potrebujeme odborníka alebo schválenie zodpovednej osoby?
- Je výsledok vhodný na automatické použitie?

### 5. Kontrola pred zdieľaním

- Nezostali vo výstupe osobné údaje?
- Nezostali tam interné pokyny alebo dôverný kontext?
- Je jasné, ktoré časti sú predpoklady?
- Je výstup vhodný pre cieľového príjemcu?

## Rizikové typy úloh

Pri nasledujúcich oblastiach vždy vykonáme externé overenie:

- právne požiadavky,
- dane a účtovníctvo,
- zdravotné rozhodnutia,
- investície a finančné záväzky,
- kybernetická bezpečnosť,
- pracovnoprávne otázky,
- aktuálne ceny, limity a produktové funkcie,
- termíny, lehoty a regulačné povinnosti.

## Prompt na kontrolu neistoty

```text
Skontroluj predchádzajúcu odpoveď.

Rozdeľ tvrdenia na:
- priamo podložené vstupmi,
- pracovné predpoklady,
- odporúčania,
- časovo citlivé informácie,
- informácie vyžadujúce externé overenie.

Pri každom rizikovom tvrdení uveď, aký typ zdroja máme použiť na overenie.
Nevymýšľaj zdroje ani citácie.
```

## Prompt na kontrolu citlivých údajov

```text
Skontroluj nasledujúci text pred zdieľaním.
Označ možné osobné, dôverné, bezpečnostné alebo obchodne citlivé údaje.

Výstup vytvor v tabuľke:
- údaj,
- typ rizika,
- dôvod,
- odporúčaná anonymizácia.

Text neupravuj, kým nepotvrdím navrhované zmeny.
```

## Kontrolný zoznam pred odovzdaním

- [ ] Použili sme iba údaje, ktoré môžeme spracovať.
- [ ] Osobné údaje sú anonymizované.
- [ ] Kritické čísla a dátumy sú overené.
- [ ] Fakty sú oddelené od odporúčaní.
- [ ] Predpoklady sú označené.
- [ ] Výstup neobsahuje vymyslené citácie.
- [ ] Časovo citlivé údaje sú skontrolované.
- [ ] Formát zodpovedá cieľovej skupine.
- [ ] Výstup skontroloval človek.
- [ ] Vieme obhájiť, z akých vstupov záver vznikol.
