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

- <b> Passo 1:</b> Coletar os dados relativos às vendas de calças jeans masculinas da H&M via webscrapping.
- <b> Passo 2:</b> Limpar e descrever os dados.
- <b> Passo 3:</b> Realizar a análise exploratória dos dados, buscando responder os problemas de negócio.
- <b> Passo 4:</b> Apresentar os resultados em um dashboard no Tableau.

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

A partir da análise dos dados sobre os produtos (calças jeans masculinas) vendidos pela H&M é possível responder às questões de negócio dos sócios.

Nesse sentido, cabe destacar as seguintes informações:

- O preço médio das calças jeans vendidas pela H&M é: US$29,86.
- O preço mínimo das calças jeans vendidas pela H&M é: US$49,99.
- O preço máximo das calças jeans vendidas pela H&M é: US$12,99.

Logo, o preço de venda médio para as calças a serem produzidas e vendidas pela nova empresa seria US$29.86, não devendo ultrapassar os valores mínimo e máximo apresentados acima.

Há 7 tipos de calças jeans masculinas: Freefit® Slim Jeans, Hybrid Regular Denim Joggers, Loose Jeans, Regular Jeans, Relaxed Jeans, Skinny Jeans, Slim Tapered Jeans.

Entre os 87 produtos analisados, os tipos de calças mais presentes são o Relaxed Jeans e Skinny Jean, enquanto os menos presentes são o Hybrid Regular Denim Joggers e Loose Jeans, como pode ser observado no gráfico abaixo:

<img src = "https://user-images.githubusercontent.com/94937578/178369536-5241f7cf-aa6a-4f2a-bac0-ae980da952a5.png" width="700px" />

Entre os tipos de calças jeans masculinas citadas acima, aquele que apresenta o maior preço médio é o Freefit® Slim Jeans (US$49,99) e o menor preço médio é o Slim Jeans	(US$20,39). No gráfico abaixo pode ser verificada a distribuição de preços por tipo do produto:

<img src = "https://user-images.githubusercontent.com/94937578/178384144-1fb4c367-3fa2-4e31-b907-0bff249f49d7.png" width="700px" />

Há 12 cores diferentes de calças jeans masculinas: Black, Black/trashed, Dark blue, Dark denim blue, Dark gray, Denim blue, Graphite gray, Gray, Light denim blue, Light denim blue/trashed, Pale denim blue e White. Entre os produtos ofertados no site da H&M, há maior número de calças da cor Light denim blue (25) e menos calças da cor Grey (1).

<img src = "https://user-images.githubusercontent.com/94937578/178385543-042776a1-0732-4652-908e-741940c75056.png" width="700px" />

As calças com maior preço médio são aquelas de cores Black/trashed, Graphite gray, Gray, Light denim blue/trashed	(US$39,99) e as de menor preço médio são as de cor Dark gray	(US$18,99), como pode ser observado no gráfico abaixo:

<img src = "https://user-images.githubusercontent.com/94937578/178385955-73176f6e-4a2b-4ffa-94b9-013cde1e67b8.png" width="700px" />

Em relação a matéria-prima, as calças jeans masculinas do conjunto de dados analisado são compostas majoritariamente por algodão, seguido por Poliéster. Abaixo são apresentados a composição média de todas as calças analisadas:
- Algodão: 78% 
- Poliéster: 22%
- Spandex: 1%
- Elasterell: 0% 

Logo, algodão e poliéster são as matérias-primas centrais para a produção das calças jeans masculinas pela nova empresa.

## 7. Produto final (dashboard):

## 8. Referências:

- [<b>Comunidade DS</b>](https://www.comunidadedatascience.com/)

