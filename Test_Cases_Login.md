# Login Feature Test Cases

Project: Demo Web Application

Module: User Login

Tester: Leonardo Cadena

---

## TC-001

### Verify login with valid credentials

**Preconditions**

- User account exists.

**Steps**

1. Open the Login page.
2. Enter a valid email.
3. Enter a valid password.
4. Click Login.

**Expected Result**

User is redirected to the Dashboard.

---

## TC-002

### Verify login with invalid password

**Preconditions**

- User account exists.

**Steps**

1. Open Login page.
2. Enter a valid email.
3. Enter an invalid password.
4. Click Login.

**Expected Result**

An error message is displayed informing that the credentials are incorrect.

---

## TC-003

### Verify login with empty fields

**Steps**

1. Open Login page.
2. Leave email empty.
3. Leave password empty.
4. Click Login.

**Expected Result**

Validation messages should appear for the required fields.
