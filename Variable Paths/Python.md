### 1. see where `python` resides:  
```bash
where python
```  
#### Output:  
```bash
C:\Users\RaSkull>where python
C:\Users\RaSkull\AppData\Local\Microsoft\WindowsApps\python.exe
# windows Alias Stub Path Default Placeholder 
```  
- this indicates the python is installed by microsoft windows  
while installing python we might gave it a custome path, if you know the path copy that path, in my case i know the path which is  
```
C:\DevLangs\Python
```  
### 2. Apply path:  
Press `Win + R`, type `sysdm.cpl`, and hit Enter. 
Go to `Advance` tab.  
choose `user` for personal & `system` for everyone  
& apply path from there.  

### 3. verify the changes:
first Restart the machine & then  
```bash
where python
```    
```bash
python --version
```   