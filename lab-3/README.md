# Лабораторна робота 3
## Тема: _Методи обходу та модифікації графів_
## Мета роботи: _Навчитись застосовувати алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева_

## Хід роботи
У роботі використовується онлайн ресурс для генерування графів [Graph Online](https://graphonline.ru/).
1. За допомогою лабораторного макету побудувати випадковий неорієнтований граф `G={8,12}`:
![граф](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/%D0%B3%D1%80%D0%B0%D1%84.png)
    1. Побудувати дерево за алгоритмом обходу в ширину (BFS); (для 2-х різних вершин)
    ![граф](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/%D0%B3%D1%80%D0%B0%D1%841%D1%88%D0%B8%D1%80%D0%B8%D0%BD%D0%B0.png)
    1. Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?

    **Відповідь:**
    
    1. Побудувати дерево за алгоритмом обходу в глибину (DFS); (для 2-х різних вершин)
    ![граф](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/%D0%B3%D1%80%D0%B0%D1%841%D0%B2%D0%B3%D0%BB%D0%B8%D0%B1.png)
    1. Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?

    **Відповідь:**

1. За допомогою лабораторного макету побудувати випадковий орієнтований граф `G={6,10}`:
![граф](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/%D0%B3%D1%80%D0%B0%D1%842.png)
    1. Побудувати дерево за алгоритмом обходу в ширину (BFS);
    ![граф](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/%D0%B3%D1%80%D0%B0%D1%842%D0%B2%D1%88%D0%B8%D1%80%D0%B8%D0%BD%D1%83.png)
    1. Яка вершина (вершини) буде знайдена останньою?
    1. Визначити чи існують цикли. Вказати послідовність ребер і їх довжину.
    1. Визначити кількість хвиль, які пройдуть по ребрах доки буде виявлена остання вершина.
    1. Побудувати дерево за алгоритмом обходу в глибину (DFS);
    ![граф](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/%D0%B3%D1%80%D0%B0%D1%842%D0%B2%D0%B3%D0%BB%D0%B8%D0%B1.png)
1. Побудувати дерево шляхів рангом `r=4` для випадкового графа `G={6,9}`.

![alt text](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/%D0%B3%D1%80%D0%B0%D1%843.png)

![alt text](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/%D0%B3%D1%80%D0%B0%D1%843%D0%B4%D0%B5%D1%80%D0%B5%D0%B2%D0%BE.png)

1. Побудувати мінімальне зв’язне дерево для графа `G`. Вказати його вагу.

![alt text](https://github.com/BobasB/lab_example/blob/master/lab_guidance/3_/images/graph.png "Знайти вагу графа")

![alt text](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/4.png)

![alt text](https://github.com/osyka-oleksandr/osyka_lab_totk_2021/blob/main/lab-3/%D0%B3%D1%80%D0%B0%D1%844.png)

**Відповідь: Вага = 29**

## Здача роботи
1. Оформити звіт лабораторної роботи. Звіт повинен бути у файлі `README.md` та завантажений у репозиторій GitHub.
1. URL посилання на виконану роботу вставити у відповідне завдання у Google Classroom.

---
