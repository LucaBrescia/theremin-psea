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

# Catta su
- Jumper
- Distanziali
- Flessibile
