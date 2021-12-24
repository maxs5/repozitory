# Описание

Если расходы больше доходов,то налог на разницу доходов и расходов становится отрицательным.

# Локация дефекта

https://github.com/netology-code/javaqa2-homeworks/blob/ac2c9089b1344aff1f64987d1f815984b31dc59a/files/javaintro/Main.java#L8

# Шаги воспроизведения

1 Открыть [код программы](https://github.com/netology-code/javaqa2-homeworks/blob/main/files/javaintro/Main.java)в IDEA<br>
2 Выставить значение переменной `income`(доходы)в 70 тыс.рублей<br>
3 Выставить значение переменной `spending`(расходы)в 100 тыс.рублей<br>
4 Запусить программу <br>
5 Посмотреть на вывод в консоли<br> 

* _Ожидаемый результат_* Вывод сообщения о налоге на второй системе в 0 рублей
* _Фактический результат_* Вывод сообщения о налоге на второй системе в -4500 рублей

# Скриншот

![image](https://user-images.githubusercontent.com/53707586/145557840-220772cb-2e3b-4a9e-80ba-4a495df60916.png)

# Окружение 

* ** Операционная система:** Ubuntu 18.04.6 LTS
* ** IDE:** intellij IDEA 2020.2 (Community Edition)
* ** Java:**OpenJDK 11