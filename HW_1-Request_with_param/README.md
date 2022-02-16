# Jmeter

Jmeter - HW_1  
Сделать сценарий с перечисленными эндпоинтами  

Дать нагрузку на 50, 250, 500 потоков.  
Результаты прогонов ввгрузить в CSV, на заняти посмотрим что и как.  
Настройки Jmeter, файл .jmx выгружаем на гит.  
#  
### Настройки тест-плана Jmeter [HW_1_Jmeter_Test_Plan.jmx](https://github.com/Pavlik1100/Jmeter/blob/main/HW_1-Request_with_param/HW_1_Jmeter_Test_Plan.jmx)
### таблица-отчет 200 потоков [HW_1_Summary_200x15m.csv](https://github.com/Pavlik1100/Jmeter/blob/main/HW_1-Request_with_param/HW_1_Summary_200x15m.csv)  
### таблица-отчет 500 потоков [HW_1_Summary_500x15m.csv](https://github.com/Pavlik1100/Jmeter/blob/main/HW_1-Request_with_param/HW_1_Summary_500x15m.csv)  
### таблица-отчет 50 потоков [HW_1_Summary_50x15m.csv](https://github.com/Pavlik1100/Jmeter/blob/main/HW_1-Request_with_param/HW_1_Summary_50x15m.csv)  
#
  
http://162.55.220.72:5005  

1) http://162.55.220.72:5005/get_method  
req.  
GET  
name: str  
age: int  
  
  
2) http://162.55.220.72:5005/user_info_2  
req.  
POST  
name: str  
age: int  
salary: int  
  
  
3) http://162.55.220.72:5005/user_info_3  
req.  
POST  
name: str  
age: int  
salary: int  
  
4) http://162.55.220.72:5005/object_info_1  
req.  
GET  
name: str  
age: int  
weight: int  
  
5) http://162.55.220.72:5005/object_info_2  
req.  
GET  
name: str  
age: int  
salary: int  
  
6) http://162.55.220.72:5005/object_info_3  
req.  
GET  
name: str  
age: int  
salary: int  
  
7) http://162.55.220.72:5005/object_info_4  
req.  
GET  
name: str  
age: int  
salary: int  
