# Análise de transações fraudulentas no E-commerce 🚨@

<div align= "center">
<img src="/material/assets/fraudador.png" alt="Fraudador">
</div>

## **Introdução**

Esse projeto foi elaborado para o trabalho de conclusão final do curso de **Análise de Dados com Python oferecido pela Instituição de ensino {Reprograma}**.  
O mesmo possui uma base de dados sintética, construída utilizando a biblioteca **Faker** do python,juntamente com dados transacionais de uma plataforma de e-commerce e atributos adicionais, além de lógica personalizada para simulação de padrões de transações realistas e cenários fraudulentos, projetados especificamente para teste de algoritmos e treinamento de machine learning para detecção de fraude. 

## **Motivação**  🚀  
Trabalhei como analista de fraude na maior empresa de análise de fraude do Brasil, a **ClerSale**, por 7 anos. Lá aprendi tudo sobre análise e após muito tempo analisando pedido a pedido, meus últimos 3 anos de empresa foram integrando a equipe de análises ostensivas, onde pude atuar na linha de frente com análise de pedidos em lote, realização de estudos para sinalização das operações de nível I e II, detectando comportamentos suspeitos de fraude, além do envio de alertas de bloqueios para os clientes da empresa assim que detectada a necessidade.   
Tendo esses anos de experiência no ramo, oque me motivou foi poder mostrar minha área de conhecimento, explicando como consigo gerar insights com análises em lote e como chego a conclusões dos pedidos. 

## **Objetivo do projeto:** 🎯  
O projeto tem por objetivo principal realizar uma análise exploratória dos pedidos, para possível detecção de anomalias e identificar padrões de fraudes.  
Ao decorrer da análise, também foi se desenvolvendo insights de comparações entre pedidos fraudulentos e pedidos não fraudulentos, possibilitando a visualização e clarificação de diferenças.  
Por fim, o projeto tem por objetivo também mostrar ao público em geral, como funciona uma análise de fraude, pois ainda é uma área desconhecida por muitos, como os dados da população são armazenados e como eles são relacionados entre si, para que uma análise seja feita com relevância.    

## **Acesse o projeto:** 📁

🔗 A análise exploratória do projeto pode ser visualizada neste link: [Análise Exploratória - Github](https://github.com/lethiciaasevedo1999/on34-python-projetofinal/blob/main/material/analise-exploratoria/analise.ipynb)  
🔗 A apresentação de resultados no Tableau pode ser visualizada neste link: [Transações Fraudulentas no E-Commerce - Tableau](https://public.tableau.com/views/TransaesFraudulentasnoEcommerce-ProjetoFinalReprograma-LethiciaAsevedo/Painel1?:language=pt-BR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)   
🔗 A apresentação de slides do projeto pode ser visualizada neste link: [Apresentação de slides](link) 

## **Conclusão após análise:**

- Com 7 anos de experiência no setor, posso afirmar que o cenário de fraudes em e-commerce da nossa base de dados, embora preocupante, ainda não ultrapassou os pedidos legítimos, cenário este que se iguala ao mundo real até o momento. Contudo, é vital que analistas e profissionais da área estejam sempre atentos às inovações tecnológicas e tendências emergentes. A evolução das ferramentas de detecção de fraudes, incluindo o uso de inteligência artificial e machine learning, é essencial para manter esse equilíbrio.  
## 
**Insights gerados durante o processo de análise exploratória**  
Durante o processo de construção e análise dos dados, seguindo meus anos de experiências e cases, começou a surgir insights como : Esses pedidos fraudulentos possuem recorrência de dados ? afinal, é muito comum ser comportamento do fraudador deixar padrõs como rastros. Foi então que comecei a investigar se: 
- Havia recorrência de dispositivos, podendo ser bom ou ruim para a análise; 
- Recorrência de métodos de pagamento;
- Além de muitos pedidos fraudulentos na mesma região.  

 **Nenhuma das características citadas foram encontradas, de modo que formassem anomalias para identificação de comportamentos suspeitos de fraude nos grupos de pedidos fraudulentos.**
##

- Considerando as análises realizadas neste material, e focando apenas nesse cenário e nos dados disponíveis, pode-se afirmar que a maioria das transações fraudulentas podem ser classificadas como autofraudes. Autofraude refere-se à situação em que o cliente efetua a compra, mas alega não tê-la feito, buscando evitar o pagamento ou solicitar o estorno do valor. Além disso, também se observa que muitos desacordos comerciais ocorrem, onde o cliente, por algum motivo, desiste da compra, opta pela troca do produto ou apresenta outras razões, e em vez de cancelar o pedido, nega a realização da compra, na expectativa de que o cancelamento aconteça de forma imediata.  

- Lembrando que a conclusão das classificações dos pedidos fraudulentos foram feitas apenas sob percepções de alguém experiente, no mundo real essas classificações são feitas por uma equipe especializada que entram em contato com o cliente para saber a história verídica e juntamente com alguns insumos disponibilizados também através de dados aos quais não foram fornecidos nessa base, chegam a uma conclusão, que mesmo assim, podem não ter 100% de veracidade. 

- As análises de fraude não apenas salvaguardam a integridade dos negócios, mas também geram milhões de reais em economia anualmente para grandes comércios e varejistas. Sem essas análises, as perdas poderiam ser drasticamente prejudiciais. Portanto, é de extrema import6ancia que os analistas de fraudes permaneçam um passo à frente, investindo em conhecimento e tecnologia para garantir um futuro mais seguro para o e-commerce.



## **Fontes e atribuições do projeto:**  🔎  
Base de dados escolhida: 📁 [Transações Fraudulentas no E-commerce](https://www.kaggle.com/datasets/shriyashjagtap/fraudulent-e-commerce-transactions)  
Fonte: 📂 [Kaggle](https://www.kaggle.com/)

## **Ferramentas utilizadas no projeto:**  
- 📌Python versão 3.12.6 [Documentação](https://devdocs.io/python~3.12/)
- 📌Biblioteca Matplotlib versão 3.7 [Documentação](https://devdocs.io/matplotlib~3.7/)
- 📌Biblioteca Pandas versão 2.2.2 [Documentação](https://devdocs.io/pandas~2/)
- 📌Vscode [Documentação](https://code.visualstudio.com/docs)
- 📌Extensão Jupyter Notebook versão 4.9.1 [Documentação](https://docs.jupyter.org/en/latest/)
- 📌Extensão Git LFS(Large File Storage) versão 3.2.0 [Documentação](https://github.com/git-lfs/git-lfs/tree/main/docs?utm_source=gitlfs_site&utm_medium=docs_link&utm_campaign=gitlfs)  



## **Autoria do projeto:**  
Projeto desenvolvido por **Lethicia Asevedo**, turma ON34 - {Reprograma}.    
- 🔗[Linkedin](https://www.linkedin.com/in/lethiciaasevedo/)  
- 🔗[Github](https://github.com/lethiciaasevedo1999)



________________________________________________________________________________________

*O projeto está sujeito a atualizações a qualquer momento caso haja necessidade*

________________________________________________________________________________________
