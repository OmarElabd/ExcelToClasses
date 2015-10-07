# Excel To Classes
Generate C# classes from worksheet headers inside an excel workbook (.xls). Useful for data conversion projects.

#Get It Here
https://www.nuget.org/packages/ExcelToClasses/

#Usage:
Please modify ClassGenerator.tt with the file path to your excel file.

Modify this line:
```csharp
List<string> filePaths = new List<string>{ @"(YOUR FILE PATH HERE).XLS" };
```

Add as many paths as you like with:
```csharp
List<string> filePaths = new List<string>{ @"(YOUR FILE PATH HERE).XLS" };
filePaths.Add(@"(YOUR SECOND PATH HERE).XLS");
```

OR
```csharp
List<string> filePaths = new List<string>{ @"(YOUR FILE PATH HERE).XLS", @"(YOUR SECOND PATH HERE).XLS" };
````
