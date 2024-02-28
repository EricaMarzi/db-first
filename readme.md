# My first Database

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Colonne|Tipo|Attributi
---|---|---
id|BIGINT|PRIMARY_KEY, AUTO_INCREMENT
targa|CHAR(7)|NOTNULL
n_telaio|CHAR(17)|NOTNULL
marca|VARCHAR(17)|NOTNULL
modello|VARCHAR(50)|NOTNULL
porte|CHAR(1)|NOTNULL
prezzo|FLOAT(6,2)|NOTNULL
condizione|CHAR(1)|NOTNULL
anno_immatricolazione|YEAR|NULL
data_acquisizione|DATA|NOTNULL
km|INT|NOTNULL
alimentazione|VARCHAR(20)|NOTNULL
cambio|CHAR(1)|NOTNULL
cavalli|CHAR(3)|NULL
cilindrata|CHAR(4)|NULL