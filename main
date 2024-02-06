def print_hi(name):
    # Use a breakpoint in the code line below to debug your script.
    print(f'Vamos jogar {name}')  # Press Ctrl+F8 to toggle the breakpoint.

# Press the green button in the gutter to run the script.
if __name__ == '__main__':
    print_hi('Pedra, Papel e Tesoura!')
    escolha = input('Escolha a sua opção:\n1 para Pedra\n2 para Papel\n3 para Tesoura\n')
    inimigo = random.randint(1,3)

    if int(escolha) == inimigo:
        print('Empate!')

    if int(escolha) == 1 and inimigo == 2:
        print('Você perdeu!\nPapel embrulha a Pedra')

    if int(escolha) == 1 and inimigo == 3:
        print('Você ganhou!\nPedra quebra a Tesoura')

    if int(escolha) == 2 and inimigo == 1:
        print('Você ganhou!\nPapel embrulha a Pedra')

    if int(escolha) == 2 and inimigo == 3:
        print('Você perdeu!\nTesoura corta o Papel')

    if int(escolha) == 3 and inimigo == 1:
        print('Você ganhou!\nPedra quebra a Tesoura')

    if int(escolha) == 3 and inimigo == 2:
        print('Você perdeu!')
