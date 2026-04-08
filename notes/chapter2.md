# 🐧 chapter 2 - File System Basics

---

## 📁 What is a File System?

A **file system** is the way Linux organizes and stores files and directories.

👉 Everything in Linux is treated as a file.

---

## 📍 File Path

A **file path** is the location of a file or directory in the system.

### 🔹 Example

```bash
/home/user/file.txt
```

👉 This shows the exact location of `file.txt`

---

## 📂 Parent Directories

A **parent directory** is the directory above the current directory.

### 🔹 Command

```bash
cd ..
```

👉 Moves one level up

---

## 🛣️ Absolute vs Relative Paths

### 🔹 Absolute Path

* Starts from root `/`
* Full path

```bash
/home/user/docs/file.txt
```

---

### 🔹 Relative Path

* Starts from current directory

```bash
docs/file.txt
```

---

### 🔹 Example

```bash
pwd
```

Output:

```bash
/home/user
```

```bash
cd docs
```

👉 This is a relative path

---

## 📄 Files

Files store data like text, images, programs, etc.

### 🔹 Create a File

```bash
touch file.txt
```

---

## 🔍 Viewing File Content

### 🔹 head (first lines)

```bash
head file.txt
```

---

### 🔹 tail (last lines)

```bash
tail file.txt
```

---

### 🔹 more (page by page)

```bash
more file.txt
```

---

### 🔹 less (better viewer)

```bash
less file.txt
```

👉 Use `q` to exit

---

## ✏️ Touch Command

Used to create empty files.

```bash
touch newfile.txt
```

---

## 📁 Directories

Directories are folders used to organize files.

### 🔹 Create Directory

```bash
mkdir myfolder
```

---

## 🔄 Move (mv)

Used to move or rename files.

### 🔹 Move file

```bash
mv file.txt myfolder/
```

### 🔹 Rename file

```bash
mv file.txt newname.txt
```

---

## ❌ Remove (rm)

Used to delete files and directories.

### 🔹 Delete file

```bash
rm file.txt
```

### 🔹 Delete directory

```bash
rm -r myfolder
```

⚠️ Be careful — deleted files cannot be recovered easily

---

## 📋 Copy (cp)

Used to copy files and directories.

### 🔹 Copy file

```bash
cp file.txt copy.txt
```

### 🔹 Copy directory

```bash
cp -r myfolder backup/
```

---

## 🏠 Home Directory

Each user has a home directory.

```bash
/home/username
```

Shortcut:

```bash
cd ~
```

---

## 🔎 Grep (Search Text)

Used to search text inside files.

### 🔹 Example

```bash
grep "hello" file.txt
```

---

## 🔎 Grep Multiple Files

```bash
grep "hello" *.txt
```

👉 Searches in all `.txt` files

---

## 🔍 Find Command

Used to search files and directories.

### 🔹 Example

```bash
find . -name "file.txt"
```

👉 Searches in current directory

---

## 📊 Common Commands Summary

| Command | Description            |
| ------- | ---------------------- |
| pwd     | Show current directory |
| cd      | Change directory       |
| touch   | Create file            |
| mkdir   | Create directory       |
| rm      | Remove file            |
| cp      | Copy file              |
| mv      | Move/rename file       |
| grep    | Search text            |
| find    | Search files           |

---

## ✅ Final Summary

* File system → organizes data
* Path → location of files
* Absolute path → full path
* Relative path → current location based
* Commands → create, move, delete, search files

---

## 💡 Practice Commands

```bash
pwd
mkdir test
cd test
touch file1.txt
echo "hello linux" > file1.txt
cat file1.txt
cp file1.txt file2.txt
mv file2.txt newfile.txt
rm newfile.txt
cd ..
rm -r test
```

---
