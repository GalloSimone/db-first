

|   Name             |   Type       |   Attributes             |   Key       |   Note                                                    |
| ------------------ | ------------ | ------------------------ | ----------- | ----------------------------------------------------------|
| ID                 | BIGINT(20)   | NOT NULL, AUTO INCREMENT | Primary key |id della macchina                                          |
| MARCA              | VARCHAR(20)  | NOT NULL                 |             |marca della mcchina                                        |
| MODELLO            | VARCHAR(15)  | NOT NULL                 |             |modello della macchina                                     |
| CHILOMETRAGGIO     | INT          | NOT NULL                 |             |chilometri compiuti dalla macchina                         | 
| COLORE             | VARCHAR(10)  | NOT NULL                 |             |colore della macchina                                      |
| PREZZO             | DECIMAL(9,2) | NOT NULL                 |             |prezzo della macchina                                      |
| ANNO               | INT          | NOT NULL                 |             |anno di fabbricazione della macchina                       |
| STATO              | CHAR(1)      | NOT NULL                 |             |stato di usura della macchina(P=pessimo O=ottima N=normale)|
| DESCRIZIONE        | TEXT         | NOT NULL                 |             |descrizionde della macchina                                |