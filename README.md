# telecomX
## 📄 Descrição do Projeto

Este projeto consiste em uma análise exploratória de dados sobre a evasão de clientes (churn) em uma empresa de telecomunicações fictícia, a TelecomX. O objetivo principal é identificar os principais fatores que levam os clientes a cancelarem seus serviços, a fim de extrair insights que possam fundamentar a criação de estratégias de retenção mais eficazes.

A análise abrange desde a importação e limpeza dos dados até a visualização de padrões e a formulação de recomendações de negócio.

## 📊 Dataset

O conjunto de dados utilizado, `TelecomX_Data.json`, é um arquivo em formato JSON que contém informações sobre os clientes da empresa, incluindo:

-   **Informações demográficas:** Gênero, se é idoso, se possui parceiro(a) ou dependentes.
-   **Informações contratuais:** Tempo de serviço (tenure), tipo de contrato, forma de pagamento e faturamento eletrônico.
-   **Serviços contratados:** Serviço de telefonia, múltiplas linhas, serviço de internet, segurança online, backup, etc.
-   **Valores:** Cobrança mensal e cobrança total.
-   **Variável Alvo:** A coluna `Churn`, que indica se o cliente evadiu ou não.

O dataset original possuía uma estrutura aninhada, que exigiu um tratamento específico para ser utilizado em análises tabulares.

## 🛠️ Tecnologias Utilizadas

-   **Linguagem:** Python 
-   **Bibliotecas Principais:**
    -   `pandas`: Para manipulação e análise de dados.
    -   `numpy`: Para operações numéricas e tratamento de dados ausentes.
    -   `matplotlib` e `seaborn`: Para visualização de dados e criação de gráficos.
-   **Ambiente:** Google Colab (`.ipynb`), que permite a execução interativa de código Sem a necessidade de baixar um ambiente.

## 📂 Estrutura do Projeto

O projeto está organizado nos seguintes arquivos:

-   `TelecomX_BR (1).ipynb`: O notebook principal que contém todo o código e a análise passo a passo, desde a extração dos dados até a geração dos gráficos e o relatório final.
-   `TelecomX_Data.json`: O arquivo com os dados brutos utilizados na análise.
-   `README.md`: Este arquivo, que fornece uma documentação completa do projeto.

## 🚀 Como Executar o Projeto

Para executar a análise contida no notebook, siga os passos abaixo:

1.  **Pré-requisitos:** Baixe o arquivo `TelecomX_Data.json` e `TelecomX_BR (1).ipynb` e adicione o arquivo `TelecomX_BR (1).ipynb` ao seu drive.
2.  **Estrutura de Arquivos:** faça upload do arquivo `TelecomX_Data.json` no seu google colab `TelecomX_BR (1).ipynb`
3.   **Execute o GoogleColaboratory**: Execute as células de código na ordem em que aparecem para a análise completa.

## 📈 Resumo da Análise e Principais Insights

A análise exploratória revelou padrões claros sobre o perfil dos clientes que tendem a evadir:

-   **Tipo de Contrato é Crucial:** A grande maioria dos clientes que cancelaram (mais de 88%) possuía um contrato **Mês a Mês**. Contratos anuais ou de dois anos estão associados a uma taxa de retenção muito maior.

-   **Evasão Ocorre Cedo:** Clientes que evadem tendem a ter um **tempo de serviço (tenure) significativamente menor**. A mediana de permanência para este grupo é de apenas 10 meses, em comparação com 38 meses para os clientes que não evadiram.

-   **Método de Pagamento como Sinalizador:** O **Cheque Eletrônico** é o método de pagamento mais comum entre os clientes que cancelaram, indicando uma possível correlação entre essa forma de pagamento e uma menor fidelidade.

-   **Cobrança Mensal:** A cobrança mensal média dos clientes que cancelaram (R$ 74,44) é **superior à média geral** (R$ 64,80). Isso sugere que clientes com planos mais caros e sem um contrato de longo prazo podem ser mais sensíveis a preço e buscar ofertas melhores.

## 🎯 Recomendações

Com base nos insights obtidos, as seguintes recomendações são propostas para a TelecomX:

1.  **Fidelização via Contratos:** Desenvolver campanhas ativas para migrar clientes do plano "Mês a Mês" para contratos de 1 ou 2 anos, oferecendo descontos, bônus ou upgrades de serviço como incentivo.

2.  **Atenção aos Novos Clientes:** Implementar um programa de acompanhamento e retenção focado nos primeiros meses do cliente. Uma oferta especial de fidelização após o terceiro mês pode ser eficaz para reduzir o churn precoce.

3.  **Otimizar Formas de Pagamento:** Incentivar o uso de métodos de pagamento automáticos (cartão de crédito, débito em conta) por meio de pequenos descontos. Além disso, investigar se há algum problema de usabilidade ou atrito no processo de pagamento com "Cheque Eletrônico".

## 👨‍🎓 Autor

-   **Nome:** [Ana Clara Moura Sanders]
-   **Contato:** [anaclaramourasanders@gmail.com]
