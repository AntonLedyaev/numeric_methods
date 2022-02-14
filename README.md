# numeric_methods

СПбГУ ПМ-ПУ 5 семестр, численные методы.

## Задание 2. Интерполяция. 

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/func.jpg)


Для заданной функции y = f(x) выполнить следующее:
1. Выбрать из области её определения интервал непрерывности.
2. Назначить некоторое число равноотстоящих узлов и построить интерполяционный полином. Проделать то же самое, взяв
в качестве узлов то же количество узлов, но определяемых по
формуле (3.2). Сравнить полученные результаты.

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/formula.jpg)
3. Повторить п.2, увеличивая число узлов.
4. Для функции h(x) = |x| · f(x) проделать ту же работу, что и
для y = f(x) на том же самом интервале. Сравнить поведение
интерполяционных полиномов в первом и втором случаях.

### Результаты:

#### Функция

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/func_plot.png)

#### Функция на отрезке

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/func_plot_short.png)

#### Полином Лагранжа

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/lagrange.png)

#### Полином Ньютона 

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/newton.png)

#### Абсолютная погрешность

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/error.png)

## Задание 2. Аппроксимация. 

1. Для указанной функции f(x) по методу наименьших квадратов построить алгебраический полином наилучшего среднеквадратичного приближения третьей степени по пяти узлам
{xi} и значениям функции {f(xi
)} в этих узлах.
2. Для той же функции на том же отрезке построить алгебраический полином наилучшего приближения в пространстве L2
третьей степени с использованием полиномов Лежандра.
3. Построить графики исходной функции и двух построенных
полиномов.

#### Функция

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/func_plot.png)

#### Результат аппроксимации.

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/approx.png)

#### Результат аппроксимации с использованием полиномов Лежандра.

![Image alt](https://github.com/AntonLedyaev/numeric_methods/raw/main/img/approx_l.png)

