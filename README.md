# Password-Strength-Analyzer
Password Strength Analyzer A simple Python script to check the strength of a password based on its structure and resistance to common patterns. Great for learning basic Python and getting started with cybersecurity concepts.


🔧 Features
Evaluates password strength as Weak, Medium, or Strong
Checks for:
Length (min 8 characters)
Uppercase & lowercase letters
Digits
Symbols
Avoidance of common weak patterns (like 123, password, etc.)



🧪 Example Usage
$ python password_checker.py
Enter your password: Hello123!

Password Analysis:
Strength: Medium ⚠️
Issues:
- No symbol



💡 How It Works
The script scores a password based on five criteria:
✅ Sufficient length
✅ Contains uppercase and lowercase letters
✅ Includes digits
✅ Includes at least one symbol
❌ Avoids common weak patterns
If it meets 4 or more criteria and avoids weak patterns, it's rated Strong.



🚀 Getting Started
Clone the repository:git clone https://github.com/yourusername/password-strength-analyzer.git
Run the script:cd password-strength-analyzer


python-password_checker.py
📁 File Structure
password-strength-analyzer/
├── password_checker.py
└── README.md


🧠 Skills Practiced
Boolean logic and control flow
Built-in functions: len(), any(), isupper(), isalnum(), etc.
String and list operations
Basic cybersecurity concepts.
