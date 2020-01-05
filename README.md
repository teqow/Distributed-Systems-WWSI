# Distributed-Systems-WWSI

## Description:
In project we focus on Azure Cloud - we use:
* Azure App Service
* Azure SQL Database
* Azure Blob Storage 
* Azure Queue Storage

* .NET Core 2.2, EF Core 3.1
* PowerBI 

## Project MVP:
Two services, first one MVC application based on azure app service - backend in .NET Core. Application is integrated with https://openweathermap.org/api, where we have storage all countries by iso and one more storage - azure sql database, where we have storage cities. Cities and countries is for autocomplete users input(requirement of project, for fetching data from two storages). When user pick country and city(please wait for autocomplete), we additionally send this data to the azure queue stoarage. Second service, counsme the message from queue, and add this data to the azue sql database. The data are necessary for generating Power BI reports about searching countries, cities weather.

## http://przetwarzanierozproszoneprojekt1.azurewebsites.net/

## PowerBi reports, and structure of databases:
![79497579_1039594599725312_4242221970868928512_n](https://user-images.githubusercontent.com/36841282/71779931-04da6480-2fbc-11ea-9771-42d2b64a58c6.png)

![81248322_813445999078613_6197476678134923264_n](https://user-images.githubusercontent.com/36841282/71779935-1885cb00-2fbc-11ea-91c5-39f34075d98a.png)

![81445043_619661498862682_9055699425606762496_n](https://user-images.githubusercontent.com/36841282/71779941-35ba9980-2fbc-11ea-9ad8-ee7dd6c15d9f.png)

![81901797_2759258034117111_5365350258006032384_n](https://user-images.githubusercontent.com/36841282/71779952-5256d180-2fbc-11ea-8582-604964fe8523.png)
