# Desafio 09: Criando um Modelo de Dados com Power BI

👋 Olá, eu sou Johnnatan Krause! Este é o meu projeto para o **Desafio 09** do módulo de Power BI no bootcamp de **Engenharia de Dados com Python**.

## Descrição do Desafio

Neste desafio, o objetivo foi construir um modelo de dados utilizando a tabela de **Financial Sample**, criando tabelas dimensão e fato com base em um esquema em estrela (star schema). 

### Objetivos

O modelo de dados contém as seguintes tabelas:

1. **Financials_origem**: Tabela de backup da tabela original (modo oculto).
2. **D_Produtos**: Contém informações sobre os produtos, como ID do produto, nome do produto, média de unidades vendidas, valores de venda (mediana, máximo, mínimo).
3. **D_Produtos_Detalhes**: Informações detalhadas dos produtos, incluindo faixa de desconto, preço de venda e unidades vendidas.
4. **D_Descontos**: Tabela relacionada a descontos, incluindo ID do produto, desconto e faixa de desconto.
5. **D_Detalhes**: Informações adicionais relevantes sobre vendas (verifique os campos que não estão nas outras tabelas).
6. **D_Calendário**: Criada utilizando DAX com a função `calendar()`.
7. **F_Vendas**: Fato das vendas, incluindo campos como ID do produto, unidades vendidas, preço de venda, faixa de desconto, segmento, país, vendedor, lucro e data.

### Processo de Construção

- **Seleção de Colunas**: Escolhi colunas relevantes da tabela original para compor as novas tabelas.
- **Criação de Tabelas**: As tabelas dimensão foram criadas com as colunas selecionadas, e a tabela fato foi organizada para refletir as métricas de vendas.
- **DAX e Funcionalidades**: Utilize funções DAX para criar medidas e cálculos, como médias e totais, além de implementar condicionais para colunas específicas.
  
### Visualização do Modelo

Abaixo está uma imagem do esquema em estrela criado durante o projeto:

![Esquema em Estrela](link-para-a-imagem-do-esquema)

## Links para Dados Utilizados

- **Dados Utilizados**: [Financial Sample no GitHub](https://github.com/julianazanelatto/power_bi_analyst)

## Dicas e Recursos para Aprofundamento

- **Cursos e Tutoriais**: Explore plataformas como DIO, Coursera, Udemy e YouTube para cursos de Power BI.
- **Comunidades**: Participe de grupos no LinkedIn e fóruns como o Power BI Community para trocar experiências.
- **Documentação Oficial**: Consulte a [documentação do Power BI](https://docs.microsoft.com/pt-br/power-bi/) para aprofundar seu conhecimento.

## Conclusão

Este desafio foi uma excelente oportunidade para aplicar conhecimentos de modelagem de dados e DAX. Estou empolgado para usar essas habilidades em futuros projetos!

## Conecte-se comigo

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/johnnatankrause/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JohnnatanKrause) 
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/channels/@johnnatankrause/)
[![DIO](https://img.shields.io/badge/DIO-0000FF?style=for-the-badge&logo=digitalocean&logoColor=white)](https://www.dio.me/users/johnnatankrause)

## Habilidades

![Power BI](https://img.shields.io/badge/Power%20BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

JK
