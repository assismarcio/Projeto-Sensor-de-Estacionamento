# Projeto-Sensor-de-Estacionamento

Atualmente com os avanços tecnológicos, o desenvolvimento de sensores está em crescimento constante. Será apresentado neste artigo o sensor ultrassônico para estacionamento de veículos. Este dispositivo sinaliza através de alertas sonoros e/ou sinais luminosos, a proximidade de obstáculos, facilitando ao condutor estacionar o veículo ou efetuar manobras com segurança.
Os materiais utilizados são uma placa Arduino, uma protobord, um sensor ultrassônico HC-SR04, quatro leds vermelhos, um buzzer, quatro resitores de 330 ohms, jumpers e um cabo usb.
Este sensor utiliza as propriedades de propagação do som para medir distâncias.
O sensor envia uma onda ultrassônica através do trigger que bate no objeto e retorna ao receptor que detecta a onda. De acordo com o tempo que essa onda viajou, podemos obter a distância. Com base nas informaçãoes obtidas pelo sensor definidas pela programação teremos a resposta nos atuadores, que nesse projeto será acender leds e um buzzer conectado irá emitir sinais sonoros.
De acordo com a definição do projeto os leds irão se acendendo gradativamente até atingir os 4 leds acesos e os buzzer irá emitir beeps em uma frequência maior e mais alto até o limite final. Com o distanciamento do objeto o inverso vai ocorrendo. Os leds vão se apagando e os beeps diminuindo até totalmente parar.
Isso é o que será demonstrado nesse projeto com um modelo prático.
