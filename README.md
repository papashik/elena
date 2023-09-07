# Golang - основы (дз)
## 1. Линейное уравнение
Даны числа `а` и `b`. Решите в целых числах уравнение `aх + b = 0`. Выведите все решения этого уравнения, если их число конечно, выведите слово `NO`, если решений нет, выведите слово `INF`, если решений бесконечно много.
|Входные данные|Выходные данные|
|-|-|
|`1 -7`|`7`|
|`6 -2`|`NO`|

## 2. Часы - 1
Идёт `k`-я секунда суток. Определите, сколько целых часов `h` и целых минут `m` прошло с начала суток. Например, если

`k = 13257 = 3 * 3600 + 40 * 60 + 57`,

тo `h = 3` и `m = 40`.
#### Входные данные
На вход программе подается целое число `k (0 ≤ k ≤ 86399)`.
#### Выходные данные
Выведите на экран фразу:
`It is ... hours ... minutes.`
Вместо многоточий программа должна выводить значения `h` и `m`, отделяя их от слов ровно одним пробелом.
|Входные данные|Выходные данные|
|-|-|
|`13257`|`It is 3 hours 40 minutes.`|

## 3. Часы - 2
Даны значения двух моментов времени, принадлежащих одним и тем же суткам: часы, минуты и секунды для каждого из моментов времени. Известно, что второй момент времени наступил не раньше первого. Определите, сколько секунд прошло между двумя моментами времени.
#### Входные данные
Программа на вход получает три целых числа: часы, минуты, секунды, задающие первый момент времени и три целых числа, задающих второй момент времени.
#### Выходные данные
Выведите число секунд между этими моментами времени.
|Входные данные|Выходные данные|
|-|-|
|`1 1 1 2 2 2`|`3661`|
|`1 2 30 1 3 20`|`50`|

## 4. Кто старше?
Программа принимает три числа: возраст Антона, возраст Бориса и возраст Виктора. Определите, кто из них старше остальных.
#### Входные данные
Входная строка содержит три натуральных числа: возраст Антона, возраст Бориса и возраст Виктора.
#### Выходные данные
Выходная строка должна содержать латинскую букву - код того человека, который старше всех. Код Антона - `А`, код Бориса - `В`, код Виктора - `С`. Если двое старше третьего, нужно вывести два кода через пробел (в алфавитном порядке). Например, если Антон и Виктор старше Бориса, программа должна вывести `А С`. Если все трое одного возраста, программа должна вывести число
0.
|Входные данные|Выходные данные|
|-|-|
|`10 12 23`|`C`|
|`12 10 12`|`A C`|

## 5. Квадратное уравнение
Решить в действительных числах уравнение `ax² + bx + c = 0`
#### Входные данные
На вход программе подаются `а`, `b`, `с` (целые, по модулю не превосходят 30 000).
#### Выходные данные
Выдать код ситуации и значения корней:

• -1 - бесконечное множество решений;

• 0 - нет действительных корней;

• 1 - уравнение вырождается в линейное, выдать `х`;

• 2 - уравнение квадратное, два различных корня, выдать `x₁` и `x₂`;

• 3 - уравнение квадратное, кратный корень, выдать `х`.

Значения корней выводить в порядке возрастания.
|Входные данные|Выходные данные|
|-|-|
|`0 0 0`|`-1`|
|`1 -2 1`|`3 1.00`|

## 6. Простой for
Дано несколько чисел. Подсчитайте, сколько из них равны нулю, и выведите это количество.
#### Входные данные
Сначала вводится число `N`, затем вводится ровно `N` целых чисел.
#### Выходные данные
Выведите ответ на задачу.
|Входные данные|Выходные данные|
|-|-|
|`5 0 7 0 2 2`|`2`|

## 7. Степени двойки
По данному числу `N` распечатайте все целые степени двойки, не превосходящие `N`, в порядке возрастания.
Операцией возведения в степень пользоваться нельзя!
#### Входные данные
Вводится натуральное число.
#### Выходные данные
Выведите ответ на задачу.
|Входные данные|Выходные данные|
|-|-|
|`50`|`1 2 4 8 16 32`|

## 8. Количество делителей
На вход программе подается натуральное число `n ≤ 2000000000`. Выведите количество делителей числа `n`, включая 1 и само число `n`.
|Входные данные|Выходные данные|
|-|-|
|`13`|`2`|
|`10`|`4`|

## 9. Кубическое уравнение
Даны числа `а`, `b`, `с`, `d`. Выведите в порядке возрастания все целые числа от 0 до 1000, которые являются корнями уравнения
`ax³ + bx² + cx + d = 0`.
#### Входные данные
Вводятся целые числа `a`, `b`, `c` и `d`.
#### Выходные данные
Выведите ответ на задачу. Если в указанном промежутке нет корней уравнения, то ничего выводить не нужно.
|Входные данные|Выходные данные|
|-|-|
|`-1` <br> `1` <br> `-1` <br> `1`|`1`|
|`1` <br> `1` <br> `1` <br> `1`||

## 10. Числа Фибоначчи
Последовательность Фибоначчи определяется так:

$F_{0} = 0$, $F_{1} = 1$, $F_{n} = F_{n-1} + F_{n-2}$

По данному числу `n` определите `n`-е число Фибоначчи $F_{n}$.
#### Входные данные
Вводится натуральное число `n`.
#### Выходные данные
Выведите ответ на задачу.
|Входные данные|Выходные данные|
|-|-|
|`1`|`1`|
|`2`|`1`|
|`6`|`8`|

## 11. Часы - 3
Электронные часы показывают время в формате `h:mm:ss`, то есть сначала записывается количество часов в диапазоне от 0 до 23, потом обязательно двузначное количество минут, затем обязательно двузначное количество секунд. Количество минут и секунд при необходимости дополняются до двузначного числа нулями.
С начала некоторых суток прошло `n` секунд. Выведите, что покажут часы. Задачу необходимо решить без использования условных операторов и\или циклов.
#### Входные данные
Вводится число `n` - целое, положительное, не превышает $10^7$.
#### Выходные данные
Выведите показания часов, соблюдая формат.
|Входные данные|Выходные данные|
|-|-|
|`3602`|`1:00:02`|
|`129700`|`12:01:40`|

## 12*. Количество членов
Дана последовательность натуральных чисел, завершающаяся числом 0. Определите, какое наибольшее число подряд идущих элементов этой последовательности равны друг другу.
Числа, следующие за числом 0, считывать не нужно.
##### Входные данные
Дана последовательность натуральных чисел, завершающаяся числом 0.
#### Выходные данные
Выведите ответ на задачу.
|Входные данные|Выходные данные|
|-|-|
|`1 7 7 9 1 0`|`2`|
