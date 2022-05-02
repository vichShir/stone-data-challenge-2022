# Stone Data Challenge 2022 🪨

![CSS3](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=#E35A16) ![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white)

### 📃 Descrição

O objetivo do projeto é propôr uma solução para o problema proposto no **Stone Data Challenge 2022**. A Stone visa ajudar o empreendedor brasileiro com seu negócio, oferecendo produtos e serviços desde **maquininha de vendas à sistemas de ERP**.

Durante a pandemia de COVID-19, a empresa teve que evoluir suas **ações de comunicação de saldos devedores de crédito**, causada pelo aumento de clientes inadimplentes.

### 😵 Problema

A Stone precisou garantir a recuperação de clientes que apresentam **problemas no ritmo de pagamento de crédito**, devido ao aumento de clientes inadimplentes provocada pela pandemia. Para isso, uma das ações tomadas foi **refinar as estratégias de comunicação com os clientes**.

Para tornar essa ação mais eficiente, questiona-se:

* Qual é a curva ideal de vezes que acionamos um cliente?

### 🎲 Entendendo a estrutura dos dados

Para este case, foi disponibilizado uma **amostra de 14 mil** contratos **gerados aleatoriamente** tendo como inspiração o cenário de dados de uma empresa real. Para isso, foram disponibilizadas as seguintes tabelas:

* **Base PORTFOLIO_GERAL.csv**
  * Esta tabela contém uma amostra aleatória do histórico de alguns contratos de crédito. Ou seja, cada contrato contém N registros, um para cada dia do histórico do contrato desde o momento de sua originação.

* **Base PORTFOLIO_TPV.csv**
  * Esta base de dados possui informações dos registros de transações relacionadas à maquininha Stone do cliente, onde é possível amortizar o empréstimo através das transações e pode ser utilizada para entender a performance de pagamento de forma geral.
* **Base PORTFOLIO_COMUNICADOS.csv**
  * Aqui você encontrará todas as informações relacionadas às ações de comunicação enviadas aos clientes bem como seu respectivo status e demais informações.
* **Base PORTFOLIO_CLIENTES.csv**
  * E nesta tabela você encontrará todas as informações relacionadas aos dados cadastrais dos clientes que contrataram empréstimos, bem como suas respectivas informações geográficas e de segmentos de negócios.

### 📚 Conteúdo

- Dados final;
- Códigos e scripts;
- Documento "Framework de avaliação";
- Dashboard.

### 🌐 Motivação

Este projeto é a proposta de resolução elaborado por mim da 2ª etapa, que será avaliado no Hackathon da **Stone Data Challenge** de 2022.

### 📖 Referências

* Satus Sistemas. **write-off: você sabe o que significa?** 2017. Disponível em: https://www.satussistemas.com.br/o-que-significa-write-off/.
* CUNHA, Helen. **TPV (Total Payment Volume): entenda o que é esse indicador e como adaptá-lo à sua realidade**. Disponível em: https://blog.tecnospeed.com.br/tpv-total-payment-volume/#:~:text=A%20sigla%2C%20que%20em%20ingl%C3%AAs,adquirentes%2C%20subadiquirentes%20e%20outros%20intermedi%C3%A1rios.
* NEOS. **The Five Zones Every Data Lake Should Consider**. 2019. Disponível em: https://www.neosllc.com/the-five-zones-every-data-lake-should-consider/.
