# 🧪 Google NotebookLM Praktické cvičenia

Praktický repozitár pre online kurz **Google NotebookLM Praktické cvičenia** na mierne pokročilej úrovni. Kurz je určený používateľom, ktorí už vedia vytvoriť notebook, pridať zdroje, používať chat a otvárať citácie. Nezaoberáme sa základným ovládaním. Trénujeme postupy, ktoré pomáhajú získať presnejšie, overiteľné a reálne použiteľné výstupy. V kurze pracujeme najmä s porovnávaním viacerých zdrojov, analýzou prepisov, rozpoznávaním zmien medzi verziami dokumentov, kontrolou citácií a syntézou oficiálnej dokumentácie.

> NotebookLM nepoužívame iba na sumarizovanie. Používame ho na riadenú analýzu zdrojov, porovnávanie tvrdení a tvorbu výstupov, ktoré vieme spätne overiť.

## 📌 Čo je Google NotebookLM

Google NotebookLM je nástroj na prácu s vlastnými zdrojmi. Do notebooku pridáme dokumenty, webové stránky, prepisy videí, zvukové súbory alebo ďalšie podporované materiály a následne nad nimi kladieme otázky, porovnávame tvrdenia a vytvárame výstupy.

Hlavný rozdiel oproti bežnému chatbotu je v tom, že odpovede môžeme viazať na konkrétny súbor zdrojov. NotebookLM pri odpovediach uvádza citácie, cez ktoré vieme prejsť na príslušnú pasáž v zdroji.

NotebookLM však automaticky nerozhoduje:

- ktorý dokument je najaktuálnejší,
- ktorý zdroj je záväzný,
- či citácia podporuje celé tvrdenie,
- či je zdroj odborne správny,
- či sa návrh v zápisnici stal schváleným rozhodnutím.

Preto v tomto kurze trénujeme nielen generovanie odpovedí, ale najmä výber zdrojov, kontrolu dôkazov a audit výsledkov.

## 📌 Základná syntax

NotebookLM nemá programovací jazyk ani príkazovú syntax. Pri praktickej práci však používame opakovateľnú skladbu zadania:

```text
ZDROJE + ÚLOHA + PRAVIDLÁ + FORMÁT VÝSTUPU + KONTROLA
```

Univerzálna šablóna:

```text
Na základe vybraných zdrojov vykonaj túto úlohu:
[čo má NotebookLM zistiť alebo vytvoriť]

Dodrž tieto pravidlá:
- používaj iba informácie zo zdrojov,
- oddeľ fakty od interpretácií,
- rozpory nezlučuj vlastným odhadom,
- chýbajúce informácie označ ako nepotvrdené,
- pri dôležitých tvrdeniach uveď citáciu.

Výstup vytvor vo formáte:
[tabuľka, zoznam, chronológia, matica, briefing, checklist]

Na konci skontroluj:
- ktoré tvrdenia sú priamo podložené,
- ktoré sú odvodené,
- ktoré zostávajú neisté.
```

Praktické pravidlo: kvalitný prompt neurčuje iba tému. Určuje aj zdroje, analytickú úlohu, hranice interpretácie, štruktúru výsledku a spôsob kontroly.

## 🎯 Na čo sa Google NotebookLM používa v praxi

NotebookLM môžeme použiť napríklad na:

- porovnávanie viacerých odborných článkov alebo návodov,
- hľadanie konsenzu a protichodných odporúčaní,
- analýzu prepisov obchodných, výskumných alebo používateľských rozhovorov,
- vytváranie chronológie udalostí z viacerých dokumentov,
- porovnávanie starej a novej verzie smernice, zmluvy alebo metodiky,
- rozlíšenie schválených rozhodnutí od návrhov a diskusných bodov,
- vytvorenie registra požiadaviek, rizík, námietok alebo otvorených otázok,
- syntézu oficiálnej dokumentácie do praktického pracovného postupu,
- prípravu briefingu pre vedenie, checklistu pre realizátora alebo podkladov pre školenie,
- audit tvrdení a kontrolu, či citácie podporujú celý záver.

NotebookLM je najužitočnejší vtedy, keď máme viacero zdrojov a potrebujeme z nich vytvoriť kontrolovateľný výstup. Menej užitočný je pri otázkach, na ktoré sme neposkytli relevantné alebo dostatočne kvalitné zdroje.

## 🧾 Praktické príklady promptov

### Porovnanie viacerých zdrojov

```text
Porovnaj všetky vybrané zdroje.

Vytvor tabuľku so stĺpcami:
- téma,
- spoločné tvrdenie,
- odlišné alebo protichodné tvrdenie,
- zdroj,
- dôkaz,
- miera istoty.

Rozpory nezlučuj vlastným odhadom. Ak sa zdroje nezhodujú, zachovaj obe verzie.
```

### Porovnanie dvoch verzií dokumentu

```text
Porovnaj starú a novú verziu dokumentu.

Každú zmenu zaraď do jednej kategórie:
- pridané,
- odstránené,
- upravené,
- nezmenené,
- nejasné.

Pri každej zmene uveď pôvodné znenie, nové znenie, praktický dôsledok a citáciu z oboch verzií.
```

### Analýza rozhovorov

```text
Analyzuj vybrané prepisy rozhovorov.

Vytvor maticu:
- potreba alebo problém zákazníka,
- presný dôkaz z rozhovoru,
- otázka obchodníka,
- reakcia obchodníka,
- výsledok reakcie,
- lepšia alternatíva.

Nepoužívaj všeobecné hodnotenia bez konkrétnej pasáže z prepisu.
```

### Audit citácií

```text
Vyber päť najdôležitejších tvrdení z odpovede.

Pri každom tvrdení uveď:
- citovaný zdroj,
- presnú podporu v zdroji,
- či ide o priamu alebo nepriamu podporu,
- či citácia podporuje celé tvrdenie,
- možné riziko nesprávneho výkladu.

Ak citácia podporuje iba časť tvrdenia, označ tvrdenie ako čiastočne podložené.
```

Ďalšie promptové vzory sú v súbore [`04_Tahak_prompty.md`](materials/04_Tahak_prompty.md).

## ✅ Čo si v kurze precvičíme

Po absolvovaní kurzu dokážeme:

- porovnať viacero odborných návodov a nájsť spoločné aj protichodné odporúčania,
- analyzovať prepisy rozhovorov bez všeobecných a nepodložených hodnotení,
- oddeliť platné pravidlá od návrhov, diskusných bodov a zastaraných informácií,
- vytvoriť maticu dôkazov s odkazmi na konkrétne zdroje,
- odlíšiť fakt, interpretáciu, výpočet a odporúčanie,
- overiť, či citácia podporuje celé tvrdenie alebo iba jeho časť,
- pripraviť výstup pre konkrétnu cieľovú skupinu,
- zostaviť odbornú syntézu z oficiálnej dokumentácie,
- rozpoznať prípady, keď výsledok pôsobí presvedčivo, ale nie je dostatočne podložený.

## 🧩 Obsah kurzu

Kurz pozostáva zo štyroch samostatných laboratórií.

| Laboratórium | Praktická situácia | Hlavný výstup |
|---|---|---|
| LAB A | Porovnanie odborných návodov | konsenzus, rozdiely a optimalizovaný workflow |
| LAB B | Analýza konzultačných rozhovorov | matica potrieb, námietok a koučovacích odporúčaní |
| LAB C | Porovnanie verzií smernice | zmenový protokol a oddelenie návrhov od platných pravidiel |
| LAB D | Syntéza oficiálnej dokumentácie | matica funkcií, obmedzení a odporúčaných postupov |

### LAB A: Porovnanie odborných návodov

Pracujeme s tromi rozdielnymi návodmi na používanie NotebookLM. Každý autor zdôrazňuje inú pracovnú filozofiu.

Úlohou nie je vytvoriť tri samostatné zhrnutia. Hľadáme:

- odporúčania, na ktorých sa autori zhodujú,
- odporúčania, v ktorých si odporujú,
- unikátne tipy jednotlivých autorov,
- slabé alebo neoverené tvrdenia,
- kroky vhodné na zostavenie jedného lepšieho workflow.

Výstupom je porovnávacia matica a vlastný optimalizovaný pracovný postup.

### LAB B: Analýza rozhovorov

Pracujeme s tromi modelovými obchodnými a konzultačnými rozhovormi.

Rozhovory sú zámerne rozdielne:

- kvalitná diagnostika potrieb,
- prezentovanie funkcií bez pochopenia problému,
- dobrá analýza bez jasne dohodnutého ďalšieho kroku.

Výstupom je:

- zoznam potrieb zákazníka,
- register námietok,
- hodnotenie reakcií obchodníka,
- dôkazy z konkrétnych pasáží,
- praktický koučovací plán.

### LAB C: Porovnanie verzií

Pracujeme s dvoma verziami internej smernice a so zápisnicou zo schvaľovania zmien.

Trénujeme rozdiel medzi týmito kategóriami:

- pravidlo platné v pôvodnej verzii,
- pravidlo platné v novej verzii,
- schválená zmena,
- zamietnutý návrh,
- odložené rozhodnutie,
- nejasná alebo konfliktná informácia.

Výstupom je zmenový protokol, ktorý neprezentuje diskutovaný návrh ako platné pravidlo.

### LAB D: Odborná syntéza

Pracujeme s oficiálnou dokumentáciou NotebookLM.

Nehľadáme všeobecný opis produktu. Z dokumentácie extrahujeme:

- pracovné situácie,
- odporúčané funkcie,
- presný postup,
- dôležité obmedzenia,
- podmienky účtu alebo dostupnosti,
- riziká nesprávneho použitia.

Výstupom je prevádzkový návod pre mierne pokročilého používateľa.

## 🗂️ Štruktúra repozitára

```text
notebook-lab/
├── README.md
└── materials/
    ├── 01_Lektorsky_scenar.md
    ├── 02_Pracovny_zosit_ucastnika.md
    ├── 03_Riesenia_a_hodnotenie.md
    ├── 04_Tahak_prompty.md
    ├── LAB_A_Porovnanie_navodov/
    │   ├── A1_... až A3_...      # offline prepisy odborných návodov
    │   ├── A4_...                # zadanie a kontrolné kritériá
    │   └── A5_...                # verejné YouTube zdroje
    ├── LAB_B_Analyza_rozhovorov/
    │   ├── B1_... až B3_...      # modelové rozhovory
    │   └── B4_...                # zadanie a kontrolné kritériá
    ├── LAB_C_Porovnanie_verzii/
    │   ├── C1_...                # smernica, verzia 1
    │   ├── C2_...                # smernica, verzia 2
    │   ├── C3_...                # zápisnica zo schvaľovania
    │   └── C4_...                # zadanie a kontrolné kritériá
    └── LAB_D_Oficialna_synteza/
        ├── D1_...                # zoznam oficiálnych zdrojov
        └── D2_...                # zadanie a kontrolné kritériá
```

Hlavné materiály:

- [`01_Lektorsky_scenar.md`](materials/01_Lektorsky_scenar.md) - presný postup, časovanie a inštrukcie pre lektora,
- [`02_Pracovny_zosit_ucastnika.md`](materials/02_Pracovny_zosit_ucastnika.md) - zadania, prompty a priestor na výsledky,
- [`03_Riesenia_a_hodnotenie.md`](materials/03_Riesenia_a_hodnotenie.md) - vzorové riešenia a hodnotiace kritériá,
- [`04_Tahak_prompty.md`](materials/04_Tahak_prompty.md) - opakovateľné promptové vzory.

## 🚀 Rýchly štart

Repozitár si môžeme naklonovať:

```bash
git clone https://github.com/miroslav-reiter/notebook-lab.git
cd notebook-lab
```

Pre každé laboratórium odporúčame vytvoriť samostatný notebook. Pri kratšom školení môžeme použiť jeden notebook, ale vždy necháme aktívne iba zdroje potrebné pre konkrétne cvičenie.

Základný postup:

1. Otvoríme príslušný adresár laboratória.
2. Pridáme zdrojové súbory do NotebookLM.
3. Otvoríme zadanie v pracovnom zošite.
4. Spustíme prvý analytický prompt.
5. Výstup porovnáme so vzorovým riešením.
6. Manuálne otvoríme citácie pri rozhodujúcich tvrdeniach.
7. Zapíšeme chyby, nejasnosti a nepodložené závery.

## 🧠 Praktický analytický workflow

Pri každom laboratóriu používame rovnakú logiku:

```text
výber zdrojov
    ↓
extrakcia faktov
    ↓
porovnanie a hľadanie rozporov
    ↓
interpretácia
    ↓
odporúčanie alebo cieľový výstup
    ↓
audit citácií
```

Nevytvárame finálne odporúčanie hneď v prvom prompte. Najskôr získame fakty a dôkazy, až potom vytvárame interpretáciu.

### Prompt na porovnanie zdrojov

```text
Porovnaj všetky vybrané zdroje.

Vytvor tabuľku so stĺpcami:
- téma,
- spoločné tvrdenie,
- odlišné alebo protichodné tvrdenie,
- zdroj,
- dôkaz,
- miera istoty.

Rozpory nezlučuj vlastným odhadom. Ak sa zdroje nezhodujú, zachovaj obe verzie.
```

### Prompt na oddelenie faktov od interpretácií

```text
Rozdeľ zistenia do štyroch kategórií:
- fakt priamo uvedený v zdroji,
- výpočet odvodený zo zdrojových údajov,
- interpretácia,
- odporúčanie.

Pri každom bode uveď zdroj alebo vysvetli, že ide o vlastnú interpretáciu.
```

### Prompt na audit citácií

```text
Vyber päť najdôležitejších tvrdení z odpovede.

Pri každom tvrdení uveď:
- citovaný zdroj,
- presnú podporu v zdroji,
- či ide o priamu alebo nepriamu podporu,
- či citácia podporuje celé tvrdenie,
- možné riziko nesprávneho výkladu.
```

Ďalšie promptové vzory sú v súbore [`04_Tahak_prompty.md`](materials/04_Tahak_prompty.md).

## ✅ Kritériá kvalitného výstupu

Výstup považujeme za kvalitný, keď:

- odpovedá na konkrétnu otázku,
- používa iba relevantné zdroje,
- oddeľuje fakty od interpretácií,
- zachováva konfliktné tvrdenia namiesto ich umelého zjednotenia,
- obsahuje citácie pri rozhodujúcich údajoch,
- citácia podporuje celé tvrdenie,
- nevymýšľa chýbajúce dátumy, čísla alebo rozhodnutia,
- označuje neistotu a chýbajúce informácie,
- používa terminológiu vhodnú pre cieľovú skupinu,
- vedie ku konkrétnemu a kontrolovateľnému výsledku.

### Hodnotenie laboratória

| Oblasť | Body |
|---|---:|
| Správny výber zdrojov | 2 |
| Zachytenie hlavných faktov | 2 |
| Rozpoznanie rozporov alebo zmien | 2 |
| Správne použitie citácií | 2 |
| Použiteľnosť výsledného výstupu | 2 |
| **Spolu** | **10** |

Podrobné riešenia a hodnotiaca rubrika sú v súbore [`03_Riesenia_a_hodnotenie.md`](materials/03_Riesenia_a_hodnotenie.md).

## ⚠️ Časté chyby pri práci s NotebookLM

### Zapnutie všetkých zdrojov bez dôvodu

Viac zdrojov neznamená automaticky lepšiu odpoveď. Pri konkrétnej úlohe nechávame aktívne iba relevantné dokumenty.

### Jeden veľký prompt na celý problém

Prompt typu „analyzuj všetko a navrhni riešenie“ často zmieša fakty, interpretácie a odporúčania. Používame viac krokov.

### Citácia ako automatický dôkaz správnosti

Citácia dokazuje, že sa tvrdenie nachádza v zdroji. Nedokazuje, že zdroj je aktuálny, správny alebo záväzný.

### Zlúčenie konfliktných verzií

Pri porovnávaní dokumentov môže vzniknúť jedna hladká, ale nepresná verzia. V prompte výslovne požadujeme zachovanie rozporov.

### Zamieňanie návrhu za rozhodnutie

Zápisnica môže obsahovať diskutovaný, zamietnutý aj schválený návrh. Nestačí nájsť vetu. Musíme overiť jej stav.

### Hodnotenie bez dôkazu

Pri analýze rozhovorov nepoužívame všeobecné závery typu „obchodník komunikoval zle“. Vyžadujeme konkrétnu pasáž a vysvetlenie jej dôsledku.

## 🔒 Bezpečnosť a ochrana údajov NotebookLM

Cvičné rozhovory, smernice a zápisnice v tomto repozitári sú modelové vzdelávacie dáta.

Pri práci s vlastnými materiálmi dodržiavame tieto pravidlá:

- nevkladáme heslá, API kľúče, prístupové tokeny ani prihlasovacie údaje,
- anonymizujeme mená, e-mailové adresy, telefónne čísla a identifikátory zákazníkov,
- nepoužívame reálne obchodné rozhovory bez oprávnenia,
- kontrolujeme interné pravidlá organizácie pre používanie AI nástrojov,
- pri citlivých dokumentoch overujeme, kto má k notebooku a výstupom prístup,
- pred zdieľaním manuálne skontrolujeme citácie aj obsah výsledného dokumentu.

## 📚 Oficiálne zdroje a dokumentácia NotebookLM

Funkcie NotebookLM sa priebežne menia. Pred školením preto kontrolujeme aktuálnu dokumentáciu.

- NotebookLM Help: https://support.google.com/notebooklm/
- Add or discover new sources: https://support.google.com/notebooklm/answer/16215270
- Use chat in NotebookLM: https://support.google.com/notebooklm/answer/16179559
- Create and manage notes: https://support.google.com/notebooklm/answer/16262519
- Generate Audio Overviews: https://support.google.com/notebooklm/answer/16212820
- Generate Slide Decks: https://support.google.com/notebooklm/answer/16757456

Kompletný pracovný zoznam zdrojov je uložený v adresári [`LAB_D_Oficialna_synteza`](materials/LAB_D_Oficialna_synteza/).

## 📖 Knihy o Google NotebookLM

Nasledujúce tituly sú nezávislé príručky dostupné na Amazone. Nejde, ale o oficiálne publikácie spoločnosti Google.

| Kniha | ASIN | Formát | Odkaz |
|---|---|---|---|
| **NotebookLM Beginner's Guide: Note-Taking and Productivity** | `B0FHGJFWG9` | Kindle eBook | [Amazon](https://www.amazon.com/NotebookLM-Beginners-Guide-Note-Taking-Productivity-ebook/dp/B0FHGJFWG9) |
| **A Complete Guide to Google Notebook LM** | `B0F6FMMTR3` | Kindle eBook | [Amazon](https://www.amazon.com/Complete-Guide-Google-Notebook-LM-ebook/dp/B0F6FMMTR3) |
| **NotebookLM Mastery: Welcome to Your Second Brain** | `B0GQQRNPYR` | Kindle eBook | [Amazon](https://www.amazon.com/NotebookLM-Mastery-Welcome-second-Everyday-ebook/dp/B0GQQRNPYR/) |
| **Mastering Google NotebookLM: Documents and Answers** | `B0GYKKVZF1` | Kindle eBook | [Amazon](https://www.amazon.com/Mastering-Google-NotebookLM-Documents-Answers-ebook/dp/B0GYKKVZF1/) |
