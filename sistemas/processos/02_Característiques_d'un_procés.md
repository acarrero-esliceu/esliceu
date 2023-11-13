## Característiques d'un Procés

### 1. Program Counter (Comptador de Programa)
El Program Counter indica la posició actual d'execució dins del codi del programa. Quan es commuta entre processos, aquest valor es guarda i es recupera per mantenir la continuïtat de l'execució.

### 2. Registres
Els registres emmagatzemen dades temporals i resultats d'operacions. Cada procés té els seus propis registres, assegurant la segregació i protecció de les dades entre els diferents processos.

### 3. Espai de Memòria
Cada procés té assignat un espai de memòria que conté el seu codi, dades i una pila per gestionar les crides a funcions i les variables locals. Aquesta separació evita interferències entre processos.

### 4. Descriptors de Fitxers
Els descriptors de fitxers emmagatzemen informació sobre els fitxers oberts pel procés, facilitant la comunicació i l'intercanvi de dades amb l'entorn del sistema operatiu.