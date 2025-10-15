# ID_01 – [Digital Accessibility] Unable to accept the cookie consent banner using the keyboard

**Description:**  
Upon entering the website, the user encounters a cookie consent banner. Attempts to navigate the banner’s buttons using the Tab or Enter keys are unsuccessful. The keyboard focus remains in the background on the main page elements, preventing interaction with the banner.

**Environment:**  
- Operating System: Windows 10 Home  
- Browser Versions:  
  - Google Chrome: Version 139.0.7258.155  
  - Firefox: Version 142.0.1  
  - Opera: Version 120.0.5543.181  
  - Microsoft Edge: Version 140.0.3485.54  

**Preconditions:**  
The user has not previously accepted cookies or enters the site in incognito/private mode.

**Steps to Reproduce:**  
1. Navigate to [https://www.pekao.com.pl/](https://www.pekao.com.pl/)  
2. Attempt to close the cookie banner using keyboard keys (e.g., Tab, Enter).

**Expected Result:**  
- The user should be able to set focus on the buttons within the cookie banner (e.g., by pressing Tab).  
- It should be possible to accept or reject cookies using only the keyboard.

**Actual Result:**  
- The focus remains in the background on the main page elements.  
- The cookie banner covers the content, and it is not possible to accept or close it using the keyboard.

**Attachment:**  


**Reported by:** Ewelina Wisińska  
**Date:** 11.09.2025

**Notes:**  
Users relying solely on keyboard navigation cannot accept the cookie banner or access the site’s content.  
This issue may also affect users who are temporarily limited in mobility (e.g., due to a hand injury).

**Related WCAG Criteria:**  
- **2.1.1 Keyboard (A):** All functionality must be operable via a keyboard.  
- **2.4.3 Focus Order (A):** The focus must move in a logical order.  
- **2.4.7 Focus Visible (AA):** Keyboard focus should be visible to the user.
