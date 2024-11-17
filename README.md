Password Strength Assessment Tool

This tool evaluates the strength of a password based on several criteria: length, presence of uppercase and lowercase letters, numbers, and special characters. The tool classifies passwords as Strong, Medium, or Weak, helping users create more secure passwords.

Features:
- Length: The password must be at least 8 characters long.
- Uppercase Letters: Requires at least one uppercase letter.
- Lowercase Letters: Requires at least one lowercase letter.
- Numbers: Requires at least one numeric digit.
- Special Characters: Requires at least one special character (e.g., @, $, !, %, *, ?, &).

Based on the number of criteria met, the password is categorized into:
- Strong: Meets all 5 criteria.
- Medium: Meets 3 or 4 criteria.
- Weak: Meets fewer than 3 criteria.

How It Works:
1. The tool prompts the user to input a password.
2. It evaluates the password based on the criteria above.
3. It then outputs the password strength and provides a breakdown of each criterion (whether it is met or not).

Installation:

Requirements:
- Python 3.x (no external libraries required, uses built-in 're' module)

Running the Script:
1. Download or Copy the Script:
   - Save the script as a Python file, e.g., password_strength_tool.py.

2. Execute Locally:
   - Open your terminal or command prompt.
   - Navigate to the directory where the script is saved.
   - Run the script:
     python password_strength_tool.py

3. Interactive Input:
   - The script will prompt you to enter a password to assess.
   - You can enter different passwords to see how they are evaluated.

Example Output:
After running the script, you'll see output similar to the following:

Enter a password to assess (or 'q' to quit): MySecureP@ssw0rd
Password: MySecureP@ssw0rd
Strength: Strong
Length: Good
Uppercase: Good
Lowercase: Good
Number: Good
Special Character: Good

Usage Example:
To assess a password:
1. Prompt: Enter a password to assess (or 'q' to quit):
2. Input: MySecureP@ssw0rd
3. Output:

   Password: MySecureP@ssw0rd
   Strength: Strong
   Length: Good
   Uppercase: Good
   Lowercase: Good
   Number: Good
   Special Character: Good

The script will continue to prompt for additional passwords until you type 'q' to quit.

License:
This tool is licensed under the MIT License. See LICENSE for more information.
