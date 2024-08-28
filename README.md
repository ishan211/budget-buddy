
# Budget Buddy

Welcome to Budget Buddy, a personal finance management app made in HTML, CSS, and JavaScript. This project was developed as part of a series of iterative updates to create a feature-rich budget management tool while enhancing my web development skills. The application allows users to track their income and expenses, visualize their financial data, and manage their budget effectively, with persistent storage for data across sessions.

### Features:

* **User Authentication:** Each user can log in with a unique username, and their financial data is stored separately, allowing multiple users to manage their budgets independently.
* **Add, Edit, and Delete Transactions:** Users can easily add new income or expense entries, edit existing transactions, or delete them as needed.
* **Category and Date Management:** Transactions can be categorized (e.g., Food, Entertainment, Bills) and dated, providing a detailed overview of spending habits over time.
* **Filter Transactions:** Users can filter transactions by date range and category to analyze specific spending patterns.
* **Summary Dashboard:** Visualize income versus expenses with a dynamic doughnut chart powered by Chart.js, providing a clear snapshot of financial health.
* **Responsive Design:** The app is fully responsive, ensuring a seamless experience on both desktop and mobile devices.
* **Persistent Storage:** All transaction data is saved in the browser's local storage, ensuring it remains available even after the page is refreshed or the browser is closed.

### How to Use Budget Buddy:

1) **Clone the Repository:**
   ```
   git clone https://github.com/ishan211/budget-buddy.git
   ```

2) **Open the Application:**
   - Navigate to the project directory and open the `index.html` file in your preferred web browser.

3) **Login to Start Managing Your Budget:**
   - Enter a username in the login field and click "Login". This will create a session for you, where your financial data will be stored separately from other users.

4) **Add a New Transaction:**
   - To add a new transaction, enter the description, amount, and date of the transaction, select a category from the dropdown menu, and click "Add". The transaction will be added to your list and the summary dashboard will be updated accordingly.

5) **Edit or Delete a Transaction:**
   - You can edit a transaction by clicking the blue "Edit" button (pencil icon) next to the transaction you wish to modify. After editing the details, click "Add" to save the changes. To delete a transaction, click the red "Delete" button (X icon) next to it.

6) **Filter Transactions:**
   - To filter transactions, enter a date range and/or select a category from the dropdown menus in the filter section. Click "Filter" to see only the transactions that match your criteria.

7) **Logout:**
   - When you’re done managing your budget, click the "Logout" button in the summary section to safely end your session. Your data will be saved and available the next time you log in.

### Project Purpose:

The development of this Budget Buddy allowed me to deepen my understanding of JavaScript, particularly in managing dynamic data with local storage, implementing user authentication, and integrating third-party libraries like Chart.js for data visualization. The project also provided an opportunity to practice responsive web design, ensuring a consistent user experience across different devices.
