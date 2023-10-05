| **NOME**              | **TIPO**      | **ATTRIBUTI**               |
| --------------------- | ------------- | --------------------------- |
| id                    | BIGINT        | PRIMARY KEY, AUTO_INCREMENT |
| marca                 | VARCHAR(30)   | NOT NULL                    |
| modello               | VARCHAR(50)   | NOT NULL                    |
| anno_Produzione       | YEAR          | NULL                        |
| anno_Immatricolazione | YEAR          | NULL                        |
| km_Percorsi           | INT           | UNSIGNED, NULL              |
| numero_Proprietari    | CHAR(1)       | NULL                        |
| incidentata_Bool      | TINYINT       | DEFAULT (0)                 |
| tipo_Carburante       | CHAR(1)       | NULL                        |
| cilindrata_cc         | INT           | UNSIGNED, NULL              |
| potenza_Motore_KW     | INT           | UNSIGNED, NULL              |
| prezzo                | DECIMAL(10,2) | NULL                        |

<!-- todo  -->
