## Phishing Emails in Action
**Platform:** TryHackMe

### Phishing Email Analysis – Example 1 (Cancel your PayPal order)

**Task context:**  
A suspicious email claiming to be from PayPal instructed the recipient to cancel an order.

**Indicators observed:**
- Sender email starts with **"noreply"**, which is commonly abused in phishing emails
- Urgent language urging immediate action
- Claims to be from PayPal but lacks legitimate verification

**Verdict:** Phishing

**SOC Level 1 Action:**  
Document findings and escalate to Tier 2 for further handling.

**Screenshots:**
- Email content:

![Email content](Paypal.png)

- Sender address: :

![Sender address](noreply.png)

- Task answer submission:

![Task answer submission](task2answer.png)




### Phishing Email Analysis – Example 2 (Your recent purchase)

**Task context:**  
An email claims a recent purchase was made and pressures the user to act quickly.

**Indicators observed:**
- Urgent and fear‑based language
- Attempts to rush the user into clicking or responding
- Lack of clear verification details

**Verdict:** Phishing

**SOC Action:**  
Escalate to Tier 2 for further handling.

**Screenshots:**
- Email content showing urgent language:

![email](emailapple.png)

- Task answer submission:

![task6answer](emailtask6.png)




### Phishing Email Analysis – Example 3 (DHL Express Courier)

**Task context:**  
A suspicious email claims to be from DHL Express and contains an unexpected attachment.

**Indicators observed:**
- Spoofed sender pretending to be a trusted courier
- Unexpected attachment delivery
- High-risk file type commonly associated with malware

**Verdict:** Phishing

**SOC Action:**  
Escalate to Tier 2 for further handling.

**Screenshots:**
- Email content with attachment:

![emailcontent](DHLemail.png)

![emailattachment](DHLattachment.png)

- Task answer submission:

![task7answer](DHLtask7.png)
