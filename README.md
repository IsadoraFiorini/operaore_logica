inteiro dia_semana
   inteiro hora
   logico loja_aberta

   dia_semana = 6 //sabado
   hora = 10

    loja_aberta = (dia_semana >= 1 e dia_semana <= 5 e hora >=9 e hora<=18 ) ou
    (dia_semana == 6 e hora>= 9 e hora < 13)

     se(loja_aberta){
      escreva ("A LOJA ESTÁ ABERTA")
     }
     senao{
      escreva("A LOJA ESTÁ FECHADA")
     }
