def calculadora(numero1, numero2, operacao):
    if operacao == 1:
        return numero1 + numero2
    elif operacao == 2:
        return numero1 - numero2
    elif operacao == 3:
        return numero1 * numero2
    elif operacao == 4:
        if numero2 != 0:  
            return numero1 / numero2
        else:
            return 0
    else:
        return 0
