# My first Database

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Colonne|Tipo|Attributi|Index
---|---|---|---
id|BIGINT|AUTO_INCREMENT|PRIMARY_KEY
targa|CHAR(7)|NULL, UNIQUE
n_telaio|CHAR(17)|NOTNULL, UNIQUE
marca|VARCHAR(17)|NOTNULL
modello|VARCHAR(50)|NOTNULL
porte|CHAR(1)|NOTNULL
prezzo|FLOAT(9,2)|NULL
condizione|CHAR(1)|NOTNULL
anno_immatricolazione|DATE|NULL
data_acquisizione|DATA|NOTNULL
km|MEDIUMINT|NOTNULL
alimentazione|VARCHAR(20)|NOTNULL
cambio|CHAR(1)|NOTNULL
cavalli|CHAR(3)|NOTNULL
cilindrata|VARCHAR(4)|NOTNULL
colore|CHAR(7)|NULL