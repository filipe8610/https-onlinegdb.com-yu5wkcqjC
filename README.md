# https-onlinegdb.com-yu5wkcqjC
'''calculadora 1.0. A calculadora basica versão 1.0 foi desenvolvida por filipe como 
uma forma de exercitar programação python, aprendida no curso em video
o código foi escrito usando como base a soma de doisi números e a partir daí foram adicionadas outras funcionalidade
O método usado para adicionar funcionalidades foi a pesquisa na internet
Aprendida nova função a mesma era adicionada ao código e testada logo em seguida para ver como e se funcionava'''
c = 0
i = 0
while i == 0:
    print('')
    aritmetica = int(input('Escolha a operação aritmética: \n1) + \n2) - \n3) / \n4) * \n-> '))
    if(aritmetica == 1):
        print('[+]soma')
        n1 = float(input('digite um número: \n '))
        n2 = float(input('+'))
        resultado = (n1+n2)
        print('_'*6)
        print(resultado)
        print('')
    
    elif(aritmetica == 2):
        print('[-]subtração')
        n1 = float(input('digite um número: \n '))
        n2 = float(input('-'))
        resultado = (n1-n2)
        print('_'*6)
        print(resultado)
        print('')
        
    elif(aritmetica == 3):
        print('[/]divisão')
        n1 = float(input('digite um número: \n '))
        n2 = float(input('/'))
        resultado = (n1/n2)
        print('_'*6)
        print(resultado)
        print('')
        
    elif(aritmetica == 4):
        print('[*]multiplicação')
        n1 = float(input('digite um número: \n '))
        n2 = float(input('x'))
        resultado = (n1*n2)
        print('_'*6)
        print(resultado)
        print('')
    else:
        print('')
        print('Não entendi muito bem.')
        print('')
    c = str(input('deseja continuar?\n1)SIM\n2)NAO\n-> '))
    if (c == '1'):
        i = 0 
    else:
        i = 1 
        print('')
        print('BYE')
            
