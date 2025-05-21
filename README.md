# Bakalárska práca
## ANALÝZA DÁT O PACIENTOCH S CUKROVKOU  
### Petronela Skorodenská
### Odkaz na dáta 
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/
### OPIS PRÁCE
Práca sa zaoberá predikciou výskytu ochorenia Diabetes Mellitus pomocou klasifikačných algoritmov strojového učenia. Cieľom je vizualizovať dáta a analyzovať korelácie medzi atribútmi. Práca sa zaoberá porovnávaním výkonnosti vybraných modelov na základe ich schopnosti klasifikovať, či pacient trpí cukrovkou a zároveň identifikovať najvhodnejší algoritmus pre túto prácu. 
### Popis dostupných datasetov
-	diabetes_binary_health_indicators_BRFSS2015.csv: je čistá množina údajov obsahujúca 253 680 odpovedí z prieskumu CDC BRFSS2015. Cieľová premenná obsahuje binárnu klasifikáciu cukrovky (0 = bez cukrovky, 1 = s cukrovkou), táto množina údajov obsahuje 21 premenných popisujúcich vlastnosti respondentov a nie je vyvážená.
-	diabetes _ 012 _ health _ indicators _ BRFSS2015.csv: je čistá množina údajov obsahujúca 253 680 odpovedí z prieskumu CDC BRFSS2015. Cieľová premenná Diabetes_012 má 3 triedy (0 znamená, že osoba nemá cukrovku alebo ju mala len počas tehotenstva, 1 znamená prediabetes, 2 znamená cukrovku). Táto množina údajov má nevyvážené triedy a 21 premenných.
-	diabetes _ binary _ 5050split _ health _ indicators _ BRFSS2015.csv: je čistá množina údajov obsahujúca 70 692 odpovedí z prieskumu CDC BRFSS2015. Obsahuje vyvážený 50-50 pomer respondentov bez cukrovky a respondentov s prediabetesom alebo cukrovkou. Cieľová premenná Diabetes_binary má 2 triedy (0 znamená, že osoba nemá cukrovku, 1 znamená, že má prediabetes alebo cukrovku). Táto množina údajov obsahuje 21 premenných popisujúcich vlastnosti respondentov a je vyvážená.
### Aktuálny obsah
- diabetes_binary_health_indicators_BRFSS2015.csv
- diabetes _ 012 _ health _ indicators _ BRFSS2015.csv
- diabetes _ binary _ 5050split _ health _ indicators _ BRFSS2015.csv
- Bakalarska_prac.ipynb a : zdrojový kód v pythone s vizualizáciou datasetu, prípravou dát a modelovaním 
- README.md : aktuálny súbor s informáciami
- test.ipynb : načítanie verzií knižníc ktoré je nutné využívať
### Požiadavky:
- *verzia Pythonu 3.11.9*
- *Seaborn version: 0.13.2*
- *Pandas version: 2.2.3*
- *NumPy version: 2.2.3*
- *Matplotlib version: 3.10.0*
- *Scikit-Learn version: 1.6.1*
- *IPyKernel version: 6.29.59*

*inštalácia knižníc*: 
- https://scikit-learn.org/stable/index.html
- https://pandas.pydata.org/docs/index.html#
- https://matplotlib.org/3.5.3/index.html
- https://numpy.org/doc/stable/index.html
- https://seaborn.pydata.org/


