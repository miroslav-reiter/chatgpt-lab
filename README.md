# 🤖 Praktické používanie AI ChatGPT

Praktický repozitár pre kurz **Praktické používanie AI ChatGPT**. Materiály sú určené pre začiatočníkov a mierne pokročilých používateľov, ktorí chcú používať ChatGPT systematicky, opakovateľne a bezpečne.

Kurz sa nezameriava iba na písanie jednotlivých otázok. Trénujeme celý pracovný postup:

```text
CIEĽ + KONTEXT + VSTUPY + PRAVIDLÁ + FORMÁT + KONTROLA
```

> Kvalitný výstup nevzniká náhodou. Vzniká z jasného zadania, vhodného kontextu, správneho nastavenia a následnej kontroly.

## 📌 Čo je OpenAI ChatGPT

OpenAI ChatGPT je konverzačný asistent založený na umelej inteligencii. Môžeme ho používať pri brainstormingu, písaní a úprave textov, štúdiu, plánovaní, programovaní, matematike, analýze obrázkov a súborov a pri ďalších pracovných alebo osobných úlohách.

ChatGPT pracuje podľa pokynov, ktoré zadávame v prirodzenom jazyku. V rámci konverzácie používa dostupný kontext a podľa plánu, platformy, regiónu a nastavení môže využívať ďalšie funkcie, napríklad nahrávanie súborov, vyhľadávanie na webe, hlas, tvorbu obrázkov, projekty, vlastné inštrukcie alebo pamäť.

ChatGPT nie je automaticky autoritatívnym zdrojom pravdy. Odpoveď môže byť presvedčivá, ale nepresná, neúplná alebo zastaraná. Dôležité tvrdenia preto overujeme v dôveryhodných a aktuálnych zdrojoch.

## 📌 Čo sa v kurze naučíme

Po absolvovaní kurzu dokážeme:

- rozlíšiť prompt, vlastné inštrukcie, osobnosť a pamäť,
- vytvoriť kvalitný prompt s cieľom, kontextom, formátom a obmedzeniami,
- používať placeholdery a vytvárať opakovateľné promptové šablóny,
- pripraviť ChatGPT na úlohu bez zbytočného generovania textu,
- analyzovať PDF dokument krokovým postupom,
- upraviť tón, cieľovú skupinu, dĺžku a formát výstupu,
- vytvoriť vlastné inštrukcie pre dlhodobý spôsob spolupráce,
- rozlíšiť dobrú vlastnú inštrukciu od príliš všeobecnej,
- používať ChatGPT pri copywritingu, komunikácii, práci, plánovaní a kreativite,
- overovať dôležité fakty a rozpoznať situácie, keď odpoveď nemáme automaticky považovať za správnu.

## 🧩 Štyri vrstvy prispôsobenia ChatGPT

| Vrstva | Účel | Platnosť | Príklad |
|---|---|---|---|
| **Prompt** | Konkrétna aktuálna úloha | Jedna úloha alebo konverzácia | „Napíš e-mail zákazníkovi...“ |
| **Vlastné inštrukcie** | Trvalé pravidlá práce | Naprieč ďalšími chatmi | Jazyk, tón, dĺžka, formát |
| **Osobnosť a štýl** | Spôsob vyjadrovania asistenta | Podľa nastavenia účtu | Profesionálny alebo neutrálny tón |
| **Pamäť** | Zapamätané informácie pre personalizáciu | Naprieč konverzáciami | Stabilné preferencie a pracovný kontext |

Tieto vrstvy sa dopĺňajú. Jednorazovú úlohu nevkladáme do vlastných inštrukcií. Citlivé údaje nevkladáme ani do promptov, ani do dlhodobých nastavení.

## 📌 Základná skladba kvalitného promptu

```text
ÚLOHA
Čo má ChatGPT vytvoriť alebo zistiť?

KONTEXT
Pre koho, na aký účel a v akej situácii výstup vzniká?

VSTUPY
Aké údaje, dokumenty, texty alebo požiadavky má použiť?

PRAVIDLÁ
Čo musí dodržať a čomu sa má vyhnúť?

FORMÁT
Ako má výsledok vyzerať?

KONTROLA
Čo má pred odovzdaním skontrolovať alebo označiť ako neisté?
```

Príklad:

```text
Napíš stručný e-mail zákazníkovi, ktorý mešká s platbou.

Kontext:
Ide o dlhodobého zákazníka. Chceme zachovať korektný obchodný vzťah.

Pravidlá:
- tón vecný a slušný,
- bez vyhrážok,
- uveď faktúru a nový termín úhrady,
- maximálne 140 slov.

Formát:
Predmet e-mailu a telo e-mailu.

Kontrola:
Nepoužívaj právne tvrdenia, ktoré nevyplývajú zo zadania.
```

## 🎯 Praktické oblasti použitia

### Copywriting a obsah

- návrhy tém pre blog a sociálne siete,
- sumarizácia dokumentov,
- úprava textu pre cieľové publikum,
- redakčné plány a harmonogramy,
- testy, kvízy a spätná väzba.

### Komunikácia

- pracovné e-maily,
- pozvánky a poďakovania,
- zdvorilé odmietnutia,
- úprava tónu správy,
- príprava argumentov do diskusie.

### Nákup, predaj a pracovné situácie

- text pracovnej ponuky,
- analýza námietok zákazníkov,
- príprava na pracovný pohovor,
- žiadosť o cenovú ponuku,
- komunikácia pri zmene termínu projektu.

### Plánovanie a kreativita

- návrh aktivít,
- plán cesty alebo podujatia,
- brainstorming názvov,
- tvorba príbehov,
- návrh jednoduchých vizuálnych alebo textových konceptov.

## 🧪 Obsah laboratórií

| Laboratórium | Hlavná téma | Výstup |
|---|---|---|
| **LAB A** | Kvalitný prompt a iterácie | prompt v šiestich vrstvách a jeho zlepšená verzia |
| **LAB B** | Placeholdery a opakovateľné šablóny | katalóg promptov pre viac situácií |
| **LAB C** | Vlastné inštrukcie a prispôsobenie | vlastná sada pravidiel a kontrolný test |
| **LAB D** | Analýza PDF a kontrola odpovede | štruktúrované zhrnutie, riziká a overenie |

## 🗂️ Štruktúra repozitára

```text
chatgpt-lab/
├── README.md
└── materials/
    ├── 00_START_HERE.md
    ├── 01_Lektorsky_scenar.md
    ├── 02_Pracovny_zosit_ucastnika.md
    ├── 03_Riesenia_a_hodnotenie.md
    ├── 04_Tahak_prompty.md
    ├── 05_Otazky_a_odpovede.md
    ├── 06_Bezpecnost_a_overovanie.md
    ├── LAB_A_Promptovanie/
    │   ├── A1_Zadanie.md
    │   └── A2_Ukazkove_prompty.md
    ├── LAB_B_Placeholdery/
    │   ├── B1_Zadanie.md
    │   └── B2_Katalog_sablon.md
    ├── LAB_C_Vlastne_instrukcie/
    │   ├── C1_Zadanie.md
    │   └── C2_Sablony.md
    └── LAB_D_PDF_a_prakticke_ulohy/
        ├── D1_Zadanie.md
        └── D2_Riesenie.md
```

Hlavné materiály:

- [`01_Lektorsky_scenar.md`](materials/01_Lektorsky_scenar.md) - časovanie, postup a debrief pre lektora,
- [`02_Pracovny_zosit_ucastnika.md`](materials/02_Pracovny_zosit_ucastnika.md) - úlohy, tabuľky a priestor na výsledky,
- [`03_Riesenia_a_hodnotenie.md`](materials/03_Riesenia_a_hodnotenie.md) - vzorové riešenia a hodnotiaca rubrika,
- [`04_Tahak_prompty.md`](materials/04_Tahak_prompty.md) - opakovateľné promptové vzory,
- [`05_Otazky_a_odpovede.md`](materials/05_Otazky_a_odpovede.md) - desať kontrolných otázok s odpoveďami,
- [`06_Bezpecnost_a_overovanie.md`](materials/06_Bezpecnost_a_overovanie.md) - pravidlá ochrany údajov a overovania výstupov.

## 🚀 Rýchly štart

Repozitár si môžeme naklonovať:

```bash
git clone https://github.com/miroslav-reiter/chatgpt-lab.git
cd chatgpt-lab
```

Odporúčaný postup účastníka:

1. Otvoríme [`00_START_HERE.md`](materials/00_START_HERE.md).
2. Vyberieme príslušné laboratórium.
3. Skopírujeme prompt do nového chatu.
4. Doplníme všetky placeholdery v hranatých zátvorkách.
5. Výstup porovnáme s kontrolnými kritériami.
6. Upravíme prompt, nie iba výsledný text.
7. Dôležité fakty manuálne overíme.

## 🧠 Praktický workflow

```text
určenie cieľa
    ↓
doplnenie kontextu a vstupov
    ↓
určenie pravidiel a formátu
    ↓
prvé vygenerovanie
    ↓
kontrola chýb a medzier
    ↓
úprava promptu
    ↓
finálny a overený výstup
```

Nezačíname vetou „napíš mi niečo o téme“. Najskôr určujeme, čo má byť výsledkom, pre koho vzniká a podľa čoho spoznáme, že je použiteľný.

## ✅ Kritériá kvalitného výstupu

Výstup považujeme za kvalitný, keď:

- rieši presne zadanú úlohu,
- zohľadňuje cieľovú skupinu a účel,
- dodržiava požadovaný tón, dĺžku a formát,
- nevymýšľa chýbajúce údaje,
- označuje neistotu alebo informačné medzery,
- neobsahuje citlivé údaje bez dôvodu,
- oddeľuje fakty, predpoklady a odporúčania,
- používa konkrétne príklady namiesto všeobecných fráz,
- upozorňuje na relevantné riziká,
- umožňuje praktické použitie bez rozsiahleho prepisovania.

## ⚠️ Časté chyby

### Príliš všeobecné zadanie

```text
Napíš mi lepší text.
```

Model nevie, čo znamená „lepší“. Chýba cieľ, publikum, tón, rozsah aj formát.

### Jeden prompt na príliš veľa krokov

Pri rozsiahlej úlohe rozdelíme prácu na analýzu, návrh, kontrolu a finálnu verziu.

### Jednorazová úloha vo vlastných inštrukciách

Vlastné inštrukcie používame na stabilné pravidlá, nie na dočasný projekt alebo jednu správu.

### Zdieľanie citlivých údajov

Nevkladáme heslá, prístupové tokeny, osobné čísla, interné tajomstvá ani údaje, na ktorých spracovanie nemáme oprávnenie.

### Automatická dôvera v odpoveď

Plynulý a profesionálne znejúci text nie je automaticky správny. Pri právnych, finančných, zdravotných, technických a časovo citlivých informáciách vykonáme kontrolu zdrojov.

## 🔒 Bezpečnosť a ochrana údajov

Pri práci s ChatGPT:

- anonymizujeme osobné údaje,
- používame modelové alebo verejné dáta na školeniach,
- neuvádzame prihlasovacie údaje ani tajomstvá,
- kontrolujeme interné pravidlá organizácie,
- pri citlivých úlohách zvážime dočasný chat,
- pred zdieľaním výstupu odstránime citlivý kontext,
- dôležité tvrdenia overujeme v autoritatívnom zdroji.

## ⌨️ Praktické ovládanie

- **Enter** odošle správu a vyvolá odpoveď.
- **Shift + Enter** vloží nový riadok bez odoslania.

Názvy položiek rozhrania a dostupnosť funkcií sa môžu líšiť podľa platformy, jazyka, účtu a aktuálnej verzie ChatGPT.

## 📚 Zdroj kurzu

Repozitár vychádza z prezentácie **Praktické používanie AI ChatGPT**. Materiály sú prepracované do formy lektorského scenára, pracovného zošita, laboratórií, promptových šablón, riešení a hodnotiacich kritérií.

Ceny, názvy modelov, limity a konkrétne prvky používateľského rozhrania sa priebežne menia. Preto ich nepovažujeme za stabilnú súčasť metodiky. Pred školením vždy overíme aktuálny stav priamo v používanom účte a v oficiálnej dokumentácii OpenAI.

## 📚 Oficiálne zdroje a dokumentácia ChatGPT

Funkcie, názvy nastavení, limity a dostupnosť sa priebežne menia. Pred školením preto kontrolujeme aktuálnu dokumentáciu OpenAI.

- [Čo je ChatGPT: FAQ](https://help.openai.com/en/articles/12677804-what-is-chatgpt-faq)
- [Vlastné pokyny ChatGPT](https://help.openai.com/sk-sk/articles/8096356-custom-instructions-for-chatgpt)
- [Časté otázky o pamäti](https://help.openai.com/sk-sk/articles/8590148)
- [Temporary Chat FAQ](https://help.openai.com/en/articles/8914046-temporary-chat-faq)
- [Data Controls FAQ](https://help.openai.com/en/articles/7730893-data-controls-faq)
- [ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)
- [OpenAI Help Center](https://help.openai.com/)

## 📖 Knihy o ChatGPT

Nasledujúce knihy sú nezávislé publikácie. Nejde o oficiálne knihy spoločnosti OpenAI a konkrétne opisy rozhrania alebo modelov môžu časom zastarať.

| Kniha | Autor | Vydavateľstvo a rok | ISBN | Zameranie |
|---|---|---|---|---|
| [ChatGPT For Dummies, 2nd Edition](https://books.google.com/books/about/ChatGPT_For_Dummies.html?id=9sFIEQAAQBAJ) | Pam Baker | Wiley, 2025 | `9781394314454` | praktické používanie ChatGPT, prompty, text, médiá a pracovné úlohy |
| [Prompt Engineering for Generative AI](https://www.oreilly.com/library/view/prompt-engineering-for/9781098153427/) | James Phoenix, Mike Taylor | O’Reilly Media, 2024 | `9781098153427` | systematické navrhovanie promptov, hodnotenie výstupov a automatizácia |
| [Co-Intelligence: Living and Working with AI](https://www.penguinrandomhouse.com/books/741805/co-intelligence-by-ethan-mollick/) | Ethan Mollick | Portfolio, 2024 | `9780593716717` | praktická spolupráca človeka s generatívnou AI v práci a vzdelávaní |
