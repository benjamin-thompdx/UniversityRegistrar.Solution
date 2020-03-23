# _To Do List_

#### _A C# MVC application to track students and courses._, _Mar. 23, 2020_

#### By _**Benjamin Thom, K. Wicz, Jonathan Carlos**_

## Description

_A program for a University registrar to keep track of students and courses._

## Project Specifications

| Behavior | Input | Output |
|---|:---:|:---:|
||||

## Setup/Installation Requirements

_In Terminal:_

* Navigate to where you want this application to be saved, i.e.:
```cd desktop```
* Clone the file from GitHub with HTTPS
```git clone https://github.com/benjamin-thompdx/WordCounter.Solution.git```
* Open file in your preferred text editor
* On Mac: ```open -a {your text editor} WordCounter.Solution```
* On Windows: ```WordCounter.Solution```

_Download Manually:_

* Navigate to https://github.com/benjamin-thompdx/WordCounter.Solution.
* Click the green "Clone or Download" button.
* Click "Download ZIP".
* Click downloaded file to unzip.
* Open folder called "WordCounter.Solution".

_Installing MySQL | MacOS:_

* Download the MySQL Community Server DMG File from [MySQL Community Server](https://dev.mysql.com/downloads/file/?id=484914)
* You can exit the mysql program by entering ```exit```.
* Download the MySQL Workbench DMG File from [MySQL Workbench](https://dev.mysql.com/downloads/file/?id=484391). (Use the No thanks, just start my download link.)
* Install MySQL Workbench to Applications folder.
* Open MySQL Workbench and select the ```Local instance 3306 server```. You will need to enter the password you set. (We used ```epicodus```.) If it connects, you're all set.

_Installing MySQL | Windows 10:_

* Download the MySQL Web Installer from [MySQL Downloads](https://dev.mysql.com/downloads/file/?id=484919) (Use the No thanks, just start my download link.)
* You can exit the mysql program by entering ```exit```
* Add the MySQL environment variable to the System PATH. We must include MySQL in the System Environment Path Variable. This is its own multi-step process. Instructions here are for Windows 10:
  1. Open the Control Panel and visit System > Advanced System Settings > Environment Variables...
  2. Then select PATH..., click Edit..., then Add.
  3. Add the exact location of your MySQL installation, and click OK. (This location is likely ```C:\Program Files\MySQL\MySQL Server 8.0\bin```, but may differ depending on your specific installation.)
* Open MySQL Workbench and select the ```Local instance 3306``` server (it may have a different name). You will need to enter the password you set (We used ```epicodus```). If it connects, you're all set.
 
 _MySQL Workbench Database Setup:_

  > CREATE DATABASE `to_do_list`;

  > USE `to_do_list`;
  
  > CREATE TABLE `categories` (`CategoryId` PRIMARY KEY, `Name` VARCHAR(255));

  > CREATE TABLE `items` (`ItemId` PRIMARY KEY, `Description` VARCHAR(255), `CategoryId` INT));

_Note For Editors:_ 

* Download the .NET Core SDK [Software Development Kit](https://dotnet.microsoft.com/download)
* Open the .Net Core SDK file and install
* To confirm installation was successful, run the ```$ dotnet --version``` command in your terminal
* Install dotnet script, run the ```$ dotnet tool install -g dotnet-script``` command in your terminal
* Restart your terminal to complete installation, and run the ```$ dotnet run``` command to run application within your terminal - Note: To exit, simply press ```Ctrl + C```
* Open project's productions directory within your terminal ```$ cd ToDoList.Solution/ToDoList```
* Run the command ```> dotnet restore```
* Run the command ```> dotnet build``` 
* If build is successful, run the command ```> dotnet run```, if build failed, make necessary updates and repeat ```> dotnet restore``` followed by ```> dotnet build```

## Known Bugs

_No known bugs at this time._

## Support and contact details

_Have a bug or an issue with this application? [Open a new issue](https://github.com/benjamin-thompdx/WordCounter.Solution/issues) here on GitHub._

## Technologies Used

* _Git 2.23.0_
* _C# language_
* _.NET Core 2.2.106_
* _dotnet script 0.50.1_
* _VS Code 1.43.1_
* _Model-View-Controller(MVC) framework_
* _Create, Read, Update, Delete (CRUD) functionality_
* _MySQL 8.0.15_
* _MySQL Workbench 8.0.15_
* _Entity Framework Core 2.2.4_
* _Language-Integrated Query (LINQ)_
* _ASP.NET Razor_

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2020 **_Benjamin Thom, K. Wicz, Jonathan Carlos_**