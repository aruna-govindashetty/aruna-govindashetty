#### List of ideas for testing Monefy App based on Priority

##### Blocker
- Add an expense.
- Edit an expense.
- Delete an expense.
- Select different currencies.
- Choose a language.
- Add an Income.
- Cross-platform testing.
- Cross-browser testing.
- Verify the export functionality.
- Verify the About information and the links inside that.
- Verify data backup functionality.
- Verify the calculator functions.
- Verify budget mode.
- Verify carry over mode.
- Verify multiple accounts.

##### Critical
- Verify all added categories are displayed in the chart.
- Check the balance.
- Verify the chart for spending distribution.
- Verify Transactions list for detailed info.
- Verify initial balance and expense.
- Verify records displayed based on date/month/year or all.
- Verify incoming and outgoing calls, SMS, and MMS.
- Verify battery discharge/removal while using app.
- Verify disconnecting and connecting to the network/Wi-Fi while using app.
- Verify all user data is saved after updates.
- Make sure that the application can be terminated by any state and that it resumes operation in the same state.
- Verify responsiveness of applications on different devices.
- Checking the response time of the application to various types of requests.

##### Minor
- Check for defaults.
- Verify the validation message when date is greater than today's date.
- Set first day of the week.
- Set first day of the month.
- Check application reviews.
- Verify the validation message when no records are available.
- Check the delimiter in numbers.
- Add duplicate data and verify the error message.
- The installation of the application should take place without significant errors.
- Verify the application automatically starts correctly.
- Verify the required fields work correctly.
- Make sure that mandatory and optional fields are displayed in different ways.
- Verify that the buttons are of the normal size and placed in one area of the screen.
- Check the navigation of the important application modules.
- Ensure the icons and pictures look natural in the app environment.
- Verify the color of the buttons that perform the same function is the same.
- The text should be simple, clear and visible to the user. 
- Verify the font size.
- Ensure correct operation of the Zoom-in and Zoom-out system.
- Verify the context menus are not overloaded.
- Ensure that the application components are synchronized with the user’s actions.
- Verify the speed of response of the element is high enough.
- Test the main design elements: buttons, icons, colors, links, fonts, font sizes, layout, text boxes, text formatting, labels, captions, buttons, lists etc.
- Verify all elements display with portrait and landscape page orientation.
- Verify advertising does not overlap application control buttons.
- Ensure the advertising has an accessible closing button.
- Testing the working capacity of the application at loads exceeding the user’s several times.
- Examine the operability of the application for long time work, under normal load.
- Determine the number of users who can simultaneously work with the application. 
- Determine whether the application is running the same under different network conditions.
- Evaluate the ability of the app to cope with planned load volumes.
- Verify the effective recovery of the application after unforeseen crash scenarios.
- Verify the ability of the application to process transactions in the event of a power failure (low battery, incorrect application shutdown, etc.).

#### Best Buy API - Summary of the solution
###### Best Buy API for Products:
- I have used Visual Studio + Specflow + C# to build the solution.
- I have defined testcases in BDD style as it makes tests more readable and easy.
- I have tested Product API by writing few positive and negative scenarios.
- FeatureFile folder in the solution contains testcases for product API in Gherkin syntax.
- Helper folder contains some generic functions which can be used through out the 
program.
- StepDefinition folder contains actual implementation of the test cases defined.



