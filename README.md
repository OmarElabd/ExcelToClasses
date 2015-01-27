# ExcelToClasses
Generate c# classes from worksheet headers inside an excel workbook (.xls). Useful for data conversion projects.

#Usage:
Please modify ClassGenerator.tt with the file path to your excel file.

Modify this line:
List<string> filePaths = new List<string>{ @"(YOUR FILE PATH HERE).XLS" };

Add as many paths as you like with:
List<string> filePaths = new List<string>{ @"(YOUR FILE PATH HERE).XLS" };
filePaths.Add(@"(YOUR SECOND PATH HERE).XLS");

OR

List<string> filePaths = new List<string>{ @"(YOUR FILE PATH HERE).XLS", @"(YOUR SECOND PATH HERE).XLS" };
