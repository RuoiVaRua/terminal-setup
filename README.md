### 1. $env:USERPROFILE corresponds to C:\Users\username depending on each machine
### 2. Copy the .config folder to $env:USERPROFILE\.config (eg: C:\Users\username\.config)
### 3. Copy the PowerShell folder to $env:USERPROFILE\Documents\WindowsPowerShell
### and $env:USERPROFILE\Documents\PowerShell
### 4. Reopen the terminal and if you get an error about missing a library, install that library using winget install <library name>

### 1. ```$env:USERPROFILE``` tương ứng với ```C:\Users\username``` tùy theo từng máy
### 2. copy thư mục ```.config``` tới ```$env:USERPROFILE\.config``` (VD: ```C:\Users\username\.config```)
### 3. copy thư mục ```PowerShell``` tới ```$env:USERPROFILE\Documents\WindowsPowerShell```
### và ```$env:USERPROFILE\Documents\PowerShell```
### 4. mở lại terminal mà gặp lỗi thiếu thư viện nào thì cài thư viện đó bằng ```winget install <tên thư viện>```
