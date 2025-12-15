# Locator-Object-Interaction-Examples-with-Playwright
This test file demonstrates the use of Playwright's Locator API methods in a structured test suite. Each test focuses on interacting with different types of UI elements—checkboxes, radio buttons, and dropdowns—while ensuring they respond as expected.

🔁 beforeEach Hook
Navigates to https://practice.cydeo.com/ before each test using page.goto().


✅ Test: Check()
Purpose:
Ensures a checkbox (box1) is checked using the .check() method.

Steps:
Clicks on the "Checkboxes" link.
Locates checkbox with id="box1".
Calls .check() on it.


❌ Test: Uncheck()
Purpose:
Ensures a checkbox (box2) is unchecked using .uncheck().

Steps:
Navigates to the "Checkboxes" section.
Locates checkbox with id="box2".
Calls .uncheck() to toggle it off.

🔽 Test: SelectOption()
Purpose:
Demonstrates how to select options from a <select> dropdown menu using .selectOption().

Steps:
Clicks the "Dropdown" link on the homepage.
Locates a select element with id="dropdown".
Selects the second option using selectOption({ index: 1 }).

🛠 Key Concepts Covered
page.locator() for targeting elements.
page.getByText() for selecting visible text.
Locator methods like .check(), .uncheck(), and .selectOption().
