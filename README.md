# Código exemplo do vídeo sobre comunicação serial do STM32 (UART - Polling):

**Descrição do programa:**<br>
Este programa tem como objetivo principal testar as funcionalidades da comunicação serial através da utilização da biblioteca HAL, fornecida pela STM32CubeIDE, conforme [este vídeo](https://www.youtube.com/watch?v=LThj7TSC9L0&list=PLjOLyDltrTdk7XqeOdhzxLlAY12-DiLUI&index=3).
Aqui podemos escrever e ler estados booleanos em saídas digitais (LEDs) e entradas digitais (*Push-Buttons*). A montagem do exemplo pode ser vista a seguir:
<br>
<br>
![montagem](https://user-images.githubusercontent.com/58537514/137427641-bb2005b6-3d56-4824-980e-1b089429ae68.png)
<br>
<br>
➡️🖥️ O microcontrolador STM32F103C8T6 (embarcado na placa *Bluepill*) **enviará**, através da sua UART:
- Valores das entradas PB4 e PB5 que são alterados de acordo com o estado das *Push-Buttons*;
- Valores armazenados nos registradores de saída (PA11, PA12, PA15 e PB3) a fim de monitorar o nível lógico das saídas;<br>

<br>

🖥️➡️ O microcontrolador STM32F103C8T6 (embarcado na placa *Bluepill*) **receberá**, através da sua UART:
- O valor do ID do LED em que se deseja inverter (*Toggle*) o valor lógico de sua saída, conforme tabela a seguir: 

| ID<br>do comando | LED <br>do comando
| :---:   | :-: |
| 1 | Azul  
| 2 | Verde 
| 3 | Amarelo 
| 4 | Vermelho 

<br>

A seguir, temos uma imagem do monitor serial, rodando o que foi descrito acima:
<br>
<br>
![monitor serial](https://user-images.githubusercontent.com/58537514/137431056-0890415b-4824-4c3b-9aab-ebc1550583bd.png) 
<br>

 &nbsp;<br> 
## Contact me:
💼[LinkedIn](https://br.linkedin.com/in/rafaeldelpino)&nbsp;&nbsp;&nbsp;
📹[Youtube](https://www.youtube.com/delpitec)&nbsp;&nbsp;&nbsp;
📸[Instagram](https://www.instagram.com/delpitec_/)&nbsp;&nbsp;&nbsp;
📧[E-mail](delpitec@gmail.com)&nbsp;&nbsp;&nbsp;

