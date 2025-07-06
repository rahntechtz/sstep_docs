# User Flow

## 1. Login
- User attempts to log in using **username/phonenumber** and **password**.
- After successful login:
  - Check if the user is **verified**.
    - If **verified**: Redirect to the **Dashboard**.
    - If **not verified**:
      - Send an **OTP**.
      - Redirect to the **OTP Verification** screen.

---

## 2. OTP Verification
- User can:
  - Enter the **OTP** to verify their account.
  - Request a **new OTP** if needed.

---

## 3. Password Change
- After first login, prompt the user to:
  - Change the **default (random) password**.
  - Use the **old password** during the update process.

---

## 4. New User Creation
- When a new user is created:
  - Generate a **random password**.
  - Send the **username and password** to the user (via email or SMS).

