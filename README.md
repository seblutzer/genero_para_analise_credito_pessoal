# Relevância do Gênero para Análise de Crédito

## 1. Introdução
Olá a todos! Neste projeto, exploraremos a intrigante questão de como o gênero pode influenciar a análise de crédito. Será que o gênero tem um impacto significativo na avaliação de crédito? Essa é uma questão importante, não apenas para aprimorar os modelos de concessão de crédito, mas também para garantir a equidade e a justiça nas decisões financeiras.

Este é um projeto em Python, e o código foi escrito para ser fácil de seguir e entender. Ele é dividido em várias seções, incluindo a limpeza dos dados, a exploração dos dados, a modelagem e a avaliação do modelo. Em cada seção, fornecemos explicações detalhadas de nossas decisões e métodos.

Este projeto está disponível tanto no GitHub ([Clique aqui](https://github.com/seblutzer/genero_para_analise_credito_pessoal.git)) quanto no Kaggle ([Clique aqui](https://www.kaggle.com/code/srgiolutzer/relev-ncia-do-g-nero-para-an-lise-de-cr-dito/edit)), e publicado um dashboard interativo no Looker Data Studio para visualização ([Clique aqui](https://lookerstudio.google.com/reporting/1f96a7ec-0df3-4c0c-8bd7-1576fdf0e72c) para que todos possam visualizar e contribuir. Acreditamos que este é um tópico importante e esperamos que este projeto possa contribuir para a discussão sobre equidade de gênero na análise de crédito. Convidamos todos a participar da discussão, fornecer feedback e contribuir com suas próprias análises e insights.

Esperamos que você ache este projeto interessante e útil. Obrigado por sua atenção e participação!

<img width="480" alt="Captura de Tela 2023-10-30 às 15 51 29" src="https://github.com/seblutzer/genero_para_analise_credito_pessoal/assets/114627479/64635299-358e-4970-b600-ce3020ef38cb">


### 1.1. Sobre o datase
Este dataset contém informações de perfil e comportamento de clientes de um banco, incluindo detalhes demográficos e dados relacionados à atividade bancária. O objetivo é fornecer insights sobre os fatores que podem influenciar o padrão de default (inadimplência) dos clientes.

### 1.2. Informação das Colunas

Os dados estão organizados em várias colunas, cada uma representando uma variável diferente, conforme descrito abaixo:

* **id:** Identificador único para cada cliente.
* **default:** Uma variável binária indicando se o cliente entrou em default (1 para sim, 0 para não).
* **idade:** A idade do cliente em anos.
* **sexo:** O gênero do cliente.
* **dependentes:** Número de dependentes que o cliente possui.
* **escolaridade:** Nível de escolaridade do cliente.
* **estado_civil:** Estado civil do cliente.
* **salario_anual:** Renda anual do cliente.
* **tipo_cartao:** Tipo de cartão de crédito que o cliente possui.
* **meses_de_relacionamento:** Quantidade de meses que o cliente tem um relacionamento com o banco.
* **qtd_produtos:** Quantidade de produtos que o cliente tem com o banco.
* **iteracoes_12m:** Quantidade de interações que o cliente teve com o banco nos últimos 12 meses.
* **meses_inativo_12m:** Quantidade de meses que o cliente esteve inativo nos últimos 12 meses.
* **limite_credito:** Limite de crédito do cliente.
* **valor_transacoes_12m:** Valor total das transações que o cliente fez nos últimos 12 meses.
* **qtd_transacoes_12m:** Quantidade total de transações que o cliente fez nos últimos 12 meses.

Estes dados podem ser usados para construir modelos de machine learning para prever a probabilidade de um cliente entrar em default, possibilitando ao banco tomar medidas preventivas. Além disso, pode-se realizar uma análise exploratória para entender melhor o perfil dos clientes e identificar padrões e tendências.

[Clique aqui para consultar a fonte original dos dados](http://github.com/andre-marcos-perez/ebac-course-utils/tree/main/dataset)

![Análise de crédito](https://github.com/seblutzer/genero_para_analise_credito_pessoal/assets/114627479/189bd47b-8bd6-44b4-9704-f0eb1b2c6067)
