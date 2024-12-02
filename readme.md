 ## Esercizio:
 
 Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


 ## Table Name

- auto_usate

 ## Table Structure

- id_auto | INT - AUTO_INCREMENT - PRIMARY_KEY (UNIQUE, NOT NULL)
- marca | VARCHAR(25) - NOT NULL
- modello | VARCHAR(25) - NOT NULL
- colore | VARCHAR(20) - NOT NULL    
- carburante | VARCHAR(11) - NOT NULL
- porte | TINYINT - NOT NULL
- cilindrata | SMALL - NOT NULL
- anno di immatricolazione | YEAR - NOT NULL
- chilometraggio | INT - NOT NULL
- prezzo | DECIMAL(10,2) - NOT NULL
- disponibile | TINYINT(1) - DEFAULT(1) 
- proprietari_precedenti | TINYINT - NULL


const auto_usate = [ 
    {
        id_auto : 1,
        marca : "Fiat",
        modello: "Punto",
        //...
    }
]