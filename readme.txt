Este projeto tem como objetivo organizar gastos de um cartão de credito que é usado por duas ou mais pessoas.

O app começa pedindo o seu nome para poder organizar suas compras que estão armazenadas em arquivos CSV
Caso seja o primeiro acesso, ele cria o CSV automaticamente
Depois de colocar o nome, o usuario terá acesso a 4 opções:

1- Adicionar item
	Esta opção serve para adicionar uma nova compra.
	Ao acessar, será pedido o nome do item que foi comprado, o valor total da compra, quantidade de parcelas, o mes e ano que foi comprado (O mes e ano atual não são obitidos automaticamente para que haja opção de compras passadas serem adicionadas).
	Por fim, para cada opção escolhida (1, 2, 3 ou 4) uma mensagem aparecerá perguntando se quer continuar a usar ou não (responda com S ou N).
2- Ver lista de itens desse mês
	Essa opção mostra todos os itens a serem pagos, seus respectivos valores do mes atual e o total a ser pago (Objetos que ja tiverem sido totalmente pagos não aparecerão).  
3- Ver total
	Mostra apenas o total a ser pago.
4- Excluir tudo
	Exclui todo o CSV.

O programa possui 2 arquivos “.py”, main.py, arquivo principal onde tem a interface do usuário e pessoa.py onde estão as funções do programa e uma pasta chamada “dados” onde fica armazenado os arquivos CSV. 