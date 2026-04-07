# 🐧 chapter 1 - Terminal & Shell Basics

---

## 🖥️ What is a Terminal?

A **terminal** is a text-based interface used to interact with the operating system using commands instead of a graphical interface (GUI).

👉 Instead of clicking buttons, we type commands.

### 🔹 Example

```bash
pwd
```

### 🔹 Output

```
/home/user
```

👉 This shows the current working directory.

---

## ⚙️ What is a Shell?

A **shell** is a command interpreter that takes input from the terminal and tells the operating system what to do.

👉 Terminal = Interface
👉 Shell = Command Executor

The most commonly used shell is **Bash (Bourne Again Shell)**.

### 🔹 Example

```bash
echo Hello Linux
```

### 🔹 Output

```
Hello Linux
```

---

## 🔣 Variables

Variables are used to store values that can be reused later.

### 🔹 Creating a Variable

```bash
name="Linux"
```

### 🔹 Using a Variable

```bash
echo $name
```

### 🔹 Output

```
Linux
```

👉 `$` is used to access the value of a variable.

---

## 📜 History

Linux stores previously executed commands, which can be reused.

### 🔹 View Command History

```bash
history
```

👉 Displays a list of previously used commands.

---

### 🔹 Run Last Command Again

```bash
!!
```

👉 Executes the last command.

---

### 🔹 Run Specific Command from History

```bash
!5
```

👉 Runs command number 5 from history.

---

## 🧰 Terminal Alternatives

There are different terminal applications available in Linux:

* GNOME Terminal
* Konsole
* Tilix
* Alacritty

👉 All perform the same function but have different interfaces and features.

---

## 📊 Common Commands Summary

| Command | Description                       |
| ------- | --------------------------------- |
| pwd     | Show current directory            |
| echo    | Print text to terminal            |
| history | Show previously used commands     |
| !!      | Run last command                  |
| !n      | Run specific command from history |

---

## ✅ Final Summary

* Terminal → Place to type commands
* Shell → Executes commands
* Variables → Store values
* History → Reuse previous commands
* Terminal alternatives → Different apps for same purpose

---

## 💡 Practice Commands

```bash
pwd
echo "Hello World"
name="Linux"
echo $name
history
```

---

