# Домашнее задание к занятию "Система мониторинга Zabbix. Часть 2" - `Важничев Георгий`


### Задание 1

`Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.`

#### Процесс выполнения

1. `Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.`
2. `В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон`
3. `Создайте Item который будет собирать информацию об загрузке CPU в процентах`
4. `Создайте Item который будет собирать информацию об загрузке RAM в процентах`

#### Требования к результатам

`Прикрепите в файл README.md скриншот страницы шаблона с названием «Задание 1`


![png](https://github.com/vajnichev/9-03-hw/blob/main/img/9.3.1.png)
![png](https://github.com/vajnichev/9-03-hw/blob/main/img/9.3.2.png)
![png](https://github.com/vajnichev/9-03-hw/blob/main/img/9.3.3.png)
![png](https://github.com/vajnichev/9-03-hw/blob/main/img/9.3.4.png)
![png](https://github.com/vajnichev/9-03-hw/blob/main/img/9.3.5.png)
![png](https://github.com/vajnichev/9-03-hw/blob/main/img/9.3.6.png)
![png](https://github.com/vajnichev/9-03-hw/blob/main/img/9.3.7.png)
![png](https://github.com/vajnichev/9-03-hw/blob/main/img/9.3.8.png)

### Задание 2

`Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.`

#### Процесс выполнения

1. `Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.`
2. `Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server`
3. `Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов`
4. `Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera`
5. `Прикрепите за каждым хостом шаблон Linux by Zabbix Agent`
6. `Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов`

#### Требования к результатам

`Результат данного задания сдавайте вместе с заданием 3`


