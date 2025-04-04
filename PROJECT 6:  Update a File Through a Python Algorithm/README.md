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

Algorithm for file updates in Python.pdf
Located in the main Project 6 folder, this document provides a detailed breakdown of the algorithm’s logic, code structure, and reasoning behind each step.

### 📁 Supporting Documents
This project includes two supporting documents located in the `Supporting Documents` folder:
- **Activity Assignment README** – A portfolio-ready breakdown of the scenario and steps taken.
- **Instructions for Including Python Code** – Guidelines for adequately documenting and presenting the Python code used in this project.

### 🛠 Technologies Used:
- Python (File I/O, Lists, Loops, Conditionals)
- Text file manipulation (`.read()`, `.split()`, `.remove()`, `.join()`, `.write()`)
