# Natural Language Processing
Repositório para minhas atividades de Processamento de Linguagem Natural
![Header](https://github.com/Farllon/Natural-Language-Processing/blob/master/header.jpg)

# Exercício do restaurante

### Problema
Neste problema, você é um consultor do restaurante italiano da DelFalco. O proprietário pediu que você identificasse se há algum alimento no menu que os clientes consideram decepcionante.

### Dados
O proprietário da empresa sugeriu que você use as avaliações de restaurantes no site do Yelp para determinar quais pratos as pessoas gostaram e não gostaram. Você puxou os dados do Yelp. O proprietário também forneceu a você uma lista de itens de menu e grafias alternativas comuns.

### Objetivo
Dados os dados do Yelp e a lista de itens de menu, você tem alguma idéia de como encontrar quais itens de menu decepcionaram os clientes?

### Solução
Você pode agrupar revisões pelos itens de menu mencionados e, em seguida, calcular a classificação média das revisões que mencionaram cada item. Você pode dizer quais alimentos são mencionados nas avaliações com pontuações baixas, para que o restaurante possa fixar a receita ou remover esses alimentos do menu.

### Saída do programa
#### Worst rated menu items:
|Item|Ave rating|Count|
| --- | --- | --- |
|chicken cutlet|3.55|11|
|turkey sandwich|3.80|5|
|spaghetti|3.85|41|
|italian combo|3.91|22|
|eggplant|3.97|95|
|italian beef|4.00|29|
|tuna salad|4.00|5|
|garlic bread|4.02|46|
|meatball|4.08|163|
|portobello|4.11|18|


#### Best rated menu items:
|Item|Ave rating|Count|
| --- | --- | --- |
|prosciutto|4.62|63|
|purista|4.64|67|
|chicken salad|4.67|6|
|pastrami|4.69|16|
|reuben|4.80|5|
|steak and cheese|4.89|9|
|artichoke salad|5.00|5|
|fettuccini alfredo|5.00|6|
|turkey breast|5.00|1|
|corned beef|5.00|2|
