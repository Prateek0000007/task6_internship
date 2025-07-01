# Password Strength Evaluation

This project is part of a Cyber Security Internship task where we evaluate the strength of various passwords using the [Password Monster](https://www.passwordmonster.com/) tool.

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

## 🧠 Key Learnings

- **Short passwords** and those with **simple patterns** (e.g., only numbers or lowercase letters) are extremely weak.
- **Mixing uppercase, lowercase, numbers, and symbols** increases password strength significantly.
- **Length matters** — longer passwords are harder to crack.
- Even common formats with multiple character sets (like "Hello@123") can still be weak if the length is low or the pattern is predictable.
- Strong passwords are those with **randomized character sets** and **long length** (10+ characters).

## ✅ Best Practices

- Use at least **12 characters**.
- Combine **uppercase, lowercase, numbers, and symbols**.
- Avoid dictionary words or common patterns.
- Use a **password manager** to store complex passwords.
