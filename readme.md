Prima di procedere con la formattazione salvati i dati che ti interessano.

## ISO File

Troviamo l'immagine del Sistema Operativo (SO)
che vogliamo installare. Come esempio per questo tutorial
prendiamo XUBUNTU 64bit [LINK](https://xubuntu.org/download)

Il file scaricato sara un `file.torrent`, per cui serve avere
l'app di torrent per poterlo scaricare [LINK](http://www.utorrent.com). Una volta scaricato,
troverete un `file.iso` salvato sul vostro PC.
Questo file e' l'immagine del SO che andremo ad installare.

* Cose' un ISO file? <br/>
I file ISO sono semplicemente un modo per raggruppare un sacco di
 file e cartelle in un unico file con l'estensione del file ISO.

## Masterizzare l'ISO in un CD, DVD o USB

We need to burn our ISO file to a CD, DVD or UDB.
If you have windows, you can use
 [Rufus](https://rufus.akeo.ie/?locale) to create a bootable USB
 drive or [CDBurner](https://rufus.akeo.ie/?locale) for a CD.
If you have linux, like in my case KDE, you can use K3b.

## Imposta il BIOS per avvio da CD, DVD o USB
* Cose' BIOS? <br/>
BIOS sta per Basic Input Output System, e' un software salvato
nella scheda madre ed e' il primo software che viene eseguito
quando il computer viene accesso. Il BIOS da istruzioni al
 computer su come fare il booting e i controlli della tastiera.

* Cose' il booting? <br/>
Il termine boot e' usato per descrivere il processo quando il
computer viene accesso, tirando su il sistema Operativo e lo
prepara per essere usato.

* Come accedere al BIOS? <br/>
Nei primi secondi del accensione del pc, viene mostrato un messaggio
di setup: `Press [KEY] to enter setup`. Se per caso non lo vedete
basta cercare su internet, scrivendo il modello del vostro pc
seguito da `BIOS`. Nel mio pc basta premere `F2` nel momento
in cui si accende, e vedrete la seguente schermata (che varia di
  poco da pc a pc):

![Image of BIOS](https://fthmb.tqn.com/CDK7JLalzFPevT2HZqA5KW48D2o=/768x0/filters:no_upscale():max_bytes(150000):strip_icc()/boot-options-cd-first-599596b1845b340010bd4a99.png)

Assicuratevi di andare nella sezione `Boot` con le frecce.
A destra vi vengono date informazioni su come cambiare l'ordine
degli elementi che si trovano a sinistra.
Se ad esempio avete masterizzato una `USB` allora `Removable Device`
deve essere messo il primo. Utilizzando `+` si puo muovere in su
quella righa.

* Salvare le modifiche <br/>
Leggete le opzioni in fondo al immagine. Se usate `ESC` fatte exit
senza salvare. Se usate `F10` Salvate e fate exit.

## Installazione
