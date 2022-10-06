**1. СОДЕРЖАНИЕ**

1. СОДЕРЖАНИЕ

2. ОБЩЕЕ ПОЛОЖЕНИЯ
	
	2.1 Полное наименование приложения и ее условное обозначение

	2.2 Номер договора (контракта)	

	2.3 Наименования организации-заказчика и организаций-участников работ	

	2.4 Перечень документов, на основании которых создается приложение	

	2.5 Плановые сроки начала и окончания работы по созданию приложения	
	
	2.6 Источники и порядок финансирования работ	3
	
	2.7 Порядок оформления и предъявления заказчику результатов работ по созданию приложения	3

	2.8 Перечень нормативно-технических документов, методических материалов, использованных при разработке ТЗ	3

	2.9 Определения, обозначения и сокращения	4
	
3. НАЗНАЧЕНИЕ И ЦЕЛИ СОЗДАНИЯ ПРИЛОЖЕНИЯ	5
	
	3.1 Назначение приложения	5
	
	3.2 Цели создания приложения	5
	
4. ХАРАКТЕРИСТИКА ОБЪЕКТА АВТОМАТИЗАЦИИ	6

5. ТРЕБОВАНИЯ К ПРИЛОЖЕНИЮ	7
   
   	5.1 Требования к приложению в целом	7
      
	5.2 Требования к функциям (задачам), выполняемым приложением	11
6. СОСТАВ И СОДЕРЖАНИЕ РАБОТ ПО СОЗДАНИЮ (РАЗВИТИЮ) ПРИЛОЖЕНИЯ		12
7. ПОРЯДОК КОНТРОЛЯ И ПРИЕМКИ ПРИЛОЖЕНИЯ	13
	7.1 Виды, состав, объем и методы испытаний приложения	13
8. ИСТОЧНИКИ РАЗРАБОТКИ	14
ПРИЛОЖЕНИЕ А	15

---

**2. ОБЩЕЕ ПОЛОЖЕНИЯ**

**2.1 Полное наименование системы и ее условное обозначение**

Dream Car – (DC).

**2.2 Номер договора (контракта)**

123456789

**2.3 Наименования организации-заказчика и организаций-участников работ**

Организация исполнитель – “Onixoft”.

**2.4 Перечень документов, на основании которых создается приложение**

Лист технического задания.

**2.5 Плановые сроки начала и окончания работы по созданию приложения**

01.10.22 – 01.12.23

**2.6 Источники и порядок финансирования работ**

Источник финансирования: Заказчик
30% - после предоставления 50% проекта
40% - после предоставления 100% проекта 
30% - после полного срока поддержки проекта 

**2.7 Порядок оформления и предъявления заказчику результатов работ по созданию приложения**

Каждую неделю компания-исполнитель обязана присылать отчет о проделанных работах.

**2.8 Перечень нормативно-технических документов, методических материалов, использованных при разработке ТЗ**

Документация ЯП ABAP,
Cистема SAP. 

**2.9 Определения, обозначения и сокращения**

ЯП – язык программирования
___

**3. НАЗНАЧЕНИЕ И ЦЕЛИ СОЗДАНИЯ ПРИЛОЖЕНИЯ**

**3.1 Назначение приложения** 

Серверное приложение предназначена для учета транспортных средств, клиентов, а также заказов в компании, которая предоставляет автомобили в аренду.

**3.2Цели создания приложения**

Цель приложения - облегчить учет/анализ заказов на автомобили, облегчить контроль клиентов сервиса аренды автомобилей и облегчить контроль автомобилей в сервисе.

---

**4. ХАРАКТЕРИСТИКА ОБЪЕКТА АВТОМАТИЗАЦИИ**

Приложение обеспечивает контроль всех этапов сервиса аренды автомобилей.

---

**5. ТРЕБОВАНИЯ К ПРИЛОЖЕНИЮ**
   
**5.1 Требования к приложению в целом**

Приложение должно корректно давать возможность работать сотруднику компании в каждой ветви приложения. Необходимо, чтоб приложение было реализованно с функционалом (рис. 1).

![](Aspose.Words.e5024749-d19b-40fb-99e2-7ace5711bff3.001.png "Рисунок - 1")

Рисунок - 1

**5.1 Требования к структуре и функционированию приложения**

Приложение должно быть разработано таким образом, чтоб, при необходимости, была возможность масштабирования приложения.

Необходимо, чтоб был доступ к добавлению нового заказа на автомобиль. А также ссылка на добавления нового пользователя в систему(рис.2).

![](Aspose.Words.e5024749-d19b-40fb-99e2-7ace5711bff3.002.png "Рисунок - 2")

Рисунок - 2

Необходимо реализовать возможность редактировать выбранный заказ. А также ссылка на добавления нового пользователя в систему(рис. 3).

![](Aspose.Words.e5024749-d19b-40fb-99e2-7ace5711bff3.003.png "Рисунок - 3")

Рисунок - 3

Необходимо реализовать возможность удалять выбранный заказ(рис. 4).

![](Aspose.Words.e5024749-d19b-40fb-99e2-7ace5711bff3.004.png "Рисунок - 4")

Рисунок - 4

В случае, если пользователя ещё нет в системе, то необходимо предоставить возможность выполнять все те же операции, что и с заказами, но уже с клиентом сервиса аренды автомобилей(рис.5).

![](Aspose.Words.e5024749-d19b-40fb-99e2-7ace5711bff3.005.png "Рисунок - 5")

Рисунок - 5

Необходимо реализовать возможность добавления в систему сервиса аренды автомобилей новый автомобиль, который недавно появился в сервисе(рис.6).

![](Aspose.Words.e5024749-d19b-40fb-99e2-7ace5711bff3.006.png "Рисунок - 6")

Рисунок - 6

Необходимо реализовать возможность просмотра всех заказов на автомобиль, а также реализовать ссылку на создания нового заказа(рис. 7).

![](Aspose.Words.e5024749-d19b-40fb-99e2-7ace5711bff3.007.png "Рисунок - 7")

Рисунок - 7

**5.2 Требования к надежности**

Система должна производить проверки на корректность ввода пользователем данных. В случае, если при каких либо обстоятельствах пользователь ввел некорректные данные, то необходимо, чтоб приложение сообщило об этом.

**5.3 Требования к безопасности**

Система нуждается в высокой степени защиты, т.к. приложение работает с персональными данными пользователей.

**5.4 Требования к эргономике и технической эстетике**

Данный программный продукт должен быть реализован так же, как и на рисунках 1 - 7.

**5.5 Требования к защите информации от несанкционированного доступа**

Приложение нуждается в защите информации. Чтоб защитить информации необходимо реализовать возможность аутентификации пользователя.

**5.6 Требования по сохранности информации при авариях**

Программный продукт относиться к серверным приложениям. В случае какой либо аварии у пользователя, все данные автоматически должны отправится на сервер.

**5.7	  Требования к функциям (задачам), выполняемым приложением**

При запуске программы система должна предоставить доступ пользователю к клавишам, необходимым для работы программы.

---

**6. СОСТАВ И СОДЕРЖАНИЕ РАБОТ ПО СОЗДАНИЮ (РАЗВИТИЮ) ПРИЛОЖЕНИЯ**

01.10.22 – 01.11.22 – разработка прототипа системы

01.11.22 – 10.11.22 – доработка основных функций приложения

10.11.22 – 20.11.22 – написание гайда и документации по использованию приложения

20.11.22 – 01.12.22 - тестирование

01.12.22 – 01.12.23 - техническая поддержка проекта

---

**7. ПОРЯДОК КОНТРОЛЯ И ПРИЕМКИ СИСТЕМЫ**

**7.1. Виды, состав, объем и методы испытаний приложения**

Необходимо испытать программное обеспечение в условиях штатного режима функционирования. Сроки проведения проведения тестирования обозначены в пункте 6. В случае положительного результата тестирования клиентом, проект переходит в стадию тех. поддержки. Статус приемочной комиссии - государственная.

---

**8. ИСТОЧНИКИ РАЗРАБОТКИ**
1. <https://westgroup.by/>
1. <https://www.sap.com/cis/index.html?url_id=auto_hp_redirect_cis>
1. https://help.sap.com/docs/.

---

**ПРИЛОЖЕНИЕ А**

**Название приложения**

---

СОСТАВИЛИ 

|Наименование организации, предприятия|Должность исполнителя|Фамилия имя, отчество|Подпись|Дата|
| :- | :- | :- | :- | :- |
| | | | | |

СОГЛАСОВАНО 

|Наименование организации, предприятия|Должность исполнителя|Фамилия имя, отчество|Подпись|Дата|
| :- | :- | :- | :- | :- |
| | | | | |





