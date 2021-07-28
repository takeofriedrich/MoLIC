# MoLIC

    def leValor() -> int:
        try:
            x = int(input())
            return x
        except Exception:
            return 0

    soma = 0

    while True:

        print('Digite 0 para SAIR')
        print('Digite 1 para SOMAR')

        lido = input()

        if lido == '0':
            break

        elif lido == '1':
            print('Informe um inteiro:')
            soma = soma + leValor()
            print('Valor da soma atual = {}'.format(soma))

    print('Encerrando...')
