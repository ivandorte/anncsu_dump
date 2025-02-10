Questo repository contiene informazioni utili per scaricare l'indirizzario e lo stradario di tutta Italia estratti dall'API dell'Archivio Nazionale dei Numeri Civici e delle Strade Urbane (ANNCSU).

Indirizzario Italia:
https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_ITA

Stradario Italia 🛣️:
https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_ITA

Esempio di download per Regione:
https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_ABRU
https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_ABRU

Pattern:
https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?[INDIR o STRAD]_[NOME_REGIONE]

NOME_REGIONE = ABRUZ̶Z̶O̶, SICIL̶I̶A̶, LAZIO̶

Appunti: 
1) Elaborare CSV indirizzario e converirlo in ?parquet? o altro formato dati
2) Caricare gpq dump 02/2024 ed integrare numeri civici mancanti (circa 600k)
