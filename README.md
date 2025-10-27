# Задача Сегментации ядер клеток с помощью моделей на основе архетикутр U-Net и DeepLabv3+
Cell nucleus segmentation by two models with  architecture: U-Net and DeepLabv3+  
## Архитектура U-Net
![Вид архитектуры](images/u-net-architecture.png)

Модель обучалась 20 эпох:</br>
Validation Accuracy: 87.93%</br>
Validation Dice Score: 0.8805
## Пример работы модели
![Пример работы модели](images/u-net-results.png)

## Архитектура DeepLabv3+
![Вид архитектуры](images/deeplabv3-architecture.png)

Модель обучалась 15 эпох:</br>
Validation Accuracy: 97.23%</br>
Validation Dice Score: 0.9020
## Пример работы модели
![Пример работы модели](images/un.jpg)

<img src="images/un.jpg" width="448"> 
<img src="images/un1.png" width="448"> </br>

**Пример на тестовых изображениях**</br>
<img src="images/un_test1.png" width="448"> 

## Сравнение моделей
<img src="images/dif1.png" height="640"> </br>
<img src="images/dif2.png" height="640"> 