# ARVAIQ Football 2.1.8

- Simplifica o pipeline de catálogo para uma única autoridade de admissão por provider ID, removendo filtros redundantes que podiam eliminar jogos válidos no cliente.
- OWNER, FRIENDS e ULTIMATE passam a consumir diretamente todo o catálogo comercial fechado com provider mapping válido, sem depender de caches ou seleções locais antigas.
- Remove discovery/fallback fuzzy no sync do Football e mantém a quarentena estática de provider identities inválidas.
- Reforça a deduplicação semântica de equipas, incluindo aliases austríacos como Wolfsberger AC/Wolfsberger e Linzer ASK/LASK Linz.
- Mantém a análise central no ARVAIQ-PC, o seletor de mercados e a melhor odd Betano/Betclic visível mesmo quando não existe value.
