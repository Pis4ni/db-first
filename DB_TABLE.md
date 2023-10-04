
| **NOME**              | **TIPO**      | **ATTRIBUTI**               |
| --------------------- | ------------- | --------------------------- |
| ID                    | BIGINT        | PRIMARY KEY, AUTO_INCREMENT |
| Marca                 | VARCHAR(30)   | NOT NULL                    |
| Modello               | VARCHAR(50)   | NOT NULL                    |
| Anno_Produzione       | YEAR          | NULL                        |
| Anno_Immatricolazione | YEAR          | NULL                        |
| Km_Percorsi           | INT           | UNSIGNED, NULL              |
| Numero_Proprietari    | VARCHAR(20)   | NULL                        |
| Incidentata_Bool      | CHAR(1)       | DEFAULT '0'                 |
| Tipo_Carburante       | VARCHAR(20)   | NULL                        |
| Cilindrata_cc         | INT           | UNSIGNED, NULL              |
| Potenza_Motore_KW     | INT           | UNSIGNED, NULL              |
| Prezzo                | DECIMAL(10,2) | NULL                        |
