# Eau Claire's Salon
### An independent project for Epicodus

### By Theron Packus

## Technologies Used

* Git
* C#
* .NET 5.0
* ASP.NET Core
* Entity Framework Core
* Razor View Engine
* MVC
* RESTful Routing, CRUD & HTTP
* REPL
* MySQL MySQL Workbench
* Bootstrap

## Description

This C# MVC web application was built to help Claire manage the stylists and clients at her salon. The application will allow her to add stylists and their associated clients to a database. Then view the clients for each of her stylists on separate organized pages.

## Diagram of the One-To-Many relationship used in this project's database

![Image of one to many relationship between stylists and clients it the SQL Designer](./HairSalon/wwwroot/img/sql_design.png)


## Setup/Installation Requirements

* _Requires Visual Studio Code Installation_
* _Requires Terminal Installation_
* _Open the terminal on your local machine_
* _Navigate to the directory inside of which you wish to house this project_
* _Clone this project with the following command  `$ git clone <https://github.com/tlpackus/HairSalon.Solution.git>`_
* _Next you will need to download and install .NET Core through this link if you don't already have it: https://dotnet.microsoft.com/download_
* _After downloading and installing .NET Core, return to your terminal and navigate to the root directory by entering `$ cd HairSalon.Solution`_
* _Open this project in Visual Studio Code with the command `$ code .`_
* _Still in the terminal, navigate to the desired subdirectory of the repository with the command `$ cd HairSalon`_
* _Retrieve and install packages listed in the .csproj files with the command `$ dotnet restore`_
* _Create internal content for build with the command `$ dotnet build`_

**Instructions for re-creating the MySQL Database using `HairSalon\theron_packus.sql`**
* Open MySQL Workbench (If you don't already have it, it can be downloaded here: https://dev.mysql.com/downloads/file/?id=484391)
* In MySQL Workbench, navigate to the _Administration_ window and click _Data Import/Restore_
* In the _Data Import_ screen, select _Import from Self-Contained File_, click the 3 dots on the right, and navigate to _HairSalon.Solution\theron_packus.sql_
* Under _Default Scheme to be Import To_ select the _New_ button
  * Enter a name for your database (e.g. hair_salon_database_test)
  * Click _Ok_
* Click _Start Import_
* In the _Navigator_ > _Schemas_ tab, right click and select _Refresh All_. The new database will appear.

* _Back in Terminal, you should still be in the `HairSalon` directory. From that directory run command `$ touch appsettings.json` to create a new file._
* _Lastly, input the following script (**note the name of the database below needs to match the name of the database you created (e.g. hair_salon_database_test)**)_
![Image of appsettings.json example](./HairSalon/wwwroot/img/appsettings.json_example.png)
* _You can now run $ dotnet run from the HairSalon Directory to launch, view and use the app in the google browser_


## Known Bugs

- No known bugs so please lets me know if you encounter any through the email I provided below.

## License

[MIT](LICENSE.txt)

Copyright © 2021 Theron Packus

All Rights Reserved

## Support and Contact Information

For contact support or any found bugs, please email me here <a href = "mailto: tlpackus@gamil.com">Send Email</a>