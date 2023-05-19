# Projeto: LIGAR E DESLIGAR LED UTILIZANDO LDR

Este é um projeto simples desenvolvido no Tinkercad que utiliza um sensor de luminosidade (LDR) para controlar o acendimento e apagamento de um LED. O objetivo é criar um sistema que ligue o LED quando a luminosidade ambiente estiver abaixo de um certo limite e desligue o LED quando a luminosidade estiver acima desse limite.

## Componentes Utilizados

- Arduino Uno
- Sensor de luminosidade (LDR)
- Resistor de 10kΩ
- LED
- Jumpers

## Como Funciona

O sensor de luminosidade (LDR) é conectado ao Arduino, e o LED é conectado a um dos pinos digitais do Arduino. O resistor de 10kΩ é utilizado para formar um divisor de tensão com o LDR.

Quando a luminosidade ambiente está baixa, o LDR apresenta uma resistência alta, fazendo com que a tensão no pino analógico do Arduino seja baixa. Isso é interpretado pelo Arduino como um sinal de que o LED deve ser ligado. Quando a luminosidade ambiente está alta, o LDR apresenta uma resistência baixa, resultando em uma tensão alta no pino analógico do Arduino, e o LED é desligado.

## Circuito

![Circuito](https://github.com/avvnessa/Implementacao_sist_embarcados/assets/96122153/5c250e26-9d12-4db4-8f18-bddb93cfb633)

## Créditos

O projeto foi desenvolvido por [Carol Correia Vianaa.](https://www.tinkercad.com/things/8MpyXxHkNPL-ligar-e-desligar-um-led-utilizando-sensor-ldr)

