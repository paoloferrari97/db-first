# DB Auto Usate

## Nome tabella: macchine

- ID PRIMARY KEY AUTOINCREMENT NOTNULL UNIQUE
- marca VARCHAR(50) NOTNULL INDEX
- modello VARCHAR(50) NOTNULL INDEX
- anno immatricolazione YEAR NOTNULL
- carburante/alimentazione VARCHAR(20) NOTNULL
- km percorsi MEDIUMINT NOTNULL
- colore VARCHAR(50) NOTNULL
- foto VARCHAR(255) NULL
- prezzo DECIMAL(8,2) NOTNULL
- porte TINYINT NULL
- cambio VARCHAR(20) NOTNULL
- numero posti TINYINT NULL
- cavalli VARCHAR(10) NULL
- cilindrata VARCHAR(10) NULL
- interni VARCHAR(100) NULL
- tecnologie di serie TEXT NULL
- optional TEXT NULL
- quanti proprietari precedenti VARCHAR(255) NOTNULL
- condizione TEXT NULL

<!-- - notes
- created_at
- updated_at -->
