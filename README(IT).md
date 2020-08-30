**ITALIANO** / [ENGLISH](README.md)

La Make XZ è una stampante 3D cartesiana con doppio carrello X che usa i profili di openbuilds e la scheda duet wifi... oltre ad essere precisa e silenziosa, ha diverse caratteristiche interessanti.

La Make XZ può avere diverse configurazioni grazie ai diversi moduli e al supporto nativo per il doppio carrello X.

>La Make XZ è in pieno sviluppo, vogliamo testare il multimateriale.

Stiamo sviluppando documentazione, manuali di installazione e file per la calibrazione.

Puoi replicare tutti i suoi componenti, esclusi: bulloni, dadi, viti, elettronica, cuscinetti e profili in alluminio (taglio laser non è necessario).

#### Vediamo le principali caratteristiche della Make XZ:

- Facile da chiudere (tutto è all'interno della struttura, hai solo bisogno di avvitare i pannelli sulla struttura!).

- Elettronica: [Duet Wifi](https://www.duet3d.com/DuetWifi) con la possibilità di usare le schede di espansione Duex2 e Duex5, il touch screen "panel due" da 4.3/5/7 pollici.

- Predisposta per il doppio carrello X (X1 e X2).

- Area di Stampa solo con X1: 300x210x200
- Area di stampa con X1 e X2: 250x210x200

- Cuscinetti su ogni asse dei motori (X1, X2, Y, Z).

- Tensionamento cinghie su ogni asse.

- Modulo X1 e X2: Il primo modulo che monta la Make XZ, usa hotend e3dv6 con sonda [ZPRep](https://github.com/mauriziospaccialbelli/ZPRep/blob/master/README(IT).md).

- Module multi materials: Multi material module (work in progress) consente di avere diverse combo per il multimateriale su entrambi i moduli X. Con il doppio carrello X le cose diventano ancora più interessanti. Comunque ora vogliamo testare un approccio diverso... troppi tubi bowden non ci piacciono.

- Fan nozzle module: Il modulo nozzle fan consente di smontare rapidamente il convogliatore dell'aria o di montare un altro tipo.

- Predisposizione per la pulizia dell'ugello su X1/X2 (work in progress). Ciò consente cambio materiali solo dove necessario, nessun limite di colore, nessun utilizzo di torri intelligenti, meno consumo di filamenti, tempi di stampa minori, più area di stampa.

- Il piatto riscaldato è rimovibile in vetro borosicato con foglio di PEI.

- Abbiamo scelto i profili v-slot di openbuilds, ma invece di utilizzare gli eccentrici sulle ruote, abbiamo utilizzato altri sistemi.

- Stiamo testando un estrusore per bowden intercambiabile da 1,75mm/2,85mm con pressione filamento a steps, motore nema gear(??). Oltre a garantire un'eccellente estrusione, è possibile condividere facilmente le impostazioni dei materiali

Grazie alle caratteristiche e ai componenti della Make XZ, è possibile stampare la maggior parte dei filamenti, inclusi quelli tecnici/speciali. Qualsiasi materiale che viene sottoposto a test viene aggiunto all'elenco dei materiali calibrati, stiamo creando una macro contenente tutte le impostazioni dei materiali calibrati, cosi da impostare rapidamente il tipo di materiale caricato.

Tutti i progetti creati da Maurizio Spaccialbelli sono sviluppati e mantenuti solo con free software e opensource. dove possiamo utiliziamo open hardware, per esempio openbuilds, duet wifi, ZPRep.

Ringraziamo tutti i progetti e le comunità free software e opensource di tutto il pianeta.
Un rigraziamento speciale alle comunità di [RepRap](http://forums.reprap.org/index.php), [Duet3d](https://www.duet3d.com/forum/), [FreeCAD](https://forum.freecadweb.org/), [OpenBuilds](http://openbuilds.org/).

La Make XZ è un progetto RepRap creato da Maurizio Spaccialbelli(Maurino Web) e Marco Spaccialbelli

Sostieni e segui il lavoro di Maurizio Spaccialbelli su [Patreon](https://www.patreon.com/mauriziospaccialbelli)
