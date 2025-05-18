# ✅ Test Case: User Login – Valid Credentials

**Test Case ID:** SW-001  
**Feature:** Login  
**Test Type:** Functional  
**Priority:** High  
**Created by:** Krizia Diaz  
**Last Updated:** [05/18/2025]

---

## 🎯 Objective

Verify that a registered user can successfully log in with valid credentials.

---

## 🧾 Preconditions

- User account exists in the system
- User knows the correct email and password
- Browser is open, and the app is accessible

---

## 🔄 Test Steps

| Step | Action                                      | Expected Result                                     |
|------|---------------------------------------------|-----------------------------------------------------|
| 1    | Launch Southwest App                        | Login screen is displayed                           |
| 2    | Enter valid usernanme or account number     | Either username or account number is accepted       |
| 3    | Enter valid password in the password field  | Password is accepted                                |
| 4    | Click the "Login" or "Submit" button        | User is redirected to the dashboard/homepage        |

---

## ✅ Expected Result

User is successfully logged in and redirected to the dashboard.

---

## ❗Postconditions

- User is logged in and session begins
- User has access to their account features

---

## 🐞 Notes / Edge Cases

- Verify error does *not* appear for valid input  
- Confirm user is redirected properly (no loop or error)  
- Test on multiple browsers and os (Chrome, Safari, Firefox, iOS/iPadOS/Android)
