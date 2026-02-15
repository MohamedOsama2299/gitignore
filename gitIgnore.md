    # Git Ignore (.gitignore) Explanation

## 1️⃣ What is `.gitignore`?
`.gitignore` is a small file you put in your Git project.  
Its job is to **tell Git which files or folders to ignore**, meaning Git will not track or commit them.  

It is important to prevent uploading unnecessary or sensitive files to GitHub, such as:  
- `node_modules/` (heavy Node.js libraries)  
- System files like `__MACOSX/`  
- Secret files like `secrets/` or passwords  
- Log files like `*.log`  

---

## 2️⃣ How to write a `.gitignore` file

### a) Ignore an entire folder
