# Problema A

## Soluzione
- Prendere una penna e un foglio
- Appuntare cosa manca nel foglio, che da adesso verrà chiamato lista, e conservarselo
- Prendere i coupun e conservarseli
- mangiare qualche snack a casa per evitare di comprare qualche snack extra inutile al supermercato a causa della fame
- uscire di casa
- dirigersi verso il supermercato
- Prendere il carrello
- entrare nella prima corsia
- DO
    - Entrare in una nuova corsia
    - DO
        - visualizzare i prodotti nello scaffale
        - SE quel prodotto è nella lista
            - Prendere il prodotto
            - Posizionare nel carrello
        - ALTRIMENTI
            - Vai avanti
    - SE hai già controllato lo scaffale della parte opposta:
        - esci dal ciclo
    - ALTRIMENTI controlla la parte opposta
    - Controllare nuovamente la lista per evitare di dimenticarsi qualcosa

- SE le corsie sono finite AND tutti gli oggetti della lista sono stati presi e messi nel carrelo , uscire dal ciclo
- SE il totale dei prodotti è superiore ai contanti che possediamo AND non possiamo pagare con cart
    - Prendere l'oggetto più costoso
    - Tornare nella corsia da dove lo abbiamo preso
    - Riposizionare dove si trovava
    - Ripetere se la condizione iniziale è ancora vera
- ALTRIMENTI esci dal ciclo

- Dirigersi verso le casse
- Scegliere una cassa aperta AND con meno persone in fila possibile
- Aspettare il proprio turno

- SE la cassa è libera
    - Prendere gli oggetti dal carrello e posizionarli sul nastro
- SE è stato preso tutto: 
- allora uscire dal ciclo

- Aspettare il prioprio turno
- SE Hai una busta?
    - Prendi e tieni in mano la busta
- ALTRIMENTI:
- Chiedi al cassiere una busta
- Prendi e tieni in mano la busta

- Dire al cassiere di avere dei coupon
- Prendere la busta
- DO
    - SE gli oggetti sono stati battuti in cassa:
    - ALLORA prendile e mettile nella busta
- SE hai già preso tutti gli oggetti, esci dal ciclo

- Prendere i coupon
- Porgerli al cassiere
- Aspettare il totale
- SE il totale è superiore ai contanti:
    - Pagare con carta la differenza
- ALTRIMENTI pagare in contanti
- Ringraziare il cassiere
- Uscire dal supermercato
- Tornare a casa
- Posare i prodotti