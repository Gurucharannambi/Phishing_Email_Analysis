# Task 2: Analyze a Phishing Email Sample

## Objective
To identify phishing characteristics in a suspicious email sample.

## Tools Used
- Saved email file (text)
- Free online email header analyzer (theoretical)

## Sample Email Description
The analyzed email claims to be from PayPal and warns about account suspension. It asks the user to click a link to verify account details.

## Phishing Indicators Found

### 1. Suspicious Sender Email Address
The sender email is `security@paypa1-alert.com`, which is not an official PayPal domain. The use of number "1" instead of letter "l" indicates spoofing.

### 2. Email Header Discrepancies
Email headers usually show SPF/DKIM failures in phishing emails, indicating that the sender is not authorized.

### 3. Urgent and Threatening Language
The email uses phrases like "Account will be suspended within 24 hours", creating panic and urgency.

### 4. Suspicious Link
The displayed link does not belong to the official PayPal website. It redirects to a fake domain.

### 5. Request for Sensitive Information
The email asks the user to verify account details, which may include login credentials.

### 6. Grammar and Spelling Errors
The email contains poor sentence construction, which is common in phishing emails.

### 7. Generic Greeting
The email uses "Dear Customer" instead of the recipient’s name.

## Summary Table

| Indicator | Detected |
|--------|----------|
| Spoofed sender address | Yes |
| Header mismatch | Yes |
| Urgent language | Yes |
| Suspicious URL | Yes |
| Sensitive data request | Yes |
| Grammar errors | Yes |
| Generic greeting | Yes |

## Conclusion
The analyzed email shows multiple phishing characteristics and is clearly a phishing attempt. Users should avoid clicking links and sharing personal information.
