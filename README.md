# TEST-work
1 work -Three famous scientists Voktaysed, Vokiruy and Veidafin decided to help
well-known brainy creature Rotsor to pass exams. Exams were on a very
interesting and useful subject - Approximate Optimization. The problem was
to write a program that behaves like the one written by Cheetah (who gave
only EXE file running away for playing Civilization III). As Cheetah's mind is
not so powerful Rotsor believes that Cheetah could write only a program
evaluating some polynomial. He is also sure that the polynomial degree is at
most four (5 is too much for Cheetah). Help the scientists to help Rotsor and
write the desired program. Remember that Rotsor is too lazy and the scientists
are too busy so the only hope is on you.
Input
On the first line of the input you will be given number of test cases T (no
greater than 100). T following lines will be numbers for evaluation (in range
[-1000; 1000])
Output
Your program should produce T lines of output. Each line is the evaluation
of the polynomial and should be same as the result of Cheetah's program. As
was already said Cheetah's program evaluates polynomial of the form f(x) =
A*x^4 + B*x^3 + C*x^2 + D*x + E. Print the values of f(x) with precision
of 3 digits.

2-Шины, установленные на одном и той же автомобиле, могут изнашиваться с
различной скоростью в зависимости от позиции шин. Например, шины на ведущих
колесах обычно изнашиваются быстрее, чем шины на ведомых колесах. Эту проблему
обычно решают, переставляя шины время от времени.
Допустим, что автомобиль имеет N колес и имеется M новых шин (шины
одинаковые). Кроме того, для каждого колеса известна скорость износа шины на этом
колесе. Напишите программу, которая определяет сколько максимально может проехать
автомобиль, если перестановку шин производить оптимально. Вы можете предполагать,
что шины изнашиваются равномерно и автомобиль движется прямолинейно.
Input
В первой строке содержатся два целых числа N (4 ≤ N ≤ 10, N четное)
и M (N ≤ M ≤ 20).
Далее следуют N строк, i-ая строка содержит одно целое число a[i] (0 < a[i] ≤
3000). Новая шина, установленная на i-том колесе, полностью изнашивается
через a[i] километров.
Output
Вывести максимальное число километров, которые может проехать автомобиль,
округленное до трех знаков после запятой.

3-Даны различные натуральные числа А, В, N: 1 < А, B < 10, 10 < N < 100.
Сумма нескольких чисел равна N, каждое из чисел равно А или B.
Найти наибольшее возможное значение произведения этих чисел. Если такая
ситуация невозможна, то вывести 0.
Input
Три целых числа в одной строке -- А, В, N.
Output
Вывести целое число -- ответ задачи.

4-Тошик проснулся ночью с жаждой охоты. Наловив N белых и M черных мышей, он
принес их утром хозяйке. Ожидая, когда она проснется и порадуется, он разложил их
следующим образом:

Его хозяйка очень любит поспать. Тошик заскучал и решил переложить мышей так,
чтобы черные лежали слева, а белые справа. При этом он соблюдает следующие правила
перекладывания:
 Белую мышь можно переложить на соседнюю от нее справа клетку, если она не
занята
 Черную мышь можно переложить на соседнюю от нее слева клетку, если она не
занята
 Белую мышь можно переложить через одну черную на свободную клетку справа от
нее
 Черную мышь можно переложить через одну белую на свободную клетку слева от
нее
Тошик, как и всякий кот, ленив, и поэтому он хочет поменять мышей местами за
наименьшее число перекладываний. Ниже приведена оптимальная последовательность
перекладываний для случая N = M = 2.
