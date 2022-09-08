Faça uma aplicação em Vue para o cálculo do grau de anjo e de não anjo de uma pessoa tendo como base sua data de nascimento. 
Para tanto, implemente uma funcão anjeza( ) que recebe como parâmetro uma data de nascimento (dia, mês e ano) e calcula a porcentagem de anjo e não anjo 
de uma pessoa que nasceu na data informada.

Os cálculos devem seguir a seguinte fórmula: 

nao_anjeza = somatorio(mes) + (ano/100) * (50-dia)
anjeza     = 100 - nao_anjeza

Sua funcão deve retornar a % de anjo e não anjo da pessoa nascida naquela data.

A funcão somatório deve receber um número inteiro n e retornar a soma de todos os números anteriores. Exemplo: se a entrada for 5, então então essa funcão deverá retornar 5+4+3+2+1 = 15
