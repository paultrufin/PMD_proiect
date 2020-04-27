# PMD_proiect
Tema proiectului:

Să se proiecteze un microsistem cu următoarea structură:
unitate centrală cu microprocesorul 8086;
128 KB memorie EPROM, utilizând circuite 27C1024;
128 KB memorie SRAM, utilizând circuite 62512;
interfaţă serială, cu circuitul 8251, plasată în zona 0DD0H – 0DD2H sau 0C50H – 0C52H, în funcţie de poziţia microcomutatorului S1;
interfaţă paralelă, cu circuitul 8255, plasată în zona 0D50H – 0D56H sau 0B50H – 0B56H, în funcţie de poziţia microcomutatorului S2;
o minitastatură cu 16 contacte;
16 led-uri;
un modul de afişare cu segmente, cu 8 ranguri.

Toate programele în limbaj de asamblare vor fi concepute sub formă de subrutine. Programele necesare sunt:

 rutinele de programare ale circuitelor 8251 şi 8255;
 rutinele de emisie/ recepţie caracter pe interfaţa serială;
 rutina de emisie caracter pe interfaţă paralelă;
 rutina de scanare a minitastaturii;
 rutina de aprindere/ stingere a unui led;
 rutina de afişare a unui caracter hexa pe un rang cu segmente.
