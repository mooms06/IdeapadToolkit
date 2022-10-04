# Ideapad Toolkit

**Ideapad Toolkit is a utility that allows you adjust the power setting from Lenovo Vantage, without having to use the slow official app**

![image](https://user-images.githubusercontent.com/62750643/193938239-28a0c725-29a0-494e-95ca-91908fd84f9f.png)


**Power profiles can be quickly adjusted from the tray icon**

![image](https://user-images.githubusercontent.com/62750643/193938407-4f96a444-4c29-44be-90e0-f6c4e182dbce.png)

## Supported laptops
- Lenovo Flex 5 14ALC05 (Windows 11)

If your model is similar enough, chances are it will work.

To test, try changing the settings and verify the changes in Lenovo Vantage

## Prerequisites
- Administrator Priviledges
  - The app needs to run as admin to support the Flip to Boot feature. See Services/UEFISettingsService.cs

- [.NET 6 Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.9-windows-x64-installer)

- [Lenovo Intelligent Thermal Solution Driver](https://www.google.com/search?q=lenovo+<YOUR+MODEL>+intelligent+thermal+solution+driver+download)

- PowerBattery.dll
  - This dll needs to be placed in the same directory as the executable
  
### How to get PowerBattery.dll
 1. Install Lenovo Vantage from the Microsoft Store
 2. Copy it from C:\ProgramData\Lenovo\Vantage\Addins\IdeaNotebookAddin\ to the Ideapad Toolkit directory
 3. Lenovo Vantage can now be uninstalled
