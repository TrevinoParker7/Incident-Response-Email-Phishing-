# Incident-Response-Email-Phishing-Urgent-Account-Suspended
 
🌐 **Business Email Compromise (BEC) Woes? Meet Your New Best Friend: Sublime Security!** 🛡️💌  

I’ve been deeply involved in addressing **Business Email Compromise (BEC)** 🔓📧 and needed a solution that’s **easy to deploy** 🚀 yet powerful enough to **customize and build detections** 🔍. Enter **Sublime Security**—a tool I’ve come to love (not sponsored, but genuinely impressed)! 💖  

### **What Is Sublime Security? 🤔**  
It’s an **email security platform** designed for **transparency** 🪟. Unlike black-box solutions, it shows you *exactly* how it prevents and detects malicious emails 📬🛑. This means you can fully **customize it to fit your needs** ✨.  

---

### **Key Features You’ll Love ❤️:**  
1. **Inbound Email Protection** 🛡️: Block **advanced attacks** like BEC. 💥  
2. **Attack Surface Reduction** 🧹: Create policies to block risky attachments (e.g., .zip, .pdf). 📂🚫  
3. **Custom Detections & Policies** 🛠️: Tailor rules to prevent threats based on specific characteristics.  

---

### **A Cool Example 🎯:**  
Imagine you’re an **incident responder** 🕵️‍♂️. Post-compromise, you discover an email with a **malicious attachment** that caused a breach. 😱 After recovery, you write a **detection rule** in Sublime Security for similar threats.  

Fast forward—someone tries sending a **malicious invoice** 📄👾, but **BOOM** 💥—it’s blocked! 🙌 You just saved your organization from another potential disaster! 🏆  

---
![Screenshot 2025-01-21 120949](https://github.com/user-attachments/assets/a06162e8-9843-4ab9-8a5c-bff36dccccd3)

Attack Score Verdict 🔍

Malicious

Attack Score Signals:

Authoritative Display Name: The sender has a display name resembling Human Resources, which is commonly used in scams.

Suspicious Sender: The sender domain’s TLD ends in ".jp," often abused to conduct attacks.

Suspicious Subject: The subject attempts to engage using a sense of urgency, a common tactic used in attacks.

---

![Screenshot 2025-01-21 133912](https://github.com/user-attachments/assets/c20483f2-e46b-4085-a69a-cb022e3e4fc9)

Message Group Details:

Subject: Urgent: Account suspended

Sender: info@nessstech.co.jp

Recipient: rachael.tyrell@tyrellcorp.com

Attachment: 1 file (image.png)

---

![Screenshot 2025-01-21 133827](https://github.com/user-attachments/assets/2a2054bf-a2f8-4e92-b258-3ae6970fafc2)

Matched Detection Rules (3):

1. Corporate Services Impersonation Phishing

Rule Description: Detects phishing attempts impersonating corporate services like HR or helpdesk, using specific language and suspicious links.

2. Display Name Impersonation Using Recipient SLD

Rule Description: Identifies when the recipient domain’s SLD is used in the sender’s display name to impersonate the organization.

![Screenshot 2025-01-21 133839](https://github.com/user-attachments/assets/1ade8fca-f5e8-447d-b9ca-28a9f14adb8e)

3. Impersonation Using Recipient Domain (Untrusted Sender)

Rule Description: Flags emails where the recipient's domain is used in the sender's display name, impersonating the organization.

---
Message Detail Sample
![Screenshot 2025-01-21 134128](https://github.com/user-attachments/assets/6ddd9e37-77b0-44d3-b314-dc3ff9bd9ec9)

Message Content
![Screenshot 2025-01-21 134140](https://github.com/user-attachments/assets/f93d7492-9882-40c9-82f1-40af759bfc84)

The Email

![Screenshot 2025-01-21 134202](https://github.com/user-attachments/assets/5d5ee75e-4e03-4357-b10c-f98871b25f0a)


### **Ease of Use 🧩:**  
Sublime Security integrates seamlessly with **Gmail** and **Microsoft 365** 📧🔗 using APIs, with **no need to modify MX records**. It’s available as:  
- **On-Premises** 🖥️  
- **Managed Cloud** ☁️  

---

### **How to Get Started 🛠️:**  
1. Head to their site and click **Deploy Now for Free**. 🖱️  
2. Create an account via **Google, Microsoft, or email**. ✉️  
3. Choose a message source (**Google Workspace, Microsoft 365, Gmail via IMAP**, etc.) or explore **Demo Mode** to test with fake data. 🎮  

---

### **Super Useful Features 🚀:**  
- **Detailed Message Analysis** 🧐: Check if users opened, replied, or forwarded emails.  
- **Attack Scoring** 🧮: Learn why an email is flagged as malicious.  
- **Matched Detection Rules** 🗂️: See the exact rules triggered and modify as needed.  
- **Hunt Feature** 🔍: Search your organization’s emails for specific keywords or indicators.  
- **API Integration** 🤝: Automate actions with SOAR solutions!  

