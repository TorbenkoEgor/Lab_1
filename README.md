В этой задаче используется полносвязная нейронная сеть из шести слоев: один Flatten и пять Dense. В первых четырёх слоях Dense используется активация selu, в последнем linear. В слоях Dense 128, 128, 128, 64 и 10 нейронов соответсвенно.

В цикле обучения используется оптимизатор Adam, функция потерь SparceCategoricalCrossentropy и метрика accuracy. Всего производится 25 эпох обучения.

Для получения графиков использовал Tensorboard.

Графики функции потерь

![Image alt](https://github.com/TorbenkoEgor/Lab_1/blob/master/epoch_loss.png)
![Image alt](https://github.com/TorbenkoEgor/Lab_1/blob/master/epoch_val_loss.png)


Графики метрики точности

![Image alt](https://github.com/TorbenkoEgor/Lab_1/blob/master/epoch_acc.png)
![Image alt](https://github.com/TorbenkoEgor/Lab_1/blob/master/epoch_val_acc.png)

Итоговая точность на тестовых данных 0.4770
