# Adventure Works | Power BI

Projeto desenvolvido durante o curso **Microsoft Power BI Desktop for Business Intelligence**, da Maven Analytics.

A Adventure Works é uma empresa fictícia usada no curso para simular um cenário de Business Intelligence. Ao longo das aulas, trabalhei com os arquivos disponibilizados e fui passando pelas principais etapas de um projeto no Power BI: tratamento dos dados no Power Query, modelagem, criação de medidas em DAX e construção do relatório.

Como é um projeto guiado, boa parte da estrutura, das análises e dos recursos usados no relatório segue a proposta do próprio curso. Meu objetivo aqui é mostrar o que trabalhei na prática e o que aprendi durante esse processo.

---

## Contexto do projeto

A proposta do exercício era transformar os arquivos brutos da Adventure Works em um relatório que permitisse acompanhar os principais resultados da empresa e analisar vendas, produtos, clientes, devoluções e regiões.

O projeto foi construído durante o curso, então ele não representa uma experiência profissional com a Adventure Works. Ainda assim, foi importante para praticar o fluxo completo de construção de um relatório no Power BI usando várias tabelas relacionadas.

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

Os dados de vendas vieram separados por ano. Durante o projeto, os arquivos de 2020, 2021 e 2022 foram combinados no Power Query para formar a consulta usada na análise de vendas.

---

## Como o projeto foi desenvolvido

### 1. Power Query

No Power Query, trabalhei na preparação dos arquivos antes de levar os dados para o modelo.

Entre as etapas feitas durante o curso estão a organização das consultas, ajuste dos tipos de dados, tratamento das tabelas e combinação dos arquivos anuais de vendas.

### 2. Modelagem de dados

Depois do tratamento, a próxima etapa foi montar o modelo de dados seguindo a estrutura trabalhada no projeto do curso.

As tabelas de vendas e devoluções foram relacionadas com calendário, clientes, produtos, categorias e territórios. Isso permite usar essas informações juntas nas análises do relatório.

![Modelo de dados do projeto](./Imagens/Tela%20de%20Modelo%20de%20Dados.jpg)

#### Visão do modelo — vendas

![Modelo focado na tabela de vendas](./Imagens/Tabela%20de%20Vendas.jpg)

#### Visão do modelo — retornos

![Modelo focado na tabela de retornos](./Imagens/Tabela%20de%20Retornos.jpg)

### 3. DAX

Ao longo das aulas, também fui criando as medidas em DAX usadas no relatório.

Elas permitem calcular e acompanhar informações como receita, lucro, pedidos, devoluções, taxa de devolução e outros indicadores que mudam conforme os filtros aplicados no dashboard.

### 4. Dashboard

A parte visual também foi construída seguindo o projeto proposto no curso.

O relatório final ficou dividido em páginas com uma visão geral dos resultados e análises mais específicas de região, produtos e clientes.

---

## Páginas e análises do relatório

### Visão executiva

A página principal reúne os indicadores gerais da Adventure Works, como receita, lucro, pedidos e taxa de devolução. Também mostra a evolução da receita, pedidos por categoria e os produtos com maior volume de pedidos.

![Visão executiva do dashboard](./Imagens/Tela%20Dashboard%20Executivo.jpg)

### Mapa

A página de mapa mostra a distribuição dos resultados entre **Europa, América do Norte e Pacífico**, além dos países presentes na base.

![Análise geográfica](./Imagens/Tela%20de%20Mapa.jpg)

### Detalhes de produto

Nesta página é possível selecionar um produto e acompanhar pedidos, receita e lucro em relação às metas. Também há análises de histórico e um ajuste de preço usado para simular cenários.

![Detalhes de produto](./Imagens/Tela%20de%20Produtos.jpg)

### Detalhes de cliente

A página de clientes mostra quantidade de clientes, receita por cliente, distribuição por renda e ocupação, ranking e destaque para os clientes com maior receita.

![Detalhes de cliente](./Imagens/Tela%20de%20Clientes.jpg)

### Outros recursos trabalhados no curso

O projeto também passou por recursos como **Decomposition Tree**, **Key Influencers** e páginas de dica de ferramenta.

#### Decomposition Tree

![Decomposition Tree](./Imagens/Tela%20de%20%C3%81rvore%20de%20Decomposi%C3%A7%C3%A3o.jpg)

#### Key Influencers

![Key Influencers](./Imagens/Tela%20de%20Chaves.jpg)

#### Dica de ferramenta

![Página de dica de ferramenta](./Imagens/Tela%20de%20Dicas%20de%20Ferramenta.jpg)

---

## O que dá para analisar

Com o relatório é possível analisar:

- evolução das vendas e da receita ao longo do tempo;
- lucro, pedidos e devoluções;
- desempenho por região e território;
- categorias, subcategorias e produtos;
- desempenho de produtos em relação às metas;
- perfil da base de clientes;
- clientes com maior participação na receita;
- diferenças entre períodos e segmentos.

---

## O que pratiquei no projeto

- Power BI Desktop
- Power Query
- Importação e tratamento de dados
- Combinação de arquivos
- Modelagem de dados
- Relacionamentos entre tabelas
- DAX
- Criação de medidas
- Parâmetros e análise de cenário
- Visualização de dados
- Dashboards interativos
- Decomposition Tree
- Key Influencers

---

## Arquivos do projeto

O arquivo final do Power BI está em:

[`Dashboard/Adventure Works - Maven Analytics.pbix`](./Dashboard/Adventure%20Works%20-%20Maven%20Analytics.pbix)

Os arquivos usados como fonte estão em:

[`Dados/`](./Dados/)

Os prints usados nesta documentação estão em:

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

Esse projeto foi uma das partes práticas do curso e serviu para juntar, em um único trabalho, os principais conteúdos que eu vinha aprendendo no Power BI.