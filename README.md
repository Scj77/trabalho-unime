loop = True
fatura = 0
dia_pagamento = 0
juros_diario = 0.05  
juros_mensal = 0.19  
taxa_adicional = 15

while loop:
    valor_compra = float(input("Digite o valor da compra: R$ "))
    fatura += valor_compra
    
    resposta = input("É a última compra? (s/n): ")
    
    while resposta.lower() not in ["s", "n"]:
        print("Resposta inválida. Por favor, digite s ou n.")
        resposta = input("É a última compra? (s/n): ")
    
    if resposta.lower() == 's':
        loop = False

# Perguntando sobre o dia de pagamento
dia_pagamento = int(input("Digite o dia do pagamento (1-31): "))

# Calculando juros
if dia_pagamento <= 25:
    juros = 0
else:
    juros = (fatura * juros_mensal) + (taxa_adicional * (dia_pagamento - 25))
    juros_diario = fatura * juros_diario * (dia_pagamento - 25)

# Imprimindo resultado
print("Fatura total: R$ {:.2f}".format(fatura))
print("Dia de pagamento: {}".format(dia_pagamento))

if dia_pagamento > 25:
    print("Juros: R$ {:.2f}".format(juros))
    print("Total a pagar: R$ {:.2f}".format(fatura + juros))
else:
    print("Não há juros.")
    print("Total a pagar: R$ {:.2f}".format(fatura))
