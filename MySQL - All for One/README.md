## Desafios Iniciais

Monte queries para encontrar as seguintes informações:

1. Exiba apenas os nomes do produtos na tabela `products`.
2. Exiba todas as colunas da tabela `products`.
3. Escreva uma query que mostre a coluna que representa a primary key da tabela `products`.
4. Conte quantos registros existem em `product_name` de `products`.
5. Monte uma query que exiba os registros da tabela `products`  a partir do registro 4 até o 13, não use `where` ou `order by`.
6. Mostre as colunas `product_name` e `ID` da tabela `products` de maneira que os resultados estejam em ordem alfabética dos nomes.
7. Mostre os 5 primeiros registros da coluna `id` da tabela `products`, quando esta está em ordem decrescente.
8. Faça uma consulta que retorne três colunas. Na primeira coluna, exiba a soma de `5 + 6` (essa soma deve ser realizada pelo SQL). Na segunda coluna deve haver a palavra "de". E por fim, na terceira coluna, exiba a soma de `2 + 8` (essa soma deve ser realizada pelo SQL). A primeira coluna deve se chamar "A", a segunda coluna deve se chamar "Trybe" e a terceira coluna deve se chamar "eh". Não use colunas pre-existentes, apenas o que for criado na hora.

---

## Desafios sobre filtragem de dados

9. Mostre todos os valores de `notes` da tabela `purchase_orders` que não são nulos.
10. Mostre todos os dados da tabela `purchase_orders` em ordem decrescente ordenados por `created_by` onde `created_by` é maior ou igual a 3.
11. Exiba os dados de `notes` da tabela `purchase_orders` e mostre apenas os dados de `notes` entre 30 a 39.
12. Mostre as datas (`submitted_date`) de `purchase_orders` onde `submitted_date` é do dia 14 do mês de janeiro do ano 2006.
13. Mostre o `supplier_id` das `purchase_orders` onde o `supplier_id` seja 1 ou 3.
14. Mostre os `supplier_id` da `purchase_orders` onde o `supplier_id` sejam 1 a 3.
15. Mostre somente as horas da `submitted_date` de todos registros de `purchase_orders`.
16. Exiba a `submitted_date` das `purchase_orders` que estão entre 2006-01-26 00:00:00 a 2006-03-27 23:59:59.
17. Mostre os registros da coluna `supplier_id` das `purchase_orders` em que os `supplier_id` sejam tanto 1 ou 6.
18. Mostre os registros de purchase_orders que tem o `supplier_id` igual a 3 e `status_id` igual a 2.
19. Quantos pedidos foram feitos na tabela `orders` pelo `employee_id` igual a 6 ou 5, e que foram enviados através do método `shipper_id` = 2 ?

---

## Desafios Manipulação de tabelas

20. Adicione ao `order_details` uma linha com os seguintes dados: `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129 (o Id deve ser incrementado automaticamente).
21. Adicione duas linhas ao `order_details` com os mesmos dados. Esses dados são novamente `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129 (o Id deve ser incrementado automaticamente).
22. Atualize os dados de `discount` do `order_details` para 15.
23. Atualize os dados de `discount` da tabela `order_details` para 30 cuja `unit_price` seja menor que 10.0000.
24. Atualize os dados de discount da tabela `order_details` para 45 cuja `unit_price` seja maior que 10.0000 e o id seja um número entre 30 a 40.
25. Delete todos os dados em que a `unit_price` seja menor que 10.0000.
26. Delete todos os dados em que a `unit_price` seja maior que 10.0000.
27. Delete todos os dados da tabela `order_details`.
