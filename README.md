# Tratamento dataset

## Tratamento de dataframe no python com pyspark

1. Transformar os campos "Premiere" e "dt_inclusao" de string para datetime.
2. Ordenar os dados por ativos e gênero de forma decrescente, 0 = inativo e 1 = ativo, todos
com número 1 devem aparecer primeiro.
3. Remover linhas duplicadas e trocar o resultado das linhas que tiverem a coluna "Seasons"
de "TBA" para "a ser anunciado".
4. Criar uma coluna nova chamada "Data de Alteração" e dentro dela um timestamp.
5. Trocar os nomes das colunas de inglês para português, exemplo: "Title" para "Título"
(com acentuação).
6. Testar e verificar se existe algum erro de processamento do spark e identificar onde
pode ter ocorrido o erro.
7. Criar apenas 1 .csv com as seguintes colunas que foram nomeadas anteriormente "Title,
Genre, Seasons, Premiere, Language, Active, Status, dt_inclusao, Data de Alteração" as
colunas devem estar em português com header e separadas por ";".
8. Inserir esse .csv dentro de um bucket do AWS s3
9. Subir o código no github com o nome TESTEPYSPARK-Confitec

# Cálculo de Matriz

Crie um algoritmo de multiplicação de matriz quadrada. O resultado do programa deverá
apresentar os valores da Matriz A, Matriz B e o Produto.
