Expense Tracker
Introduction
The Expense Tracker is a web application for tracking expenses, allowing users to add, edit, and delete expenses based on category and date, as well as view a summary of their expenses. The application ensures that users do not spend more than their available wallet balance, which starts at a default value of 5000 and can be increased. The app also features responsive design for various screen sizes.

Features
Wallet Balance
Default Balance: Set to 5000.
Increase Balance: Users can add more funds to the wallet.
Spending Restriction: Users cannot spend more than their available wallet balance. An alert is shown if a user tries to do so.
Expense Management
Add Expenses: Users can add new expenses with details like title, amount, category, and date.
Edit Expenses: Users can edit existing expenses.
Delete Expenses: Users can delete expenses.
Update Wallet Balance: The wallet balance updates accordingly with each expense added or removed.
Expense Summary and Trends
Summary: View a summary of total expenses, categorized by date or type.
Expense Trends: Display a bar chart showing spending trends based on category.
Pie Chart: Show a summary of total expenses in a pie chart.
Persistence
LocalStorage: Wallet balance and list of expenses are persisted in localStorage to maintain state upon page refresh.
Responsive Design
Usability: The application is usable on different devices and screen sizes.
Functional Requirements
Add Expense Form
Provide fields for title, amount, category, and date.
Validate required fields.
Add Income Form
Provide a field for adding balance to the wallet.
Expense List
Display a list of expenses with options to edit or delete each expense.
Expense Summary
Show a summary of total expenses in a pie chart.
Expense Trends
Show a bar chart that shows the trending spends based on category.
Edit/Delete
Allow users to edit or delete expenses.
Responsive Design
Ensure the application is usable on different devices.
Technologies
Frontend: React.JS, HTML, CSS, JavaScript
Charts: Recharts (for pie and bar charts)
Modals: react-modal
Alerts: notistack
Icons: react-icons
Styling: Plain CSS (no third-party libraries for CSS)
Contributing
Contributions are welcome! Please fork the repository and submit a pull request for review.

License
This project is licensed under the MIT License.

Acknowledgements
ReactJS
Recharts
react-modal
notistack
react-icons
Node.js
Contact
For any questions or feedback, please contact officialrohitguru@gmail.com
# Expense-Tracker
