# Cyber Security Internship  
## Password Strength Evaluation Report

---

### Project Overview
This repository contains the deliverables for Task 6 of the Cyber Security Internship, focused on understanding password strength and best practices for creating secure passwords. The task involved creating multiple passwords with varying complexity, testing their strength using an online password meter, analyzing the results, and summarizing key learnings.

---

### Password Testing Summary

Two example passwords were tested on [Password Meter](https://passwordmeter.com/):

| Test | Password Length | Password Features                             | Score | Complexity   |
|-------|-----------------|----------------------------------------------|-------|--------------|
| Test 1| 11 characters   | Lowercase letters, numbers                    | 43%   | Good         |
| Test 2| 17 characters   | Uppercase, lowercase, numbers, symbols       | 100%  | Very Strong  |

---

### Test 1 Details:
- Password met the minimum length but lacked uppercase letters and symbols.
- Score: 43% (Good)
- Feedback highlighted deductions due to consecutive lowercase letters, sequential numbers, and repeated characters.
- The password's lack of mixed character types reduced its overall strength.

### Test 2 Details:
- Password included a strong mix of uppercase letters, lowercase letters, numbers, and symbols.
- Score: 100% (Very Strong)
- Received bonuses for length, variety of characters, and middle numbers/symbols.
- Minor deductions for some repeated characters and consecutive letters.
- Overall demonstrated best practices in password creation.

---

### Key Learnings and Best Practices

- Use at least 12-16 characters to improve password strength.
- Combine uppercase letters, lowercase letters, numbers, and special characters.
- Avoid sequences, repeated characters, and predictable patterns.
- Longer passwords with diverse character sets significantly resist brute force and dictionary attacks.
- Regularly use password strength checkers to evaluate passwords.
- Consider using passphrases for easier memorization with strong security.

---

### Common Password Attacks

- **Brute Force Attack:** Attempts every possible combination until the correct password is found.
- **Dictionary Attack:** Uses a precompiled list of common passwords and words to guess passwords quickly.

Increasing password length and complexity exponentially increases the difficulty of these attacks.

---

### Repository Contents

- `README.md` - This document.
- `Password_Test_Results.md` - Detailed test results and analysis.
- Screenshots of password meter evaluations (optional).
- Final strong password example and its evaluation report.

---

### Conclusion

This exercise highlights the importance of password complexity and length for securing accounts against common cyber attacks. Using online tools to test password strength provides actionable feedback to improve password security.

---

### References

- [Password Meter](https://passwordmeter.com/)  
- OWASP Password Guidelines  
- Various cybersecurity tutorials and articles

---

