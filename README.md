# Sistema de Gerenciamento de Vendas

Este sistema foi desenvolvido para gerenciar vendas e calcular o total de vendas realizadas. Ele é capaz de armazenar as vendas em um relatório e calcular o valor total com base na quantidade de produtos vendidos e seus respectivos preços.

## Estrutura do Código

O programa é composto por duas classes principais: `Venda` e `Relatorio`, além de uma função principal (`main`) que executa a lógica do programa.

### Classe `Venda`
A classe `Venda` é responsável por representar uma venda individual, armazenando informações sobre o produto, quantidade e valor unitário. Cada instância da classe contém:
- `produto`: O nome do produto vendido.
- `quantidade`: A quantidade de unidades vendidas.
- `valor`: O valor unitário do produto.

Exemplo de criação de uma instância de `Venda`:
```python
venda = Venda("Notebook", 3, 1500.00)
