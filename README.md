# Projekt_Power_BI

Druhý projekt do Engeto Online Datové Akademie

# Tornáda v USA v letech 1996 - 2013

## Popis projektu
Tento projekt se zaměřuje na analýzu a vizualizaci vývoje tornád v USA v období let 1996 až 2013. Výstupem projektu je Power BI report, který obsahuje výskyt tornád v čase, ekonomické dopady v jednotlivých státech, nejničivější tornáda a mapu četnosti tornád. 

## Zdroje dat
Použitá data pocházejí z internetových stránek oficiálního zdroje NOAA: https://www.ncei.noaa.gov/pub/data/swdi/stormevents/csvfiles/legacy/
Pro každý rok jsou data v samostatném CSV souboru. Data byla vyčištěna a upravena v Power Query.
Seznam a popis jednotlivých sloupců je k dispozici v dokumentaci z internetové stránky NOAA: https://www.ncei.noaa.gov/pub/data/swdi/stormevents/csvfiles/Storm-Data-Bulk-csv-Format.pdf

## Problémy
* Zobrazení státu Puerto Rico v Power BI:

Při tvorbě mapových vizualizací výskytu tornád jsem byla nucena vyloučit stát Puerto Rico, protože Power BI nedokáže správně zobrazit jeho polohu a chybně jej umisťuje do Jižní Ameriky.

* Sjednocení stupcie síly tornáda (F/EF-scale):

Od února roku 2007 začala Národní meteorologická služba USA používat vylepšenou Fujitovu stupici (EF-scale) místo původní Fujitovy stupnice (F-scale) pro klasifikaci síly tornád. Aby při vizualizaci byla data sjednocená pro celé časové období, převedla jsem je z EF-scale na F-scale.