# command-vsCode-dotNet
     
# dotne new sln - add new solution
     
 # dotnet sln add (path csproj)- include .csproj references
       Ex: C:\CursoBalta\PaymentContext> dotnet sln add .\PaymentContext.Tests\PaymentContext.Tests.csproj 
       
 # dotnet new classlib - create a class library
     
 # dotenet restore - restore all packages
       Result:dotnet restore
       Restauração concluída em 23,31 ms para C:\CursoBalta\PaymentContext\PaymentContext.Domain\PaymentContext.Domain.csproj.
       Restauração concluída em 23,32 ms para C:\CursoBalta\PaymentContext\PaymentContext.Shared\PaymentContext.Shared.csproj.
       Restauração concluída em 13,31 ms para C:\CursoBalta\PaymentContext\PaymentContext.Tests\PaymentContext.Tests.csproj.
     
 # dotenet build - build all projects
       Result: C:\CursoBalta\PaymentContext> dotnet build
         Microsoft(R) Build Engine versão 16.3.0+0f4c62fea para .NET Core 
         Copyright (C) Microsoft Corporation. Todos os direitos reservados.

         Restauração concluída em 22,34 ms para C:\CursoBalta\PaymentContext\PaymentContext.Domain\PaymentContext.Domain.csproj.
         Restauração concluída em 22,31 ms para C:\CursoBalta\PaymentContext\PaymentContext.Shared\PaymentContext.Shared.csproj.
         Restauração concluída em 45,04 ms para C:\CursoBalta\PaymentContext\PaymentContext.Tests\PaymentContext.Tests.csproj.
         PaymentContext.Shared -> C:\CursoBalta\PaymentContext\PaymentContext.Shared\bin\Debug\netstandard2.0\PaymentContext.Shared.dll
         PaymentContext.Domain -> C:\CursoBalta\PaymentContext\PaymentContext.Domain\bin\Debug\netstandard2.0\PaymentContext.Domain.dll
         PaymentContext.Tests -> C:\CursoBalta\PaymentContext\PaymentContext.Tests\bin\Debug\netcoreapp3.0\PaymentContext.Tests.dll

         Compilação com êxito.
              0 Aviso(s)
               0 Erro(s)

         Tempo Decorrido 00:00:11.10
