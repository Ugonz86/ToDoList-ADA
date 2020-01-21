# TO DO LIST 

####  C# and .NET Advanced Databases and Authentication - _01/21/2020_

#### _By **Uriel Gonzalez**_

## Description

DETAILED DESCRIPTION

### Specs
| Spec | Input | Output |
| :-------------     | :------------- | :------------- |
| **BEHAVIOR** | INPUT | OUTPUT |

## Setup/Installation Requirements

1. Clone this repository:
    ```
    $ git clone REPO URL HERE
    ```
2. Run the application
    ```
    $ dotnet run
    ```
## Database Setup

```sh
1. mysql start
2. Access MySql by executing the command: `mysql -uroot -pepicodus`
3. CREATE DATABASE `to_do_list`
4. USE `to_do_list`
5. CREATE TABLE `Categories` (`CategoryId` int(11) NOT NULL AUTO_INCREMENT, `Name` varchar(255) DEFAULT NULL, PRIMARY KEY (`CategoryId`))
6. CREATE TABLE `Items` (`ItemId` int(11) NOT NULL AUTO_INCREMENT, `Description` varchar(255), `UserId` int(11), PRIMARY KEY (`ItemId`))
7. CREATE TABLE `CategoryItem` (`CategoryItemId` int(11) NOT NULL AUTO_INCREMENT, `ItemId` int(11) NOT NULL, `CategoryId` int(11) NOT NULL, PRIMARY KEY (`CategoryItemId`))
8. Run program with dotnet run (or $ dotnet watch run).

```
OR
* > dotnet restore, dotnet ef migrations add addIdentity, dotnet ef migrations add Authorization, dotnet ef database update

## Known Bugs
* No known bugs at this time.

## Technologies Used
* C# / .NET

## Support and contact details

_Please contact Uriel Gonzalez with questions and comments._

### License

*GNU GPLv3*

Copyright (c) 2019 **_Uriel Gonzalez_**
