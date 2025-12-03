# Py-Syntax-Checker (Python Project)
AI Code Checker is a simple Python tool that helps users check Python code for syntax errors, provides fix suggestions, and also shares learning tips based on the code written.
This tool is helpful for beginners, students, and those who want to improve their coding habits.

🚀 Features

✔️ Checks Python code syntax using ast
✔️ Detects common beginner mistakes
✔️ Suggests fixes for common syntax errors
✔️ Provides learning tips based on code usage
✔️ Supports multi-line code input (type END to finish)
✔️ Beginner-friendly and interactive CLI tool

📌 How It Works

User pastes Python code line by line

Type END to finish input

Program checks syntax using ast.parse()

If no error → "No syntax error!"

If error → shows the error and suggestions

Gives helpful learning tips at the end

🧠 Code Flow

check_syntax(code)
Checks syntax and returns error if found.

suggest_fix(error_msg)
Suggests solutions for common syntax mistakes.

give_tips(code)
Looks at the code and provides learning tips (print, loop, if, function, etc.)

📂 Project Files
File	Description
AI_Code_Checker.py	Main Python script
AI_Code_Checker.ipynb	Jupyter Notebook version (for demonstration)
README.md	Project documentation
▶️ How to Run
python AI_Code_Checker.py


In Notebook:
Just open .ipynb and run the cells.

📝 Example Usage
Welcome to AI Code Checker!
Paste code (type 'END' when finished):

print("Hello"


Output:

 Syntax Error : EOL while scanning string literal
 Suggestion : Check quotes in your string properly.

💡 Learning Tips Example

Used print() – consider f-strings too.

Using for loop – check range usage.

Conditional used – handle all possible cases.

🙌 Thanks for Using AI Code Checker!

Feel free to fork, improve, or suggest new features.
⭐ Star the repo if you find it helpful!
