# Estação de Monitoramento de Temperatura
Atividade 2 - Sistemas Embarcados - UNIFESP SJC

Prof. Dr. Sérgio Barros e Prof. Dr. André Marcorin

## Implemente um programa para monitorar a temperatura e fornecer informações sobre sua variação no ambiente

● Os leds deverão ser usados para indicar a quantidade de vezes que os botões
(b1, b2 e b3) foram pressionados.

● Cada led deve ser acionado de forma suave usando o PWM.

● O desligamento dos leds deve ser feito de forma direta, ou seja, aplicando nível
lógico 0 para desligá-los.

● A soma da quantidade de pressionamento dos botões (b1, b2 e b3) deve ser
mostrado nos leds, usando a representação binária do valor da somatória. 

● Quando a contagem (b1+b2+b3) ultrapassar o valor decimal igual a 15, os leds
devem ser ligados por 1 segundo e desligar por 1 segundos, três vezes
consecutivas.

● Após os leds piscarem por três vezes, o contador deve ser zerado e os leds
devem retornar ao valor inicial (zero).

● O LM35 deve realizar a medição da temperatura a cada 1 segundo.

● Quando a temperatura medida for superior ao valor limite estabelecido pelo
usuário, o buzzer deve ser ligado por 0,5 segundos e desligado por 2 segundos,
3 vezes consecutivas.

● Sempre que a temperatura estiver abaixo do limite estabelecido, o buzzer deve
permanecer desligado.

● Quando o botão 1 for pressionado, deve ser mostrado no monitor serial o menor
valor de temperatura mensurado durante o monitoramento

● Quando o botão 2 for pressionado, deve ser mostrado no monitor serial o valor
médio de temperatura calculada a partir das últimas 30 medições realizadas
(lembrando que as medições devem ser feitas a cada 1 segundo).

● Quando a chave 3 for pressionada, deve ser mostrado no monitor serial a
temperatura máxima mensurada durante o monitoramento. 
