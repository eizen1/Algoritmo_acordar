"# Algoritmo_acordar" 
algoritmo "acordar_e_sair_trabalho"

// Declaração de variáveis
inicio
   // Acordar
   escreva("Acordou? (sim/nao): ")
   leia(resposta)
   
   se resposta = "sim" então
      escreva("Levante-se da cama!\n")
      
      // Escovar os dentes
      escreva("Escovar os dentes (sim/nao): ")
      leia(resposta)
      se resposta = "sim" então
         escreva("Escovando os dentes...\n")
      senão
         escreva("Não escovou os dentes.\n")
      fimse

      // Tomar banho
      escreva("Tomou banho? (sim/nao): ")
      leia(resposta)
      se resposta = "sim" então
         escreva("Tomando banho...\n")
      senão
         escreva("Não tomou banho.\n")
      fimse
      
      // Se vestir
      escreva("Já se vestiu? (sim/nao): ")
      leia(resposta)
      se resposta = "sim" então
         escreva("Vestindo-se...\n")
      senão
         escreva("Não se vestiu ainda.\n")
      fimse
      
      // Tomar café da manhã
      escreva("Tomou café da manhã? (sim/nao): ")
      leia(resposta)
      se resposta = "sim" então
         escreva("Tomando café...\n")
      senão
         escreva("Não tomou café da manhã.\n")
      fimse

      // Preparar para sair
      escreva("Está pronto para sair de casa? (sim/nao): ")
      leia(resposta)
      se resposta = "sim" então
         escreva("Pegando chave, celular e bolsa...\n")
         escreva("Saiu para o trabalho!\n")
      senão
         escreva("Ainda não está pronto para sair.\n")
      fimse
   senão
      escreva("Você não acordou ainda.\n")
   fimse

finm
