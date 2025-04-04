## 📘 README: Activity Assignment – Update a File Through a Python Algorithm

### 🎯 Activity Overview
This activity documents my ability to develop a Python algorithm that automates the management of IP-based access controls. It highlights my hands-on experience with file parsing, list manipulation, and security protocols. This work will be included in my cybersecurity portfolio to demonstrate my Python scripting skills in a real-world context.

### 🧪 Scenario
As a healthcare cybersecurity professional, I manage a file containing IP addresses of employees allowed to access a restricted subnetwork. I developed a Python algorithm that automatically removes IP addresses from this allow list based on a separate `remove_list`. This ensures that only authorized personnel have access at any given time.

### ✅ Steps Completed
1. **Opened** the `allow_list.txt` file using a `with open()` statement.
2. **Read** its contents and store them in a string variable.
3. **Converted** the string into a list of individual IP addresses.
4. **Iterated** through the `remove_list` using a `for` loop.
5. **Checked** for matches and removed the IPs using `.remove()`.
6. **Converted** the updated list back into a string using `"\n".join()`.
7. **Wrote** the final string back to the original file to update it.

### 📌 Summary
This algorithm automates maintaining network access control by manipulating text files containing IP addresses. It enhances security by reducing the potential for human error and ensures that only current employees retain access to sensitive systems. The script is efficient, readable, and reusable for similar access control tasks.
