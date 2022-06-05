## Трекинг теннисного мяча с использованием нейронных сетей
### Практическое задание №2 в рамках курса «Нейронные сети в обработке изображений»

В результате выполнения задания была реализована и обучена модель для трекинга мяча на серии видеофрагментов теннисного матча и выполнена постобработка предсказаний. Тестовая выборка представляет собой 2 игры, состоящие суммарно из 17 клипов. Клипы представлены в виде последовательности кадров в формате .jpg разрешения $1280 \times 720$.

Достигнута точность `81.7%` на тестовом наборе данных. 

В качестве модели использовалась `U-Net`, в качестве функции потерь - `1 - IoU`.

### Список дополнений:
| Метка | Описание |
| ----- |--------|
| LBL1  | Автоматическое сохранение модели при обучении |
| LBL2  | Валидация модели на тестовой выборке |
| LBL3  | Вывод функции потерь и точности в процессе обучения |

### Пример работы модели:

<img src="video/test.gif" alt="example"/>

В `video` можно посмотреть остальные примеры работы модели.