# Family Expense Tracker

## Introduction
The **Family Expense Tracker** is an application designed to track and manage family expenses efficiently. It allows users to add monthly expenses categorized into different sections such as rent, utilities, groceries, etc. The system maintains a detailed record of individual and family expenses using **linked lists** to ensure efficient data management.

## Features
- **Add Users:** Users are added and stored in a sorted manner based on their User ID.
- **Add Expenses:** Expenses are stored in a sorted manner by User ID and then by Expense ID.
- **Create Families:** Users belong to families (1-4 members), and total monthly expenses and incomes are automatically calculated.
- **Update/Delete Individual or Family Details:** Updates to an individual reflect in the family details. If a single-member family is deleted, the family is also removed.
- **Update/Delete Expenses:** Modifications to expenses update all dependent records.
- **Get Total Expense:** Displays total family expenses and checks if it surpasses the family income.
- **Get Categorical Expense:** Shows total family expense for a specific category, along with individual contributions.
- **Get Highest Expense Day:** Identifies the date with the highest family expenditure.
- **Get Individual Expense:** Shows a user's total monthly expenses and category-wise breakdown in descending order.

## Data Structures Used
- **Singly/Doubly Linked Lists:** Used to store individual, family, and expense details efficiently.
- **Stack & Queue ADTs:** Used where necessary to optimize operations.

## Data Management
- Initial data of **25 individuals, 10 families, and 40 expenses** is loaded from a file.
- Assumptions:
  - Maximum **1000 users** and **1000 expenses**.
  - Maximum **100 families**.
  - Expenses and incomes are stored as **floating-point numbers (2 decimal places).**

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/family-expense-tracker.git
   ```
2. Compile and run the program:
   ```sh
   g++ expense_tracker.cpp -o expense_tracker
   ./expense_tracker
   ```

## File Structure
- `expense_tracker.cpp` - Main implementation of the expense tracker.
- `data.txt` - File containing initial dataset.
- `README.md` - Project documentation.

## Future Enhancements
- Implement a **graphical user interface (GUI)**.
- Integrate a **database** for better data management.
- Add **real-time tracking** with WebSockets.
- Provide **export options** (CSV, JSON) for expense reports.

## Contributors
- **[Rajas Daryapurkar]** - [Luytheti](https://github.com/Luytheti)

## License
This project is licensed under the **MIT License**.

---

