<h1 name="content" align="center"><a href="">
</a> MSSQL</h1>

<p align="center">
  <a href="#-lab1"><img alt="lab1" src="https://img.shields.io/badge/Lab1-blue"></a> 
  <a href="#-lab2"><img alt="lab2" src="https://img.shields.io/badge/Lab2-pink"></a>
  <a href="#-lab3"><img alt="lab3" src="https://img.shields.io/badge/Lab3-green"></a>
  <a href="#-lab4"><img alt="lab4" src="https://img.shields.io/badge/Lab4-purple"></a>
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

# <a name="-lab2"></a><img src="https://github.com/user-attachments/assets/e080adec-6af7-4bd2-b232-d43cb37024ac" width="20" height="20"/> Лабораторная работа №2
<p align="justify">
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
  
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/2025-10-05_08-16-51.png" width="2000" height="2000"/>
  
</h3>
  
<h3>
  Таблицы
</h3>
<h4>
  Факультет:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/факультет.png" width="2000" height="2000"/>
</h4>
<h4>
  Кафедра:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/кафедры.png" width="2000" height="2000"/>
</h4>

<h4>
  Сотрудник:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/сотрудник.png" width="2000" height="2000"/>
</h4>
<h4>
  Должность:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/2025-10-04_18-58-41.png" width="2000" height="2000"/>
</h4>
<h4>
  Сотрудник - должность:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/сотрудник-должность.png" width="2000" height="2000"/>
</h4>
<h4>
   Помещение:
  <img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/таблицы/Снимок%20экрана%202025-10-04%20185636.png" width="1500" height="1500"/>
</h4>
<h4>
  Сотрудник - помещение:
  <img src="https://github.com/ekatherina123/databases_Tyumeneва_PMI-32_10_var/blob/main/pictures/таблицы/сотрудник-помещение.png" width="2000" height="2000"/>
</h4>

# <a name="-lab3"></a><img src="https://github.com/user-attachments/assets/e080adec-6af7-4bd2-b232-d43cb37024ac" width="20" height="20"/> Лабораторная работа №3

<p align="justify">
<h3>
  <a href="#client"></a>

Часть 1 [Посмотреть SQL запросы и их результаты](https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/LAB3/Тюменева_ПМИ_32_часть1.docx)

Цель: изучить конструкции языка SQL для манипулирования данными в СУБД  MSSQL.
Задания и краткое описание работы:
1. Выборка из одной таблицы.
2. Выборка из нескольких таблиц.
3. Представления
4. Функции ранжирования
5. Объдинение, пересечение, разность
6. Использование CASE, PIVOT и UNPIVOT.

Часть 2 [Посмотреть SQL запросы и их результаты](https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/LAB3/Тюменева_ПМИ_32_часть2.docx)

Составить следующие запросы:
a)  Для каждого факультета вывести список кафедр с ФИО руководителя и секретаря  
b)  Выдать список адресов, по которым находятся подразделения  
c)  Для каждой комнаты выдать название кафедры, телефон, кол-во сотрудников  
d)  Вывести список сотрудников, упорядоченный по факультету, кафедре, ФИО  
e)  Вывести список телефонов для всех подразделений  
</h3>

# <a name="-lab4"></a><img src="https://img.shields.io/badge/Lab4-purple" width="20" height="20"/> Лабораторная работа №4

<ol type="a">
	<h3>Создать 4 различных хранимых процедуры:</h3>

a) Процедура без параметров, формирующая список руководителей и секретарей факультетов с телефонами и номерами комнат


```
CREATE PROCEDURE GetFacultyLeaders
AS
BEGIN
    SELECT 
        f.name AS faculty_name,
        dean.full_name AS dean_name,
        dean.phone AS dean_phone,
        dean_room.number AS dean_room,

        sec.full_name AS secretary_name,
        sec.phone AS secretary_phone,
        sec_room.number AS secretary_room
    FROM Faculty f
    LEFT JOIN Employee dean ON f.dean_id = dean.id
    LEFT JOIN Employee_Room dr ON dean.id = dr.employee_id
    LEFT JOIN Room dean_room ON dr.room_id = dean_room.id

    LEFT JOIN Employee sec ON f.secretary_id = sec.id
    LEFT JOIN Employee_Room sr ON sec.id = sr.employee_id
    LEFT JOIN Room sec_room ON sr.room_id = sec_room.id;
END;
GO
EXEC GetFacultyLeaders;
```
<img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/LAB4/4_1_1.png" alt="Схема 4.1.1" width="650">

b) Процедура, на входе получающая название факультета и формирующая список комнат, которые занимают все кафедры факультета, и общефакультетских помещений
```

CREATE PROCEDURE GetFacultyRooms
    @FacultyName NVARCHAR(100)
AS
BEGIN
    SELECT DISTINCT 
        r.id AS room_id,
        r.number AS room_number,
        r.phone AS room_phone,
        d.name AS department_name
    FROM Faculty f
    JOIN Room r ON r.faculty_id = f.id
    LEFT JOIN Department d ON d.room_id = r.id
    WHERE f.name = @FacultyName;
END;
GO
EXEC GetFacultyRooms @FacultyName = N'Факультет информационных технологий';
```
<img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/LAB4/4_1_2.png" alt="Схема 4.1.2" width="450">


c) Процедура, на входе получающая номер комнаты, выходной параметр –название факультета, которому она принадлежит

```
CREATE PROCEDURE GetFacultyByRoom
    @RoomNumber INT
AS
BEGIN
    SELECT f.name AS FacultyName
    FROM Room r
    JOIN Faculty f ON r.faculty_id = f.id
    WHERE r.number = @RoomNumber;
END;
GO
EXEC GetFacultyByRoom 101;

```
<img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/LAB4/4_1_3.png" alt="Схема 4.1.3" width="450">


d) Процедура, вызывающая вложенную процедуру, которая находит среднюю численность сотрудников в одой комнате, а сама формирует список комнат с численностью сотрудников > средней в форме: факультет, кафедра, комната, количество сотрудников

  
```
--Вложенная процедура — считает среднее число сотрудников в одной комнате

IF OBJECT_ID('GetAverageEmployeesPerRoom', 'P') IS NOT NULL
    DROP PROCEDURE GetAverageEmployeesPerRoom;
GO

CREATE PROCEDURE GetAverageEmployeesPerRoom
    @AvgCount FLOAT OUTPUT
AS
BEGIN
    SELECT @AvgCount = AVG(cnt)
    FROM (
        SELECT room_id, COUNT(*) AS cnt
        FROM Employee_Room
        GROUP BY room_id
    ) AS t;
END;
GO

DECLARE @avg FLOAT;
EXEC GetAverageEmployeesPerRoom @AvgCount = @avg OUTPUT;
SELECT @avg AS AverageEmployeesPerRoom;


--Основная процедура — показывает комнаты,в которых сотрудников больше среднего

IF OBJECT_ID('GetRoomsAboveAverage', 'P') IS NOT NULL
    DROP PROCEDURE GetRoomsAboveAverage;
GO

CREATE PROCEDURE GetRoomsAboveAverage
AS
BEGIN
    DECLARE @avg FLOAT;

    EXEC GetAverageEmployeesPerRoom @AvgCount = @avg OUTPUT;

    SELECT 
        f.name AS Faculty,
        d.name AS Department,
        r.number AS RoomNumber,
        COUNT(er.employee_id) AS EmployeeCount
    FROM Room r
    LEFT JOIN Faculty f ON r.faculty_id = f.id
    LEFT JOIN Department d ON d.room_id = r.id  
    LEFT JOIN Employee_Room er ON er.room_id = r.id
    GROUP BY f.name, d.name, r.number
    HAVING COUNT(er.employee_id) > @avg;
END;
GO

EXEC GetRoomsAboveAverage;



```
<img src="https://github.com/ekatherina123/databases_Tyumeneva_PMI-32_10_var/blob/main/pictures/LAB4/4_1_4.png" alt="Схема 4.1.4" width="450">


