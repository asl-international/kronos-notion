# Instituto Kronos · Painel — Layout Notion Sidebar

Hub agregador do Instituto Kronos num único arquivo HTML.

- **Versão**: v0.13-teste · Layout Notion Sidebar
- **Inspiração**: Notion — sidebar persistente à esquerda com árvore completa (sub-áreas expansíveis), breadcrumb no topo, hover sutil
- **Conteúdo**: 6 camadas (Gestão/Operação/Produtos/SOPs/Biblioteca/Conhecimento) + 7 sub-áreas de Operação + 5 produtos + Playbook Mentoria Kairós com 10 notas
- **Persistência**: localStorage (`kronos_state_v1`)

## Como rodar

```bash
python -m http.server 8000
# abrir http://localhost:8000
```

Single-file, sem build, sem dependências. Funciona offline.

## Funcionalidades

- Sidebar fixa 260px à esquerda com tree nav completa
- Sub-áreas expansíveis (clique na seção)
- Breadcrumb no topo (Visão Geral / Gestão / Comercial / etc)
- Cada item da sidebar tem contador `filled/total`
- Tudo reachable em 1 click
- Botão Resumo no rodapé da sidebar
- Busca com stemmer + 200+ sinônimos (na própria sidebar)
- 4 abas: Gestão / Operação / Produtos / SOPs / Biblioteca / Conhecimento
