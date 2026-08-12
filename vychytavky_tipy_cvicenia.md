# 🧠 Gemini Notebook: 30 vychytávok, tipov a praktických cvičení

Táto zbierka obsahuje 30 praktických vychytávok, tipov a cvičení pre **Google Gemini a Gemini Notebook**, pôvodne známy ako NotebookLM. Materiál je zameraný na reálnu prácu so zdrojmi, vyhľadávanie, overovanie informácií, poznámky, myšlienkové mapy, infografiky, audio prehľady, Deep Research, organizáciu zdrojov, fakturáciu a prepojenie Gemini s Gemini Notebook.

> **Aktualizácia:** Google 16. 7. 2026 premenoval NotebookLM na **Gemini Notebook**. Ide naďalej o samostatný výskumný nástroj, ktorý je však tesnejšie prepojený s aplikáciou Gemini a ďalšími službami Google.

> **Odporúčanie:** Pri práci s Gemini Notebook rozlišujme medzi faktami zo zdrojov, odpoveďami modelu a informáciami získanými cez web. Gemini Notebook je primárne nástroj založený na vybraných zdrojoch, preto kvalita výsledku výrazne závisí od kvality a výberu vstupných materiálov.

## 🔄 1. Zorientujme sa po premenovaní NotebookLM na Gemini Notebook

**Typ:** Vychytávka

**Popis:** NotebookLM sa od 16. 7. 2026 volá Gemini Notebook. Nejde iba o kozmetickú zmenu názvu. Zošity sa postupne prepájajú s ekosystémom Gemini a môžeme ich používať aj priamo v aplikácii Gemini.

**Cvičenie:**

1. Otvorme Gemini Notebook.
2. Otvorme aplikáciu Gemini.
3. Skontrolujme sekciu so zošitmi.
4. Porovnajme, ktoré funkcie sú dostupné v oboch rozhraniach.
5. Zapíšme si minimálne tri rozdiely.

**Dôležité:** Studio artefakty ako Audio Overview, Mind Map, Infographic alebo Slide Deck vytvárame v Gemini Notebook. Samotná aplikácia Gemini používa zošit ako kontext, ale neposkytuje všetky Studio funkcie.

---

## 🔗 2. Vytvorme zošit priamo v Gemini a pokračujme v Gemini Notebook

**Typ:** Vychytávka

**Popis:** Zošity vytvorené v Gemini sa synchronizujú s Gemini Notebook. Môžeme teda začať prácu v bežnom Gemini chate a následne pokračovať v špecializovanom prostredí Gemini Notebook.

**Cvičenie:**

1. V Gemini vytvorme nový zošit.
2. Pridajme PDF alebo webovú stránku.
3. Položme jednu otázku.
4. Otvorme rovnaký zošit v Gemini Notebook.
5. Skontrolujme synchronizáciu názvu a zdrojov.

**Prompt:**

```text
Na základe obsahu tohto zošita navrhni 10 konkrétnych otázok, ktoré by sme mali ďalej preskúmať. Otázky rozdeľ na základné, analytické a kritické.
```

---

## 🧭 3. Rozlišujme odpovede Gemini a Gemini Notebook

**Typ:** Tip

**Popis:** Rovnaký zošit môže v Gemini a Gemini Notebook viesť k rozdielnym odpovediam. Gemini Notebook odpovedá primárne na základe zdrojov zošita, zatiaľ čo Gemini môže okrem zdrojov použiť aj webové vyhľadávanie a ďalšie nástroje.

**Cvičenie:**

Položme rovnakú otázku v oboch aplikáciách a porovnajme:

- použité fakty,
- citácie,
- informácie mimo zdrojov,
- rozsah odpovede,
- istotu formulácií.

**Prompt:**

```text
Odpovedz iba na základe zdrojov v tomto zošite. Pri každom dôležitom tvrdení uveď, z ktorého zdroja pochádza. Ak zdroje odpoveď neobsahujú, napíš to explicitne a nič nedopĺňaj z všeobecných znalostí.
```

---

## 📌 4. Pripnime najdôležitejšie zošity v Gemini

**Typ:** Vychytávka

**Popis:** Ak používame viac zošitov, najdôležitejšie si môžeme v Gemini pripnúť. Znížime tým čas potrebný na hľadanie často používaných projektov.

**Cvičenie:**

Pripnime si tri zošity:

- jeden pracovný,
- jeden vzdelávací,
- jeden experimentálny.

Potom vytvorme jednotnú konvenciu názvov, napríklad:

```text
[KURZ] Gemini Notebook 2026
[PROJEKT] AI výskum
[OSOBNÉ] Odborné články
```

---

## 💳 5. Stiahnime faktúru alebo doklad za služby Google

**Typ:** Praktická vychytávka

**Popis:** Nákupy a predplatné služieb Google môžeme kontrolovať cez Google Payments Center. V Európskom hospodárskom priestore môže byť pri podporovaných transakciách dostupná faktúra s DPH alebo daňový doklad.

**Postup:**

1. Otvorme `https://payments.google.com/gp/w/home/activity`.
2. Prihlásme sa správnym Google účtom.
3. Otvorme **Activity**.
4. Vyberme konkrétnu transakciu.
5. Skontrolujme dostupnosť položky **Download VAT invoice** alebo **Download VAT receipt**.
6. Pri predplatných skontrolujme aj sekciu **Subscriptions & services**.

**Pozor:** Dostupnosť konkrétneho typu faktúry závisí od služby, krajiny, platobného profilu a daňových údajov. Pri niektorých nákupoch musí byť daňové identifikačné číslo uvedené ešte pred nákupom.

---

## 🏷️ 6. Používajme jednotné názvy zošitov a vlastné emoji

**Typ:** Tip

**Popis:** Gemini Notebook automaticky priradí zošitu emoji, ale môžeme ho zmeniť. Pri väčšom počte zošitov pomáha kombinácia emoji, kategórie a jednoznačného názvu.

**Príklad:**

```text
🎓 KURZ - Gemini Notebook
🔬 VÝSKUM - AI agenti
📊 ANALÝZA - Trh práce
📚 ZDROJE - Dizertačná práca
🧪 LAB - Experimenty
```

**Cvičenie:** Premenujme päť zošitov tak, aby už z názvu a emoji bolo jasné ich použitie.

---

## 🗂️ 7. Aktivujme vlastné usporiadanie a štítky zdrojov

**Typ:** Vychytávka

**Popis:** Pri minimálne piatich zdrojoch dokáže Gemini Notebook zdroje automaticky kategorizovať a označiť štítkami. Štítky môžeme pridávať, premenovať, mazať a presúvať medzi nimi jednotlivé zdroje.

**Cvičenie:**

Vytvorme zošit s minimálne 10 zdrojmi a rozdeľme ich napríklad na:

- Oficiálna dokumentácia
- Odborné články
- Blogy
- Videá
- Vlastné poznámky
- Praktické príklady

**Tip:** Pri rozsiahlejšom výskume oddeľme autoritatívne zdroje od sekundárnych komentárov.

---

## 🌐 8. Použime Fast Research na rýchle vyhľadanie zdrojov na internete

**Typ:** Cvičenie

**Popis:** Fast Research slúži na rýchle vyhľadanie relevantných webových alebo Drive zdrojov. Výsledky pred importom vidíme a môžeme sa rozhodnúť, ktoré z nich skutočne pridáme.

**Prompt:**

```text
Vyhľadaj kvalitné a aktuálne zdroje o používaní generatívnej AI vo vysokoškolskom vzdelávaní. Uprednostni univerzity, výskumné organizácie, oficiálne dokumenty a odborné publikácie. Neimportuj výsledky automaticky, najprv mi umožni posúdiť ich relevantnosť.
```

**Cvičenie:** Vyhľadajme 10 zdrojov, ale importujme iba päť najlepších.

---

## 🔎 9. Pred importom urobme selekciu zdrojov

**Typ:** Tip

**Popis:** Viac zdrojov automaticky neznamená kvalitnejší výsledok. Nadbytočné, duplicitné alebo nekvalitné zdroje môžu zvýšiť šum a sťažiť presné odpovedanie.

**Kontrolný postup:**

Pri každom zdroji posúďme:

1. Kto je autor alebo organizácia.
2. Kedy bol obsah publikovaný.
3. Či ide o primárny alebo sekundárny zdroj.
4. Či priamo súvisí s našou otázkou.
5. Či neprináša iba duplicitu už importovaných informácií.

**Prompt:**

```text
Navrhni kritériá, podľa ktorých mám vybrať 5 najkvalitnejších zdrojov pre túto výskumnú otázku. Zohľadni autoritu zdroja, aktuálnosť, metodologickú kvalitu, relevanciu a možný konflikt záujmov.
```

---

## 🕵️ 10. Spustime Deep Research až po dobre formulovanej otázke

**Typ:** Cvičenie

**Popis:** Deep Research dokáže prehľadávať veľké množstvo webových stránok a vytvoriť rozsiahlu výskumnú správu. Kvalita výsledku však veľmi závisí od presnosti zadanej výskumnej otázky.

**Slabé zadanie:**

```text
Preskúmaj AI.
```

**Lepšie zadanie:**

```text
Preskúmaj, ako európske univerzity v rokoch 2024 až 2026 používajú generatívnu AI pri tvorbe študijných materiálov. Zameraj sa na konkrétne univerzity, pravidlá používania AI, ochranu osobných údajov, akademickú integritu a praktické príklady využitia. Uprednostni primárne a oficiálne zdroje.
```

**Cvičenie:** Spustime Deep Research s oboma zadaniami a porovnajme kvalitu výsledkov.

---

## 🎯 11. Z Deep Research neimportujme automaticky všetko

**Typ:** Tip

**Popis:** Po dokončení Deep Research môžeme vidieť výslednú správu aj zoznam nájdených zdrojov. Namiesto automatického importu všetkého je vhodné výsledky skontrolovať a vybrať iba tie zdroje, ktoré chceme dlhodobo používať v zošite.

**Cvičenie:**

1. Spustime Deep Research.
2. Otvorme zoznam použitých a nájdených zdrojov.
3. Vyberme iba zdroje priamo podporujúce našu výskumnú otázku.
4. Zvyšné neimportujme.
5. Porovnajme kvalitu následných odpovedí pred a po selekcii.

---

## ☑️ 12. Pýtajme sa iba nad vybranou podmnožinou zdrojov

**Typ:** Vychytávka

**Popis:** Nemusíme pri každej otázke používať celý zošit. V paneli Sources môžeme označiť iba konkrétne zdroje a dostať odpoveď založenú na zvolenej podmnožine.

**Cvičenie:**

Vyberme tri oficiálne zdroje a položme otázku:

```text
Aké sú hlavné spoločné odporúčania týchto troch vybraných zdrojov? Vytvor tabuľku s riadkami podľa tém a stĺpcami podľa jednotlivých zdrojov. Na konci identifikuj oblasti, v ktorých sa zdroje nezhodujú.
```

---

## 🏷️ 13. V otázke používajme presné názvy zdrojov

**Typ:** Tip

**Popis:** Ak máme v zošite veľa dokumentov, pomáha priamo pomenovať zdroj, ktorý má Gemini Notebook analyzovať. Znižujeme tým riziko, že systém vyberie nesprávny kontext.

**Prompt:**

```text
V dokumente „Google Gemini Notebook Help“ nájdi všetky informácie o limitoch zdrojov a porovnaj ich s dokumentom „Gemini Notebook FAQ“. Uveď iba rozdiely a potenciálne nejasnosti.
```

---

## ⚖️ 14. Nechajme Gemini Notebook hľadať rozpory medzi zdrojmi

**Typ:** Cvičenie

**Popis:** Jednou z najpraktickejších analytických úloh je vyhľadávanie rozporov. Namiesto jednoduchého súhrnu môžeme žiadať porovnanie tvrdení, čísel, definícií alebo odporúčaní.

**Prompt:**

```text
Porovnaj všetky vybrané zdroje a identifikuj tvrdenia, pri ktorých sa navzájom nezhodujú. Pri každom rozpore uveď:
1. presné tvrdenie zdroja A,
2. presné tvrdenie zdroja B,
3. možné vysvetlenie rozdielu,
4. ktorý zdroj pôsobí autoritatívnejšie a prečo,
5. čo by sme mali ešte overiť.
```

---

## 🧾 15. Urobme audit citácií odpovede

**Typ:** Cvičenie

**Popis:** Citácia ešte automaticky neznamená, že zdroj skutočne podporuje celé tvrdenie. Pri dôležitých informáciách otvoríme citáciu a porovnáme formuláciu odpovede s pôvodným textom.

**Prompt:**

```text
Odpovedz na otázku a pri každom podstatnom tvrdení uveď citáciu. Potom vytvor druhú sekciu „Audit citácií“, v ktorej ku každému tvrdeniu stručne vysvetlíš, čo presne citovaný zdroj podporuje a čo už je interpretácia.
```

**Cvičenie:** Overme ručne minimálne päť citácií.

---

## 🚫 16. Otestujme otázku, na ktorú zdroje nepoznajú odpoveď

**Typ:** Cvičenie

**Popis:** Kvalitný systém založený na zdrojoch by nemal sebavedomo dopĺňať chýbajúce fakty. Preto je užitočné zámerne položiť otázku, ktorú naše zdroje nepokrývajú.

**Prompt:**

```text
Odpovedz iba z vybraných zdrojov. Ak odpoveď v zdrojoch nenájdeš, napíš presne: „Táto informácia sa v dostupných zdrojoch nenachádza.“ Nedomýšľaj si údaje a nepoužívaj všeobecné znalosti.
```

**Cieľ:** Naučíme sa rozpoznať hranice zošita a kvalitu uzemnenia odpovede.

---

## 💾 17. Uložme kvalitnú odpoveď z chatu ako poznámku

**Typ:** Vychytávka

**Popis:** Ak dostaneme správnu alebo užitočnú odpoveď, môžeme ju uložiť pomocou **Save to Note**. Takto si budujeme vlastnú vrstvu vybraných poznatkov nad pôvodnými zdrojmi.

**Cvičenie:**

1. Položme päť otázok.
2. Vyberme dve najlepšie odpovede.
3. Uložme ich ako poznámky.
4. Pomenujme ich podľa témy.

**Pozor:** Poznámka vytvorená priamo uložením odpovede z chatu nie je po vytvorení editovateľná.

---

## ✍️ 18. Vlastné poznámky používajme pre editovateľný obsah

**Typ:** Tip

**Popis:** Ak chceme text ďalej meniť, dopĺňať alebo štruktúrovať, je vhodnejšie vytvoriť vlastnú poznámku cez **Add note**. Môžeme do nej písať vlastné závery, pracovné hypotézy, otázky alebo obsah skopírovaný z iných miest.

**Odporúčaná štruktúra poznámky:**

```text
Názov témy

Hlavné zistenia
- ...

Dôležité čísla
- ...

Otvorené otázky
- ...

Moje poznámky
- ...

Čo treba overiť
- ...
```

---

## 🔄 19. Transformujme správnu poznámku na nový zdroj

**Typ:** Vychytávka

**Popis:** Poznámku môžeme zmeniť na zdroj pomocou **Convert to source**. To je užitočné, keď sme z viacerých zdrojov vytvorili vlastnú kvalitnú syntézu a chceme, aby sa stala súčasťou ďalšieho kontextu zošita.

**Cvičenie:**

1. Vytvorme syntetickú poznámku z troch zdrojov.
2. Skontrolujme jej správnosť.
3. Premeňme ju na zdroj.
4. Položme ďalšiu otázku s novým zdrojom zapnutým.
5. Porovnajme výsledok.

**Pozor:** Transformáciou vlastnej syntézy na zdroj môžeme zároveň preniesť vlastné chyby. Pred konverziou vždy skontrolujme fakty.

---

## 🧹 20. Konvertujme všetky poznámky na zdroj až po ich vyčistení

**Typ:** Tip

**Popis:** Gemini Notebook umožňuje premeniť všetky poznámky na zdroj. Funkcia je praktická pri uzatváraní jednej etapy výskumu, ale nemali by sme ňou bez kontroly premieňať pracovné alebo neoverené poznámky.

**Cvičenie:**

Pred konverziou rozdeľme poznámky na:

- overené,
- pracovné,
- otázky,
- neaktuálne.

Na zdroj premeňme iba overenú vrstvu.

---

## 🧠 21. Využime rýchle transformácie poznámok

**Typ:** Vychytávka

**Popis:** Vybrané poznámky môžeme zlúčiť, skrátiť, transformovať na osnovu, študijný materiál alebo nad nimi získať konštruktívnu spätnú väzbu.

**Prompt:**

```text
Z týchto poznámok vytvor logickú osnovu školenia pre začiatočníkov. Začni základnými pojmami, pokračuj praktickými funkciami a skonči samostatnými cvičeniami. Odstráň duplicity a označ informácie, ktoré si navzájom odporujú.
```

---

## 🧠 22. Vytvorme myšlienkovú mapu pred detailným štúdiom

**Typ:** Cvičenie

**Popis:** Mind Map je vhodná na prvotnú orientáciu v rozsiahlych zdrojoch. Zobrazí hlavné témy a vzťahy medzi nimi v stromovej štruktúre.

**Cvičenie:**

1. Importujme minimálne päť tematicky súvisiacich zdrojov.
2. Vytvorme Mind Map.
3. Nájdime tri vetvy, ktorým nerozumieme.
4. Na každú vetvu položme jednu konkrétnu otázku.
5. Porovnajme mapu s textovým súhrnom.

**Pozor:** Mind Maps majú denné limity podľa typu účtu a na mobilnej aplikácii nemusia byť dostupné.

---

## 🎨 23. Vytvorme infografiku iba z vybraných zdrojov

**Typ:** Cvičenie

**Popis:** Infographic dokáže zmeniť vybrané zdroje na jeden vizuálny súhrn. Môžeme nastaviť jazyk, úroveň detailu, orientáciu, vizuálny štýl a vlastný prompt.

**Prompt:**

```text
Vytvor profesionálnu infografiku určenú pre účastníkov IT školenia. Zobraz 5 najdôležitejších princípov práce so zdrojmi v Gemini Notebook, hlavné limity a odporúčaný pracovný postup. Použi čistú profesionálnu vizuálnu hierarchiu, minimum dekorácií a zvýrazni kľúčové čísla.
```

**Cvičenie:** Vygenerujme ten istý obsah v štýloch Professional a Sketch Note a porovnajme čitateľnosť.

---

## 🎙️ 24. Vytvorme viac Audio Overview pre rôzne cieľové skupiny

**Typ:** Vychytávka

**Popis:** Nemusíme sa uspokojiť s jedným audio prehľadom. Z rovnakých zdrojov môžeme vytvoriť viac variantov s rozdielnym zameraním, odbornou úrovňou a publikom.

**Prompt pre začiatočníka:**

```text
Vysvetli tému pre úplného začiatočníka. Nepredpokladaj predchádzajúce znalosti. Používaj jednoduché príklady z praxe a vysvetli všetky odborné pojmy.
```

**Prompt pre odborníka:**

```text
Vytvor odborný audio prehľad pre skúseného používateľa AI nástrojov. Preskoč základné definície a sústreď sa na limity, metodiku práce so zdrojmi, kvalitu citácií, Deep Research a riziká nesprávnej interpretácie.
```

---

## 🌍 25. Vytvorme audio v slovenčine aj v cudzom jazyku

**Typ:** Cvičenie

**Popis:** Gemini Notebook podporuje Audio Overview vo viac ako 80 jazykoch vrátane slovenčiny. Z jedného zošita môžeme vytvoriť obsah pre rozdielne jazykové publikum.

**Cvičenie:**

Vytvorme:

1. slovenský Deep Dive,
2. anglický Brief,
3. český prehľad pre začiatočníkov.

**Prompt:**

```text
Zachovaj odbornú presnosť, ale prispôsob slovník cieľovému publiku. Nevytváraj doslovný preklad. Použi terminológiu prirodzenú pre zvolený jazyk.
```

---

## 🗣️ 26. Experimentujme s formátmi Deep Dive, Brief, Critique a Debate

**Typ:** Vychytávka

**Popis:** Audio Overview nemusí byť iba klasický rozhovor dvoch moderátorov. K dispozícii sú rôzne formáty podľa účelu.

**Praktické použitie:**

- **Deep Dive:** dôkladné pochopenie témy,
- **Brief:** rýchle zopakovanie podstaty,
- **Critique:** kritické posúdenie textu alebo návrhu,
- **Debate:** porovnanie rozdielnych pohľadov.

**Cvičenie:** Z rovnakých zdrojov vygenerujme Deep Dive a Debate. Porovnajme, ktorý formát lepšie odhalí rozpory.

---

## 🖼️ 27. Vytvorme vlastný vizuálny titulný motív zošita

**Typ:** Kreatívna vychytávka

**Popis:** Oficiálna dokumentácia Gemini Notebook aktuálne popisuje zmenu emoji zošita. Univerzálne nastavenie ľubovoľného vlastného cover obrázka nie je v dokumentácii popísané pre všetkých používateľov. Ako praktický vizuálny motív však môžeme vytvoriť vlastný obrázok v Gemini a pridať ho do zošita ako obrazový zdroj alebo ho použiť v súvisiacich materiáloch.

**Prompt:**

```text
Vytvor čistý profesionálny titulný obrázok pre zošit s témou „Gemini Notebook a AI výskum“. Moderná technologická estetika, notebook, prepojené dokumenty, grafické uzly reprezentujúce zdroje a výskum, realistické modré a neutrálne tóny, bez logotypov, bez textu, široká kompozícia 16:9.
```

**Tip:** Ak účet ponúka iba emoji zošita, zvoľme tematické emoji a rovnaký vizuálny motív používajme v infografikách a prezentáciách.

---

## 📷 28. Použime knižnicu promptov na fotorealistické obrázky

**Typ:** Cvičenie

**Popis:** V repozitári je pripravená knižnica promptov pre fotorealistické osoby, produkty a miesta. Môžeme ju použiť ako zdroj promptov pre Gemini a výsledné obrázky následne zaradiť medzi zdroje alebo výstupy projektu.

**Zdroj promptov:**

```text
https://github.com/miroslav-reiter/notebook-lab/blob/main/prompty_AI_obrazky_ludia_produkty_miesta.md
```

**Cvičenie:**

1. Otvorme knižnicu promptov.
2. Vyberme jeden prompt pre osobu, jeden pre produkt a jeden pre miesto.
3. Vygenerujme obrázky v Gemini.
4. Porovnajme anglickú a slovenskú verziu promptu.
5. Jeden výsledný obrázok pridajme do experimentálneho zošita ako obrazový zdroj.

**Prompt na analýzu výsledkov:**

```text
Porovnaj tieto tri vygenerované obrázky z pohľadu fotorealizmu, kompozície, svetla, anatomickej správnosti, textúr a použiteľnosti v profesionálnom materiáli. Pri každom obrázku navrhni tri konkrétne úpravy pôvodného promptu.
```

---

## 📏 29. Otestujme limity Gemini Notebook na malom experimentálnom zošite

**Typ:** Cvičenie

**Popis:** Limity sa líšia podľa plánu a môžu sa meniť. Pri štandardnom prístupe Google aktuálne uvádza 100 zošitov, do 50 zdrojov na zošit, maximálne 500 000 slov alebo 200 MB na jeden lokálne nahraný zdroj, 50 chatových otázok denne a 3 audio generovania denne.

**Cvičenie:**

Vytvorme zošit **🧪 LAB - Limity Gemini Notebook** a otestujme:

- import PDF,
- import webovej stránky,
- import Markdown súboru,
- import obrázka,
- viac zdrojov naraz,
- deaktiváciu zdroja,
- otázku nad jedným zdrojom,
- otázku nad všetkými zdrojmi.

**Pozor:** Prémiové plány majú odlišné limity. Limity a dostupnosť funkcií sa môžu meniť, preto ich pred školením vždy overme v aktuálnej dokumentácii.

---

## 📱 30. Urobme kompletné záverečné cvičenie od výskumu po výstup

**Typ:** Záverečné cvičenie

**Popis:** Toto cvičenie spája vyhľadávanie, selekciu, overovanie zdrojov, poznámky, štítky, Deep Research a Studio artefakty do jedného pracovného postupu.

**Zadanie:**

Preskúmajme tému:

```text
Ako môžu firmy prakticky používať generatívnu AI pri vzdelávaní zamestnancov v roku 2026?
```

**Postup:**

1. Vytvorme nový zošit.
2. Použime Fast Research.
3. Vyberme minimálne päť kvalitných zdrojov.
4. Pridajme minimálne jeden vlastný dokument.
5. Zdroje označme štítkami.
6. Položme tri špecifické otázky.
7. Skontrolujme minimálne päť citácií.
8. Spustime Deep Research na jednu úzku podotázku.
9. Uložme najlepšiu odpoveď ako poznámku.
10. Vytvorme vlastnú editovateľnú syntetickú poznámku.
11. Premeňme overenú syntézu na zdroj.
12. Vytvorme Mind Map.
13. Vytvorme Infographic.
14. Vytvorme slovenský Audio Overview.
15. Vytvorme druhý Audio Overview pre manažment.
16. Na záver napíšme tri limity a tri riziká výsledného výskumu.

**Záverečný prompt:**

```text
Na základe všetkých aktuálne vybraných zdrojov vytvor záverečný audit tohto zošita.

Vyhodnoť:
1. kvalitu a autoritu zdrojov,
2. aktuálnosť zdrojov,
3. prípadné duplicity,
4. rozpory medzi zdrojmi,
5. tvrdenia, ktoré nemajú dostatočnú oporu,
6. témy, pri ktorých chýbajú zdroje,
7. tri najdôležitejšie zistenia,
8. tri najväčšie metodologické riziká,
9. päť otázok pre ďalší výskum.

Nevychádzaj mimo obsahu vybraných zdrojov. Jasne oddeľ fakty, interpretácie a odporúčania.
```

# ⚠️ Dôležité limitácie a upozornenia

Gemini Notebook je výkonný nástroj na prácu so zdrojmi, ale výsledky sú stále generované AI a môžu obsahovať nepresnosti. Citácie treba pri dôležitých výstupoch kontrolovať voči pôvodnému zdroju.

Každý zošit je samostatný. Gemini Notebook nedokáže pri jednej odpovedi automaticky pracovať naprieč viacerými nezávislými zošitmi. Pri prepájaní tém preto zvažujme konsolidáciu vhodných zdrojov do jedného projektu.

Pri importovaní webovej URL sa spravidla používa textový obsah HTML stránky. Pri Google dokumentoch sa nemusia importovať všetky prvky, napríklad komentáre alebo poznámky pod čiarou. Chránené PDF alebo príliš veľké zdroje môžu pri importe zlyhať.

Mobilná aplikácia nemusí obsahovať všetky funkcie desktopovej verzie. Napríklad poznámky, Mind Maps, reporty alebo dátové tabuľky môžu byť na mobile obmedzené alebo nedostupné. Na komplexnú prácu preto používajme primárne desktopovú webovú verziu.

Pri faktúrach a daňových dokladoch sa dostupnosť líši podľa služby, regiónu a platobného profilu. Google Payments Center je centrálne miesto na kontrolu transakcií a podporovaných dokladov.

# 🔗 Použité a odporúčané zdroje

## Google

NotebookLM is now Gemini Notebook:

```text
https://blog.google/innovation-and-ai/products/gemini-notebook/notebooklm-gemini-notebook/
```

Gemini Notebook Help:

```text
https://support.google.com/gemininotebook/
```

Frequently asked questions a limity:

```text
https://support.google.com/gemininotebook/answer/16269187?hl=en
```

Práca so zdrojmi, Fast Research, Deep Research a štítky:

```text
https://support.google.com/gemininotebook/answer/16215270?hl=en
```

Vytváranie zošitov a Studio výstupy:

```text
https://support.google.com/gemininotebook/answer/16206563
```

Poznámky:

```text
https://support.google.com/gemininotebook/answer/16262519?hl=en
```

Myšlienkové mapy:

```text
https://support.google.com/gemininotebook/answer/16212283?hl=en
```

Infografiky:

```text
https://support.google.com/gemininotebook/answer/16758265?hl=en
```

Audio Overview:

```text
https://support.google.com/gemininotebook/answer/16212820
```

Prepojenie zošitov s Gemini:

```text
https://support.google.com/gemininotebook/answer/17003757?hl=en
```

Google Payments Center:

```text
https://payments.google.com/gp/w/home/activity
```

Faktúry s DPH a daňové doklady:

```text
https://support.google.com/googlepay/answer/7644144
```

## GitHub

Prompty pre AI obrázky ľudí, produktov a miest:

```text
https://github.com/miroslav-reiter/notebook-lab/blob/main/prompty_AI_obrazky_ludia_produkty_miesta.md
```

> **Stav overenia:** 12. 8. 2026. Funkcie, limity a názvy položiek používateľského rozhrania sa môžu meniť podľa plánu, účtu, regiónu, platformy a postupného zavádzania funkcií.
