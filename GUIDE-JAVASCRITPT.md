# Guia Básico de Javascript

## Print´s

    console.log()     # Print no console
    
    document.write()  # escreve no HTML da página
    
    alert()           # Print em uma janela no navegador

## String´s

    replace("String  de origem", "String de destino")   # Atualiza uma string dentro de uma cadeia
    
    toUpperCase()                                       # Coloca tudo em caixa alta
    
    toLowerCase()                                       # Coloca todas as Strings em minúscula

## Array´s e Dicionário

### Lista

    var lista = ["Teste 1","teste 2","teste 3"]     # declarar lista
    
    lista.push("teste 4")                           # colocar um elemento na lista
    
    lista.pop()                                     # retirar o ultimo elemento da lista
    
    lista.length                                    # quantidade de elementos da lista
    
    lista.reverse()                                 #  Lista em ordem contrária
    
    lista.toString()                                # Converte para String
    
    lista.join(" - ")                               # Transforma em String e separa por "-" (Caracter de Preferência) 

### Dicionário

    var fruta = {nome: "maçã", cor: "vermelha"}       # Criando um discionário 
    
    fruta.cor                                         # Acessando o valor através da chave 
    
    var frutas = [ {nome: "maçã", cor: "vermelha"} ,  {nome: "maçã", cor: "vermelha"} ]  # Criando um discionário de listas 

### Matrizes

     var matriz = [ ]                                                                   # Declarando uma matriz comum
    
     var matriz =  [ [ " Banana", "Maçã "] , [" Pêra", "Abacate" ], ["Uva", Tamara ] ]  #  Declarando uma matriz  com elemtos dentro

### Inserindo valores dentro de uma matriz:

          ------------------------------------------------------------------------------------------------------------------------------  
    
     ​     0:  var vetor = []
    
    ​      1:  for (var linha = 0; linha < 3; linha++) {
    
    ​      2:     vetor[linha] = []
    
    ​      3:     for (var coluna = 0; coluna < 3; coluna++) {
    
    ​      4:          vetor[linha][coluna] = prompt("Informe o valor da " + linha + " linha e da " + coluna + " Coluna")
    
    ​      5:     }
    
    ​      6:  }
    
         ------------------------------------------------------------------------------------------------------------------------------

