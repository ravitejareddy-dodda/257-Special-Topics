Part-1:

Task performed: Performed Data Science using chatgpt code interpreter by picking a popular data set in kaggle website. Here I have picked up spotify dataset for Data Analysis.

Link to the chat that is performed using GPT4: https://chat.openai.com/share/ffca6ff4-e34c-42d4-9dc7-3f04a681e614

Generated a report in medium.com and added screenshots: https://medium.com/@ravitejareddy.dodda/data-driven-insights-from-spotifys-2023-dataset-a-comprehensive-analysis-a11ddaf7ac2d

Part-2: 

Explored the capabilities of GitHub Copilot within Visual Studio Code. ALso necessary environment has been setup, generated a project using GPT-Engineer, and created a screencast demonstrating various use cases of GitHub Copilot.

Created a web application similar to Splitwise that allows users to track shared expenses among friends. The application have user authentication, the ability to add friends, record expenses, and settle up. It also provide a dashboard showing who owes what to whom.

Uploaded code files: https://github.com/ravitejareddy-dodda/297-Special-Topics/blob/main/Assignment1.zip

Code file description: 

app.py: Main entry point or the Flask application file.
split.py, modified_split.py, solid_split.py: Different versions or implementations of the Splitwise-like functionality.
unit.py: Contains unit tests for the application.
static: Typically, in Flask applications, this directory contains static files like CSS, JS, and images.
templates: This directory likely contains HTML templates used for rendering the web pages.

Class Definitions:
User: Represents a user with attributes such as name, email, and password.
Expense: Represents an expense and includes details like description, amount, payer, and participants.
Payment: Represents a payment transaction between users.
Group: Represents a group of users. It has a list of expenses and payments associated with that group. There's also a method to add an expense and update the balance.

Group Class Methods:
add_expense: Adds an expense to the group. The expense details include description, amount, payer, and participants.
add_payment: Adds a payment transaction to the group, detailing the amount, payer, and payee.
update_balances: This method recalculates the balances for each member in the group based on the expenses and payments.





