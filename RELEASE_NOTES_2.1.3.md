# ARVAIQ Football 2.1.3

- Nova lista principal de jogos baseada em tabela nativa de baixo overhead para reduzir lag no scroll, pesquisa e filtros.
- Deduplicação semântica de fixtures equivalentes recebidas com IDs ou aliases diferentes dos providers.
- Em duplicados, prioridade à representação com odds/análise e contexto mais ricos.
- Evita duplicados visuais como Benfica vs Estoril / Estoril Praia e Braga vs Vitória S.C. / Vitória SC.
- Mantém múltiplos mercados válidos do mesmo jogo; apenas elimina cópias do próprio fixture.
- Mantém catálogo comercial fechado e isolamento do ARVAIQ Admin.
