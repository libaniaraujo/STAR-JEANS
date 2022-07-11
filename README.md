# STAR JEANS
 
<img src = "https://user-images.githubusercontent.com/94937578/178168655-72a2ab65-b7b9-4a91-aada-135258a8d330.png" width="1000px" />
</div>

## 1. Resumo:

- <b>Código no Jupyter Notebook</b>
- <b>Dashboard no Tableau</b>

## 2. Contexto:

Dois brasileiros, amigos e sócios de empreendimento, depois de vários negócios bem sucedidos planejam entrar no mercado de moda dos USA como um modelo de negócios do tipo e-commerce. A ideia inicial é entrar no mercado com apenas um produto e para um público específico, no caso o produto seria calças Jeans para o público masculino. O objetivo é manter o custo de operação baixo e escalar a medida que forem conseguindo clientes. Porém, mesmo com o produto de entrada e a audiência definidos, os dois sócios não tem experiência nesse mercado de moda e portanto não sabem definir coisas básicas como preço, tipo de calça e material de fabricação de cada peça. Portanto, decidem se basear nos produtos vendidos pela concorrente H&M.

## 3. Problema de negócio:

Assim, os dois sócios contrataram uma consultoria de ciência de dados para responder as seguintes perguntas:

1. Qual o melhor preço de vendas para as calças?
2. Quantos tipos de calças e suas cores para o produto inicial?
3. Quais as matérias-prima necessárias para confeccionar as calças?

## 4. Planejamento da solução:

- Obter os dados relativos às vendas de calças jeans masculinas da H&M via webscrapping.
- Limpar e descrever os dados.
- Realizar a análise exploratória dos dados, buscando responder os problemas de negócio.
- Apresentar os resultados em um dashboard no Tableau.

## 5. Dados:

Após o webscrapping no site da H&M e o tratamento dos dados, obtém-se informações referentes aos seguintes atributos dos produtos: 

**Atributo** | **Descrição**
--- | --- 
 `ID` | Número de identificação do produto
 `Composicao` | Materiais que compõe o produto
 `Estilo` | Estilo do produto
 `Cor` | Cor do produto
 `Tipo` | Tipo do produto
 `Preco` | Preço do produto (em dólares)
 `Tamanho_num` | Tamanho do produto (em centímetros)
 `Tamanho_modelo` | Tamanho do produto
 `Algodao` | Proporção de algodão que compõe o produto (0 a 1)
 `Poliester` | Proporção de poliéster que compõe o produto (0 a 1)
 `Spandex` | Proporção de spandex que compõe o produto (0 a 1)
 `Elasterell` | Proporção de elasterell que compõe o produto (0 a 1)
 
## 6. Principais resultados:

- O preço médio das calças jeans vendidas pela H&M é: US$29.86.
- O preço mínimo das calças jeans vendidas pela H&M é: US$49.99.
- O preço máximo das calças jeans vendidas pela H&M é: US$12.99.

O número de calças do tipo 'Freefit® Slim Jeans' é: 8.
O número de calças do tipo 'Hybrid Regular Denim Joggers' é: 1.
O número de calças do tipo 'Loose Jeans' é: 2.
O número de calças do tipo 'Regular Jeans' é: 10.
O número de calças do tipo 'Relaxed Jeans' é: 17.
O número de calças do tipo 'Skinny Jeans' é: 17.
O número de calças do tipo 'Slim Tapered Jeans' é: 12.

<img src = "https://user-images.githubusercontent.com/94937578/178369536-5241f7cf-aa6a-4f2a-bac0-ae980da952a5.png" width="700px" />


## 7. Produto final (dashboard):

## 8. Referências:

- [<b>Comunidade DS</b>](https://www.comunidadedatascience.com/)

