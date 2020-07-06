# Tarea_4.0

En el archivo bits10k.csv se encuentran 10.000 bits (actualizado) generados a partir de una fuente binaria equiprobable. El objetivo es hacer una modulación digital para "transmitir" estos datos por un canal ruidoso. La modulación se hace con una frecuencia en la portadora de f = 5000 Hz y con un período de símbolo igual a un período completo de la onda portadora.

# Pregunta 1

El primer paso fue realizar una lectura de los bits brindados por el profesor, para realizar una modulación de tipo BPSK. para esto se ingreso la frecuencia de la protadora y con esto se sacó el periodo de modulación.
Seguidamente se creó una línea temprotal para ser uno de los ejes de la señal a partir del periodo y el número de bits analizados. por otra parte, se creó una señal de la forma de onda portadora, y se realizó después de esto la senal modulada.en la cual según el balor binario de los bits ( 0 o 1) cambiaba de forma sinus y -sinus resoectivamente.

# Pregunta 2
2. Calcular la potencia promedio  e la señal modulada generada. 
 En la presentación de procesps estocásticos de las variables aleatorias se puede observar que la potencia pomedio puede ser generada a partir de una señal como a integral de la potencia instantánea entre el periodo por el numero de bits en el tiempo
 
 # Pregunta 3
 
Con un rango de sigma dado desde -2 hasta 3 se sacó la potencia del ruido, y con esto se sacó la desviación estándar (sigma de cada una), después de esto se generó ruido de manera aleatoria con la desviación, y se graficó la señal con ruido.

# Pregunta 4
En esta parte se graficó la densidad espectral de potencia 
de la señal con el método de Welch (SciPy) el cual es brindado por python como una herramienta para poder visualizar la señal generada antes de pasar por el canal ruidoso y después de pasar por el canal ruidoso

# Pregunta 5
Pimero se determinó la pseudo energía de la onda original, seguidamente, se inicializan los bits recibidos con la forma característica que posee, seguidamente se realiza el producto de sos funciones para visualizar el error que corresponde a la suma del valor absulutro de los bits originales entre los bits resultantes del producto de dos funciones, y la taza de error es el valor anteriormente calculado para cada una de las partes de la reñal Rx según la desviación .

# Pregunta 6
Se grafica el taza de señal a ruido entre la taza de error obtenida




