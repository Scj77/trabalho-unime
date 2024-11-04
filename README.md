
TRABALHO LOGICA E MATEMATICA 

PROFESSORA: Maiara Sacramento

PRIMEIRO SEMESTRE

PROJETO

Desenvolver uma aplicação prática que simule a lógica do cálculo de uma fatura de cartão de crédito com juros. O projeto visa a compreensão e prática de conceitos.
Nesse projeto foi sugerido três métodos SouDev, SouData e SouSolver. Onde escolhi usar DEV "front - end".

O projeto visa a compreensão e prática de conceitos como:

Código de Compras com Loop e Validação

- Pergunta valores de compras até que usuário diga "s" (sim)
- Valida resposta para garantir "s" ou "n"
- Calcula fatura total
- Pergunta dia de pagamento
- Calcula juros, se aplicável
- Imprime resultado

Características:

- Loop para múltiplas compras
- Validação de resposta
- Cálculo de fatura e juros
- Impressão de resultado

Objetivo:

- Simular um sistema de compras simples
- Demonstrar uso de loop e validação em Python

Aqui estão algumas características que identificam o código como Python:

1. Sintaxe simples e legível.
2. Uso de indentação para definir blocos de código.
3. Uso de variáveis dinâmicas (sem declaração explícita de tipo).
4. Uso de funções integradas (como input(), print(), format()).
5. Uso de operadores lógicos e aritméticos.

Além disso, o código utiliza recursos específicos do Python, como:

1. Loop while.
2. Condicionais if/else.
3. Função input() para leitura de dados do usuário.
4. Função print() para impressão de saída.
5. Formatação de strings com o método format().

Vamos demonstrar o funcionamento do código:

Início do Programa
Digite o valor da compra: R$ 100
Usuário digita o valor da compra.

Passo 2: Pergunta se é a última compra
É a última compra? (s/n): n
Usuário responde que não é a última compra.

Passo 3: Novo valor de compra
Digite o valor da compra: R$ 50
Usuário digita outro valor de compra.

Passo 4: Pergunta se é a última compra (novamente)
É a última compra? (s/n): s
Usuário responde que sim, é a última compra.

Passo 5: Pergunta o dia de pagamento
Digite o dia do pagamento (1-31): 28
Usuário digita o dia de pagamento.

Passo 6: Resultado

Fatura total: R$ 150.00
Dia de pagamento: 24
Não há juros.
Total a pagar: R$ 150.00

O programa calcula a fatura total, dia de pagamento e não aplica juros, pois o pagamento foi feito antes do dia 25.

Caso 2: Pagamento após o dia 25

Passo 1: Início do Programa

Digite o valor da compra: R$ 100
Usuário digita o valor da compra.

Passo 2: Pergunta se é a última compra
É a última compra? (s/n): s
Usuário responde que sim, é a última compra.

Passo 3: Pergunta o dia de pagamento
Digite o dia do pagamento (1-31): 30

Usuário digita o dia de pagamento.

Passo 4: Resultado

Fatura total: R$ 100.00
Dia de pagamento: 30
Juros: R$ 5.00
Total a pagar: R$ 105.00


O programa calcula a fatura total, dia de pagamento e aplica juros, pois o pagamento foi feito após o dia 25.

OBS: Caso seja digitado algo não referente ao proposto o sistema fara mesma pergunta ate obter resposta correta por isso foi empregado o "LOOP"



 FIM
