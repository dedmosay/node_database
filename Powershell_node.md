Windows 

1. Создать директорию C:\Users\Oleg\Documents\WindowsPowerShell

2. Создать файл profile.ps1

3. Добавить в файл

          $env:Path += ";C:\Program Files\nodejs\"


Вы также можете постоянно изменять пользовательские/системные переменные среды 
(т.е. они будут постоянными при перезапуске оболочки) следующим образом:

```ps
          [Environment]::SetEnvironmentVariable
               ("Path", $env:Path, [System.EnvironmentVariableTarget]::Machine)


          [Environment]::SetEnvironmentVariable
               ("INCLUDE", $env:INCLUDE, [System.EnvironmentVariableTarget]::User)

          [Environment]::SetEnvironmentVariable(
              "Path",
              [Environment]::GetEnvironmentVariable("Path", [EnvironmentVariableTarget]::Machine) + ";C:\bin",
              [EnvironmentVariableTarget]::Machine)
```
