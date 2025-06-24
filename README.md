# 📧 Cybersecurity Internship – Task 2: Phishing Email Analysis

## 🎯 Objective

Analyze a sample **phishing email** to identify potential threats such as spoofing, suspicious links, social engineering tactics, and header discrepancies. This task builds awareness of how phishing attacks work and how to detect them.

---

## 🧰 Tools Used

- **Email Header Analyzer**: https://mxtoolbox.com/EmailHeaders.aspx
- **URL Scanner**: https://urlscan.io or https://www.virustotal.com
- **Text Editor / Browser**: To inspect email content

---

## 📩 Sample Phishing Email (Simulated)

From: PayPal security@paypaI.com
To: victim@example.com
Subject: Urgent: Your Account is Suspended

Dear Customer,

We detected unauthorized activity on your account. For your protection, your account has been suspended. Please verify your identity within 24 hours to avoid permanent closure.

Click here to verify: http://paypal.verification-update-login.com

Thank you,
PayPal Security Team

---

## 🔍 Phishing Indicators Found

| Indicator | Description |
|----------|-------------|
| **Sender Address Spoofing** | The email address appears as `security@paypaI.com`, but it uses a capital "i" instead of lowercase "l" in "paypal". |
| **Urgent Tone** | The message creates panic by saying the account will be closed within 24 hours. |
| **Suspicious Link** | Link points to `paypal.verification-update-login.com`, which is not a valid PayPal domain. |
| **Generic Greeting** | The email uses "Dear Customer" instead of a real name. |
| **Language Tricks** | Threatening tone and fake urgency used for manipulation. |

---

## 🧠 Key Learnings

- Identified common traits of phishing emails: spoofed domains, urgent tone, suspicious links.
- Understood how attackers use **email spoofing** to gain user trust.
- Learned to hover over links and verify domain names.
- Practiced safe handling of suspicious emails.

---

## 🔒 Security Reflection

- Never click on links or download attachments from unknown or suspicious emails.
- Always verify sender addresses carefully (watch for small differences like “paypaI.com”).
- Be alert to urgent or emotional language designed to cause panic.
- Report suspicious emails to IT or use built-in phishing reporting tools.

---

## 📂 Files in This Repository

| File | Description |
|------|-------------|
| `sample_email.txt` | Simulated phishing email content |
| `README.md` | Documentation and phishing analysis |

---

## ❗ Disclaimer

> This content is a **fictional simulation** created purely for **educational and internship purposes**. It does not target any real service, user, or domain. No sensitive or live data is included.

---

## ✅ Conclusion

This task built practical awareness of how phishing emails trick users. By identifying common red flags and analyzing suspicious elements, we gained beginner-level insight into social engineering and email security.
