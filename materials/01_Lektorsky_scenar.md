**Lektorský scenár | 90 minút | úroveň mierne pokročilý**

# Charakter kurzu

Kurz je postavený na štyroch laboratóriách odvodených z verejne zdokumentovaných spôsobov použitia NotebookLM: porovnanie odborných zdrojov, analýza prepisov, sledovanie zmien dokumentov a syntéza oficiálnej dokumentácie. Nepoužívame cvičenia typu „zhrň PDF“. Každá úloha končí kontrolovateľným pracovným výstupom.

| **Vstupná podmienka:** Účastník už vie vytvoriť notebook, pridať zdroje, používať chat a otvoriť citáciu. |
|-----------------------------------------------------------------------------------------------------------|

# Ciele

- Porovnáme viaceré zdroje a oddelíme konsenzus, rozdiely a výnimky.
- Vytvoríme koučovací výstup z prepisov rozhovorov bez nepodloženého hodnotenia.
- Rozlíšime schválenú zmenu, návrh, zamietnutý návrh a odloženú otázku.
- Z oficiálnej dokumentácie vytvoríme prevádzkový návod s obmedzeniami.
- Skontrolujeme, či citácia podporuje celé tvrdenie, nie iba jeho časť.

# Časový plán

| **Čas** | **Laboratórium** | **Výstup** |
|---|---|---|
| 0 - 5 min | Nastavenie a pravidlá | Notebooky, zdroje, pravidlo dôkazov |
| 5 - 23 min | LAB A: porovnanie odborných návodov | Konsenzus, rozpory, optimalizovaný workflow |
| 23 - 43 min | LAB B: analýza obchodných rozhovorov | Matica námietok a koučovací plán |
| 43 - 63 min | LAB C: porovnanie verzií | Zmenový protokol a komunikačný súhrn |
| 63 - 86 min | LAB D: oficiálna syntéza | Prevádzková matica a kontrolný zoznam |
| 86 - 90 min | Záver | Audit jedného tvrdenia a odovzdanie |

# Pravidlo proti generickému výstupu

- Každá analytická tabuľka musí obsahovať zdroj alebo citáciu.
- Každý záver označíme ako fakt, interpretáciu alebo odporúčanie.
- Ak zdroje neposkytujú odpoveď, výsledkom je pomenovaná informačná medzera.
- Vzorové riešenie nie je jedna pekná veta, ale kontrolovateľná štruktúra.

# LAB A: Porovnanie troch odborných návodov

Pracujeme s offline prepismi A1 až A3. Verejné YouTube odkazy A4 používame ako alternatívu, ak je dostupný kvalitný prepis.

## Postup lektora

1. Účastníci pridajú A1, A2 a A3 do jedného notebooku a premenujú zdroje podľa názvov autorov.
2. Najskôr nechajú vybrané všetky tri zdroje.
3. Spustia extrakčný prompt a až potom syntetický prompt.
4. Otvoria citácie pri jednom konsenze a jednom rozpore.

### Krok 1: Extrakcia

> Pre každý zdroj vytvor samostatný profil. Uveď odporúčaný pracovný postup, postoj k výberu zdrojov, postoj ku kontrole citácií, moment použitia Studio výstupov a jedno explicitné varovanie. Nevytváraj spoločný súhrn.

### Krok 2: Porovnanie

> Vytvor tabuľku: téma, zhoda všetkých autorov, rozdiel, priamy rozpor, dôsledok pre používateľa a citácie. Ak ide iba o rozdielny kontext použitia, neoznačuj ho ako rozpor.

### Krok 3: Syntéza

> Navrhni šesťkrokový workflow pre analytickú prácu v NotebookLM. Každý krok musí mať pôvod v minimálne jednom zdroji. Pri konflikte vysvetli, ktorú možnosť vyberáš a pre aký typ úlohy.

## Očakávaný debrief

- A1 a A3 uprednostňujú kurátorovaný výber a kontrolu citácií. A2 používa širší zber a rýchle Studio výstupy.
- Rozdiel nemusí byť chyba. Workflow pre marketingový obsah môže byť iný než workflow pre výskum alebo rozhodnutia.
- Kvalitná syntéza zachová podmienky použitia jednotlivých odporúčaní.

# LAB B: Analýza troch obchodných rozhovorov

Pracujeme s prepismi B1 až B3. Účastníci nesmú hodnotiť osobu bez konkrétneho dôkazu v prepise.

### Krok 1: Matica rozhovorov

> Pre každý rozhovor extrahuj: cieľ zákazníka, počet používateľov, časový limit, bezpečnostnú požiadavku, rozpočet, rozhodovateľov, kritérium úspechu, dohodnutý ďalší krok a citáciu. Ak údaj chýba, napíš CHÝBA.

### Krok 2: Koučovací audit

> Ohodnoť každý rozhovor v oblastiach diagnostika, práca s námietkami, návrh riešenia a uzavretie ďalšieho kroku. Každé hodnotenie podlož minimálne jednou konkrétnou vetou alebo udalosťou z prepisu. Nepoužívaj všeobecné osobnostné súdy.

### Krok 3: Prenos dobrej praxe

> Vyber tri konkrétne otázky alebo postupy z najsilnejšieho rozhovoru, ktoré by zlepšili ostatné rozhovory. Uveď, kam presne by sme ich vložili a aký problém riešia.

## Očakávaný debrief

- B1 je najsilnejší v diagnostike, práci s rozhodovateľmi a dohode ďalšieho kroku.
- B2 prezentuje funkcie skôr, než pozná rozsah, a navrhuje prácu s firemnými dokumentmi bez bezpečnostného rámca.
- B3 má dobrú diagnostiku, ale neuzavrie termín, vlastníkov ani ďalšie stretnutie.

# LAB C: Porovnanie verzií a zápisnice

1. Pridáme C1, C2 a C3.
2. V otázke uvedieme, že verzia 2.0 je aktuálna smernica a zápisnica obsahuje viac stavov.
3. Vytvoríme zmenový protokol a následne komunikačný text.

### Krok 1: Zmenový protokol

> Porovnaj smernicu v1 a v2. Pre každú zmenu uveď: oblasť, pôvodné pravidlo, nové pravidlo, praktický dopad a presné citácie z oboch verzií. Nečerpaj zatiaľ zo zápisnice.

### Krok 2: Audit zápisnice

> Porovnaj zmenový protokol so zápisnicou. Označ, ktoré zmeny boli schválené, ktoré návrhy boli zamietnuté a ktoré otázky boli odložené. Samotnú zmienku v zápisnici nepovažuj za rozhodnutie.

### Krok 3: Komunikácia

> Vytvor oznam pre zamestnancov s maximálne 220 slovami. Uveď iba pravidlá platné od 1. 7. 2026, povinnosti zamestnanca a spôsob hlásenia incidentu. Neuvádzaj zamietnuté ani odložené návrhy.

# LAB D: Syntéza oficiálnej dokumentácie

Účastníci pridajú URL zo súboru D1. Pri tomto laboratóriu pracujeme iba s oficiálnymi zdrojmi Google.

### Krok 1: Prevádzková matica

> Vytvor maticu funkcií so stĺpcami: pracovná situácia, funkcia, postup, obmedzenie, riziko nesprávneho použitia a zdroj. Zahrň výber zdrojov, synchronizáciu Google Drive, poznámky, Audio Overview, Slide Deck a Deep Research.

### Krok 2: Failure modes

> Nájdi najmenej päť situácií, keď používateľ môže vytvoriť nesprávny alebo zastaraný výstup aj pri správnom fungovaní NotebookLM. Ku každej uveď príčinu, prevenciu a zdroj.

### Krok 3: Kontrola pred odovzdaním

> Vytvor kontrolný zoznam s maximálne 15 položkami. Rozdeľ ho na zdroje, aktuálnosť, citácie, Studio výstupy a zdieľanie. Každá položka musí byť vykonateľná kontrola, nie všeobecná rada.

# Záverečný audit

Každý účastník vyberie jedno tvrdenie zo svojho výstupu, otvorí citáciu a odpovie na tri otázky:

1. Podporuje citácia celé tvrdenie?
2. Je citovaný zdroj aktuálny a autoritatívny pre danú otázku?
3. Je tvrdenie fakt, interpretácia alebo odporúčanie?

# Hodnotenie

| **Kritérium** | **0 bodov** | **1 bod** | **2 body** |
|---|---|---|---|
| Práca so zdrojmi | Bez výberu alebo bez rozlíšenia zdrojov | Čiastočné rozlíšenie | Zdrojový výber a autorita sú explicitné |
| Dôkazy | Bez citácií | Citácie sú prítomné, ale nekontrolované | Citácie podporujú celé tvrdenia |
| Syntéza | Generický súhrn | Zachytené hlavné témy | Konsenzus, rozpory, výnimky a podmienky |
| Praktický výstup | Nejasná rada | Použiteľný výstup s medzerami | Konkrétny krok, vlastník alebo kontrola |
| Práca s neistotou | Model dopĺňa chýbajúce údaje | Niektoré medzery označené | Chýbajúce údaje sú systematicky označené |

# Verejne zdokumentované východiská

Kurz vychádza z verejne popísaných prípadov použitia NotebookLM pri práci s historickými archívmi, prepismi obchodných rozhovorov a dokumentmi miestnej samosprávy. Funkcie a obmedzenia sú overené v oficiálnej dokumentácii Google k zdrojom, poznámkam, Audio Overview, Slide Deck a Deep Research.

- https://blog.google/innovation-and-ai/products/notebooklm-goes-global-support-for-websites-slides-fact-check/
- https://support.google.com/notebooklm/answer/16215270?hl=en
- https://support.google.com/notebooklm/answer/16262519?hl=en
- https://support.google.com/notebooklm/answer/16212820?hl=en
- https://support.google.com/notebooklm/answer/16757456?hl=en
- https://blog.google/innovation-and-ai/models-and-research/google-labs/notebooklm-deep-research-file-types/
