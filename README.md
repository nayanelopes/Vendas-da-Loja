# Vendas-da-Loja
Exercício da aula sobre linguagens de programação
programa
{
	
	funcao inicio()
	{
		real vendadeabril,vendademaio,vendadejunho,vendadejulho,vendadeagosto,totaldevendas,totaldevendas2,totaldevendas3,vendasdaloja,mediadaloja
		cadeia vendedor1,vendedor2,vendedor3

		escreva("Qual seu nome?")
		leia (vendedor1)
		escreva ("Você é o vendedor 1!, de quanto foi sua venda de abril?")
		leia (vendadeabril)
		escreva ("De quanto foi sua venda de maio?")
		leia (vendademaio)
		escreva ("De quanto foi sua venda de junho?")
		leia (vendadejunho)
		escreva ("De quanto foi sua venda de julho?")
		leia (vendadejulho)
		escreva ("De quanto foi sua venda de agosto?")
		leia (vendadeagosto)

         totaldevendas = (vendadeabril+vendademaio+vendadejunho+vendadejulho+vendadeagosto)
          
		escreva("Qual seu nome?")
		leia (vendedor2)
		escreva ("Você é o vendedor 2!, de quanto foi sua venda de abril?")
		leia (vendadeabril)
		escreva ("De foi sua venda de maio?")
		leia (vendademaio)
		escreva ("De quanto foi sua venda de junho?")
		leia (vendadejunho)
		escreva ("De quanto foi sua venda de julho?")
		leia (vendadejulho)
		escreva ("De quanto foi sua venda de agosto?")
		leia (vendadeagosto)
 totaldevendas2 = (vendadeabril+vendademaio+vendadejunho+vendadejulho+vendadeagosto)
 

		escreva("Qual seu nome?")
		leia (vendedor3)
		escreva ("Você é o vendedor 3!, de quanto foi sua venda de abril?")
		leia (vendadeabril)
		escreva ("De quanto foi sua venda de maio?")
		leia (vendademaio)
		escreva ("De quanto foi sua venda de junho?")
		leia (vendadejunho)
		escreva ("De quanto foi sua venda de julho?")
		leia (vendadejulho)
		escreva ("De quanto foi sua venda de agosto?")
		leia (vendadeagosto)
totaldevendas3 = (vendadeabril+vendademaio+vendadejunho+vendadejulho+vendadeagosto)

vendasdaloja = (totaldevendas+totaldevendas2+totaldevendas3)

mediadaloja = vendasdaloja/4

      escreva ("o total de vendas desse mês foi:" + vendasdaloja ) 

      
      escreva ("Nossa média mensal foi de:" + mediadaloja ) 

      

     
	}
}
