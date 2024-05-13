SUMADOR 64 BITS

este sumador  se construyo a partir de un sumador de un bit 
![image](https://github.com/Gianluigi26/sumador_64/assets/54091081/e7dbfc90-c417-478d-b8e1-5550a7ada463)

sumador de 64 bits
![image](https://github.com/Gianluigi26/sumador_64/assets/54091081/259f140f-38ca-4ec2-b20f-1b481b0adc5d)


1.	RTL Code (Registre-Transfer Level)
En este paso describimos el comportamiento de un circuito digital a nivel abstracción que incluye registros, utilizando leguaje de descripción de hardware (HDL).

![image](https://github.com/Gianluigi26/sumador_64/assets/54091081/4668bf22-ef60-48d0-94cd-df884795836b)
![image](https://github.com/Gianluigi26/sumador_64/assets/54091081/0f19969e-3d52-4625-b884-a2a9eabb9207)

2.	Simulation
En este paso se emplea la herramienta de simulación para verificar el comportamiento del diseño antes de sintetizarlo en un dispositivo FPGA real. Se crean tesbenches, que verifican la sintaxis, para el funcionamiento del código.
 Acá simulamos la suma de dos valores en los cuales, son :

A = 6'b11110; // 30 en binario
B = 6'b10100; // 20 en binario

![image](https://github.com/Gianluigi26/sumador_64/assets/54091081/2edfdfc7-6b22-46b8-92d0-a6b1dd48db8d)

3.	Synthesis
El proceso de síntesis se convierte la descripción del comportamiento del circuito digital en una representación más detallada que se puede implementar en el hardware real. Esto quiere decir que va a transformar el código a nivel de compuertas y flip flop.

![image](https://github.com/Gianluigi26/sumador_64/assets/54091081/d40aada4-ee1b-430d-8ced-5ad438ceaafe)

4.	Implementation
En este paso es donde se lleva a cabo la asignación física de recursos y el enrutamiento de conexiones para nuestro diseño en la FPGA específica seleccionada. 

![image](https://github.com/Gianluigi26/sumador_64/assets/54091081/a5723dcc-f81c-40d3-b56c-58e5df44e917)

5.	Device programming (programación del Dispositivo) 
implica cargar el bitstream generado durante la implementación en el dispositivo FPGA real o en la tarje de programación. Acá ya procedemos a cargas nuestro código a la placa para ya visualizar físicamente nuestro circuito. 

![image](https://github.com/Gianluigi26/sumador_64/assets/54091081/2d784a5b-6a1b-418c-b272-04d64704f7fd)
