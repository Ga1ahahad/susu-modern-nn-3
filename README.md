# Лабораторная работа 3

Датасет: Smoker Detection [Image] classification Dataset. Бинарная классификация есть на изображении курильщик или нет. Картинки 250x250 цветные.  
Ссылка: https://www.kaggle.com/datasets/sujaykapadnis/smoking

Архитектура CNN:  

![image](https://github.com/Ga1ahahad/susu-modern-nn-3/assets/90559631/43adb2b6-648e-4010-ae99-a6c5b55b1604)
![image](https://github.com/Ga1ahahad/susu-modern-nn-3/assets/90559631/f88c2f33-28ce-48c4-ac9c-c8254dc9ff74)

Итого три свёрточных, три пулинговых и два линейных слоя. Активация тангенсом с сигмоидой в конце.  
Функция потерь - бинарная кроссэнтропийная, оптимизатор - Адам с lr=0.001.  

Результат - loss = 0.0014300222974270582, samples = 4352, accuracy 0.7666666666666667 на валидационном датасете.  

На тестовом датасете получены следующие метрики:  
  Precision: 0.46  
  Recall: 0.21  
  Accuracy: 0.22  

Матрица ошибок:  
![image](https://github.com/Ga1ahahad/susu-modern-nn-3/assets/90559631/5521a9da-3a9b-4f26-8737-38b008bd49f4)
