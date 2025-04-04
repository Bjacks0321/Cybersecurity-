## 📂 Project 6 Overview – Update a File Through a Python Algorithm

### 🧾 Description  
This project demonstrates how Python can automate file updates to manage IP-based access control for a sensitive healthcare subnetwork. The goal is to ensure only authorized users maintain access by removing outdated IP addresses from an allow list based on a removal list.

### ⚙️ What the Algorithm Does:
- Opens and reads the `allow_list.txt` file.
- Parses the contents into a list of IP addresses.
- Iterates through a predefined `remove_list`.
- Removes matching IPs from the allow list.
- Converts the list into a string and writes the updated content to the file.

This ensures up-to-date access control with minimal manual effort and reduced risk of error.

📚 Documents Overview

📘 Algorithm for file updates in Python.pdf

Located in the Assignments folder, this PDF comprehensively explains the algorithm's purpose and structure and provides a detailed step-by-step breakdown.

📝 README – Update a File Through a Python Algorithm.md
Also in the Assignments folder, this README is a polished write-up of the assignment that highlights the scenario, goals, and development process. It’s designed to be used in a professional portfolio.

📄 Instructions for including Python code.pdf
Located in the Supporting Documents folder, this guide offers formatting tips for documenting Python code in a presentable and readable format.

### 🛠 Technologies Used:
- Python (File I/O, Lists, Loops, Conditionals)
- Text file manipulation (`.read()`, `.split()`, `.remove()`, `.join()`, `.write()`)
