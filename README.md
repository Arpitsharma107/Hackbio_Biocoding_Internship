
# HackBio Biocoding Internship - Stage Zero Task  

## 📖 Project Overview  
This repository contains my submission for the **HackBio Biocoding Internship - Stage Zero Task**. The task requires organizing personal details using **any data structure** of choice and performing **basic data retrieval** using Python.  

---

## 📝 Task Description  

The goal of this task is to:  
✔️ Store the following personal information in a structured format  
✔️ Print the stored information.  
✔️ Access and retrieve a specific key-value pair.  

The **chosen data structure** for this task is a **Python dictionary**, which provides an efficient way to store and access key-value pairs.

---

## 🛠 Implementation Details  

### **👨‍💻 Code Explanation**  
🔍 What I Did in This Code
1️⃣ Chose a Data Structure
    I used a dictionary (choice_datastru), which allows storing key-value pairs.
    Each piece of information was stored with a unique key (e.g., "Name" as a key and "Arpit Sharma" as its value).
2️⃣ Stored the Data
    Created a dictionary named choice_datastru containing:
    "Name": My full name
    "Slack Username": My Slack username
    "Email": My email address
    "Hobby": My hobbies
    "Country": My country
    "Discipline": My academic field
    "Preferred Programming Language": My favorite programming language
3️⃣ Printed the Entire Dictionary
    Used print(choice_datastru) to display all stored information in the terminal.
4️⃣ Accessed a Specific Value
    Used choice_datastru["Name"] to extract and print my name separately.

```python
"""
## Use any data structure of your choice to organize the following information:
- Your Name
- Your Slack Username
- Your Email
- Your Hobby
- Your Country
- Your Discipline
- Your Preferred Programming Language
"""

# Storing personal information in a Python dictionary
choice_datastru = {
    "Name": "Arpit Sharma",
    "Slack Username": "Arpit",
    "Email": "8920arpit@gmail.com",
    "Hobby": "Gaming and cooking",
    "Country": "India",
    "Discipline": "Bioinformatics",
    "Preferred Programming Language": "Python"
}

# Printing the entire dictionary
print(choice_datastru)

# Accessing and printing a specific value (Name)
Name = choice_datastru["Name"]
print(Name)
