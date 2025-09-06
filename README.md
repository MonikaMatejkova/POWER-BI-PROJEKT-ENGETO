# Power BI projekt – Přehled žádostí o dotace Středočeského kraje 2020–2024

## Zadání projektu

- V rámci prvního projektu Datové Akademie máš připravené vhodné datové podklady a zodpovězené několikery výzkumné otázky.  
- Rozsah: **2–5 stránek**  
- Použití **minimálně 5 různých typů vizuálů**  
- **Filtrování** (primárně) pomocí **průřezů/slicerů**  
- Využití **interaktivních prvků**: záložky, navigace po stranách, odkazy na webové stránky  
- **Propojení několika (2+) datových tabulek**, buď přes vazby v rámci Power BI, nebo přes propojení v Power Query  
- Vytvoření **alespoň 1 measure (metrika/míra)** a **1 kalkulovaného sloupce/tabulky**  
- **Grafická úprava vizuálů**, volba správných typů vizuálů a vizuálně přívětivý výstupní report

---

## Zpracování

Použitý dataset je z portálu otevřených dat ČR. K dokonalosti datasetu chybělo jen určení minimálně **okresu žadatele**, neboť to je zrovna jedna z věcí, která je na tomto tématu zajímavá – jsou to dotace, které poskytuje **Středočeský kraj**, ovšem mnoho žadatelů je z **ostatních krajů ČR**.

To mě navedlo na myšlenku **rozdělit žadatele do okresů** a ty pak **vizualizovat na mapě ČR**. K tomu bylo potřeba sehnat **tabulku okresů s jejich PSČ**. Nikdy by mě nenapadlo, že by to mohl být takový problém, ale nakonec jsem jednu takovou našla na **GitHubu**. Bohužel jsem následně zjistila, že byla **neúplná**, takže zbytek jsem si **vytvořila sama**. Toto bylo tedy potřeba **napojit k samotnému datasetu dotací**.

Při zpracování projektu bylo potřeba si i vytvořit **nové metriky**, jako byly **počty dotací (jak schválených, tak neschválených)**.

Když příprava dat byla konečně hotová, rozhodla jsem se – mimo hlavní stránku – rozdělit projekt na:

- **Stránku s vizualizací dat** a  
- **Přehledovou stránku**, kde uživatelé mohou dle jednotlivých charakteristik najít každou dotaci, kterou potřebují. V oblasti dotací jsem pracovala a moc dobře vím, jak těžké bývá v tolika datech najít rychle to, co člověk zrovna potřebuje.
