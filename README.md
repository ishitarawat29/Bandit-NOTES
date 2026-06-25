# Bandit Wargame - Learning Log & Cheat Sheet

This repository documents my progress through the [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) wargame. It serves as a technical log of the Linux command-line skills, security concepts, and problem-solving techniques I have acquired.

## 🚀 Overview

- **Objective:** Master Linux fundamentals and basic exploitation techniques.
- **Current Status:** Completed Levels 0–12.
- **Focus:** Command-line navigation, file permissions, data manipulation, and basic networking.



## 🛠 Command-Line Cheat Sheet

| Category | Commands Used | Implementation Notes |
| :--- | :--- | :--- |
| **Navigation** | `ls`, `cd`, `pwd`, `find` | Used for system exploration and locating hidden files. |
| **File Operations** | `cat`, `less`, `strings`, `xxd` | Used for reading file contents and inspecting binary/hidden data. |
| **Data Processing** | `grep`, `sort`, `uniq`, `tr` | Used for filtering, sorting, and decoding obfuscated text (ROT13). |
| **Permissions** | `chmod`, `ls -l` | Used for identifying and modifying file access restrictions. |
| **Networking** | `ssh`, `nc`, `openssl` | Used for establishing secure connections and testing ports. |



## 📝 Key Concepts & Techniques

*   **Pipes & Redirection:** Utilized `|` to chain commands and `>`/`>>` to redirect output for analysis.
*   **Encoding & Decoding:** Practiced decoding Base64 strings and handling hex dumps to retrieve sensitive data.
*   **System Enumeration:** Leveraged `find` with specific flags (e.g., `-user`, `-size`, `-perm`) to locate target  files within the directory structure.
*   **Obfuscation Handling:** Applied `tr` for character manipulation to solve ciphers like ROT13.



## 🔍 Level-by-Level Learning Notes

*   **Levels 0-5 (Navigation & Basic Tools):** Learned how to navigate the file system and use `cat`/`grep` to extract text from files.
*   **Levels 6-10 (File Finding & Analysis):** Leveraged `find` with flags (`-user`, `-size`, `-group`) to locate target files. Used `strings` to find passwords hidden in binary files.
*   **Levels 11-12 (Encoding & Decoding):** Mastered `base64` decoding and ROT13 cipher resolution using the `tr` command. Learned to use `xxd` for hex-dump analysis.



## ⚡ Useful Tips & Tricks

* **Ignore Errors:** Use `2>/dev/null` with `find` to hide "Permission denied" errors.
* **Manual Pages:** Always use `man [command]` to understand command flags better.
* **Documentation:** Keeping a log helps in revising concepts faster.


## 📈 Learning Roadmap
-[x]**Phase 1 (Foundations):** Linux Navigation, Permissions, and Bash Basics.
-[ ]**Phase 2 (Intermediate):** Networking, Scripting, and Web Security Fundamentals.



## 🔗 Learning Platforms 

- **Active:** [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) (Level 12 completed)
- **Upcoming/Targeted:** [picoCTF](https://picoctf.org/) (Starting soon to expand my CTF skills)
- **Goal:** Continuously building a strong foundation for a career in Cyber Security.

## 📈 Progress

- [x]Levels 0-12: Completed
- [ ]Levels 13-20: In Progress (Currently exploring) 




