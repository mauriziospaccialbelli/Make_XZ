**ITALIANO** / [ENGLISH](README.md)

Make XZ è il primo progetto nato in www.3dingegno.com da MaurinoWeb e Marco Spaccialbelli. È una stampante 3D precisa e silenziosa, può avere diverse configurazioni grazie ai diversi moduli e al supporto nativo per il doppio carrello X, è multimateriale.

Per esempio: Fino a 7 colori con un carrello X, fino a 6 colori da dividere su due carrelli X, carrelli X indipendenti o in copia, utilizzare filamenti con diversi diametri durante la stampa ect...

La struttura è rigida e silenziosa con profili v-slot di openbuilds, anche l'elettronica è silenziosa con il Duet Wifi!

>La Make XZ è in pieno sviluppo e c'è ancora molto da fare...

![stampante 3d make xz](http://www.3dingegno.com/wp-content/uploads/2017/09/3d-printer-make-xz.jpg)

Stiamo sviluppando documentazione, manuali di installazione e file per la calibrazione ... tutti saranno condivisi presto.

I file dei modelli stampabili sono già disponibili, ma nella versione finale possono avere cambiamenti. Per ora consiglio di stampare i modelli solo se sei veramente interessato alla sperimentazione o sviluppo.

Tutte le parti di questa stampante sono opensource e fanno parte del progetto RepRap. Puoi replicare tutti i suoi componenti, esclusi: bulloni, dadi, viti, elettronica, cuscinetti e profili in alluminio (taglio laser non è necessario).

Puoi seguire il progetto su www.3dingegno.com github ecc...

Vediamo le principali caratteristiche della Make XZ:

Predisposizione per una facile chiusura. (work in progress)

Elettronica: [Duet Wifi](https://www.duet3d.com/DuetWifi) con la possibilità di usare le schede di espansione Duex2 e Duex5, il touch screen "panel due" da 4.3/5/7 pollici.

Predisposta per il doppio carrello X (X1 e X2).

Area di Stampa solo con X1: 300x210x200
Area di stampa con X1 e X2: 250x210x200

Cuscinetti su ogni asse dei motori (X1, X2, Y, Z).

Sistema Z con un motore, cinghia chiusa e due barre trapezoidali TR8 * 8-2p (4 starts). Meno calibrazioni, più sincronizzazione.

Tensionamento cinghie su ogni asse e file gcode per regolare la stessa tensione sulle cinghie X1, X2, Y (file gcode work in progress).

Modulo X1 e X2:
Il primo modulo che monta la Make XZ, usa hotend e3dv6 con sonda  Z induttiva(presto cambiamo tipo di sonda). Le sonde Z si incrociano e arrivano fino a 40mm di offset tra il moduli e3dv6_X1 e e3dv6_X2. Il modulo e3dv6 ha due moduli secondari: multimaterial module and fan nozzle module.

Module multi materials:
Multi material module (work in progress) consente di avere diverse combo per il multimateriale su entrambi i moduli X. Con il doppio carrello X le cose diventano ancora più interessanti.
Minimo due colori/materiali (1,75 o 2,85)

Fan nozzle module:
Il modulo nozzle fan consente di smontare rapidamente il convogliatore dell'aria o di montare un altro tipo.

Predisposizione per la pulizia dell'ugello su X1/X2 (work in progress). Ciò consente cambio materiali solo dove necessario, nessun limite di colore, nessun utilizzo di torri intelligenti, meno consumo di filamenti, tempi di stampa minori, più area di stampa.

Il piatto riscaldato è rimovibile in alluminio con foglio di PEI.

Il frame è rigido perchè abbiamo scelto i profili v-slot di openbuilds, ma invece di utilizzare gli eccentrici sulle ruote, abbiamo utilizzato altri sistemi.

Stiamo testando un estrusore per bowden intercambiabile da 1,75mm/2,85mm con pressione filamento a steps, motore nema gear.
Oltre a garantire un'eccellente estrusione, è possibile condividere facilmente le impostazioni dei materiali

Grazie alle caratteristiche e ai componenti della Make XZ, è possibile stampare la maggior parte dei filamenti, inclusi quelli tecnici/speciali. Qualsiasi materiale che viene sottoposto a test viene aggiunto all'elenco dei materiali calibrati, stiamo creando una macro contenente tutte le impostazioni dei materiali calibrati, cosi da impostare rapidamente il tipo di materiale caricato.

Tutti i progetti nati in 3dingegno.com sono sviluppati e mantenuti solo con free software e opensource. dove possiamo utiliziamo open hardware, per esempio openbuilds e duet wifi.

Ringraziamo tutti i progetti e le comunità free software e opensource di tutto il pianeta.
Un rigraziamento speciale alle comunità di [RepRap](http://forums.reprap.org/index.php), [Duet3d](https://www.duet3d.com/forum/), [FreeCAD](https://forum.freecadweb.org/), [OpenBuilds](http://openbuilds.org/).

In tutte le immagini mancano la maggior parte delle viti a altri dettagli, presto le prime foto e video della Make XZ.

