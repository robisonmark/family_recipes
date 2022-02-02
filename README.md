# Family Recipes

## Introduction
Many families share recipes but as time gets shorter and distance travelled gets longer it becomes harder to share and keep family recipes.
The `Family Recipes` Project is a C#/Dotnet Core API being displayed by a VueJs front end for the intent of creating a family recipe book to keep recipes and standard location, categorize them, and make them available to your family. This app will allow you to create new recipes, make notations to old recipes, upload pictures of the process (and end result), and keep the secerts within the family ;-). You can even list the ingredients you have availble to figure out what you can make.

## Repo Contents
    1. Dockerfile
    2. RecipeBook
        - The API is a ServiceStack (.Net Core) API user to deliever the recipes to the front end.
    3. RecipeCards - VueJS UI
        - Stardard VueJS front end using NPM and authenticated via <figureout>
    4. Recipes - Database
        - The database is a standard SQL database.

## Up and Running
#### Pre-Reqs - .Net, NodeJs, and NPM install on local machine
### To Do: Once Dev env is running fill this in

### To_Do
1. Create Docker Install to run all 3 pieces
    - Debugging C# Project
2. Create Database - Recipe DB
    - SQL/Postgres
        - <https://docs.microsoft.com/en-us/troubleshoot/developer/visualstudio/csharp/language-compilers/create-sql-server-database-programmatically>
        - <https://docs.microsoft.com/en-us/visualstudio/data-tools/create-a-sql-database-by-using-a-designer?view=vs-2022>
    - Elasticsearch
    - Search Pattern
    - Catagories
3. Create C#/Dotnet API - Recipe API
    - ServiceStack
        - <https://docs.servicestack.net/create-your-first-webservice>

    - Explore Linting
        - <https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/code-style-rule-options>
        - <https://docs.microsoft.com/en-us/visualstudio/ide/create-portable-custom-editor-options?view=vs-2022>
        - <https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/overview#code-style-analysis>

    - Explore patterns:
        - Factory
        - Akka.net (Actor) <https://petabridge.com/bootcamp/>
4. Create VueJS UI
    - New 2021/22 Features
        - <https://v3.vuejs.org/guide/installation.html#release-notes>

    - Typescript
    - React for fun


## Feedback

Contact <robisonmark@comcast.net>

## License

This product is being developed by <\Robros Tech> in conjuction with @mjrobison.
