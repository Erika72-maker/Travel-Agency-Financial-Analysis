PROJEKT PORTFÓLIÓ: Utazási Iroda Pénzügyi Teljesítmény Elemzés

1. Vezetői Összefoglaló (Executive Summary)
A projekt célja egy magyar utazási iroda teljes éves számlázási adatbázisának (kb. 1600 tranzakció) tisztítása, feldolgozása és elemzése volt. A feladat során a nyers adatokból (szamlazz.hu export) olyan döntéstámogató információkat állítottam elő, amelyek segítik a vezetőséget a likviditás tervezésében és a működési hatékonyság növelésében.
A projekt során demonstrált kompetenciák:
•	Adattisztítás és ETL: Python (Pandas) használata a hibás rögzítések szűrésére.
•	Adatvizualizáció: Interaktív Power BI dashboard készítése.
•	Üzleti elemzés: Szezonalitás, kintlévőség-kezelés és profitabilitás vizsgálata.
2. Üzleti Probléma és Célkitűzések
Az utazási iroda vezetése számára az alábbi kérdések megválaszolása volt kritikus fontosságú:
1.	Likviditás-menedzsment: Pontosan mikor és mekkora bevételre lehet számítani? Hogyan lehet felkészülni a szezonon kívüli időszakra?
2.	Hatékonyság: Mekkora az adminisztrációs hibaarány (sztornózott számlák)?
3.	Pénzügyi fegyelem: Mekkora a kintlévőség állománya?
3. Alkalmazott Technológiák és Módszertan
A projekt során a "Data Analyst" munkafolyamatot követtem:
•	Adatforrás: CSV export (Travel_Agency_FINAL_HUNGARIAN.csv), amely tartalmazta a számla keltét, teljesítését, összegét, a partner adatait és az úti célt.
•	Python (Pandas): Az adattisztításhoz használtam.
o	Dátumformátumok egységesítése (YYYY-MM-DD).
o	Késedelmes napok számítása (Days_Overdue kalkulált oszlop).
o	Hiányzó értékek és duplikációk kezelése.
•	Power BI: Az adatok vizualizálása és interaktív szűrési lehetőségek (pl. úti cél vagy hónap szerinti bontás) megteremtése.
4. Elemzési Eredmények és Megállapítások
A. Szezonalitás és Cash-Flow
Az adatok elemzése kimutatta az iparágra jellemző extrém szezonalitást. Az éves árbevétel 60%-a mindössze 4 hónap alatt (június-szeptember) realizálódik.
•	Üzleti javaslat: A nyári csúcsidőszakban képzett tartalékokat elkülönített alszámlán kell kezelni a Q1-es (január-március) időszak működési költségeinek fedezésére. 
 
1. ábra: Havi árbevétel alakulása a vizsgált időszakban.
B. Adminisztrációs Hatékonyság (Hibaarány)
Az elemzés feltárta, hogy a kiállított bizonylatok közel 12%-a került sztornózásra vagy érvénytelenítésre. Ez magas adminisztrációs terhet ró a pénzügyi munkatársakra.
•	Üzleti javaslat: A foglalási folyamat felülvizsgálata javasolt a manuális adatbeviteli hibák csökkentése érdekében.
C. Helyszín alapú Elemzés (Destination Analysis)
A Destination (Úti cél) adatok alapján összehasonlítottam a legnépszerűbb üdülőhelyek teljesítményét (pl. Neoi Pori vs. Platamon).
•	Eredmény: A vizualizáció segítségével azonosíthatóvá váltak a legmagasabb átlagos kosárértéket generáló desztinációk, ami segíti a jövő évi marketing-költségvetés fókuszálását.

