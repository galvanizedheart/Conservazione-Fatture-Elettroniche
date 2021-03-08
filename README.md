# Conservazione-Fatture-Elettroniche

Questo programma è pensato per i commercialisti o lavoratori nel settore al fine di preparare in pochi click i pacchetti zip richiesti dalla Agenzia delle Entrate per le fatture elettroniche di tipo XML e P7M, ignorando i file metadati, separati in gruppi da 10.

## Step 1
Una volta scaricati i file vi troverete con due componenti, una cartella chiamata gui e un file chiamato Conserva Fatture, quest'ultimo è un collegamento, lo potete mettere ovunque nel vostro PC, la cartella mettela in un posto che vi è comodo perché non sarà necessario aprirla.

In caso il collegamento non funzionasse, cercate nella cartella il file Conserva Fatture.exe e fate partire quello, ma NON rimuovetelo dalla cartella.

## Step 2
Una volta aperto Conserva Fatture vi troverete una finestra di questo tipo:

![cfhome](https://user-images.githubusercontent.com/79949135/110250733-30206100-7f7d-11eb-9d2a-8191120a01ee.png)

Cliccate su sfoglia e navigate all'interno di Esplora File fino a trovare la cartella che contiene le vostre fatture, ad esempio io userò la cartella "Fatture":

![cfselect](https://user-images.githubusercontent.com/79949135/110251025-ca34d900-7f7e-11eb-87e9-c6cb8b34e87c.png)


## Step 3
Adesso la schermata iniziale vi mostrerà a sinistra tutte le fatture .xml e .p7m presenti nella cartella, escludendo i file "_metaDato.xml", a destra invece verranno mostrati tutti i file .zip già presenti:

![cffile](https://user-images.githubusercontent.com/79949135/110251045-ecc6f200-7f7e-11eb-9920-55284ac45225.png)

A questo punto tutto ciò che dovete fare è inserire la Partita Iva del vostro cliente all'interno del box "Partita IVA", successivamente premete "Zippa" e se il codice è stato scritto correttamente vedrete apparire nella colonna di destra i file zippati:

![CFZIP](https://user-images.githubusercontent.com/79949135/110251158-89898f80-7f7f-11eb-9902-e30bf19a829b.png)

Ed il gioco è fatto! Spero che questa piccola utility vi possa aiutare un po' di più :)


## In più
Se lo desiderate potete inserire la partita iva prima di selezionare la cartella, vi appariranno i file già filtrati!
