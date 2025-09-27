# code-to-docx

A simple tool to automatically compile your source code and output screenshots into a single Word document.  
Perfect for creating assignment reports, documentation, or submissions with minimal effort.

Note: Previous repo name was Code_n_Output_to_docx
---

## ✨ Features
- Combine source code and corresponding output images into a `.docx` file.  
- Supports multiple programming languages (as long as all files are of the same type).  
- Option to generate a document **with or without code**.  
- Easy folder-based organization.

---

## 📦 Requirements
- **Python** 3.7 or 3.8  
- **python-docx** module  

Install dependency:  
```bash
pip install python-docx
```

---

## 🚀 Usage (Step by Step with Screenshots)

### 1. Clone the repository
```bash
git clone https://github.com/aadityaprabu/code-to-docx.git
cd code-to-docx
```
![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/1.PNG)

---

### 2. Open the source code
Open the project in **IDLE** or your favorite editor.  
![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/3.PNG)

---

### 3. Add your code files
- Place your code files inside `Files/Codes/`  
- Example: `1.c`, `2.c`, `3.c` … (any extension works, just keep them ordered and of the same type).  

![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/6.PNG)

---

### 4. Add your output images
- Place your output screenshots inside `Files/Images/`  
- Example: `1.png`, `2.png`, `3.png` … (all images should be the same type).  

![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/5.PNG)  
![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/7.PNG)

---

### 5. Run the script
Locate and run the script:
```bash
python automator.py
```
![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/9.PNG)  
![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/8.PNG)

---

### 6. Get your Word document
- After running, check the `Documents/` folder.  
- You’ll find the compiled `.docx` file there.  

![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/11.PNG)  
![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/12.PNG)  
![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/13.PNG)  
![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/14.PNG)

---

## 📷 Example File Structure

```
Files/
 ├── Codes/
 │   ├── 1.c
 │   ├── 2.c
 │   └── 3.c
 └── Images/
     ├── 1.png
     ├── 2.png
     └── 3.png
```

Output in `Documents/`:  
```
assignment.docx
```

---

## 📝 Sample Output

If everything runs correctly, your output Word file will look like this:  

![](https://github.com/aadityaprabu/code-to-docx/blob/main/Automator/Instruction/Images/10.PNG)

---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to improve.

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).
