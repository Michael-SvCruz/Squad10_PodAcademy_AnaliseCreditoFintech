# Dataset Description

**OBSERVAÇÃO:** Baixe os arquivos para a competição diretamente da página do [Kaggle](https://www.kaggle.com/competitions/pod-academy-analise-de-credito-para-fintech/data)

Para resolver o problema de negócio a empresa reuniu os dados que estavam disponíveis e disponibilizou no formato de arquivo CSV para o treinamento e avaliação dos modelos.
Abaixo segue uma breve descrição do conteúdo de cada arquivo disponibilizado

1. **application_train.csv/application_test.csv:** Estes são os principais dados de treino e teste com informações sobre cada
   solicitação de empréstimo na PoD Bank. Cada empréstimo tem sua própria linha e é identificado pela variável SK_ID_CURR.
   Os dados de aplicação de treinamento vêm com a variável TARGET, indicando 0: o empréstimo foi pago ou
   1: o empréstimo não foi pago (inadimplência).
   
2. **previous_application.csv:** Contém informações sobre aplicações de empréstimo anteriores de um cliente na PoD Bank.

3.  **installments_payments.csv:** Detalha o histórico de pagamentos de empréstimos anteriores na PoD Bank.

4.  **bureau.csv:** Fornece dados de crédito de outras instituições financeiras.

5.  **POS_CASH_balance.csv:** Informações sobre o histórico de pagamentos de POS (Point of Sale) ou empréstimos em
    dinheiro na PoD Bank.

6.  **bureau_balance.csv:** Informações mensais sobre créditos anteriores do cliente em outras instituições financeiras.

7.  **credit_card_balance.csv:**  Informações mensais sobre saldos de cartões de crédito do cliente na PoD Bank.

Para obter os Metadados, contendo a descrição de cada varável de cada arquivo, 
consulte o arquivo HomeCredit_columns_description.csv

![Imagem](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F742482%2F94cce05a6f5ff19dce16050b0fbdf1c9%2FPoD_Bank_Dados.JPG?generation=1700179419643836&alt=media)
   

