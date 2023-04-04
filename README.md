# media-alunos-com-vetor
media dos alunos com vetor
Algoritmo "semnome"
//
//
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 03/04/2023
const
   qtd_alunos = 3
   
Var
   // Seção de Declarações das variáveis

   x : inteiro
   alunos: vetor [ 1..qtd_alunos] de caractere
   media, nota1, nota2, nota3, nota4: vetor [1..qtd_alunos] de real



Inicio

   para x de 1 ate qtd_alunos faca
      escreval("Digite o nome do aluno: ")
      leia(alunos[x])


      Escreval("Digite a primeira nota: ")
      leia(nota1[x])

      Escreval("Digite a primeira nota: ")
      leia(nota2[x])

      Escreval("Digite a primeira nota: ")
      leia(nota3[x])

      Escreval("Digite a primeira nota: ")
      leia(nota4[x])
      media[x] <- (nota1[x]+nota2[x]+nota3[x]+nota4[x])/4
      
   fimpara

   para x de 1 ate qtd_alunos faca
   Escreval(Alunos [x] )
   Escreval(" Media : ", media[x])
   




   fimpara

Fimalgoritmo
