# ANNCSU dump

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Questo repository contiene informazioni utili per scaricare l'indirizzario e lo stradario di tutta Italia dall'API dell'Archivio Nazionale dei Numeri Civici e delle Strade Urbane (ANNCSU).

### Indirizzario Italia:

https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_ITA

### Stradario Italia:

https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_ITA

### Esempio di download per Regione:

https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_ABRU

https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_ABRU

Pattern:

- INDIR_[NOME_REGIONE]
- STRAD_[NOME_REGIONE]

dove

NOME_REGIONE = ABRUZ̶Z̶O̶, SICIL̶I̶A̶, LAZIO̶

### Appunti: 

1) Caricare zip stradari/indirizzari (LFS se zip > 25mb);
2) Elaborare CSV indirizzario (Italia/regioni) e converirlo in ?parquet? o altro formato dati
3) Caricare gpq dump 02/2024 ed integrare numeri civici mancanti (circa 600k)
4) Action per aggiornare periodicamente zip (1
5) ...
