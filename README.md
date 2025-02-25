


# Wordlist Generator – The Ultimate Brute Force Companion  
<img width="666" alt="WordlistGen" src="https://github.com/user-attachments/assets/99f7efbf-a7b9-4673-b1a0-6819409076b0" />



A **custom wordlist generator** designed to create highly targeted password lists for **brute-force attacks**, **password cracking**, and **penetration testing**. This tool takes user-defined keywords (such as names, birth years, and common phrases) and generates passwords based on **realistic password patterns**.  

Whether you're conducting a **CTF challenge**, performing a **pentest**, or need to simulate a password attack scenario, this tool helps you craft a **powerful and customized wordlist**.  

---

## 🎯 Features  

- **Brute-force optimized**: Generates targeted password lists to increase success rates in brute-force attacks.  
- **Common password patterns**: Incorporates predictable structures used by real-world users.  
- **Special character variation**: Adds symbols and numbers to increase effectiveness.  
- **Weak password injection**: Includes common weak passwords (e.g., `password123`, `admin`, `qwerty`).  
- **Randomization & mutation**: Applies transformations like capitalization, reversal, and keyword mixing.  
- **Fast & lightweight**: Quickly generates thousands of password variations.  
- **Auto-save**: Saves the generated wordlist to a file for easy access.  

---

## Installation  

Ensure you have Python installed, then install dependencies:  

```bash
pip install -r requirements.txt
```

### Dependencies  
- `pyfiglet` (for ASCII banners)  
- `termcolor` (for colored console output)  

Or install manually:  
```bash
pip install pyfiglet termcolor
```

---

## 📌 Usage  

Run the script using:  
```bash
python WordlistGenerator.py
```

### Input Example  
```plaintext
[?] Enter keywords (comma-separated): Alice, 1995, hacker  
[?] How many passwords do you want to generate? 50
```

### Output Example  
```
Alice@1995!
Hacker_1995
1995Alice*
Alice1995Password
Hacker@1995Qwerty
1995_Alice_Hacker
Alice123!
```
The wordlist will be saved in `passwords_wordlist.txt`.  

