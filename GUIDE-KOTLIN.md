# Guia Básico de Kotlin           



## Prints

    println(Int.MAX_VALUE)    # 2147483647
    println(Double.MAX_VALUE) # 1.7976931348623157E308
    println(Float.MAX_VALUE)  # 3.4028235E38
    println(Byte.MAX_VALUE)   # 127



## Conversão de Tipos

    toByte()
    toShort()
    toInt()
    toLong()
    toFloat()
    toDouble()
    toChar()



## Declaração de Variáveis 

    var            # Valor mutável
    val            # valor imutável
    const Val      # valor imutável
    var valor:Int? # pode ser tanto cheio quanto vazio"null"



## Operador ´in´ e ´range´

    in   # verifica se o valor etsa nalista ou uma faixa (range)
    
    12 in  lista
    12 !in lista
    
    range # cria um intervalo de valores Inicio..Fim
       
    12 in 0..20



## Criando funções

    private fun nome_funcao( parametro1:Int, parametro2:String):String{
    		return "exemplo"
     }



## Funções de ordem superior

    val x = funcao (12,4::sum)
    
    val y = funcao (12,4){a, b -> a*b}



## Funções single-line

    fun nomeDaFuncao (nome:Tipo) = retorno



## Funções / extensões

    fun tipo.nomeDaFuncao();



## Estruturas de Fluxo de Controle ( if/else, when, elvis operator )

     when{
        condicao1 ->{}
        condicao2 ->{}
        else  ->{}
    }




## Estruturas de de repetição

     while(condicao){ }


     do{ }(condicao)


    for(i in 0..20 step 2){
      print(i)
    }



## ARRAYS

    var number = IntArray(2)
    var letras = Array(3){""}



### Mostrando Valores dentro de um ARRAY

     fun main(args: Array<String>) {
    
          var vector = IntArray(2)
    
          vector[0] = 18
          vector[1] = 20
    
          for(i in 0 until vector.size){
             print("${vector[i]} ")
          }
    
     }



## Kotlin Orientada a Objeto






​    







​    







