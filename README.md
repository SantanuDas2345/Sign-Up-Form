# Form-Validation-React-Solution

## Form validation
Some financial company wants to collect their user's information to provide better users experience.
They want to make a login page to gather data but also at the same time they also want to prevent malicious users. Your job is to **create a simple login page** and prevent malicious users.
**Form validation** is a technique that checks the correctness of the user's data.
Form validation is required to prevent web-form abuse by malicious users.
You've seen that today a lot of website validates user's data before submission.
Ex: Newton school login page, Google form, etc.

Acceptance Criteria:
- Form must have the following Input Fields with given attributes:
    1) Name ```data-testid = 'name'```
    2) Email address ```data-testid = 'email'```
    3) Gender ```data-testid = 'gender'```
    3) Phone Number ```data-testid = 'phoneNumber'```
    4) Password ```data-testid = 'password'```
    5) Submit button ```data-testid = 'submit'```
- Accept Form only if the following criteria are satisfied:
  - All fields are compulsary to fill.
  - Name must be alphanumeric ({space} allowed)
  - Email must contain one and only one ```@```
  - Gender values must be ```male``` or ``` female```or ```other```.
  - Phone Number must be number
  - Password length at least should be 6.
- Display the users' mistake if he don't submit the form with proper inputs.
- Show only one error on the screen with the following priority
  - If any of the input fields are empty
  - Name Error
  - Email Error
  - Phone Number Error
  - Password Error
  - * Note: Provide useful information and point out users' mistakes so that it is easy for users to correct it. *
- After the form submitted successfully, extract the username from the Email address and display Hello ```{username} ```. For example: if the email address is zen@newtonschool.com then show ```Hello zen```.
- Do not clear input fields when wrong submission are made-only points out the errors.
