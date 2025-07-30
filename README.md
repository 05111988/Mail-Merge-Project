# Mail-Merge-Project
The Mail Merge Project is a Python automation script that personalizes letters for multiple recipients by dynamically inserting names into a predefined letter template.
# 📬 Mail Merge Project

This project automates the process of creating personalized letters using Python. It reads recipient names from a file, merges each name into a pre-written letter template, and saves the result as a separate file for each recipient.

## 📁 Project Structure

MAIL MERGE PROJECT/
├── Input/
│ ├── Letters/
│ │ └── starting_letter.txt
│ └── Names/
│ └── invited_names.txt
├── Output/
│ └── ReadyToSend/
│ └── [Personalized letters saved here]
├── mail_merge.ipynb

## ✨ Features

- Reads a list of names from a `.txt` file.
- Replaces the `[name]` placeholder in a template letter with each actual name.
- Saves the personalized letters into the `ReadyToSend` folder as `.txt` files.

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook

## 🧠 Concepts Covered

- File input/output operations
- String manipulation and replacement
- Using context managers (`with` statement)
- Directory handling

## 🔧 How It Works

1. Read all names from `invited_names.txt`.
2. Load the template from `starting_letter.txt`.
3. Replace `[name]` with each recipient's name.
4. Write each personalized letter to `Output/ReadyToSend/`.

## 📌 Example

**Template (starting_letter.txt):**
Dear [name],

You are invited to my birthday party this Saturday!
Hope to see you there.


**Output (for name = "Angela"):**
Dear Angela,

You are invited to my birthday party this Saturday!
Hope to see you there.

## 🚀 How to Run

1. Make sure Python is installed.
2. Place your `.txt` files inside the `Input` folders.
3. Run the notebook `mail_merge.ipynb`.

## 📬 Use Cases

- Bulk invitation letter generation
- Email marketing template preparation
- Mass mailing for events or functions

## 🖊️ Author

Lakshika Tomar  
[GitHub Profile](https://github.com/yourusername)  
Date: July 2025

---

