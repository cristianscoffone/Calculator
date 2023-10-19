# Calculator
### calcolatrice 2023
Lo scopo di questo progetto è quello di ricreare una calcolatrice simile a quella di windows tramite il linguaggio in c#.
<br>

# Funzionalità Principali

### Gestione degli Operatori
  - Le operazioni tra operandi sono gestite dai metodi `ManageOperator` e `specialManageOp`.
  - `ManageOperator` calcola il risultato delle operazioni aritmetiche base (addizione, sottrazione, moltiplicazione, divisione).
  - `specialManageOp` gestisce operazioni speciali come percentuale, radice quadrata, reciproco, quadrato.

### Legenda dei Pulsanti
- `%`: Percentuale
- `Œ`: Cancella Inserimento
- `C`: Cancella Tutto
- `⌫`: Backspace
- `⅟x`: Reciproco (1/x)
- `²`: Quadrato (x²)
- `√`: Radice Quadrata (√x)
- `÷`: Divisione
- `×`: Moltiplicazione
- `-`: Sottrazione
- `+`: Addizione
- `±`: Segno Più/Meno
- `,`: Punto Decimale
- `=`: Uguale

### lbl_result e lbl_cronologia
- lbl_result serve a mostrare l'operatore cliccato e il numero cliccato.
- lbl_cronologia serve a mostrare tutte le operazioni e i passaggi eseguiti

