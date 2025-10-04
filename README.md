<h1 name="content" align="center"><a href="">
</a> MSSQL</h1>

<p align="center">
  <a href="#-lab1"><img alt="lab1" src="https://img.shields.io/badge/Lab1-blue"></a> 
  <a href="#-lab2"><img alt="lab2" src="https://img.shields.io/badge/Lab2-red"></a>
</p>
<h3 align="center">
  <a href="#client"></a>
  Вариант 10. Справочник вуза
  
Факультеты: название, адрес, телефон, ФИО руководителя,  ФИО секретаря, список общефакультетских  помещений;
Кафедры: название, адрес, телефон, ФИО руководителя,  ФИО секретаря, список помещений кафедры;
Сотрудники подразделений: ФИО,  должность(лаборан,|ассистент,преподаватель,старший преподаватель ,доцент,профессор),  паспорт, телефон;

Реализовать:
- Поиск сотрудников по фамилии (выдача всей информации);
- Выдача информации о комнате (к какой кафедре относится, список сотрудников, работающих в комнате);
- Выдача информации о подразделении (номера комнат,относящихся к подразделению, телефоны комнат, список сотрудников по каждой комнате);
- Вывод телефонного справочника по кафедрам для одного факультета;
- Вывод телефонного справочника факультетов.

</h3>

# <img src="https://github.com/user-attachments/assets/e080adec-6af7-4bd2-b232-d43cb37024ac" width="20" height="20"/> Lab1
[Назад](#content)
<h3 align="center">
  <a href="#client"></a>
  Разработать ER-модель данной предметной области: выделить сущности, их атрибуты, связи между сущностями. 
Для каждой сущности указать ее имя, атрибут (или набор атрибутов), являющийся первичным ключом, список остальных атрибутов.
Для каждого атрибута указать его тип, ограничения, может ли он быть пустым, является ли он первичным ключом.
Для каждой связи между сущностями указать: 
- тип связи (1:1, 1:M, M:N)
- обязательность

ER-модель д.б. представлена в виде ER-диаграммы (картинка)

По имеющейся ER-модели создать реляционную модель данных и отобразить ее в виде списка сущностей с их атрибутами и типами атрибутов,  для атрибутов указать, явл. ли он первичным или внешним ключом 
</h3>


#### №1. ER-модель
![image](/pictures/er.png)

#### №1.1. Реляционная модель
![image](/pictures/REL.jpg)

 # Лабораторная работа №2
 <p aligh="justify>
<h3>
  <a href="#client"></a>
 
 Задание:
  В соответствии с реляционной моделью данных, разработанной в Лаб.№1, создать реляционную БД на учебном сервере БД :
- создать таблицы, определить первичные ключи и иные ограничения
- определить связи между таблицами
- создать диаграмму
- заполнить все таблицы адекватной информацией (не меньше 10 записей в таблицах, наличие примеров для связей типа 1:M )

</h3>

[Посмотреть SQL-код создания таблицы](https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/LAB2)

<h3>
  Диаграмма таблицы:
  
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/2025-10-04_18-41-36.png" width="3000" height="3000"/>
  
</h3>
  
<h3>
  Таблицы
</h3>
<h4>
  Факультет:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/2025-10-04_18-53-56.png" width="3000" height="3000"/>
</h4>
<h4>
  Кафедра:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/2025-10-04_18-55-45.png" width="3000" height="3000"/>
</h4>
<h4>
  Продукт:
  <img src="https://github.com/nik1kit/BD_labs/blob/main/charts/tables/%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82.png" width="3000" height="3000"/>
</h4>
<h4>
  Сотрудник:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/2025-10-04_18-57-52.png" width="3000" height="3000"/>
</h4>
<h4>
  Должность:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/2025-10-04_18-58-41.png" width="3000" height="3000"/>
</h4>
<h4>
  Сотрудник - должность:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/2025-10-04_18-59-52.png" width="3000" height="3000"/>
</h4>
<h4>
  Сотрудник - помещение:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/2025-10-04_19-02-32.png" width="3000" height="3000"/>
</h4>
<h4>
  Помещение:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/Снимок%20экрана%202025-10-04%20185636.png" width="3000" height="3000"/>
</h4>
