# Python
DIGITAL IDENTITY STRENGTH CHECKER
================================

A simple Python program that evaluates the strength of a password and provides suggestions to improve it.

--------------------------------------------------

FEATURES
--------

- Checks password length
- Verifies:
  * Uppercase letters
  * Lowercase letters
  * Numbers
  * Special characters
- Generates a security score
- Provides improvement suggestions
- Classifies password as:
  * Strong Identity
  * Needs Improvement
  * High Risk of Cybercrime

--------------------------------------------------

TECHNOLOGY USED
---------------

- Python
- No external libraries required

--------------------------------------------------

HOW TO RUN
----------

1. Install Python on your system
2. Download or clone the project
3. Open terminal or command prompt
4. Navigate to project folder
5. Run the program using:

   python main.py

Example Output 

=========================
 Digital Identity check 
=========================
Enter a password to test your identity: Pass123

--- Security Audit Results ---
Status: Needs Improvement

Recommendations to Increase Complexity:
- Min one special character should be present

--------------------------------------------------


Scoring Criteria:

- Length >= 12 characters  → +2 points
- Length >= 8 characters   → +1 point
- Upper + Lower case mix   → +1 point
- Contains digits          → +1 point
- Contains special chars   → +1 point

