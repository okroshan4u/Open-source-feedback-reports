# HackerOne UI Issue – Weakness Dropdown Extends Beyond View

## 📋 Overview

This repository documents a **UI usability issue** found on the [HackerOne](https://hackerone.com) platform. While submitting a vulnerability report, users encounter a problem with the **Weakness Type** dropdown. The list of options extends beyond the visible screen area, making it difficult or impossible to select certain options without scrolling the entire page.

---

## ✅ Issue Details

- **Affected Page:** `https://hackerone.com/<program>/reports/new?type=team&report_type=vulnerability`  
- **Domain:** `hackerone.com`  
- **Impact:** Users cannot easily select the correct weakness, leading to incomplete or inaccurate reports, which can affect data integrity and user privacy.
- **Severity:** Low to Medium – usability issue that can disrupt report submission.

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

(Screenshots are available in this repository to demonstrate how the dropdown is cut off and unusable.)
![image alt](https://github.com/okroshan4u/Open-source-feedback-reports/blob/6259014a39cea0df0ac89a40358393e4184628aa/hackerone/1.jpg)

---

## 📂 Potential Security Impact

While this is primarily a UI issue, it may:
- Prevent users from selecting the correct vulnerability type.
- Lead to incomplete or inaccurate reports.
- Affect the integrity and confidentiality of sensitive information shared in the report.

---

## 📬 Reporting

This issue has been submitted to HackerOne’s support for review. It is categorized as a **Privacy Violation (CWE-359)** with **Low Confidentiality and Integrity Impact**.

---

## 📖 License

This repository is for educational and reporting purposes. Feel free to explore the documentation and learn how usability issues can indirectly impact security.

---

## 📞 Contact

For questions or feedback, reach out at:  
`okroshan4u@gmail.com`

