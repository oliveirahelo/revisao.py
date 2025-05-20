nome = input("escreva seu nome: ")
idade = int(input("escreva sua idade"))
if idade>= 18: 
    print("acesso liberado")
else:
    print("acesso nao liberado")    

humor
nome = input("escreva seu nome: ")
nivel = float(input("escreva o nivel de energia"))
if nivel <= 19: 
    print("exalsto")
elif nivel >= 20 and nivel <= 39:
    print("cansado")
elif nivel>= 40 and nivel <= 59:
    print("neutro")    
elif nivel>= 60 and nivel <=79:
    print("animado")
elif nivel>=80 and nivel <= 100:
    print("euforico")  
else:
    print("energia invalida")


    notas
    nome = input("escreva seu nome: ")
nota_final  = float(input("escreva sua nota "))
if nota_final >= 9.0 and nota_final<= 10.0:
    print("exelente")
elif nota_final >= 7.0 and nota_final<= 8.9:
    print("bom")
elif nota_final>= 5.0 and nota_final <=6.9:
    print("regula")    
elif nota_final>= 3.0 and nota_final <=4.9:
    print("ruim")
elif nota_final>= 0.0 and nota_final <= 2.9:
    print("critico")  
else:
    print("nota invalida")
