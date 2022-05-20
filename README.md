<h1 align="center">Привет! Меня зовут <a href="https://t.me/qmboc" target="_blank">Роман</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">C# backend developer 🇷🇺</h3>

![codewars](https://www.codewars.com/users/AzarovRoman/badges/micro)

<h2 align="left">Языки</h2>

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)

<h2 align="left">Интсрументы</h2>

![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Sever-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)
---

![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=AzarovRoman&theme=solarized_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=AzarovRoman&theme=solarized_dark)
---

<h3 align="center">Серьезное изучение C# началось в ноябре 2021 когда я пошел на курсы.</h3>

-Первый интересный самостоятельный проект - рукописные связные и двусвязные списки: цель - научиться работать с ссылками в C#
https://github.com/AzarovRoman/ArrayList/tree/main/ArrayList/LinkList  
https://github.com/AzarovRoman/ArrayList/tree/main/ArrayList/DoubleLinkedList

-Затем было два проекта в разных командах (4 и 6 человек)
1) Семейны десктопный финансовый трекер(не было базы данных, все данные писались в json и десериализовались при старте программы)
цель - познакомиться с WPF и работой в команде
https://github.com/AzarovRoman/FinTracker/tree/main

2) Десктопная CRM-система. Впервые использовали БД, общались с ней при помощи Dapper и хранимых процедур
цель - научиться работать с БД
https://github.com/AzarovRoman/CustomerAnalyticSystem/tree/master

На этом базовый трехмесячный курс закончился. Попутно с проектами мы ознакомились с примитивными юнит-тестами и Mock, несколькими паттернами проектирование (и даже применяли их)

<h3 align="center">После пройденного собеседования я попал на углубленный курс Backend-разработки на C#</h3>

На спец курсе мы реализуем два проекта (так же в разных командах). Оба с применением практики разделения ответственности (DAL, BLL, API)

1) Бэкенд для сайта школы Софт-скиллов. В проекте впервые используется Entity Framework Core с подходом Code-First, хэширование паролей, знакомство с технологией MiddleWare, DataAnnotation, аутентификация и авторизация пользователей, Dependency-Injection, Extension methods.
цель - познакомиться с ASP.Net, EF Core, REST и вышеперечисленными технологиями  
https://github.com/hekkaaa/Bear-goodbye-kolkhoz/tree/main

2) Всей группе был дан проект на микросервисной архитектуре - площадка для торговли валютами. Я с напарником делал репортинг-сервис.
Основной задачей нашего сервиса являлось хранение и максимально быстрая выдача данных потребителям (другим сервисам, аналитикам), при этом скорость записи данных в БД не важна. Работа с БД осуществлялась при помощи Dapper и хранимых процедур. Данные в бд заполнялись программно (~4 000 000 клиентов, ~10 000 000 счетов и ~20 000 000 транзакций). Высокая скорость выдачи данных достигается за счет оптимизации sql-запросов и использованию некластеризованных индексов в sql.

Данные от других сервисов мы получали из очередей RabbitMq, в качестве провайдера использовался MassTransit  
https://github.com/NikPletnev/MarvelousReportMicroService
