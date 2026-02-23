# Identify and Remove Suspicious Browser Extensions

## 📌 Objective
To audit installed browser extensions and identify any potentially malicious or unnecessary extensions to improve browser security hygiene.

---

## 🛠 Tools Used
- Google Chrome Browser
- Manual permission analysis
- Extension review verification

---

## 🔍 Step 1: Review Installed Extensions

Navigated to:

chrome://extensions/

Screenshot:

![Installed Extensions](extensions_before_audit.png)

### Installed Extensions Found:

1. Adobe Acrobat: PDF edit, convert, sign tools
2. Google Docs Offline
3. McAfee WebAdvisor
4. Ubuntu Free Online Linux Server (OnWorks)

---

## 🔎 Step 2: Permission Analysis

Each extension was reviewed by clicking:

Details → Permissions

### Observations:

- No unknown developers detected
- No extensions disabled by Chrome for security
- Permissions aligned with extension functionality
- No suspicious pop-ups or abnormal browser behavior observed

---

## ⚠️ Potential Security Risks of Extensions

Even legitimate extensions can pose risks such as:

- Access to browsing history
- Ability to read and modify website data
- Credential harvesting
- Session hijacking
- Injection of malicious scripts

Extensions with permissions like:
- “Read and change all your data on all websites”
- “Access browsing history”
- “Access clipboard”

should always be carefully evaluated.

---

## ✅ Step 3: Action Taken

- Verified developer authenticity
- Checked user reviews and legitimacy
- Reviewed permissions for each extension
- Confirmed extensions were intentionally installed
- Restarted browser after audit

No malicious or suspicious extensions were identified during the audit.

---

## 📚 Key Learnings

- Browser extensions increase attack surface.
- Least privilege principle should be followed.
- Regular extension audits improve security posture.
- Trusted vendors do not eliminate all risk.

---

## 🎯 Conclusion

After conducting a detailed browser extension audit, no suspicious or malicious extensions were found.

The browser environment is currently secure and properly maintained.

---

## 🔐 Security Best Practices

- Install extensions only from official web stores
- Avoid unnecessary extensions
- Review permissions before installation
- Periodically audit installed extensions
- Keep browser and extensions updated
