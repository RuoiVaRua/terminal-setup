### 1. ```$env:USERPROFILE``` tương ứng với ```C:\Users\username``` tùy theo từng máy
### 2. copy thư mục ```.config``` tới ```$env:USERPROFILE\.config``` (VD: ```C:\Users\username\.config```)
### 3. copy thư mục ```PowerShell``` tới ```$env:USERPROFILE\Documents\WindowsPowerShell```
### và ```$env:USERPROFILE\Documents\PowerShell```

### 4. mở lại terminal mà gặp lỗi thiếu thư viện nào thì cài thư viện đó bằng ```winget install <tên thư viện>```