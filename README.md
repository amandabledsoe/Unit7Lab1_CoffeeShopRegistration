This my solution for Unit 7: Lab 1 "Coffee Shop Registration" in the 2022 C# .NET After-Hours Boot Camp at Grand Circus.

# COFFEE SHOP REGISTRATION
### Objectives: 
- Introductory MVC

### Task: 
- Create a User Registration Form using the MVC framework. 

### What does the application do?
- The registration page will register a new user. The form should take in the user’s first and last name, email, and password.
- When submitted, the page should show the user a summary page with a message, such as Welcome {UserName}
- The Index View should have a link pointing to the registration page. (Tip: Try using tag helpers, specifically asp-controller and asp-action.)
- Go crazy! Design the form by adding different kinds of controls, such as text boxes, drop down lists, radio buttons, and check boxes. 

### Build Specifications
- Index page has a working link to the registration page (1 point).
- Registration page has a form with a valid action and method (1 point) and the four required fields (1 point each = 4 points).
- The C# function inside the controller takes all four fields correctly through GET or POST (2 points), then returns a view (1 point), passing the correct information along (1 point).
- Result page shows at least the user’s first name with a welcome message (1 point).

### Extra Challenges:
- Do form validation! 
- Example: If you want to explore HTML5 regular expression validation, go for it!
Or in your controller include code to validate using regular expressions, or any other methods you can come up with to do validation. Make up your own rules for a valid password.
