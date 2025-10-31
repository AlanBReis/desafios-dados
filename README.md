Pratica de desafios técnicos

Objetivo: Praticar e demonstrar habilidades em  dados, automação e integração de sistemas, utilizando ferramentas e linguagens comuns na área de Dados e TI.

Cada desafio deve ser resolvido sem consulta, apenas com lógica, documentação e tentativa/erro.

<br>

## Desafio 1 — Criação de Dataset Sintético

Crie um dataset fictício com 100 linhas e 6 colunas representando dados de vendas (ex: id_venda, data, produto, categoria, quantidade, valor_total).
Salve em formato CSV e JSON.
Use Python (pandas) para gerar e exportar os dados.

<br>

## Desafio 2 — Limpeza e Tratamento de Dados

Com base no dataset anterior, escreva um script que:

remove valores nulos,

corrige tipos de dados,

formata datas,

e salva o resultado em um novo arquivo vendas_limpo.csv.

<br>

## Desafio 3 — Análise Exploratória

Usando Python (pandas + matplotlib):

Calcule métricas simples (ex: total de vendas, ticket médio, produto mais vendido);

Gere gráficos simples (barras, pizza ou linha);

Mostre insights no terminal.

<br>

## Desafio 4 — ETL com Python

Implemente um mini processo ETL (Extract, Transform, Load):

Extraia dados de um CSV,

Transforme — ex: normalize colunas, converta tipos, adicione uma nova coluna calculada,

Carregue em outro CSV formatado.

<br>

## Desafio 5 — Consumo de API Pública

Acesse uma API REST pública (ex: IBGE, OpenWeather, ViaCEP, PokéAPI).
Faça uma requisição GET e exiba no terminal:

Código da resposta,

Estrutura do JSON,

Alguns campos específicos (ex: nomes de cidades, temperaturas, etc).

<br>

## Desafio 6 — Integração de Dados via API

Combine os dados da API do IBGE (nomes de cidades) com um dataset local (ex: vendas por cidade).
Gere um novo dataset combinando ambos — isso simula uma integração real.

<br>

## Desafio 7 — Power BI Dashboard

Crie um dashboard no Power BI com:

Total de vendas,

Produtos mais vendidos,

Filtro por mês ou categoria.
Exporte uma captura de tela e documente o processo no README.

<br>

## Desafio 8 — Automação de Tarefas

Usando Python, crie um script que:

Leia um arquivo CSV,

Gere um relatório resumido,

E envie o resultado por e-mail (ou salve automaticamente em uma pasta de “Relatórios”).

Dica: simule o envio de e-mail se não quiser usar SMTP real.

<br>

## Desafio 9 — Validação de Dados

Escreva um script que valide se:

Existem valores duplicados,

Datas estão no formato correto,

Colunas obrigatórias não estão vazias.
Ao final, gere um log de inconsistências.

<br>

## Desafio 10 — Documentação e Fluxo de Dados

Crie um documento em Markdown explicando um fluxo de dados fictício da empresa:

Onde os dados são coletados (fontes),

Como são tratados,

Onde são armazenados,

E como são visualizados (BI, relatórios, dashboards).

Use diagramas simples (pode usar Mermaid ou ASCII).
