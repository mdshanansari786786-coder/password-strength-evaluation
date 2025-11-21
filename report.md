# Password Strength Evaluation Report

## 1. Introduction
This report evaluates password strength using multiple sample passwords tested on online password strength meters such as passwordmeter.com.  
The goal is to understand how password length, complexity, and randomness impact overall security.

---

## 2. Passwords Tested

| Password | Description |
|----------|-------------|
| `sunshine123` | dictionary word + digits |
| `BlueSky!45` | mixed case + symbol + digits |
| `r9T!fP2@xQ` | random 10-character complex password |
| `G7!qP$9mV@e#4Lz` | random 16-character highly complex password |

---

## 3. Strength Evaluation Results

### **Password 1: `sunshine123`**
- **Score:** ~30%
- **Rating:** Weak  
- **Feedback:**
  - Contains dictionary word
  - Lacks uppercase letters
  - No symbols
  - Predictable pattern
- **Screenshot:** `screenshots/passwordmeter-result1.png`

---

### **Password 2: `BlueSky!45`**
- **Score:** ~70%
- **Rating:** Good  
- **Strengths:**
  - Mixed case
  - Contains symbol and numbers
- **Weaknesses:**
  - Some dictionary-like structure
  - Only 10 characters
- **Screenshot:** `screenshots/passwordmeter-result2.png`

---

### **Password 3: `r9T!fP2@xQ`**
- **Score:** ~90%
- **Rating:** Strong  
- **Strengths:**
  - Random characters
  - High entropy
  - All character sets included
- **Weaknesses:**
  - Could be longer (12+ preferred)
- **Screenshot:** `screenshots/passwordmeter-result3.png`

---

### **Password 4: `G7!qP$9mV@e#4Lz`**
- **Score:** 100%
- **Rating:** Very Strong  
- **Strengths:**
  - 16 characters
  - High randomness
  - Contains uppercase, lowercase, symbols, and digits
  - No dictionary patterns
- **Screenshot:** `screenshots/passwordmeter-result4.png`

---

## 4. What Makes a Password Strong?

### ✔ Length
The most important factor.  
Passwords **12–16 characters or longer** greatly increase brute-force resistance.

### ✔ Character Variety
A strong password uses:
- Uppercase letters  
- Lowercase letters  
- Numbers  
- Symbols  

### ✔ Randomness
Avoid:
- Dictionary words
- Personal information
- Patterns (`abc123`, `qwerty12`)
- Reused passwords

### ✔ Use a Password Manager
They generate and securely store complex passwords.

---

## 5. Common Password Attacks

### **Brute Force**
Attackers try every possible combination.  
Longer passwords (12–16+ characters) become very difficult to brute force.

### **Dictionary Attack**
Uses common words, names, and leaked password lists.  
Password 1 (`sunshine123`) is vulnerable to this.

### **Hybrid Attack**
Combines dictionary words + variations (like adding `123` or `!`).

### **Credential Stuffing**
Attackers use leaked usernames/passwords on multiple websites.  
This is why password reuse is dangerous.

### **Phishing**
Tricks users into entering passwords on fake websites.

---

## 6. Summary of Findings
- The strongest passwords are **long, random, and use all character types**.
- Password meters consistently penalize dictionary words and short length.
- Random passwords outperform “clever” human-created passwords.
- High complexity dramatically improves resistance to brute-force and dictionary attacks.

---

## 7. Conclusion
Using long, randomly generated passwords significantly increases security.  
Password managers should be used to avoid reusing passwords and to generate high-entropy keys.

This evaluation demonstrates that password complexity and length are essential to protecting accounts from modern password attacks.

