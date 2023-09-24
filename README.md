# DotNet Lab
    Welcome to .Net repo, this is where all the labs related to .NET development will be posted.

#Lab 1: Instruction
    Setup Environment
    • Open the integrated terminal.
    • Change directories (cd) to the folder that will contain the project folder.
    • Run the following commands:

    .NET Core CLI
    dotnet new webapi -o TodoApi
    cd TodoAp       i
    dotnet add package Microsoft.EntityFrameworkCore.SqlServer
    dotnet add package Microsoft.EntityFrameworkCore.InMemory
    code -r ../TodoApi
    • When a dialog box asks if you want to add required assets to the project,
    select Yes.

The preceding commands:
    o Creates a new web API project and opens it in Visual Studio Code.
    o Adds the NuGet packages which are required in the next section.

    #Running the project:s
        - dotnet build
        - dotnet run
    
    Output:
        https://web.postman.co/workspace/My-Workspace~40e55e14-633b-4648-855e-b26a2553d473/request/29985538-88c46e96-cf61-45b6-9bbb-5b462ee1ef39
    


