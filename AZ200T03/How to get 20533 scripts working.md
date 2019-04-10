# Как заставить работать срипты курса 20533

Все очень просто:
1. скачиваем [содержимое соответствующего репозитория](https://github.com/MicrosoftLearning/20533-ImplementingMicrosoftAzureInfrastructureSolutions/archive/master.zip) 
2. распаковываем все, что есть в этом архиве в папке *AllFiles* на диск *F* в папку *20533*
3. запускаем **PowerShell ISE** и в области редактирования скрипта набираем следующее:
```powershell
    #Save the current value in the $p variable.
    $p = [Environment]::GetEnvironmentVariable("PSModulePath")

    #Add the new path to the $p variable. Begin with a semi-colon separator.
    $p += ";F:\20533\Modules\"

    #Add the paths in $p to the PSModulePath value.
    [Environment]::SetEnvironmentVariable("PSModulePath",$p)
```
4. сохраняем скрипт в произвольном месте и под произвольным названием, *запускаем его*
5. теперь в области консоли пишем и выполняем такую команду:
```powershell
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```
6. готово! Можно пользоваться:
```powershell
   Add-20533EEnvironment 
``` 
IntelliSense работает, вам все подскажут. Но если не получается - возможно, придется написать: 
```powershell 
   Import-Module Add-20533EEnvironment
```
