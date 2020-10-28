# Отчет о лабораторных работах
# студент группы [ИДБ-17-07](https://github.com/stankin/design-part-1/wiki/list-idb-17-07) Смирнов Г.Д.

## Лабораторная 1

### RAMUS - программное средство разработки структурно-функциональных моделей
Текст с постановкой задачи: Нарисовать чертёж

![none](https://github.com/Notespeak/projectmanagement/blob/master/lab_1/Screenshot_8.png)



### PLANTUML - программное средство автоматической генерации UML-диаграмм
#### Class diagram
![none](https://github.com/Notespeak/projectmanagement/blob/master/lab_1/uml1.png)



#### Usecase diagram
![none](https://github.com/Notespeak/projectmanagement/blob/master/lab_1/uml2.png)
 

## Лабораторная 2
IDEF0 diagram
### Контекстная модель

![none](https://github.com/Notespeak/projectmanagement/blob/master/lab_2/Screenshot_2145.png)

### PDC
Средний уровень:
![none](https://github.com/Notespeak/projectmanagement/blob/master/lab_2/Screenshot_2161.png)

### DFD
блок:Оформление товара и выдача
![none](https://github.com/Notespeak/projectmanagement/blob/master/lab_2/Screenshot_2162.png)
[Файл .rsf](https://github.com/Notespeak/projectmanagement/blob/master/lab_2/pdc-tildag.rsf)

### Usecase diagram

![none](https://github.com/Notespeak/projectmanagement/blob/master/lab_2/uml.png)
[Код](https://github.com/Notespeak/projectmanagement/blob/master/lab_2/uml.txt)

## Лабораторная 3
### Диаграмма ERD
![none](https://github.com/Notespeak/projectmanagement/blob/master/lab_3/erd.png)
[Код](https://github.com/Notespeak/projectmanagement/blob/master/lab_3/erd.txt)
В БД: Товары находятся все позиции товаров приобретаемые в процессе оформления заказа на покупку товара или услуги, для которых необходимы:Денежные средства, код товара и инструкция (описание товара).
### Диаграмма последовательности
![none](https://github.com/Notespeak/projectmanagement/blob/master/lab_3/uml.png)
[Код](https://github.com/Notespeak/projectmanagement/blob/master/lab_3/uml.txt)
Покупатель, чтобы приобрести товар регистрирует заявку в биллинг системе, которая в свою очередь генерирует запрос на создание ссылки на оплату на Pos терминале и выдает эту ссылку клиенту. Как только оплата прошла успешна, и товар, воспринимаемый как код в БД,  отправляется на управляющий сервер для фиксации информации БД, что один экземпляр данного товара куплен. В последствии, управляюшему серверу возвращается сообщение об успешном изменении соответствующих ячеек в БД,а также статус успешности предоставления услуги.
## Семинары 3-4
![none](https://github.com/Notespeak/projectmanagement/blob/master/sem3-4.md)
## Лабораторная 4
## Лабораторная 5

## Лабораторная 6
