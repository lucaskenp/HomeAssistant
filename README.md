# HomeAssistant
### Projeto

O projeto consiste em uma simulação de um assistente de casa com:

Sensores periódicos que enviam seus dados para o servidor usando a tecnologia publisher/subscriber, implementada utilizando RabbitMQ

Atuadores que se comunicam com o server utlizando chamadas de procedimento remoto que foram implementadas utilizando GRPC e protocol Buffer

O cliente foi simulado como um site feito em html, site esse que recebe informações dos sensores e envia comando para os atuadores.


## Diagrama de Blocos
![diagrama_sis_dis](https://user-images.githubusercontent.com/52925699/151473433-26e75a38-5201-4ed4-afe2-d6f9b33585ba.jpg)
