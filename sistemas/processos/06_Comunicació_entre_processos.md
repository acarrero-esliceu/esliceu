## Comunicació entre Processos

Els processos poden comunicar-se entre ells mitjançant diferents mètodes.

### 1. Memòria Compartida
Diversos processos poden compartir àrees de memòria per intercanviar informació. Aquest mètode és eficient però requereix una sincronització adequada per evitar problemes de coherència.

### 2. Comunicació per Missatges
Els processos poden intercanviar informació mitjançant missatges, evitant la necessitat de compartir memòria. Aquesta abstracció facilita la comunicació entre processos, però pot tenir un cost addicional de rendiment.