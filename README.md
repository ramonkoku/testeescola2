print("Olá, somos o restaurante Mama Mia")

Opção = '1. BurgerBlend de 2 carnes'
Opção1 = '2. Sorvete de ninho com abacaxi'
Opção2 = '3. Patel carne bovina com caldo de cana'
Opção3 = '4. Prime Rib grelhado'
Opção4 = '5. Smash burger'
Opção5 = '6. Petit Gateau'
Opção6 = '7. Pasta con pesto e mozzarella di bufala'
Opção7 = '8. Pizza de Costela e mussarela de bufala'
Opção8 = '9. Sorvete de pistache'
Opção9 = '10. Lasanha à bolonhesa'
Opção10 = '11. Risoto de camarão'
Opção11 = '12. Salmão grelhado com molho de maracujá'

teste1 = "1. Xereta"
teste2 = "2. Coca cola"
teste3 = "3. Urina dos ursos da malásia"
teste4 = "4. Água tônica"
teste5 = "5. Suco de laranja"

sobremesa1 = "1. Tiramisu"
sobremesa2 = "2. Mousse de chocolate"
sobremesa3 = "3. Pudim de leite"
sobremesa4 = "4. Cheesecake de morango"

aperitivo1 = "1. Bruschetta"
aperitivo2 = "2. Bolinhos de bacalhau"
aperitivo3 = "3. Camarão empanado"
aperitivo4 = "4. Batata frita"

while True:
    Restaurante = input(f'O que gostaria de pedir? \n{Opção} \n{Opção1} \n{Opção2} \n{Opção3} \n{Opção4} \n{Opção5} \n{Opção6} \n{Opção7} \n{Opção8} \n{Opção9} \n{Opção10} \n{Opção11}\n')
    if Restaurante in ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10', '11', '0']:
        break
    else:
        print("Por favor, escolha uma opção válida ou digite 0 para continuar.")

while True:
    teste = input(f"Bom, gostaria de bebida para acompanhar? \nTemos as opções abaixo\n{teste1} \n{teste2} \n{teste3} \n{teste4} \n{teste5}\nDigite 0 se não deseja bebida.\n")
    if teste in ['1', '2', '3', '4', '5', '0']:
        break
    else:
        print("Por favor, escolha uma opção válida.")

while True:
    sobremesa = input(f"Que tal uma sobremesa? Aqui estão algumas opções:\n{sobremesa1} \n{sobremesa2} \n{sobremesa3} \n{sobremesa4}\nDigite 0 se não deseja sobremesa.\n")
    if sobremesa in ['1', '2', '3', '4', '0']:
        break
    else:
        print("Por favor, escolha uma opção válida.")

while True:
    aperitivo = input(f"Gostaria de começar com um aperitivo? Temos estas opções:\n{aperitivo1} \n{aperitivo2} \n{aperitivo3} \n{aperitivo4}\nDigite 0 se não deseja aperitivo.\n")
    if aperitivo in ['1', '2', '3', '4', '0']:
        break
    else:
        print("Por favor, escolha uma opção válida.")

print("Você selecionou como alimento: ", end='')

if Restaurante == '1':
    print('BurgerBlend de 2 carnes')
elif Restaurante == '2':
    print('Sorvete de ninho com abacaxi')
elif Restaurante == '3':
    print('Patel carne bovina com caldo de cana')
elif Restaurante == '4':
    print('Prime Rib grelhado')
elif Restaurante == '5':
    print('Smash burger')
elif Restaurante == '6':
    print('Petit Gateau')
elif Restaurante == '7':
    print('Pasta con pesto e mozzarella di bufala')
elif Restaurante == '8':
    print('Pizza de Costela e mussarela de bufala')
elif Restaurante == '9':
    print('Sorvete de pistache')
elif Restaurante == '10':
    print('Lasanha à bolonhesa')
elif Restaurante == '11':
    print('Risoto de camarão')
elif Restaurante == '12':
    print('Salmão grelhado com molho de maracujá')

if teste != '0':
    print("Você selecionou como bebida: ", end='')
    if teste == '1':
        print('Xereta')
    elif teste == '2':
        print('Coca cola')
    elif teste == '3':
        print('Urina dos ursos da malásia')
    elif teste == '4':
        print('Água tônica')
    elif teste == '5':
        print('Suco de laranja')
else:
    print("Você não selecionou bebida.")

if sobremesa != '0':
    print("Você selecionou como sobremesa: ", end='')
    if sobremesa == '1':
        print('Tiramisu')
    elif sobremesa == '2':
        print('Mousse de chocolate')
    elif sobremesa == '3':
        print('Pudim de leite')
    elif sobremesa == '4':
        print('Cheesecake de morango')
else:
    print("Você não selecionou sobremesa.")

if aperitivo != '0':
    print("Você selecionou como aperitivo: ", end='')
    if aperitivo == '1':
        print('Bruschetta')
    elif aperitivo == '2':
        print('Bolinhos de bacalhau')
    elif aperitivo == '3':
        print('Camarão empanado')
    elif aperitivo == '4':
        print('Batata frita')
else:
    print("Você não selecionou aperitivo")
