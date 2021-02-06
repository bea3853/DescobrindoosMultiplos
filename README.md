# DescobrindoosMultiplos
Em Portugol, descubra os múltiplos de 3.

algoritmo "DescobrindoosimpareseMultiplos"
var
i,n,totImp,s:inteiro
inicio
 totImp:=0
 
 para i de 1 ate 4  passo 1 faca

 escreval("Digite um nº:")
 leia(n)
  se (n mod 2 <> 0) ou (n mod 3 = 0)entao
 totImp:= totImp+1
 s:=s+n
 fimse

 fimpara
 
 escreval("O total de impares: ", totimp)
 escreval("Multiplo de 3:", s )
 
 
fimalgoritmo
