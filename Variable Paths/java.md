### 1. see where `java` resides:  
```bash
where java
# this works only if you already gave the path, since you dont know yet skip this command  
```  
this will search for gcc executable  
```bash
dir C:\ /s /b | findstr node.exe
```  
#### Output:  
```vbnet
C:\DevLangs\Java\bin\java.exe
C:\Program Files\Common Files\Oracle\Java\javapath\java.exe
C:\Program Files\Common Files\Oracle\Java\javapath_target_337406\java.exe
C:\Users\RaSkull\.vscode\extensions\georgewfraser.vscode-javac-0.2.46\dist\windows\bin\java.exe
C:\Users\RaSkull\.vscode\extensions\redhat.java-1.36.0-win32-x64\jre\17.0.13-win32-x86_64\bin\java.exe

C:\Users\RaSkull>
```  
so `C:\DevLangs\Java\bin\` is our path URL  


### 2. Apply path:  
Press `Win + R`, type `sysdm.cpl`, and hit Enter. 
Go to `Advance` tab.  
choose `user` for personal & `system` for everyone  
& apply path from there.  


### 3. verify the changes:
first Restart the machine & then  
```bash
where java
```    
```bash
java --version
```    