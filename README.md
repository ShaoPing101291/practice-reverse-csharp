# practice-reverse-csharp

# Reverse Engineering Practice 
I worked on a test with a software file.  
It is part of a **company project** and not a real product.  
The vendor gave us an **account and password** to try it.  
Right now, we are only in the **testing stage**.  
We do not have the **official software** yet.

I used **ILSpy in VS Code** to decompile the `.exe` file.  
The goal was only to **practice reverse engineering** and  
to understand how the program checks for registration.  

This was not hacking for illegal use.  
It was just a **lab exercise** to learn and test the process.  

## Steps I Did

1. **Get the test file**  
   - I received a test `.exe` file from the vendor.  
   - This file is only for testing, not the final product.  

2. **Open in ILSpy (VS Code)**  
   - I installed the **ILSpy extension** in Visual Studio Code.  
   - I used it to **decompile** the `.exe` file.  

3. **Look at the code**  
   - I checked the program code to see how it works.  
   - I found the part where it uses a **system code** and  
     checks the **registration code**.  

4. **Test with Python**  
   - I wrote a small **Python script** to scan the file for strings.  
   - This was only to understand how the program stores data.  

5. **Check Registry Key**  
   - I saw that the program writes to  
     `HKEY_CURRENT_USER\Software\BES_Report\RegStatus`.  
   - If the value is `"1"`, it means "registered".
## What I Learned
- How to use **ILSpy** to look at a `.NET` program.  
- How software can use **system code + registration code**.  
- How a program can save status in the **Windows Registry**.  
## Notes
- This practice is only for our **company project**.  
- The vendor gave us a test account and password.  
- It is still in the **testing stage**.  
- We do **not** have the final software.  
