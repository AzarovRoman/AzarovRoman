<h1 align="center">Hi all! My name is <a href="https://t.me/qmboc" target="_blank">Roma</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">C# backend developer 🇷🇺</h3>

![codewars](https://www.codewars.com/users/AzarovRoman/badges/micro)

<h2 align="left">programming languages</h2>

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)

<h2 align="left">Tools</h2>

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

<h3 align="center"Serious study of C# began in November 2021 when I took courses.</h3>

-The first interesting independent project - handwritten linked and doubly linked lists: the goal is to learn how to work with links in C # 
https://github.com/AzarovRoman/ArrayList/tree/main/ArrayList/LinkList  
https://github.com/AzarovRoman/ArrayList/tree/main/ArrayList/DoubleLinkedList

-Then there were two projects in different teams (4 and 6 people)
1) Family desktop financial tracker (there was no database, all data was written in json and deserialized at the start of the program)
the goal is to get acquainted with WPF and work in a team 
https://github.com/AzarovRoman/FinTracker/tree/main

2) Desktop CRM system. We used the database for the first time, communicated with it using Dapper and stored procedures, the goal is to learn how to work with the database
https://github.com/AzarovRoman/CustomerAnalyticSystem/tree/master

This is the end of the basic three-month course. Along the way with projects, we got acquainted with primitive unit tests and Mock, several design patterns (and even applied them)

<h3 align="center">After the interview, I got into an in-depth course in Backend development in C#</h3>

On a special course, we implement two projects (also in different teams). Both using separation of concerns (DAL, BLL, API) 

1) Backend for the site of the school of soft-skills. The project is the first to use Entity Framework Core with Code-First approach, password hashing, familiarity with MiddleWare technology, DataAnnotation, user authentication and authorization, Dependency-Injection, Extension methods. goal is to get familiar with ASP.Net, EF Core, REST and the above technologies
https://github.com/hekkaaa/Bear-goodbye-kolkhoz/tree/main

2) The whole group was given a project on a microservice architecture - a platform for trading currencies. My partner and I did a reporting service. The main task of our service was to store and provide data to consumers (other services, analysts) as quickly as possible, while the speed of writing data to the database is not important. Working with the database was carried out using Dapper and stored procedures. The data in the database was filled programmatically (~4,000,000 clients, ~10,000,000 accounts and ~20,000,000 transactions). High data output speed is achieved by optimizing sql queries and using non-clustered indexes in sql.

We received data from other services from RabbitMq queues, MassTransit was used as a provider
https://github.com/NikPletnev/MarvelousReportMicroService
