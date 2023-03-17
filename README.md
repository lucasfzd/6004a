# 6004a
kkkkkkkkkkkkkkkkkkk


fun main() {
 println("ola mundo")
    println("argentino_ hablas espanol")
    println("br_ entao tu e campeao del mundo?")
    println("argentino_si si!! messi mejor que pele!!")
    println("br_ pele e uma lenda! jogador caro")
    println("argentino_ pero messi fue 7 veces mejor del mundo, talvez este ano lleve la octava!!")
    println("br_ pele foi o melhor do mundo e ganho 3 copas seguidas seu bostas!!")
    println("argentino_ eres mejor que nosotros lo siento brasil mejor del mundo)
}
///////////////////////////////////////////////////////////////////

 
fun main() {
    //exercicio 2 - faca uma propaganda que indique no console, se um numero
    //verificando e positivo ou negativo
    /*
    var minecraft = 0
    
    if(minecraft > 0){
        println("o $minecraft e um numero positivo")
    }else if(minecraft < 0){
        println("o $minecraft e um numero negativo")
    }else{
        println("0 $minecraft nao e nem positivo e nem negativo")
    }
    */
    
  
    //operadores  logicos 
    //
    //sao usados para comparar mais de um valor na mesma condicao
    //
    // && --> e (shift + 7) -->
    // \\ --> ou (shift + A barrinha invertida ao dele)(pipele)
    //
    //tabela verdade
    // e...  --> para que o resultado seja verdadeiro, todas as condicoes precisam ser
    // verdadeiras
    // 
    // vv - v
    // vf - f
    // fv - f
    // ff - f
    // ou...--> para que o resultado seja verdadeiro, pelo menos uma condicao deve ser
    // verdadeira
    // 
    // vv - v
    // vf - v
    // fv - v
    // ff - f
    // 
    // 
    // 
    // 
    /*
    var coracoes = 9
    var vidas = 0
    if(vidas <= 0 && coracoes <= 0){
    }else{
        println("-----o jogo sera reiniciado")
    }
     */
    // when - quado...
    // quando um derterminado valor for verdadeiro, uma derteminada acao
    // sera executada
    // 
    //
    // estrutura do when
    //
    // when(var a ser comparada){
    // valor -> {acao}
    // valor -> {acao}
    // valor -> {acao}
    // else -> {acao
    /*
    var mes = 12
    when(mes){
        1 -> {println("janeiro")}
        2 -> {println("feverreiro")}
        3 -> {println("marco")}
        4 -> {println("abril")}
        5 -> {println("maio")}
        6 -> {println("junho")}
        7 -> {println("julho")}
        8 -> {println("agosto")}
        9 -> {println("setembro")}
        10 -> {println("outubro")}
        11 -> {println("novenbro")}
        12 -> {println("dezembro")}
        else -> {println("mes invalido")}
    }
    */ 
    //lacos de repeticao
    //
    // while - enquanto
    // do..while - faca... enquanto
    // for - para 
    // repeat - repita 
    // 
    // while --> enquanto uma condicao verdadeira, uma derterminada 
    // acao e executada, ate que nao seja mais verdadeira
    // 
    var bolo = 500 
    
    while(bolo <= 520){
        println(bolo)
        bolo++ 
    } 
    
     
    //do.. while -> ele vai executar uma determinada acao 
    //enquando uma condicao for verdadeira
    println("")
    do{
        println(bolo)
        bolo++ 
    }while(bolo <= 520)
------------------------------------------------------------------------------------------------

fun main() {
/*
    var sorvete = 0
    var strogonoff = 0
    
    while(sorvete <= 10){
        println(sorvete)
        sorvete++
        
        
    }            
         do{
             println(strogonoff)
             strogonoff++ 
         }while(strogonoff > 10)
         */
         //exercicio 
         //
         //exiba a porcentagen da bateria descarrgando a cada linha do console
         //quando a bateria chega a 15%, deve ser exibida a porcentagem e tambem
         //o aviso da bateria descarregando,
         //quando a bateria chega a 0%, deve ser exibida a porcentagem e tambem
         //o aviso de celular desligando usando while ou do..while
         
         /*
          
         var bateria = 100 
         
         while(bateria >= 0){
           println("${bateria}%")                     
         
            when(bateria){
                15 -> {println("celular descarregando, faca algo!")} 
                0 -> {println("celular desligando, dando tchauzinho")}                 
            } 
            bateria--                       
         }  
         */
             
          // for - para... 
          /*
         for(churrasco in 0..10){
             println(churrasco)
         } 
         */
    
    
          // exercicio - exibir uma tabuada ate pelo menos o decimo multiplo de um
          // numero escolhido(que nao seja a do 0, do 1, e do 2(, utilizando
          // o laco for 
          
         
          for(tabuada in 0..10)
          println("${tabuada}x8 = ${tabuada*8}")
          
          
  }
             
