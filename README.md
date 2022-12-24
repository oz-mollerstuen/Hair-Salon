# _Clair's Salon_

#### By _**Lucas Mollerstuen**_

#### _Barber/salon Website_

## Technologies Used

* _C#_
* _.NET_
* _HTML_
* _CSS_
* _MySQL_
* _Entity_

## Description

_Website to track and change employees and customers for the salon._

## Setup/Installation Requirements

* _Open up your terminal and navigate to the project folder_
* _In terminal enter, ' "git clone https://github.com/oz-mollerstuen/Hair-Salon '_
* _In terminal enter 'code .' to open files in Visual Studio Code_
* _In VS Code terminal navigate to the HairSalon directory (file path ex. user/desktop/epicodus/projects/HairSalon.Solution/HairSalon)_
* _Configure files with '$ dotnet add package Microsoft.EntityFrameworkCore -v 6.0.0' & '$ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 6.0.0-alpha.2'_
* _Run '$ dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 6.0.0' to install Lazy Loading_
* _Run '$ dotnet restore'_
* _Create 'appsettings.json' file_
* _Enter the following into the file:_

{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=lucas_mollerstuen;uid=root;pwd=YOUR_PASSWORD;"
  }
}
```
* _To setup the database you open up MySQL and under 'Administration' select 'Data Import'_
* _Check the 'Import from self contained file' option and enter the file path of the Database within HairSalon, then start Import_
* _Enter '$ dotnet run to start program'_

## Known Bugs

* None found. If issues arise please contact mollerstuen.works@gmail.com

## License

_[MIT](https://en.wikipedia.org/wiki/MIT_License)_

Copyright (c) _2022_ _Lucas Mollerstuen_
