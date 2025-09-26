# HackerOne UI Issue – Weakness Dropdown Extends Beyond Viewport

## 📋 Overview

This repository documents a **UI usability issue** found on the [HackerOne](https://hackerone.com) platform. While submitting a vulnerability report, users encounter a problem with the **Weakness Type** dropdown. The list of options extends beyond the visible screen area, making it difficult or impossible to select certain options without scrolling the entire page.

---

## ✅ Issue Details

- **Affected Page:** `https://hackerone.com/<program>/reports/new?type=team&report_type=vulnerability`  
- **Domain:** `hackerone.com`  
- **Impact:** Users cannot easily select the correct weakness, leading to incomplete or inaccurate reports, which can affect data integrity and user privacy.  
- **Severity (initial triage):** Medium  
- **Final Severity (HackerOne decision):** None (Not Applicable)  
- **Status:** Closed  

---

## 📂 Steps to Reproduce

1. Visit the report submission page on HackerOne for any program (e.g., Snapchat).  
2. Scroll to the **Weakness** section.  
3. Click the **Select Weakness Type** dropdown.  
4. Observe that the dropdown extends beyond the viewport and cannot be fully accessed without scrolling the entire page.

---

## 🛠 Expected Behavior

The dropdown should:  
- Stay within the visible viewport, or  
- Allow internal scrolling so all options remain accessible without affecting the page layout.

---

## 📸 Screenshots

Screenshots are included in this repository to demonstrate how the dropdown is cut off and unusable.
![image_alt](https://github.com/okroshan4u/Open-source-feedback-reports/blob/3f9a33acc841f8573616884c1a308f8c087f3ca6/hackerone/screencapture-hackerone-bugs-2025-09-26-19_23_37.png)

---

## 📂 HackerOne Report Status

- The report **passed preliminary review** and entered triage.  
- Analysts later determined the issue was a **UI/UX bug** rather than a security vulnerability.  
- Severity was changed from **Medium → None** and the report was marked **Not Applicable**.  
- HackerOne suggested contacting **Customer Support** for non-security issues.  

---

## 📖 Note

Although this issue was closed as **Not Applicable** in the bounty program, it highlights how **UI/UX flaws can impact vulnerability reporting workflows** and why clear documentation is important.

---

## 📖 License

This repository is for educational and reporting purposes. Feel free to explore the documentation and learn how usability issues can indirectly affect security processes.

---

## 📞 Contact

For questions or feedback, reach out at:  
`okroshan4u@gmail.com`
