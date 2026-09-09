🔐 Password Strength Analyzer

A Python-based Password Strength Analyzer that evaluates the strength of a password using multiple security checks.

📌 Project Overview

This project analyzes passwords based on common security requirements and identifies patterns that may make a password easier to guess.

The analyzer provides a strength score and helpful warnings to encourage users to create stronger passwords.

✨ Features

- Checks password length
- Detects uppercase letters
- Detects lowercase letters
- Checks for numbers
- Checks for special characters
- Identifies commonly used passwords
- Detects excessive character repetition
- Detects simple sequential patterns
- Provides an overall password strength rating
- Displays a score out of 5

🛠️ Technologies Used

- Python
- Regular Expressions ("re")
- Google Colab / Jupyter Notebook

⚙️ How It Works

The analyzer evaluates a password using five basic criteria:

1. Length of at least 8 characters
2. At least one uppercase letter
3. At least one lowercase letter
4. At least one number
5. At least one special character

It also performs additional checks for:

- Common passwords
- Repeated characters
- Sequential patterns

Based on the basic criteria, the password receives a score from 0/5 to 5/5.

📊 Strength Levels

Score| Strength
0–2| Weak
3| Moderate
4| Strong
5| Very Strong

🧪 Example

For a password such as:

"Hello123!"

The analyzer can produce:

🔐 Password Analysis
------------------------------
✅ Length (8+ characters)
✅ Uppercase letter
✅ Lowercase letter
✅ Number
✅ Special character

Strength: Very Strong
Score: 5/5

✅ Password is not in the common password list.
✅ No excessive character repetition detected.
✅ No obvious sequential pattern detected.

▶️ How to Run

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Enter a test password when prompted.
4. View the password analysis and security warnings.

⚠️ Disclaimer

This project is an educational password-strength checker. It does not guarantee that a password is secure against real-world attacks.

For privacy, avoid entering your actual passwords into demonstration notebooks.

🚀 Future Improvements

- Add a password generator
- Expand the common-password database
- Detect more types of predictable patterns
- Add a graphical user interface
- Provide personalized password improvement suggestions
- Improve the scoring algorithm

👩‍💻 Author

Palak Chhillar

---

⭐ If you found this project useful, consider giving the repository a star!
