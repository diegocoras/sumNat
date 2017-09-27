# sumNat
aprox=function(x,n)
{
valor=x
for(i in 1:n) 
valor= valor+(-1)^i*(x^(2*i+1))/(2*i+1)
valor}
options(digits=10)
