# README: User Login Test Case

## Overview
This README outlines the automated test case designed for verifying user login functionality on [Automation Exercise](http://automationexercise.com). It details the steps for successfully logging into the system with valid credentials and subsequently deleting the account to ensure the cleanup after the test.

## Tools and Technologies
- **Selenium WebDriver**: For automating web browser interaction.
- **Python**: Scripting language used to write the test.
- **Pytest**: Python testing framework used for structuring and running the test.

### Test Steps
1. **Launch the Browser**: Start a browser session using Chrome or Firefox.
2. **Navigate to URL**: Go to 'http://automationexercise.com'.
3. **Verify Home Page**: Ensure the home page of the site is loaded and visible.
4. **Navigate to Login**: Click on the 'Signup / Login' button to go to the login page.
5. **Check Login Section**: Verify the 'Login to your account' text is visible to confirm you are on the correct page.
6. **Enter Credentials**: Type in the correct email address and password into the respective fields.
7. **Submit Login**: Click the 'login' button to submit the login form.
8. **Confirm Login**: Check for the 'Logged in as username' text to verify successful login.
9. **Initiate Account Deletion**: Click on the 'Delete Account' button to remove the user account.
10. **Verify Account Deletion**: Confirm that the 'ACCOUNT DELETED!' message appears
