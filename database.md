<!-- Istruzioni:
Create un file di testo per descrivere un database di un negozio di videogiochi.
Strutturate il file come fatto oggi in classe.  Specificate: il nome del database, la tabella e le potenziali colonne con i tipi di dato. -->

# database name : Libreria
# nome tabelle : Videogiochi

- id BIGINT PRIMARYKEY NOTNULL AUTO_INCREMENT UNIQUE
- title string VARCHAR(50) NOTNULL
- description string TEXT NULL
- publisher VARCHAR (30) NOTNULL
- developer VARCHAR (30) NOTNULL
- year date YEAR NOTNULL
- genre VARCHAR (30) NOTNULL
- price FLOAT(6,2) 9999,99 NULL
- availability number TINYINT NULL DEFAULT (0)
- img_cover string VARCHAR() NULL
- language string VARCHAR(20) NOTNULL