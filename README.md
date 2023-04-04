O projeto parte do princípio de que a luminosidade, temperatura e umidade influenciam diretamente na qualidade dos vinhos que estão armazenados, com base nisso montamos um esquema para evitar que a qualidade dos vinhos caiam... e nessa primeira etapa, com o fator de luminosidade sendo o principal, conta com uma demonstração de três LEDs, cada um com sua função, sendo um verde que indica se a luminosidade do ambiente estiver OK, um amarelo que indica um estado de alerta que faz com que com uma buzina soe por 3 segundos (caso permaneça em estado de alerta volta a soar por 3 segundos), e um vermelho indicando algum problema; conta também com um LDR, este que varia sua resistência coforme o indice de luz incide sobre ele; um arduino que faz a captura de luminosidade dom ambiente; um software para usar o código.
Como reproduzi-lo: 

-Usam-se três resistores de 220 ohms, nos polos negativos dos LEDs, todos numa placa de ensaio pequena; 

-o LDR tem um resistor de 10 kohms e um fio que vai para a saída A0 na mesma coluna, outro fio que o liga para a saída positiva da placa;

-um fio positivo que vai para saída 5V e um negativo para a GND no arduino;

-um piezo, onde na mesma coluna do lado positivo tem um fio que vai para a saída positiva da placa, e na mesma coluna do lado negativo tem um fio que vai para a entrada 8 no arduino;

-os fios dos LEDs verde, amarelo e vermelho vão, respectivamente, para a entrada 2, -3 e 4 no arduino.

Os usuários que tiverem dúvidas sobre o projeto entrem no link: 

Autores do projeto: Gabriel Augusto Maciel Toledo, RM551654, Nick no GitHub: GabrielToledoo;

Henrique Parra Benitez, RM551973, Nick no GitHub: rickparra; 

Luan Nijou, RM98920, Nick no GitHub: Luan-Nijou;

Roberto Oliveira Azzalin Navas, RM551460, Nick no GitHub: Robertooan07;

Tony Willian da Silva Segalin, RM550667, Nick no GitHub: TonyWillianFIAP.