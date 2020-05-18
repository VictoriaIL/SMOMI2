# SMOMI2
В второй лабораторной необходимо было менять различные параметры сети, такие как количество слоёв, скорость обучения, количество нейронов в слоях.

1. Сверточная сеть с четырьмя слоями Conv2D(filters=14, kernel_size=3)
~~~ lr == 2*10^-7 ~~~~

Метрики точности

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/A_1_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/A_1.PNG)

Функции потерь

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/L_1_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/L_1.PNG)

2. Сверточная сеть с пятью слоями Conv2D(filters=16, kernel_size=3)
~~~ lr == 2*10^-6 ~~~~

Метрики точности 
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/A_2_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/A_2.PNG)

Функции потерь

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/L_2_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/L_2.PNG)

3. Свёрточная сеть со слоями Conv2D(filters=4, kernel_size=3),Conv2D(filters=8, kernel_size=3), Conv2D(filters=12, kernel_size=3),
Conv2D(filters=16, kernel_size=3)
~~~ lr == 2*10^-6 ~~~~

Метрики точности

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/A_3_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/A_3.PNG)

Функции потерь

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/L_3_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/L_3.PNG)

4. 







