# theremin-psea

## Cose da fare

 - Test oscillazioni basse
 - Test distorsione
 - Filtro passa ALTO passivo per tagliare le continue da implementare dopo il mixer (vedere se servono dopo XR e oscillatore)
 - Prendere uscite prima e dopo il filtro
 - Caratterizzazione e diagramma pratico del filtro del 4o ordine
 - Ragionare se vale la pena di fare dei test per aumentare la frequenza di oscillazione e vedere quanto cambia con la mano
 - Prendere misure mano, vedendo cosa cambia al variare della dimensione della mano (magari utilizzando un altro oggetto)
 - Provare con il generatore di funzione inserendo forme d'onda diverse come cambia la risposta del mixer


## Cosa abbiamo inserito: XR2206

- Reistenza su pin7 è una 100k singola
- Su pin 8 inseriamo un'altra 100k (che non utilizziamo per la sinusoide) per eventuali tirangolari e quadra
- La capacità minima sui pin 5 e 6 è di 10pF
- Le alimentazioni sono 100nF e non 1uF
- La resistenza da 200ohm nel nostro caso è una serie di due resistenze da 100

```bash
 TODO: Modificare lo schematico di conseguenza
```

## Oscillatore di Wien

- Modificare schema in accordo con il circuito: rimozione diodi e forse utilizzo di potenziometri al posto delle R.
- Aggiungere i pin sul diagramma e i valori utilizzati.

## Filtro passa alto ua741
 Taglio a 15 Hz:
 - R = 106kOhm
 - C = 100nF
 (vedi filterPro)

# Immagini che servono
FFT:
- Oscillatore di Wien (THD)
- Uscita dal filtro LP4 o TUTTO

Altro:
- Studio della variazione della capacità. Su XR solo senza collegare il tutto. (Immagini sinusoide in uscita ?)
- Immagini con metro.

# Da provare
- Oscillatore + fcngen e visualizzare l'uscita dell AD con FFT.

# Misure
- Passa alto reale
- Passa basso 4 ordine (vpp aumentata e più preciso)

# Tabelle 
Capacità - frequenza - distanza (capacità ricavata con formula)

# N B
Controllare che i circuiti mostrati sulla relazione e il pcb siano concordi

Aggiungere nel paragrafo 2.4 Q e Csi del filtro (sito mike)
