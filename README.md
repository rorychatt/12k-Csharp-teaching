`dotnet new gitignore`

-- создаст темплейт для игнора компилированных файлов

`dotnet new solution`

-- создаст пустой проект

`dotnet new classlib -o Calculator.Business`

-- создаст класс библиотек для калькулятора

`dotnet add reference ./Calculator.Business/Calculator.Business.csproj`

-- Добавляет ссылку на класс библиотек в проект

`dotnet new console -o Calculator.Console`

-- Создает приложение под консоль

`dotnet add reference ./Calculator.Console/Calculator.Console.csproj`

-- Добавляет ссылку на консольное приложение в проект

`dotnet add ./Calculator.Business/Calculator.Business.csproj reference ./Calculator.Console/Calculator.Console.csproj`

-- Добавляет ссылку на логику калькулятора в консольное приложение