# Федеративное обучение и эпистемическая логика

## Классификаторы
- [Федеративное обучение](https://en.wikipedia.org/wiki/Federated_learning)
- [наивный байесвоский классификатор](https://scikit-learn.org/stable/modules/naive_bayes.html)
- [К ближайших соседей](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html#sklearn.neighbors.KNeighborsClassifier)
- [метод опорных векторов](https://scikit-learn.org/stable/modules/svm.html#svm-classification)

## Модальные логики
- [эпистемическая логика](https://en.wikipedia.org/wiki/Epistemic_modal_logic)
  - cинтаксис
  - cемантика
  - логический вывод
- [доксастическая логика (логика мнений)](https://en.wikipedia.org/wiki/Doxastic_logic)

## Имплементация эпистемической логики в онтологии
- возможные миры -> индивиды
- высказывание -> класс A
- онтология как эпистемический агент
- отношение эпистемической неразличимости -> рефлексивное, симметричное, транзитивное ObjectProperty r1
- отношение доксастической неразличимости -> симметричное, транзитивное ObjectProperty r2
- модальный оператор Ka -> класс KnowA equivalentTo r1 only A
- модальный оператор Ba -> класс BelieveA equivalentTo r2 only A

## Открытый и закрытый миры
- [допущение открытого мира](https://en.wikipedia.org/wiki/Open-world_assumption)
- [допущение закрытого мира](https://en.wikipedia.org/wiki/Closed-world_assumption)
- [немонотонные логики](https://en.wikipedia.org/wiki/Non-monotonic_logic)
- [реализация закрытого мира в owlready2](https://owlready2.readthedocs.io/en/latest/disjoint.html)

## Эпистемико-онтологическая модель федеративного обучения
- генерация классов KnowL и BelieveL для каждого лейбла L
- генерация индивида для каждого предикта каждого классификатора
- установление неразличимости для индивидов, относящихся к одной записи набора данных
- логический вывод производных отношений неразличимости
- замыкание индивидов
- логическая классификация индивидов

---
[Запись лекции](https://youtu.be/zARpf-_PDSo)

---
[Лабораторная работа](https://github.com/ldrbmrtv/hybrid_ai_course/blob/main/el/task.md)
