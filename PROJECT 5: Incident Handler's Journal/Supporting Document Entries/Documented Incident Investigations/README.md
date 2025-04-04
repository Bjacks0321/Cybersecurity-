## 🛡️ Entry 1: Documenting a Ransomware Attack

### 📖 Scenario Summary  
This simulated activity described a ransomware attack that affected a small U.S.-based healthcare clinic. On a Tuesday morning around 9:00 a.m., several employees discovered they could no longer access essential files like medical records. A ransom note on their computers stated that the organization’s data had been encrypted. The attackers demanded a large sum of money for a decryption key.  

The investigation revealed that the attack originated from phishing emails sent to multiple employees. These emails contained malicious attachments that, once opened, deployed ransomware and locked the organization out of its critical systems. As a result, operations were halted, and external assistance was needed to respond to the incident.

### 🔍 Activity Overview  
My task was to document the incident using the structure of an incident handler’s journal entry. This helped me practice breaking down an incident clearly and professionally while identifying key threat factors using the 5 W’s: Who, What, When, Where, Why.

### 🛠️ Steps Taken  
1. Read through the scenario and note key event details.  
2. Opened my incident handler’s journal and logged the actual date.  
3. Added an entry number and description.  
4. Answered the 5 W’s based on the facts provided.  
5. Added personal notes and thoughts about the situation.  
6. Saved the entry for my cybersecurity portfolio.

## 🔍 Entry 4: Investigating a Suspicious File with VirusTotal and Mapping IoCs with the Pyramid of Pain

### 🔍 Activity Overview  
In this combined activity, I investigated a file hash reported in a security alert using **VirusTotal**, then categorized the **Indicators of Compromise (IoCs)** using the **Pyramid of Pain** framework. The scenario involved a password-protected spreadsheet received via phishing, which triggered a payload after being opened.

### 🛠️ Steps Taken  
1. Reviewed the incident timeline:  
   - Employee received a phishing email  
   - File downloaded and opened  
   - Payload executed, creating suspicious files  
   - Alert triggered by the IDS  
2. I took the SHA256 hash and searched for it on VirusTotal.  
3. Examined results across tabs:  
   - **Detection**: Checked how many vendors flagged it as malicious  
   - **Details**: Found related hashes (MD5, SHA1)  
   - **Behavior**: Analyzed sandbox actions like process creation and network traffic  
   - **Relations**: Reviewed domains and IPs contacted by the file  
4. Determined the file was malicious based on vendor ratio and community score.  
5. Documented IoCs in the **Pyramid of Pain.pdf**, placing each indicator in the proper category:  
   - **Hash value** (SHA256): Identifies the file uniquely, but it is easy for attackers to change  
   - **IP Address** (e.g., 114.149.208.238): Used by malware for communication  
   - **Domain Name** (e.g., `org.misecure.com`): Flagged as malicious contact domain  
   - **Network/Host Artifacts**: Evidence of file creation and HTTP requests  
   - **TTPs**: Noted tactics like phishing and sandbox evasion behaviors  
6. Reflected on which IoCs are most valuable to defenders and hardest for attackers to alter.
