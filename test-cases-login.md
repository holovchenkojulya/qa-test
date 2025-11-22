Test Cases: Login

**TC-001: Successful login with valid credentials**
**Preconditions:**
- User is registered in the system

**Steps:**
1. Open the login page
2. Enter valid email
3. Enter valid password
4. Click "Login" button

**Expected result:**
- User is redirected to the dashboard
- User name is visible in the header

---

**TC-002: Login with invalid password**
**Steps:**
1. Open the login page
2. Enter valid email
3. Enter invalid password
4. Click "Login"

**Expected result:**
- User stays on the login page
- Error message is shown: "Invalid email or password"
