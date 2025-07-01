# Password Strength Evaluation

This task is part of a Cyber Security Internship task where we evaluate the strength of various passwords using the [Password Monster](https://www.passwordmonster.com/) tool.

## 🔧 Tool Used
**PasswordMonster.com** — A free online password strength checker that estimates time to crack passwords based on character sets and length.

## 🔍 Evaluation Results

| Password       | Length | Strength     | Time to Crack     | Characters Used                          |
|----------------|--------|--------------|-------------------|-------------------------------------------|
| 123456         | 6      | Very Weak    | 0 sec             | Numbers                                   |
| password       | 8      | Very Weak    | 0 sec             | Lowercase                                 |
| qwerty         | 6      | Very Weak    | 0 sec             | Lowercase                                 |
| abc123         | 6      | Very Weak    | 0 sec             | Lowercase, Numbers                        |
| Pass1234       | 8      | Very Weak    | 0.01 sec          | Uppercase, Lowercase, Numbers             |
| Qwerty!2       | 8      | Very Weak    | 0.19 sec          | Uppercase, Lowercase, Numbers, Symbols    |
| Hello@123      | 9      | Very Weak    | 0.32 sec          | Uppercase, Lowercase, Numbers, Symbols    |
| G@9kL#pZ&      | 10     | Very Strong  | 10 Thousand Years | Uppercase, Lowercase, Numbers, Symbols    |
| 9&dL@P$4mQr    | 11     | Very Strong  | 5 Thousand Years  | Uppercase, Lowercase, Numbers, Symbols    |
| R@8k#Lm!4Tz    | 11     | Very Strong  | 1 Million Years   | Uppercase, Lowercase, Numbers, Symbols    |

## 🔐 Common Password Attacks

### 1. Brute Force Attack
- **Definition**: Tries every possible combination until the correct password is found.
- **Effective Against**: Short or simple passwords.
- **Example**: Trying `0000`, `0001`, ..., up to `9999`.
- **Prevention**:
  - Use long passwords (12+ characters).
  - Enable account lockout after failed attempts.

### 2. Dictionary Attack
- **Definition**: Uses a list of common passwords or words from the dictionary.
- **Effective Against**: Common or predictable passwords.
- **Example**: `password`, `admin123`, `qwerty`.
- **Prevention**:
  - Avoid real words, names, or known patterns.
  - Use a mix of random characters.

## 🧠 How Password Complexity Affects Security

- **Longer = Stronger**: More characters make brute force attacks take exponentially longer.
- **Character Variety**: Including uppercase, lowercase, numbers, and symbols increases the number of possible combinations.
- **Unpredictability Matters**: Avoid dictionary words and common substitutions like `P@ssw0rd`.

### Example:
- `123456` → cracked instantly (very weak).
- `R@8k#Lm!4Tz` → estimated 1 million years to crack (very strong).

## ✅ Best Practices

- Use at least **12 characters**.
- Mix **uppercase, lowercase, numbers, and symbols**.
- Avoid using **real words** or **common patterns**.
- Store passwords in a **secure password manager**.
- Enable **multi-factor authentication (MFA)** wherever available.
