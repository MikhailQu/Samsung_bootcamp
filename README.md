# Bootcamp_tack1
Обучение sklearn.LinearRegression

Задача: используя sklearn.LinearRegression обучить модель на данных о сверхпроводниках взяты из базы данных сверхпроводящих материалов, собранной Национальным институтом материаловедения Японии NIMS. MSE не менее 300.

Данные содержат сведения о 21 263 сверхпроводников.

Тренировочный набор - 17010 строк.
Тестовый набор - 4253 строк.
Для каждого сверхпроводника в данных приведены полная химическая формула сверхпроводника, а также 8 основных химических свойств (абсолютное значение, среднее, взвешенное среднее и так далее): атомная масса, энергия ионизации, радиус атома, плотность, удельная теплота плавления, энергия сродства к электрону, теплопроводность, валентность.

Результат : для LinearRegression  MSE = 278.712
так же применены методы sklearn.linear_model
