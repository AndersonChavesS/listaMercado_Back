# Sistema Lista de Mercado
## Requisitos
- Ser capaz de gerenciar várias listas de mercado (e marcar seu status como concluída ou não)
- Ser capaz de cadastrar produtos e consultá-los
- Ser capaz de incluir produtos nas listas e especificar suas quantidades, bem como marcar se o item já foi comprado ou não
- Ser capaz de atribuir valores aos itens comprados para depois ter uma gestão dos custos da lista
- Ser capaz de adicionar quantidades (kg, unidades, litros, etc)

## Casos de Uso - Produto
### Cadastrar Produtos
Informar palavras chaves para consultar ou mesmo buscar os produtos a partir de uma lista
### Alterar dados de produtos
Basicamente alterar o nome do produto e termos de efetivação no banco de dados

## Casos de Uso - Lista
### Criação de listas
Criar kuma nova lista, inserindo a data e o local onde foi feita a compra (nome do supermercado/feira, etc)
### Apagar uma lista
Remover uma lista que foi criada por engano e remover todos os seus itens que foram criados
### Inserção de itens na lista
Criar um item associando a uma lista e um produto, bem como deixar disponível a possibilidade de modificar quantidade e preço que foi pago
### Alteração de itens da lista
Alterar apenas quantidade, preço pago e status
### Remoção de itens da lista
Poder remover um item que foi cadastrado na lista
### Fechamento da lista
Concluir a lista como sendo completa e gerar seu custo total a partir dos itens comprados
