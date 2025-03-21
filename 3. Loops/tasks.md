# Loops tasks

## Задача 0 
Да се пресметне `n!` за дадено `n`.

```
Примерен вход: 5
Примерен изход: 120

Примерен вход: 16
Примерен изход: 20922789888000

Примерен вход: 0
Примерен изход: 1
```


## Задача 1 
Да се пресметнат и отпечатат първите `n` члена на редицата ai = i^2 + 3i за въведено цяло неотрицателно `n`.

```
Примерен вход: 7
Примерен изход: 4; 10; 18; 28; 40; 54; 70;
```

## Задача 2 
Да се напише програма, която чете от клавиатурата `n` числа и извежда най-голямото отрицателно число.

```
Примерен вход: 8 2 3 4 -5 -4 3 -2 3
Примерен изход: -2
```


## Задача 3 
По въведено естествено число `n` изведете `n`-тото число от редицата на Фибоначи.

```
Примерен вход: 6
Примерен изход: 8

Примерен вход: 12
Примерен изход: 144
```

## Задача 4 
От клавиатурата се въвеждат произволен брой числа. Намерете сбора на всички числа до въвеждането на 0.

```
Примерен вход: 1 2 3 0 5
Примерен изход: 6 
```

## Задача 5 
От клавиатурата се въвежда естествено число. Намерете сбора на цифрите му.

```
Примерен вход: 5550
Примерен изход: 15
```

## Задача 6 
Напишете програма, която, по дадено число `а` и степенен показател `n`, намира `а` нa `n`-та степен.

```
Примерен вход: 2 5
Примерен изход: 32
```

## Задача 7 
По дадено естествено число определете дали то е просто.

``` 
Примерен вход: 8
Примерен изход: NO

Примерен вход: 7
Примерен изход: YES
```

## Задача 8 
Изкарайте всички главни букви от английската азбука, които са съгласни. 


## Задача 9
Да се въведе някое естествено число от клавиатурата и да се изведе неговото двуично представяне.

```
Примерен вход: 6
Примерен изход: 110

Примерен вход: 76
Примерен изход: 1001100
```


## Задача 10 
По дадено число `n` изкарайте на екрана квадрат от `n` x `n` символи, където по главния диагонал стоят нули, над него +, а под него -.

```
Примерен вход: 4
Примерен изход:
0+++
-0++
--0+
---0
```

## Задача 11
Представете си, че имаме един стенен аналогов часовинк. Стрелката му започва от 12 часа. По въведен брой часове `elapsedHours` да се изкара броя пълните ротации на малата стрелка и в колко часа ще приключи ротацията.

```
Примерен вход: 15
Примерен изход: 1 rotation(s) and the hour hand is at 3 o'clock

Примерен вход: 32372635
Примерен изход: 2697719 rotation(s) and the hour hand is at 7 o'clock.
```
> Да се реши с цикли и без цикли


## Задача 12
Господин Денев е учител по програмиране в един много известен и почитан електротехникум във Великотърновска област. Той преподава на учениците си основите на програмирането на един много древен език наречен C++. Неговата задача е да въведе оценките на своите ученици и да пресметне какъв е средният им успех. Също така иска да разбере колко ученици каква оценка имат. Както и колко проценти има от всяка оценка. Вашата задача е да измислите система по която той да въведе оценките и да изкара нужната за него информация.

## Задача 13
Марто имал за задача да вземе една купчина **естествени** числа и да разбере дали те се палиндроми. Така като не му се занимавало да гледа всяко число цифра по цифра, той решил да се обърне към ФМИ и да си наеме програмист, който да му свърши задачата. На него му трябва проста програма в която въвежда число и изкарва на екрана дали е палиндром.

```
Примерен вход: 132
Примерен изход: false

Примерен вход: 1885881
Примерен изход: true
```

> Палиндром е такова число, което се чете по един и същ начин дали е обърнато или не.


## Задача 14
Тошко Терцата искал да си направи малка програмка, чрез която по зададени ден, месец и година иска да разбере каква дата ще бъде след определен брой дни. Помогнете му да си направи програмата, за да спре да изтърва турнирите си по белот.

```
Примерен вход: 26-10-2022 1234
Примерен изход: The date after 1234 days would be 13-3-2023

Примерен вход: 02-09-1658 165245
Примерен изход: The date after 165245 days would be 5-2-2111
```


## Задача 15
Да се намери дали дадено число е перфектно.

> Едно число е перфектно тогава когато е равно на сбора от делителите си.
> Пример 28 = (1 + 2 + 4 + 7 + 14)

```
Примерен вход: 6
Примерен изход: true

Примерен вход: 200
Примерен изход: false

Примерен вход: 28
Примерен изход: true
```

> Бонус: Намерете някое друго перфектно число

## Задача 16
Да се изведат първите 20 естествени числа, довичиният запис на които съдържа равен брой 0 и 1.


## Задача 17
Ники е студент първи курс във ФМИ и има един тегав предмет наречен дискретни структури. В този предмет той се занимава с доказателство на различни множества. За домашно, той има да направи програма, която да провери по зададени две множества, дали дадено число принадлежи на:
- Тяхното обединение
- Тяхното сечение
- Тяхната разлика
- Дали се намира само в едно от множествата

Уловката е, че трябва да намери дали числото се намира в само едно от множествата без да прави други проверки освен за обединение, сечение и разлика. Първото множество съдържа числата от първото въведено число до второто. А второто множество съдържа числата от третото въведено число до четвъртото.

> Приемаме, че първото множество винаги ще бъде преди второто

> Решава се без цикли ^^

```
Примерен вход: 1 5 3 5 5
Примерен изход:
Is in union: true
Is in intersection: true
Is in difference: false
Is in only one set: false

Примерен вход: 1 5 3 5 5
Примерен изход:
Is in union: true
Is in intersection: false
Is in difference: true
Is in only one set: true

Примерен вход: 1 5 9 12 6
Примерен изход:
Is in union: false
Is in intersection: false
Is in difference: false
Is in only one set: false

Примерен вход: 1 5 6 9 7
Примерен изход:
Is in union: true
Is in intersection: false
Is in difference: false
Is in only one set: true
```

# Задача 18 (Важна!)

Имате ред от 8 лампи, представени с 8-битово цяло число, където всеки бит съответства на лампа. Всяка лампа може да бъде в едно от двете състояния: включена (1) или изключена (0). Напишете програма, която ви позволява да извършвате различни действия с тези лампи.

## Условия:

> Решете без цикли!

### Проверка на състоянието на лампа  
Пример:
```cpp
Вход: 2
Изход: Lamp 2 is OFF
```

### Извеждане на състоянието на лампите
Пример:

```cpp
Изход:
1 - OFF
2 - ON
3 - OFF
4 - ON
5 - ON
6 - ON
7 - ON
8 - ON
```

### Включване на определена лампа

Пример:
```cpp
Вход: 4
Изход: Lamp 4 is now ON
```

### Изключване на определена лампа

Пример:
```cpp
Вход: 4
Изход: Lamp 4 is now OFF
```

### Изключване на захранването
Изключва всички лампи

### Превключване на състоянието на лампа

Ако лампата е включена, я изключете, и обратно.

Пример:
```cpp
// ако лампа 3 е изключена
Вход: 3
Изход: Lamp 3 is now ON
```

***Bonus1:*** *без if за проверка на състоянието на лампата*
***Bonus2 (requires Bonus1):*** *без if за отпечатване*

### Обръщане на състоянието на всички лампи

Превключете състоянието на всички лампи, като направите лампите, които са ВКЛЮЧЕНИ, да станат ИЗКЛЮЧЕНИ и обратно.

Пример:
```cpp
// преди
1 - OFF
2 - ON
3 - OFF
4 - ON
5 - ON
6 - ON
7 - ON
8 - ON
```

```cpp
// след
1 - ON
2 - OFF
3 - ON
4 - OFF
5 - OFF
6 - OFF
7 - OFF
8 - OFF
```