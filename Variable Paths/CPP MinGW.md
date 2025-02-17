### 1. see where `gcc` resides:  
```bash
where gcc
# this works only if you already gave the path, since you dont know yet skip this command  
```  
this will search for gcc executable  
```bash
dir C:\ /s /b | findstr gcc.exe
```  
#### Output:  
```vbnet
C:\DevLangs\MinGW\bin\gcc.exe
C:\DevLangs\MinGW\bin\mingw32-gcc.exe
```  
so `C:\DevLangs\MinGW\bin\` is our path URL  


### 2. Apply path:  
Press `Win + R`, type `sysdm.cpl`, and hit Enter. 
Go to `Advance` tab.  
choose `user` for personal & `system` for everyone  
& apply path from there.  

### 3. verify the changes:
first Restart the machine & then  
```bash
where gcc
```    
```bash
gcc --version
```    