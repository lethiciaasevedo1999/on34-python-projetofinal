# **Introdução**

Esse projeto foi elaborado para o trabalho de conclusão final do curso de **Análise de Dados com Python oferecido pela Instituição de ensino {Reprograma}**.
O mesmo possui uma base de dados sintética, construída utilizando a biblioteca **Faker** do python,juntamente com dados transacionais de uma plataforma de e-commerce e atributos adicionais, além de lógica personalizada para simulação de padrões de transações realistas e cenários fraudulentos, projetados especificamente para teste de algoritmos e treinamento de machine learning para detecção de fraude. 

**Objetivo do projeto:**
- Definir e reunir uma fonte de dados.
- Tratar os dados aplicando as etapas necessárias para limpeza e visualização. 
- Analisar os dados gerando percepções.
- Trazer uma conclusão com base no objetivo inicial. 

Base de dados escolhida: [Transações Fraudulentas no E-commerce](https://www.kaggle.com/datasets/shriyashjagtap/fraudulent-e-commerce-transactions)  
Fonte: [Kaggle](https://www.kaggle.com/)

**Descrição de colunas:**
- `Transaction ID:` Número identificador para cada transação.
- `Costomer ID:` Número identificador para cada cliente.
- `Transaction Amount:` Valor da compra. 
- `Transaction Date:` Data e hora da compra. 
- `Payment Method:` Método de pagamento (cartão de crédito, paypal, transferência bancária)
- `Product Category:` Categoria do produto. 
- `Quantity:` Quantia de produtos adquiridos. 
- `Costomer Age:` Idade do cliente.
- `Customer Location:` Endereço do cliente.
- `Device Used:` Dispositivo utilizado para realizar a compra (Tablet, celular, computador)
- `IP Address:` Endereço de IP do dispositivo usado para realizar a compra. 
- `Shipping Address:` Endereço de entrega da compra. 
- `Billing Address:` Endereço de cobrança ou envio da fatura do cartão. 
- `Is Fraudulent:` Indicador binário de se a transação é fraudulenta (1 para fraudulenta, 0 para legítima).
- `Account Age Days:` Há quantos dias a conta foi criada. 
- `Transaction Hour:` Hora do dia em que a compra foi feita. 

________________________________________________________________________________________
