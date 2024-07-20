`dotnet new gitignore`

-- создаст темплейт для игнора компилированных файлов

`dotnet new solution`

-- создаст пустой проект

`dotnet new classlib -o Calculator.Business`

-- создаст класс библиотек для калькулятора

`dotnet add reference ./Calculator.Business/Calculator.Business.csproj`

-- Добавляет ссылку на класс библиотек в проект