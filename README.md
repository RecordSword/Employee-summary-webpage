# Employee-summary-webpage
This Application  generates an HTML webpage to display a team for a Manager to easily create. It will generate questions dependent on roles and create a webpage that can link to GitHub sites and email addresses.

## Summary of roles
4 roles: Employee, Manager, Engineer, Intern
EMPLOYEE role - All employees at the firm will have a common attribute

MANAGER role - extend Employee role
will have all of the properties for Employee role, plus the office Number

ENGINEER role - extend Employee role
will have all of the properties for Employee role, plus the GitHub username with link

INTERN role - extend Employee role
will have all of the properties for Employee role, plus the school they are based at.

## Installation
Run npm install to install all dependencies

Folder Structure
lib/           // classes and helper code
output/        // rendered output
templates/     // HTML template(s)
test/          // jest tests
  Employee.test.js
  Engineer.test.js
  Intern.test.js
  Manager.test.js
app.js         // Runs the application
Usage
Run node apps.js to start the application

Enter the number of users within your team

Enter the employees name > ENTER

Enter the employee's ID > ENTER

Enter the employee's email > ENTER

Select the employee's title > ENTER

If you selected Engineer, input their GitHub. If you selected Manager, input their office number. If you selected Intern, input their school

Repeat for all employees until you receive the "Success!" notification.

## Testing
run `npm run test watchAll'