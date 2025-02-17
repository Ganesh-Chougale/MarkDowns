```cmd
dir C:\ /s /b | findstr <somehing>
```  
### **E.g:**  
```bash
dir C:\ /s /b | findstr node.exe
dir C:\ /s /b | findstr node.exe
```

---

### **1. `dir C:\ /s /b`**  
This part lists all files and directories under `C:\` using these flags:  

- **`dir`** → Lists files and directories.  
- **`C:\`** → Searches the entire `C:` drive.  
- **`/s`** → Searches **all subdirectories** recursively.  
- **`/b`** → Uses **bare format**, meaning it **only shows full file paths** (without extra details like file sizes or headers).  

🔹 **Example Output (without filtering)**  
```plaintext
C:\Program Files\nodejs\node.exe
C:\Users\YourUser\AppData\Roaming\npm\node.exe
C:\SomeOtherFolder\node.exe
```

---

### **2. `|` (Pipe Operator)**  
The `|` (pipe) takes the **output** of the first command (`dir C:\ /s /b`) and sends it as **input** to the next command (`findstr node.exe`).

---

### **3. `findstr node.exe`**  
- **`findstr`** → Searches for specific text in the input.  
- **`node.exe`** → Filters the results to **only show lines containing `node.exe`**.  
