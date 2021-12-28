# Домашнее задание к занятию "3.8. Компьютерные сети, лекция 3"

1. Подключитесь к публичному маршрутизатору в интернет. Найдите маршрут к вашему публичному IP
```
telnet route-views.routeviews.org
Username: rviews
show ip route x.x.x.x/32
show bgp x.x.x.x/32
```
![image](https://user-images.githubusercontent.com/60435210/147558911-ec072d81-c0bb-4541-b8dc-225f91845429.png)
![image](https://user-images.githubusercontent.com/60435210/147558945-001518f9-c363-4188-af52-5f3d6535d99a.png)

2. Создайте dummy0 интерфейс в Ubuntu. Добавьте несколько статических маршрутов. Проверьте таблицу маршрутизации. 
![image](https://user-images.githubusercontent.com/60435210/147559276-5c229d4a-ec58-4d7f-8843-009b49aeef8a.png)

3. Проверьте открытые TCP порты в Ubuntu, какие протоколы и приложения используют эти порты? Приведите несколько примеров.   
![image](https://user-images.githubusercontent.com/60435210/147559362-6c3ded8f-907d-43ca-af90-10eec1c24a67.png)


4. Проверьте используемые UDP сокеты в Ubuntu, какие протоколы и приложения используют эти порты?
![image](https://user-images.githubusercontent.com/60435210/147559440-205ce94b-ffaf-4e72-961e-0cb79c39cb17.png)


5. Используя diagrams.net, создайте L3 диаграмму вашей домашней сети или любой другой сети, с которой вы работали. 
![Untitled Diagram](https://user-images.githubusercontent.com/60435210/147560762-70cf9d78-bb37-44e4-bc62-23fd1629e899.jpg)
