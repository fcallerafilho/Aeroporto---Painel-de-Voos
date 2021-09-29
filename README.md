# Aeroporto  - Painel de Voos
Projeto Final da disciplina de ECOP04 - Programação Embarcada do 2º período de Engenharia Eletrônica da UNIFEI.
Esse projeto simula o painel de informações de voos de um aeroporto na placa PIC18F4520, usando suas seus botões, painel LCD, LEDs e display de 7 segmentos.
Com os botões, é possível alternar entre as informações do voo, como seu status, duração, destino e aeronave. Essas informações aparecerão no display LCD.
No Display de Sete Segmentos, há um timer, que simula o tempo de embarque do voo. Durante esse período, os LEDs piscam para alertar os passageiros sobre o embarque.
Quando ele chega em 0, o avião decola, e no Display de Sete Segmentos aparece a informação de que o voo decolou. Em seguida, ele fica por alguns momentos em StandBy e 
depois volta ao seu estado natural.
