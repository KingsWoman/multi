# multi
# IO-bound
## Время работы оригинального скрипта

![](https://github.com/KingsWoman/multi/blob/main/io-bound%20original.png?raw=true)


## Время работы с пятью потоками
![](https://github.com/KingsWoman/multi/blob/main/io-bound%205.png?raw=true)


## Время работы с десятью потоками
![](https://github.com/KingsWoman/multi/blob/main/io-bound%2010.png?raw=true)


## Время работы со ста потоками
![](https://github.com/KingsWoman/multi/blob/main/io-bound%20100.png?raw=true)


## Выводы
Как можно заметить, с увеличением числа потоков
время работы уменьшается, причем нагрузка на 
систему остается примерно на одном уровне.
----
# CPU-bound


## Время работы оригинального скрипта
![](https://github.com/KingsWoman/multi/blob/main/cpu-bound%20original.png?raw=true)
Нагрузка на ЦПУ - 30%
---
## Время работы в два процесса
![](https://github.com/KingsWoman/multi/blob/main/cpu-bound%202.png?raw=true)
Нагрузка на ЦПУ - 60%
---
## Время работы в четыре процесса
![](https://github.com/KingsWoman/multi/blob/main/cpu-bound%204.png?raw=true)
Нагрузка на ЦПУ - 100%
---
## Время работы в пять процессов
![](https://github.com/KingsWoman/multi/blob/main/cpu-bound%205.png?raw=true)
Нагрузка на ЦПУ - 100%
---
## Время работы в десять процессов
![](https://github.com/KingsWoman/multi/blob/main/cpu-bound%2010.png?raw=true)
Нагрузка на ЦПУ - 100%
---
## Время работы в шестьдесят процессов
![](https://github.com/KingsWoman/multi/blob/main/cpu-bound%2060.png?raw=true)
Нагрузка на ЦПУ - 100%
---
## Выводы
По полученным результатам можно сделать вывод, что время работы 
уменьшается с увеличением числа процессов, пока их число не превышает
число ядер у процессора. После того, как число процессов превысит число
ядер, время работы будет находиться примерно на одном уровне, то уменьшаясь,
то увеличиваясь, т.к. при переборе используются случайно сгенерированные 
значения. Также, с увеличением числа процессов увеличивается нагрузка на
процессор.
