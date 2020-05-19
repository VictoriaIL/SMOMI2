# SMOMI2
Во второй лабораторно необходимо было проследить, как меняются метрика точности и функция потерь в зависимости от изменеия различных параметров сети: количество слоёв, скорость обучения, количество нейронов в слоях.

1.Свёрточная сеть со тремя слоями слоями Conv2D(filters=4, kernel_size=3)
``` lr == 2*10^-4 ```

Метрики точности

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/A_4_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/A_4.PNG) 

Функции потерь

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/L_4_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/L_4.PNG) 
 
2. Сверточная сеть с четырьмя слоями Conv2D(filters=14, kernel_size=3)
``` lr == 2*10^-7 ```

Метрики точности

![ff](https://github.com/VictoriaIL/SMOMI2/blob/master/train/A_5_train.PNG)
![a](https://github.com/VictoriaIL/SMOMI2/blob/master/test/A_5.PNG)

Функции потерь

![q](https://github.com/VictoriaIL/SMOMI2/blob/master/train/L_5_train.PNG)
![re](https://github.com/VictoriaIL/SMOMI2/blob/master/test/L_5.PNG)

2. Сверточная сеть с пятью слоями Conv2D(filters=16, kernel_size=3)
``` lr == 2*10^-6 ```

Метрики точности 
![rr](https://github.com/VictoriaIL/SMOMI2/blob/master/train/A_1_train.PNG)
![w](https://github.com/VictoriaIL/SMOMI2/blob/master/test/A_1.PNG)

Функции потерь

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/L_1_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/L_1.PNG)
 
4. Свёрточная сеть со слоями Conv2D(filters=4, kernel_size=3),Conv2D(filters=8, kernel_size=3), Conv2D(filters=12, kernel_size=3),
Conv2D(filters=16, kernel_size=3)
``` lr == 2*10^-6 ```

Метрики точности

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/A_2_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/A_2.PNG)

Функции потерь

![.](https://github.com/VictoriaIL/SMOMI2/blob/master/train/L_2_train.PNG)
![.](https://github.com/VictoriaIL/SMOMI2/blob/master/test/L_2.PNG)







