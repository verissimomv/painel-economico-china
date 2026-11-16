🇨🇳 Painel Estratégico: Economia e Política da China (2023–2035)
Bem-vindo ao repositório do Observatório Econômico e Político da China. Este projeto reúne uma aplicação web interativa com recursos de acessibilidade, uma base de dados completa em formato CSV e um caderno analítico de pesquisa sobre o modelo de desenvolvimento chinês sob as diretrizes do Partido Comunista da China (PCC).
---
📂 Estrutura de Arquivos do Repositório
O projeto está organizado em quatro arquivos independentes na raiz do repositório:
`index.html` — Painel web interativo estilizado nas cores da China e do PCC (vermelho e amarelo/dourado), com controle de fonte, alternador de contraste e glossário técnico integrado;
`dados_economia_china.csv` — Base de dados tabulada (UTF-8) contendo séries históricas, conjuntura de 2026, projeções do Banco Mundial até 2028, os 20 indicadores do 15º Plano Quinquenal (2026–2030), simulações CGE para 2035, dívida de governos locais (LGFVs), matriz de PPPs e indicadores sociais;
`CADERNO_PESQUISA_NOTEBOOK.md` — Síntese analítica, teórica, jurídica e institucional que conecta todas as fontes do Notebook (NDRC, IEDI, Xinhua, USCC, SciELO, FD-USP e relatos de negócios);
`README.md` — Documentação de apresentação e guia de publicação no GitHub Pages.
---
🖥️ Recursos do Painel Interativo
O painel web foi construído em arquivo único (Single-File Application), sem dependências externas:
Identidade Visual (China & PCC): Paleta institucional em vermelho imperial (`#8B0000`), vermelho bandeira (`#DE2910`) e amarelo/ouro (`#FFDE00`).
Acessibilidade (Padrão WCAG):
Redimensionamento dinâmico de texto (`A-`, `A`, `A+`);
Alternância entre 3 temas de leitura: Padrão PCC (Vermelho/Ouro), Fundo Claro e Alto Contraste (WCAG AAA);
Navegação completa por teclado (`Tab` / `Enter`), skip-link e atributos semânticos `ARIA`.
Compreensão Facilitada:
Resumos "Como entender em 30 segundos" no topo de cada aba;
Ala de Termos Técnicos com busca instantânea em tempo real e atalhos clicáveis ao longo do texto (explicando conceitos como NQPF, LGFVs/Chengtou, Hukou, Competição Involutiva, PTF, Dangjian e Dados como Capital).
---
📊 Estrutura da Base de Dados CSV
O arquivo CSV pode ser aberto diretamente no Excel, Google Sheets, Power BI ou importado via Python (`pandas.read_csv('dados_economia_china.csv')`) e R. Ele está dividido em 7 módulos (`id_modulo`):
`1_MACRO` — Escala histórica, fechamento de 2025, conjuntura trimestral de 2026 e comércio exterior/subsídios;
`2_PROJ_BM` — Projeções macroeconômicas detalhadas do Banco Mundial, ING, OCDE e FMI (2024–2028);
`3_PLANO_15` — Os 20 indicadores oficiais comparando o 14º e o 15º Plano Quinquenal (2026–2030) e sua natureza (Expectativa vs. Vinculativo);
`4_CENARIOS_2035` — Simulações de longo prazo do modelo DRCCGE (Cenário Base vs. Cenário de Alta Qualidade até 2035);
`5_TECNOLOGIA_DADOS` — Economia digital, contabilização de dados nos balanços corporativos, IA, semicondutores, robótica e transição energética;
`6_IMOVEIS_PPPS` — Crise imobiliária, endividamento das LGFVs e matriz regulatória do Novo Mecanismo de PPPs (Doc. nº 115/2023 e Ordem nº 17/2024 da NDRC);
`7_DEMOGRAFIA_BRASIL` — Envelhecimento populacional até 2050, seguros públicos de saúde (UEBMI, URBMI, NRCMS), sistema Hukou e impactos para o Brasil.
