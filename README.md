# Employee-Selector
🧠 Employee Selector
Short Description
Create a React component that displays a dropdown of employee names and shows detailed information when one is selected. The data should be both fetched from a remote URL and also provided as a local fallback constant in case the fetch fails.

Requirements
* Display a dropdown with employees’ full names (firstName + lastName).
* When an employee is selected, show:
  - First Name
  - Last Name
  - Document Number
  - Phone Number
* The employee list should be fetched from this URL:
  - https://s3.amazonaws.com/coderbyteprojectattachments/builders-095na-tacvhmm4-employees.json
* If the request fails, use a local constant array of employees instead.
* Use React state and hooks appropriately.

✅ Expected Behavior
* On page load, try to fetch the employee list.
* If successful, populate the dropdown with the remote data.
* If the request fails, fallback to the local constant.
* Display the selected employee’s details below the dropdown.
