## O que é
https://colab.research.google.com/drive/1XiB_6z5cNc25HhRR5FVnqUlx87qqhFew?usp=sharing
Notebook  com exploração dos dados de (ocorrências aeronáuticas, tipos de evento, tipo de aeronave) e  modelagem para classificar categorias de ocorrência.

## Por que existe
Organizar a análise em um único lugar, com narrativa clara e células executáveis do começo ao fim.

## Como usar
- Abra o notebook no Google Colab ou Jupyter.
- Execute as células na ordem. Sem dependências fora das listadas no próprio notebook.

## Estrutura (alto nível)
1. Contexto e objetivo
2. Dados e preparação
3. EDA (tendências, distribuições)
4. Baseline e candidatos
5. Preparação de features e split
6. Treino/avaliação
7. Conclusões e próximos passos

## Resultados em uma frase
Incidentes aumentam em 2023–2024; “falha/mau funcionamento de sistema/componente” é a categoria mais frequente; aviões concentram mais registros. Modelagem ainda limitada para classes raras.

## Limitações
- Desbalanceamento de classes e possível subnotificação.
- Mudanças de taxonomia podem afetar comparações históricas.
- Validação deve considerar dependência temporal.

## Próximos passos sugeridos
- Incluir variáveis operacionais (idade, horas/ciclos, clima).
- Testar ensembles com validação temporal.
- Monitorar qualidade e drift dos dados.

## Reprodutibilidade
Defina uma semente quando houver aleatoriedade e fixe versões das dependências ao publicar resultados.
