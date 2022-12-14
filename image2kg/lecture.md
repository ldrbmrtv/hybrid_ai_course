# Извлечение графов знаний из изображений

## Набор изображений
- создание проекта на [Roboflow](https://roboflow.com/)
- импорт проекта в Colab

## Распознавание объектов
- подключение GPU в Colab
- модель YOLO
- клонирование [репозитория YOLOv5](https://github.com/ultralytics/yolov5)
- дообучение YOLOv5 на наборе изображений
  - размерность изображений
  - количество эпох
- распознавние объектов на тестовой выборке
- формирование датафрейма с результатами распознавания

## Извлечение отношений
- one-hot encoding
- поиск ассоциативных правил
- отбор правил по lift

## Граф знаний
- создание экземпляров на основе распознанных объектов
- создание транзитивного отношения и объявление отношений между экземплярами
- вывод новых отношений с помощью ризонера

---

[Запись лекции](https://youtu.be/4eUb3ZoVeg0)

---

[Лабораторная работа](https://github.com/ldrbmrtv/hybrid_ai_course/blob/main/image2kg/task.md)
