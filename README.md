# 🧠 Custom Shell Implementation in C++

## 📘 Project Description

This project implements a simple **command-line shell** in C++ that executes Linux commands, manages processes, and supports input/output **redirection**, **piping**, and **job control**. It is a lightweight and educational shell that demonstrates practical system-level programming and process management concepts in Unix/Linux environments.

---

## 🚀 Features

* Execute standard Linux commands using `execvp()`
* Built-in commands: `cd`, `exit`, `jobs`, `fg`, `bg`
* Run processes in **foreground** and **background** (`&`)
* **Piping (`|`)** and **I/O redirection (`<`, `>`)**
* Job control with process tracking and signal handling

---

## 🗓️ Development Plan

**Day 1:** Parse and tokenize user input
**Day 2:** Execute basic commands (`fork`, `execvp`)
**Day 3:** Add process management (background jobs)
**Day 4:** Implement piping and redirection
**Day 5:** Add job control (list, fg, bg)

---

## 🧩 Technologies Used

* **Language:** C++ (C++17)
* **Platform:** Linux / Unix
* **System Calls:** `fork`, `execvp`, `waitpid`, `pipe`, `dup2`, `tcsetpgrp`

---

## ⚙️ How to Compile and Run

```bash
# Clone the repository
git clone https://github.com/your-username/custom-shell.git
cd custom-shell

# Compile (example for Day 5)
g++ -std=c++17 Day5.cpp -o mysh

# Run
./mysh
```

---

## 🧪 Example Commands

```bash
ls -l
cat input.txt | grep error > output.txt
sleep 10 &
jobs
fg 1
```

---

## 📚 Learning Outcomes

* Hands-on experience with **Unix process control**
* Understanding **system calls**, **pipes**, and **signals**
* Implementation of a functional **command-line shell**

---

## 🤝 Contributors
ANANYA RAY
2241018100
ITER SOA UNIVERSITY

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
