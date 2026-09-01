# Adventure Works | Power BI

Projeto desenvolvido durante o curso **Microsoft Power BI Desktop for Business Intelligence**, da Maven Analytics.

A proposta foi trabalhar com a Adventure Works, uma empresa fictícia usada no curso, como se eu estivesse atuando como Analista de Business Intelligence. A partir dos arquivos brutos disponibilizados, passei pelo processo completo no Power BI: tratamento dos dados no Power Query, modelagem, criação de medidas em DAX e construção do dashboard.

O resultado é um relatório que permite acompanhar vendas, receita, lucro, pedidos, devoluções, produtos, clientes, regiões e a evolução dos resultados ao longo do tempo.

---

## Contexto do projeto

O projeto foi desenvolvido como parte prática do curso e usa a Adventure Works como cenário para aplicar os conteúdos aprendidos em uma situação próxima de um projeto de BI.

O objetivo era sair dos arquivos brutos e chegar a um relatório interativo que ajudasse a acompanhar os principais indicadores da empresa, comparar resultados e aprofundar a análise de produtos, clientes e regiões.

Por ser um projeto de estudo, ele não representa uma experiência profissional com a Adventure Works. O foco aqui é mostrar o processo que desenvolvi dentro do Power BI e as habilidades que apliquei durante o projeto.

---

## Dados utilizados

Os dados foram disponibilizados em arquivos CSV e estão organizados na pasta [`Dados`](./Dados/).

### Tabelas de apoio

- Calendar Lookup
- Customer Lookup
- Product Categories Lookup
- Product Subcategories Lookup
- Product Lookup
- Territory Lookup

### Dados transacionais

- Returns Data
- Sales Data 2020
- Sales Data 2021
- Sales Data 2022

Os dados de vendas estavam separados por ano. No Power Query, os arquivos de 2020, 2021 e 2022 foram combinados para formar a consulta utilizada na análise de vendas.

---

## Como o projeto foi desenvolvido

### 1. Power Query

Comecei pela preparação dos dados no Power Query. Organizei as consultas, conferi e ajustei tipos de dados, tratei as tabelas e combinei os arquivos anuais de vendas.

Essa etapa deixou os dados prontos para serem relacionados e utilizados no modelo.

### 2. Modelagem de dados

Depois do tratamento, organizei as tabelas em um modelo relacional.

Os dados de vendas e devoluções foram conectados às tabelas de calendário, clientes, produtos, categorias e territórios, permitindo analisar os resultados por diferentes perspectivas sem precisar trabalhar cada arquivo de forma isolada.

### 3. DAX

Com o modelo pronto, criei as medidas utilizadas no relatório para que os indicadores respondessem aos filtros e às seleções feitas no dashboard.

As medidas dão suporte a análises como receita, lucro, pedidos, devoluções, taxa de devolução, desempenho de produtos, resultados por cliente e comparações ao longo do tempo.

### 4. Dashboard

Por último, organizei as análises em diferentes páginas do relatório.

A ideia foi deixar uma visão geral para acompanhamento dos principais indicadores e, a partir dela, permitir que a análise fosse aprofundada por região, produto e cliente.

---

## Páginas e análises do relatório

### Visão executiva

A página principal reúne os indicadores gerais da Adventure Works e permite acompanhar receita, lucro, quantidade de pedidos, taxa de devolução, evolução da receita, desempenho por categoria e produtos com maior volume de pedidos.

### Mapa

A análise geográfica permite comparar a distribuição dos resultados entre **Europa, América do Norte e Pacífico**, além de visualizar os países presentes na base.

### Detalhes de produto

A página de produtos permite selecionar um item específico e acompanhar pedidos, receita e lucro em relação às metas, além de analisar o histórico do produto e testar ajustes de preço.

### Detalhes de cliente

A análise de clientes mostra o total de clientes, receita por cliente, distribuição por faixa de renda e ocupação, ranking de clientes e destaque para o cliente com maior receita.

### Recursos analíticos adicionais

O relatório também utiliza recursos como **Decomposition Tree** e **Key Influencers** para explorar relações nos dados e aprofundar algumas análises além dos gráficos tradicionais.

---

## O que dá para analisar

Com o relatório é possível explorar, entre outros pontos:

- evolução das vendas e da receita ao longo do tempo;
- lucro, pedidos e devoluções;
- desempenho por região e território;
- categorias, subcategorias e produtos;
- desempenho de produtos em relação às metas;
- perfil e comportamento da base de clientes;
- clientes com maior participação na receita;
- diferenças entre períodos e segmentos.

---

## O que apliquei no projeto

- Power BI Desktop
- Power Query
- Importação e tratamento de dados
- Combinação de arquivos
- Modelagem de dados
- Relacionamentos entre tabelas
- DAX
- Criação de medidas
- Parâmetros e análises de cenário
- Visualização de dados
- Dashboards interativos
- Decomposition Tree
- Key Influencers

---

## Arquivos do projeto

O arquivo final do Power BI está em:

[`Dashboard/Adventure Works - Maven Analytics.pbix`](./Dashboard/Adventure%20Works%20-%20Maven%20Analytics.pbix)

Os arquivos utilizados como fonte estão em:

[`Dados/`](./Dados/)

Os prints utilizados na documentação ficam em:

[`Imagens/`](./Imagens/)

---

## Como abrir o projeto

1. Baixe o arquivo `.pbix` disponível na pasta `Dashboard`.
2. Abra o arquivo no **Power BI Desktop**.
3. O relatório pode ser navegado normalmente com os dados já armazenados no arquivo.

> **Observação:** as fontes foram configuradas originalmente com arquivos locais usados durante o curso. Caso seja necessário atualizar os dados depois do download, pode ser necessário redefinir os caminhos das fontes no Power Query.

---

## Sobre o curso

**Curso:** Microsoft Power BI Desktop for Business Intelligence  
**Plataforma:** Maven Analytics  
**Ferramenta principal:** Microsoft Power BI Desktop

Este projeto foi uma das etapas práticas da minha formação em análise de dados e serviu para aplicar, em um único trabalho, o fluxo completo de construção de um relatório no Power BI.