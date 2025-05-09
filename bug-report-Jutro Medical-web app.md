# Bug Report: ID_01

## Title
**LOGIN PANEL** – The user can enter letters in the **'Your phone number'** field

## Description
The user can enter letters in the **'Your phone number'** field, even though this field should only accept digits. This is related to **PT.11**.

## Acceptance Criteria
In the **'Your phone number'** field, the user should be able to enter only **9 digits**.  
*Referencing the acceptance criteria from user stories/business requirements.*

## Environment

- **Operating System:** Windows 10 Home  
- **Browsers:**
  - Google Chrome: Version 131.0.6778.86  
  - Firefox: Version 133.0  
  - Opera: Version 114.0.5282.185  
  - Microsoft Edge: Version 131.0.2903.63  

## Steps to Reproduce

1. Go to the website: [https://doctor.st.jutromedical.com/](https://doctor.st.jutromedical.com/)
2. In the **'Your phone number'** field, enter `00000000O` (eight zeros and the letter "O").

## Expected Result
A message should appear:  
**"The 'Your phone number' field may only contain digits."**

## Actual Result
There is no error message indicating that the field contains invalid characters.  
The message: **"Your phone number may only contain digits"** does not appear.

## Attachment
*None provided*

## Priority
**Low/Medium**

## Reported by
Ewelina Wisińska

## Date
05.04.2025

## Comment
This issue is related to the validation of the **'Your phone number'** field.  
The application currently allows letters to be entered, even though the field should only accept digits. The validation of this field needs to be improved so that the user cannot enter letters or any other invalid characters.
