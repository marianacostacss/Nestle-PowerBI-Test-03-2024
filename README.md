O Projeto em questão trata-se de um desafio de conhecimento em Power BI aplicado pela Nestlé para avaliação de habilidades. Segue abaixo os processos avaliados:


1. **Data Load**  
   1.1. Parameter Creation and Loading Dimension Tables  
   1.2. Parameter Creation and Loading Sales Tables  

2. **Data Modeling**  
   2.1. Data Preparation  
   2.2. Create a GeoKey  
   2.3. Create a Function  
   2.4. Create a Data Model  

3. **DAX Calculations**  
   3.1. Total Revenue  
   3.2. Total Cost  
   3.3. Gross Profit  
   3.4. Gross Profit %  
   3.5. AVG Sales Per Day  
   3.6. Market Share Measure (MS%)  
   3.7. Time Measures Calculation  

4. **Visualization**  
   4.1. Showcase Best Practices in Visualization

##Resultado:

O Dashboard criado é composto por três telas interativas correpondentes às imagens a seguir:

Tela 1 (Home)

![image](https://github.com/user-attachments/assets/0997b441-b79b-476b-b20c-316ea95382fe)

Tela 2 (Sales First View)

![image](https://github.com/user-attachments/assets/d9d9fea3-70c1-4b25-8764-f9f9ac805abb)

Tela 3 (Revenue Analysis View)

![image](https://github.com/user-attachments/assets/b06d0a24-79bf-4ada-958d-f9537ec4e900)


Os botões interativos exibidos na lateral esquerda das telas 2 e três tem as seguintes funções respectivamnete:
- Retornar á página inicial
- Navegar entre as páginas 2 e 3
- Ecibir os filtros interativos

![image](https://github.com/user-attachments/assets/f04fd31f-8f2d-42b9-b12b-15ed5d29f6e4)


###Modelagem e relacionamentos:

![image](https://github.com/user-attachments/assets/188c9be7-ce1f-44f0-bbe2-420c7f4bb21a)


###Feedback:

( + ) Pontos positivos

( - ) Pontos de melhoria



Power Query:

Utilizou parâmetros ( + )

Passos não optimizados – o mesmo passo é feito várias vezes na mesma query desnecessariamente ( - )

Não utilizou função como solicitado ( - )

                                             

Tabelas importadas:

Relacionamento corretos de 1 para muitos( + )

Esquema estrela. ( + )

 

Dax:

Utilização de Variáveis ( + )

Utilização de funções temporais (DATESYTD, DATESMTD e SAMEPERIODLASTYEAR) ( + )

Utilização correta de Filtro (CALCULATE, ALL) ( + )

Utilização correta da função SUMX - Valores corretos ( + )

 

Visual:

Atencioso com os títulos dos visuais ( + )

Escolha ruim de gráficos e visuais ( - )


   
