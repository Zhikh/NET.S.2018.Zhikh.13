# NET.S.2018.Zhikh.13
Tasks for day 13
## Tasks
### [Task1](https://github.com/Zhikh/NET.S.2018.Zhikh.03/blob/master/Logic.Task4/GreatestCommonDivisor.cs) 
Выполнить рефакторинг класса (с целью сокращения повторного кода) в алгоритмах Евклида (рефакторинг возможен только в случае, когда все методы находятся в одном классе!). Интерфейс класса измениться не должен. Проверить работу существующих модульных тестов.
### [Task2](https://github.com/Zhikh/NET.S.2018.Zhikh.09/tree/master/Task1/Logic.Task1)
В класс с алгоритмом сортировки не прямоугольной матрицы, принимающим как компаратор интерфейс IComparer (из System.Collection.Generic) добавить метод, принимающий как параметр делегат-компаратор (Comparision), инкапсулирующий логику сравнения строк матрицы. Протестировать работу разработанного метода на примере сортировки матрицы, используя прежние критерии сравнения. Класс реализовать двумя способами (два отдельных класса), «замкнув» в первом варианте реализацию метода сортировки с делегатом на метод с интерфейсом (работу выполняет метод с параметром-интерфейсом, метод с делегатом его вызывает), во втором – наоборот (работу выполняет метод с параметром-делегатом, метод с интерфейсом его вызывает).
