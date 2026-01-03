# HULM Solutions - Website Quality Assurance Project

## 📌 Project Overview
**HULM Solutions** (https://hulmsolutions.com/) is a corporate web platform showcasing IT consultancy and software solutions. This repository contains the complete Quality Assurance (QA) documentation, detailing the manual testing lifecycle to ensure the website's professional integrity, lead generation functionality, and mobile responsiveness.

**Client:** HULM Solutions
**QA Focus:** Web Functionality, Lead Form Validation, Cross-Browser Compatibility, and UI/UX consistency.

## 📂 Repository Structure
This repository organizes the testing artifacts into the following categories:
* **Test Plans:** Strategy outlining the scope (Home, Services, Contact, About Us).
* **Test Cases:** Detailed steps for validating UI elements and functional workflows.
* **Bug Reports:** Documented defects regarding broken links, layout shifts, and form errors.
* **Execution Logs:** Pass/Fail records for each module.

## 📊 Test Statistics & Analysis
*Note: These statistics represent the testing outcomes from the [Month/Year] cycle.*

### **Test Coverage**
| Metric | Count |
| :--- | :--- |
| **Total Modules Tested** | 5 (Home, Services, About, Contact, Careers) |
| **Test Cases Executed** | [Insert Count, e.g., 120+] |
| **Browsers Tested** | Google Chrome, Microsoft Edge, Safari |
| **Device Viewports** | Desktop (1920x1080), Mobile (375x667) |

### **Module Stability Status**
| Module | Status | Observations |
| :--- | :--- | :--- |
| **Home Page** | 🟢 **Stable** | Hero sections and navigation links function correctly. |
| **Contact Us** | 🟡 **Mixed** | Form submits, but validation for "Business Email" is weak. |
| **Services** | 🟢 **Stable** | Service cards and internal linking are accurate. |
| **Mobile UI** | 🔴 **Unstable** | Hamburger menu behaves inconsistently on smaller screens. |

## 🐞 Defect Highlights
The following critical issues were identified and reported during the testing phase:

1.  **Contact Form Validation:**
    * *Issue:* The "Contact Us" form accepts invalid email formats (e.g., `user@domain` without `.com`) and submits successfully.
    * *Impact:* Potential loss of client leads and data clutter.

2.  **Responsiveness (Mobile View):**
    * *Issue:* The footer content overlaps with the body text on devices with < 375px width.
    * *Impact:* Poor user experience for mobile visitors.

3.  **Broken Navigation Links:**
    * *Issue:* The "Get Started" CTA on the Services page redirects to a 404 error instead of the Inquiry page.
    * *Severity:* High (Conversion blocker).

## 🧪 Tools & Methodologies
* **Manual Testing:** Exploratory testing for UI/UX issues.
* **Cross-Browser Testing:** Verified consistency across Chromium and WebKit browsers.
* **Bug Tracking:** Defects logged with severity/priority levels in Excel.
* **Chrome DevTools:** Used for inspecting element responsiveness and console errors.

## 📝 Author
**Meesum**
*QA Engineer*

---
*This project demonstrates proficiency in Web Application Testing, Defect Lifecycle Management, and Client-Facing Documentation.*
