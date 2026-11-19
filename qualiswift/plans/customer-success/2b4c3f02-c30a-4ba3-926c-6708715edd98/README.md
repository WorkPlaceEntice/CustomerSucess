Qualiswift approved plan: OrangeHRM_Login2
Version 2 · SHA-256 5f298ace49335cbd651fa38c12caa15df7463257871196396dfab82f788a4c8c
1. Successful login with valid credentials
Case ID: TC-001
Story IDs: Login to OrangeHRM Using Valid Credentials, User should log in successfully with valid credentials, User should be redirected to the Dashboard, Dashboard should display the logged-in user's details, User should be able to access authorized modules
Preconditions: User is on the OrangeHRM login page
1. Navigate to the OrangeHRM login page at https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
2. Enter username as 'Admin'
3. Enter password as 'admin123'
4. Click the login button
Step Expected: User is logged in successfully, redirected to the Dashboard. The Dashboard displays the logged-in user's details and user can access authorized modules.
Test Data: Username: Admin, Password: admin123
Expected: User is logged in successfully, redirected to the Dashboard. The Dashboard displays the logged-in user's details and user can access authorized modules.
2. Verify Dashboard displays logged-in user details after successful login
Case ID: TC-007
Story IDs: Dashboard should display the logged-in user's details
Preconditions: User is successfully logged in
1. Log in with valid credentials (Admin / admin123)
2. Observe the Dashboard page
Step Expected: Dashboard displays correct logged-in user details such as username and possibly user role or name as specified by the application.
Test Data: Username: Admin, Password: admin123
Expected: Dashboard displays correct logged-in user details such as username and possibly user role or name as specified by the application.
