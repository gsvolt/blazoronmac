## blazoronmac

a simple repo to track steps, techniques, etc. to get developing with blazor on mac

### Steps

- Install VS Code
- Install razor+ extension. Ref [3]
- Install [.NET Core SDK](https://www.microsoft.com/net/core)
    Basically download a .dmg and run it on your system
- Open a terminal and type 
1. dotnet new --install "Microsoft.AspNetCore.Blazor.Templates"
2. mkdir microsoft
3. dotnet new blazor
4. dotnet run


```
Run into this error:
dotnet run
myApp/Program.cs(7,21): error CS0017: Program has more than one entry point defined. Compile with /main to specify the type that contains the entry point. [/Users/gsvolt/microsoft/microsoft.csproj]

The build failed. Please fix the build errors and run again.
```



### References

1. [.NET Core SDK](https://www.microsoft.com/net/core)
2. [dotnet templates](https://dotnetnew.azurewebsites.net/Search/blazor)
3. [razor+ vscode extension](https://marketplace.visualstudio.com/items?itemName=austincummings.razor-plus)
