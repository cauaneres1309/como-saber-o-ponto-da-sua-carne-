# como-saber-o-ponto-da-sua-carne-tem_cel= int(input('qual a temperatura da carne '))
if tem_cel<42:
    print('cozinhar por mais alguns minutos')
elif tem_cel in range(48,53):
    print('selada')
elif tem_cel in range(54,60):
    print('frio')
elif tem_cel in range(61,65):
    print('ao ponto')
elif tem_cel in range(66,70):
    print('quente')
elif tem_cel>=71:
    print('muito quente')
