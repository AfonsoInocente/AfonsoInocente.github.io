# AfonsoInocente.github.io

. Desenvolver uma tela usando html/css/js em que o usuário tenha as seguintes interações:

-> Na primeira "fase" a tela apenas pede para o usuário o número de renavam (somente o input e o botão pra avançar)
-> Validar se é um número com 9 a 11 dígitos numéricos
-> Depois que o usuário digitar um número válido e clicar em avançar a tela deve esconder esse campo e botão,
e mostrar a lista de débitos.

-> Apenas para o teste, em vez de consultar uma API essa tela deve usar os próprios números digitados pelo 
usuário como se fossem os débitos, na seguinte regra:
	- Os primeiros três dígitos formam um débito chamado "Licenciamento"
	- Os últimos quatro dígitos formam um débito chamado "IPVA"
    
-> A tela deve mostrar a lista dos débitos, o valor total, e doze botões para parcelamento.
-> Cada botão representa uma opção de financiamento, indo de 1x até 12x
-> O parcelamento contém juros na seguinte progressão:
	- De 1 a 4 parcelas: 4% de juros por parcela
	- De 5 a 8 parcelas: 3,5% de juros por parcela
	- De 9 a 12 parcelas: 3% de juros por parcela
	Exemplo: Digamos que o valor total dos débitos fique em 2500,00. 
	O usuário poderá escolher entre 1x de 2600,00 ou 2x de 1350,00, ... ,  7x de 444,64, ... ,  ou 10x de 325,00 , ...

-> Depois que o usuário selecionar a opção de parcelamento a página apenas gera um alert informando que foram 
selecionadas X parcelas de Y reais e o valor total Z