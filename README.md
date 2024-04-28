![Captura de tela 2024-04-28 172029](https://github.com/Amadaaiid/Receiving-Data-Basic-Python-/assets/112103916/d554d39e-6149-4356-9923-35908e497ca4)

# Receiving-Data-Basic-Python
This is a basic exercise about receiving data.

cpf: False = input('Digite seu CPF:')

if cpf is True:
    print('Seja bem vindo')
    exit()
else:
    print('Faça seu cadastro')

nome = input('Qual é o seu nome? ')
ano = int(input('Qual é o ano em que você nasceu? '))
idade = (2024 - ano)

if idade == 18:
    print(f'Bem vindo(a) {nome}, você tem {idade} anos, idade mínima para acessar site.')
elif idade > 18:
    print(f'Bem vindo(a) {nome}, você tem {idade} anos, idade permitida para acesso.')
else:
    print(f'Que pena {nome}, pessoas com a sua idade {idade} anos, não tem permissão para acessar esse conteúdo')
