### 1. see where `node` resides:  
```bash
where node
# this works only if you already gave the path, since you dont know yet skip this command  
```  
this will search for gcc executable  
```bash
dir C:\ /s /b | findstr node.exe
```  
#### Output:  
```vbnet
C:\Users\RaSkull>dir C:\ /s /b | findstr node.exe
C:\DevLangs\nodejs\node.exe
```  
so `C:\DevLangs\nodejs\` is our path URL  


### 2. Apply path:  
Press `Win + R`, type `sysdm.cpl`, and hit Enter. 
Go to `Advance` tab.  
choose `user` for personal & `system` for everyone  
& apply path from there.  

### 3. verify the changes:
first Restart the machine & then  
```bash
where node
```    
```bash
node --version
```   