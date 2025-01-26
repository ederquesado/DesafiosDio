# **Desafio: Recriando um Pipeline ETL com Criatividade e Inovação**

## **Descrição do Projeto**
Este projeto consiste na construção de um pipeline ETL (Extract, Transform, Load) inspirado no desafio apresentado durante o **Santander Dev Week 2023**. O objetivo principal foi explorar conceitos de Ciência de Dados e replicar (ou melhorar) um fluxo de ETL eficiente, aplicando técnicas de extração, transformação e carregamento de dados de maneira inovadora. Para este desafio, adaptei o processo ao meu próprio domínio, simplificando a implementação e evitando dependências de APIs externas.

---

## **Objetivos**
1. Criar um pipeline ETL personalizado que:
   - Extraia dados de uma fonte local, como arquivos CSV ou planilhas.
   - Realize transformações nos dados, utilizando lógica customizada para gerar insights relevantes.
   - Carregue os dados transformados em uma estrutura reutilizável ou visualize os resultados em um formato amigável.
2. Substituir dependências de APIs externas por implementações próprias ou fontes locais, tornando o projeto independente e acessível.
3. Consolidar conhecimentos de Ciência de Dados, Python, e boas práticas de desenvolvimento.

---

## **Etapas do Pipeline**
1. **Extração**  
   - Os dados foram extraídos de uma planilha (CSV), contendo informações fictícias sobre usuários. Cada entrada incluía dados como ID, nome, e status de pagamento.
   - Utilizei a biblioteca `pandas` para carregar e estruturar os dados em DataFrames.

2. **Transformação**  
   - Realizei limpezas básicas nos dados, incluindo:
     - Criei mensagens personalizadas para o usuarios

3. **Carregamento**  
   - Os dados transformados foram carregados em um arquivo CSV final e apresentados de forma visual.
   - Adicionei suporte para salvar relatórios detalhados que pudessem ser utilizados por equipes ou sistemas externos.
   - Carreguei em um ariquivo local para que dev menos experientes tivessem um ambiente controlado para testes antes de subir para a produção.
