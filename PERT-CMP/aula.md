```ruby

###########################
# TEMPO INICIAL MAIS CEDO #
###########################

# ES = Maior tempo dos requeridos
# EFa = Tempo de termino
# Da = Duracao

# Evento A
ESa = 0
EFa = ESa + Da = 0+2 = 2

# Evento B
ESb = EFa = 2
EFb = ESb + Db = 2+4 = 6

# Evento C
ESc = EFb = 6
EFc = EFb + Dc = 6+10 = 16

# Evento D
ESd = EFc = 16
EFd = EFc + Dd = 16+6 = 22

# Evento E
ESe = EFc = 16
EFe = EFc + De = 16 + 4 = 20

# Evento I
ESi = EFc = 16
EFi = EFc + Di = 16+7 = 23

# Evento G
ESg = EFd = 22
EFg = EFd + Dg = 22 + 7 = 29

# Evento H
ESh = max EFg , EFe = max 29, 20 = 29
EFh = 29 + Dh = 29 + 4 = 33

# Evento F
ESf = max EFe = 20
EFf = 20 + Df = 20 + 5 = 25

# Evento J
ESj = max EFf , EFi = max 25, 23 = 25
EFj = 25 + Dj = 25+8 = 33

# Evento K
ESk = EFj = 33
EFk = 33 + 4 = 37

# Evento L
ESl = EFj = 33
EFl = 33 + 5 = 38

# Evento N
ESn = max EFk, EFl = max 37, 38 = 38
EFn = 38 + 6 = 44

# Evento M
ESm = EFh = 33
EFm = 33 + 2 = 35

# Evento FIM
ESfim = max 35, 44 = 44
EFfim = 44 + 0 = 44


####################
# FINAL MAIS TARDE #
####################

# LSk = O mais tarde que posso comecar a atividade k
# LFm = O mais tarde que posso terminar a atividade m

LFfim = EFfim + 44 = LSfim

# Evento M

LFm = LSfim = 44
LSm = 44 - 2 = 42

# Evento N

LFn = LSfim = 44
LSn = 44 - 6 = 38

# Evento K
LFk = LSn = 38
LSk = 38-4 = 34

# Evento L
LFl = 38
LSl = 38-5 = 33

# Evento J
LFj = min LSk, LSl = 33
LSj = 33 - 8 = 25

...

```
