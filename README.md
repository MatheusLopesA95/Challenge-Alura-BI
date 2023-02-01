# Challenge Alura BI
Alura is a program course platform that teaches data science. The platform is designed in order for us  to practice what we learnt and create portfolios . On the challenge BI 2 we received three datasets and a trello card,inquiring for some information to make a dashboard. I selected Power BI software  in order to execute this challenge.

In the first week I received datasets from logistics and I did the following dashboard (Dashboard Logística). 
![image](https://user-images.githubusercontent.com/99135339/215925428-f91002fb-789a-446f-81c9-0dc40ddc950a.png)

In addition to the execution, I presented the general information using a big card, where I organized all of them. By the side, I positioned a pizza chart showing the percentage of deliveries late and on time.
![image](https://user-images.githubusercontent.com/99135339/215925484-3fb023e9-161b-4d46-961e-534b8a338d7d.png)

I performed a table showing the comparative between the months throughout the  years of  2019 and 2020.
![image](https://user-images.githubusercontent.com/99135339/215925584-8b6fc5e3-62dc-47e1-b8f3-8c533d209302.png)
To compose it , I applied  a year filter in the 2019 column and with a DAX function ‘sameperiodlasyear’ ("Pedidos Ano Anterior = CALCULATE([Soma pedidos], sameperiodlastyear(Calendario[Date]))") it was created  a 2020 column, to show the growth in % and the use of  the following DAX formula: "%Crescimento = DIVIDE([Soma pedidos] - [Pedidos Ano Anterior], [Pedidos Ano Anterior])"
![image](https://user-images.githubusercontent.com/99135339/215925844-f5242adf-e77b-4a0c-8661-571445d55568.png)

The following information was demonstrated by using bar charts: “Orders per year”, “Percentage of Orders by state”, “Mean of products in Stock” and the “Number of orders per month”.
![image](https://user-images.githubusercontent.com/99135339/215926368-16a853fb-ea8b-4d60-b4d9-afea4d55a7c0.png) ![image](https://user-images.githubusercontent.com/99135339/215926410-055c6041-a325-42c1-bebb-15559f9ca5e9.png) ![image](https://user-images.githubusercontent.com/99135339/215926449-58ca02d4-733e-42c5-9bd7-9658b3fb1e30.png)

![image](https://user-images.githubusercontent.com/99135339/215926283-9e2036ad-6395-4878-bc24-fe8016c7a470.png)

To make the “Percentage of orders by state” It was chosen by the power query where the name was changed by the states, since São Paulo and Rio de Janeiro are the main destinations, with 45%. The other states have the same amount, so I decided to group them together creating a new column
.

