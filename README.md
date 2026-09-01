# Adventure Works | Power BI

Projeto de Business Intelligence desenvolvido durante o curso **Microsoft Power BI Desktop for Business Intelligence**, da Maven Analytics.

Neste projeto trabalhei com a base fictícia da Adventure Works, passando pelas principais etapas de construção de uma solução em Power BI: preparação dos dados, modelagem, criação de medidas em DAX e desenvolvimento do dashboard.

A proposta foi transformar os dados brutos disponibilizados no curso em uma estrutura de análise que permitisse acompanhar o desempenho da empresa e explorar informações relacionadas a vendas, produtos, clientes, devoluções, regiões e períodos.

---

## Contexto do projeto

O projeto utiliza a Adventure Works como cenário de negócio para simular a atuação de um Analista de Business Intelligence.

O objetivo foi construir uma solução capaz de organizar diferentes fontes de dados e transformá-las em informações úteis para análise, aplicando em um único projeto os conhecimentos desenvolvidos ao longo do curso.

Por ser um projeto de estudo, ele não representa uma experiência profissional com a Adventure Works. O foco aqui é demonstrar a aplicação prática do processo de construção de uma solução em Power BI.

---

## Dados utilizados

A base do projeto é formada por arquivos CSV disponibilizados para o exercício. Os arquivos utilizados no modelo estão organizados na pasta [`Dados`](./Dados/).

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

Os arquivos anuais de vendas foram tratados em conjunto para formar a base utilizada na análise de vendas.

---

## Processo de desenvolvimento

### 1. Preparação dos dados — Power Query

Os arquivos brutos foram importados e preparados no Power Query antes de serem utilizados no modelo.

Nesta etapa foram aplicadas transformações como organização das consultas, ajuste dos tipos de dados, tratamento das tabelas e combinação dos arquivos anuais de vendas.

### 2. Modelagem de dados

Após o tratamento, as tabelas foram organizadas em um modelo relacional para permitir que as diferentes áreas da análise trabalhassem de forma integrada.

A modelagem conecta os dados de vendas e devoluções às informações de calendário, clientes, produtos e territórios.

### 3. Medidas e cálculos — DAX

As métricas do relatório foram criadas com DAX para permitir análises dinâmicas conforme os filtros e seleções realizados no dashboard.

O projeto utiliza medidas para acompanhar indicadores de desempenho e comparar resultados em diferentes contextos do modelo.

### 4. Visualização

A etapa final foi a construção do relatório no Power BI, reunindo os principais indicadores e análises em uma interface interativa.

Os visuais foram organizados para facilitar a navegação e permitir que diferentes dimensões do negócio fossem exploradas através de filtros e interações entre os gráficos.

---

## O que o projeto permite analisar

Entre as possibilidades de análise presentes no projeto estão:

- evolução das vendas ao longo do tempo;
- desempenho por região e território;
- comportamento de produtos e categorias;
- perfil e desempenho da base de clientes;
- devoluções;
- comparação entre diferentes períodos e segmentos.

---

## Habilidades aplicadas

- Power BI Desktop
- Power Query
- Modelagem de dados
- Relacionamentos entre tabelas
- DAX
- Criação de medidas
- Visualização de dados
- Construção de dashboards interativos
- Organização de indicadores e informações para análise

---

## Arquivos do projeto

### Dashboard

O arquivo final do Power BI está disponível em:

[`Dashboard/Adventure Works - Maven Analytics.pbix`](./Dashboard/Adventure%20Works%20-%20Maven%20Analytics.pbix)

### Dados

Os arquivos utilizados no projeto estão disponíveis em:

[`Dados/`](./Dados/)

### Imagens

A pasta [`Imagens/`](./Imagens/) será utilizada para os prints do dashboard apresentados nesta documentação.

---

## Como abrir

1. Baixe o arquivo `.pbix` disponível na pasta `Dashboard`.
2. Abra o arquivo utilizando o **Power BI Desktop**.
3. O relatório pode ser visualizado normalmente com os dados já armazenados no arquivo.

> **Observação:** as fontes do projeto foram originalmente configuradas a partir dos arquivos locais utilizados durante o curso. Caso seja necessário atualizar os dados após o download, pode ser necessário redefinir os caminhos das fontes no Power Query.

---

## Sobre o projeto

Este projeto faz parte do meu processo de formação em Análise de Dados e Business Intelligence e foi desenvolvido para praticar, em um cenário completo, o fluxo de trabalho utilizado na construção de relatórios no Power BI.

**Curso:** Microsoft Power BI Desktop for Business Intelligence  
**Plataforma:** Maven Analytics  
**Ferramenta principal:** Microsoft Power BI Desktop
