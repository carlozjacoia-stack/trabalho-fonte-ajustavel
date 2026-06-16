# **Fonte de Tensão Ajustável**

Projeto que consistiu em desenvolver uma fonte de tensão ajustável de 3V a 12V, com uma corrente de 100mA. Realizado na disciplina SSC0180 - Eletrônica para Computação, aplicada pelo professor Eduardo do Valle Simões.

# Alunos
  * Carloz Eduardo Rosa Jacoia
  * Luana Sampaio de Oliveira
  * Rafael Tiosso Brancalhão

# Componentes

| Componente | Quantidade | Valor |
| -------- | ------- | ------- |
| Diodo Retificador 1N4007 LGE=1N4004 | 4 | R$ 0,80 |
| Capacitor 470uF X 50V | 1 |  R$ 5,50 |
| Resistor CR25 5K6 Carvão | 10 |  R$ 0,70 |
| Resistor CR25 3K3 Carvão | 10 |  R$ 0,70 |
| Transistor BC548B N 30V 0,1A 0,5W 300MHZ TO-92 FSC | 1 |  R$ 0,60 |
| Diodo Zener 13V  1W = 1N4743 SEMTECH | 1 |  R$ 0,50 |
| Total || R$8,80 |

## Cálculo dos Componentes

## Diodos
* São componentes semicondutores que atuam como "válvulas", permitindo que a corrente elétrica flua em apenas um sentido.
* Eles trabalham em conjunto com a ponte retificadora para direcionar o fluxo de elétrons, conduzindo ou bloqueando a passagem de acordo com a fase da corrente alternada.
* O termo "retificar" refere-se à ação de "alinhar" a forma de onda. Ou seja, a ponte retificadora converte a tensão alternada — que inverte de polaridade constantemente — em uma tensão contínua (CC), que flui em uma única direção.

## Diodo Zener
* Atua como um regulador e estabilizador de tensão.
* Diferente de um diodo comum, ele é projetado para conduzir corrente no sentido reverso assim que a tensão atinge o seu valor nominal — que, no caso deste projeto, é de 13V.
* Ele atua como uma trava de segurança. O diodo Zener "corta" os excessos e fixa o valor da tensão em 13V, garantindo que este seja o limite máximo na saída da fonte.

## Capacitador
* Funciona como um pequeno reservatório de energia. Ele armazena carga elétrica durante os momentos em que a tensão está subindo e a descarrega quando a tensão começa a cair.
* Após a ponte retificadora, a tensão ainda possui altos e baixos. O capacitor entra em ação fornecendo energia nos momentos de declínio, estabilizando a tensão contínua e suavizando a oscilação residual (fenômeno conhecido como ripple).

## Led
* É um semicondutor capaz de converter energia elétrica diretamente em energia luminosa.
* Atua como um sinalizador visual prático, indicando ao usuário que a fonte está ligada e que há corrente fluindo pelo sistema.
  
## Resistores
* Dispositivos eletrônicos que limitam a corrente elétrica em um circuito.

## Potenciômetro
* É, na prática, um resistor de resistência variável. Ele serve para controlar o sinal de tensão que será enviado ao transistor.
* Através de seu ajuste mecânico (girando o eixo), o usuário consegue regular a tensão de saída da fonte — variando, por exemplo, de 3V a 12V — para se adequar exatamente à necessidade do aparelho que será alimentado.

## Transistor
* Atua no controle e na amplificação da corrente que será entregue ao dispositivo conectado.
* Ele permite que uma corrente muito maior seja fornecida à saída da fonte sem exigir muito do diodo Zener. A corrente principal passa pelo transistor, enquanto o Zener e seu resistor lidam apenas com uma corrente bem menor, usada apenas para controlar o transistor.

# Imagens do projeto

# Circuito no [Falstad](https://tinyurl.com/27lq3p9g)
![imagem do circuito no falstad](https://github.com/carlozjacoia-stack/trabalho-fonte-ajustavel/blob/main/falstad.png)

# Foto do circuito
![foto protoboard](https://github.com/carlozjacoia-stack/trabalho-fonte-ajustavel/blob/main/img1.jpeg)

# Esquemático no [EasyEDA](https://oshwlab.com/carloz.jacoia/project_pjhicrbv)
![imagem do circuito no easyeda](https://github.com/carlozjacoia-stack/trabalho-fonte-ajustavel/blob/main/easyEDA.png)

# PCB no [EasyEDA](https://oshwlab.com/carloz.jacoia/project_pjhicrbv)
![pcb no easyeda](https://github.com/carlozjacoia-stack/trabalho-fonte-ajustavel/blob/main/pcbEasyEDA.png)

# Vídeo explicativo sobre o projeto

