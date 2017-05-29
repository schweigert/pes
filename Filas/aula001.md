Uma copiadora é usada pelas secret-arias de um escritório. Como o trabalho a ser copiado varia em tamanho (número de páginas do original) e quanto ao número de cópias, a taxa de atendimento é distribuída aleatoriamente, mas se aproxima de uma distribuição de Poisson, tendo em média de 10 trabalhos por hora. As necessidades de uso são aleatórias durante as 8horas de trabalho diário, mas chegam a uma taxa de 5 por dia.
Se o tempo de uma secretária custa $3.50 por hora, determine:

a) A utilização do equipamento.
b) O tempo médio do sistema.
c) O custo médio de espera e operação da máquina por dia.

```ruby

canal = copiadora
clientes = trabalhos
lambda = 5 t/h

turno = 8h

$ = 3,50R$ /h

a) p = 5/10 = 0.5 = 50%

b) w = 1/(u-lamb) = 1/5 = 0.2h

c) custo/dia

1/(cli/h - cli/h) h/cli


 tempo total : 8*5*0.2 = 8h / dia

 custo / dia = 8*3.5 = $28.00

```

Um caixa tem tempo médio de atendimento de 2 minutos, e os clinetes chegam a uma taxa de 20/hora:

```
a) qual a ociosidade do caixa

b) quanto tempo médio um cliente fica 

lambda = 20/h

u = 1/2 (1 cliente a cada 2 minutos) = 30 cli/h

p = lambda / u

P0 = 1 - p

P0 = 1 - 20/30 = 33.33%

wq = 20/(30(30-20)) = 0,066667h

l = 20 / (30-20)

```

Um caixa tem capacidade de atender em média 25 clientes por hora. Quantos clientes poderiam chegar por minuto para que o tempo total na fila e no atendimento não ultrapasse 4 minutos?

w = 1/(u - lamb)
0.0667 = 1 /(25-lamb) = 25 - lamb = 15
lamb = 10
