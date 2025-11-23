# 📘 2.3 Using Directories and Listing Files (Weight: 2)
**Navigation of home/system directories & listing files.**

---

## 📝 Key Knowledge Areas — Study Notes

### ⭐ Files & Directories
- Linux stores everything as **files** or **directories** 📂  
- Directories contain files/subdirectories  
- Case-sensitive filesystem (`File` ≠ `file`)  

---

### ⭐ Hidden Files & Directories
- Hidden items start with a **dot (`.`)**  
- Often used for **config files** in a user’s home directory  
- Example: `.bashrc`, `.config/`  

---

### ⭐ Home Directories
- Each user has a home directory: `/home/username`  
- `~` expands to **current user’s home**  
- `$HOME` variable also points to the home directory  

---

### ⭐ Absolute & Relative Paths
- **Absolute path** → starts from root `/`  
  - Example: `/etc/passwd`  
- **Relative path** → based on current working directory  
  - Example: `Documents/work/`  
- `.` → current directory  
- `..` → parent directory  

---

## 🧩 Partial List of Key Knowledge — Notes & Context
- **Common options for ls**  
  - `ls` → list files  
  - `ls -l` → long format  
  - `ls -a` → show hidden files  
  - `ls -lh` → human-readable sizes  
- **Recursive listings**  
  - `ls -R` → show subdirectories  
- **cd**  
  - `cd /path` → absolute  
  - `cd ..` → go up  
  - `cd ~` → go home  
- **. and ..**  
  - Navigation markers in all directories  
- **home and ~**  
  - Access home directory quickly  

---

## 📌 Practice Tips (Minimal Labbing)
- Navigate with `cd`, `cd ..`, `cd ~`  
- List hidden files: `ls -a`  
- Compare absolute vs relative:  
  - `cd /etc` → absolute  
  - `cd ../var` → relative  
- Explore recursion: `ls -R /etc | less`  
- Check your home path: `echo $HOME`  

Keep focus on:  
- Directory structure  
- Path differences  
- Hidden files  
- Common `ls` options  

This is exactly what LPI tests.
