# Expense Tracker App

This is a simple Transaction Management App built with React. The app allows users to track their income and expenses, view their balance, and manage transactions efficiently.

## Features

- **Balance Display:** View the current balance based on income and expenses.
- **Income and Expenses Summary:** See a breakdown of total income and expenses.
- **Transaction List:** View a list of all transactions with details.
- **Add Transaction:** Add new income or expense transactions to the list.
- **Global State Management:** The app uses context API for global state management.

## Technologies Used

- **React:** A JavaScript library for building user interfaces.
- **Context API:** Used for state management to handle global state.
- **CSS:** Used for styling components.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm (Node Package Manager)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Abhishekabym/Expense-Tracker.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd Expense-Tracker-app
   ```

3. **Install the dependencies:**

   ```bash
   npm install
   ```

### Running the App

To start the app, run the following command:

```bash
npm start
```

The app will run in development mode, and you can view it in the browser at `http://localhost:3000`.

### Project Structure

- **`src/`**: Contains all the source code for the app.
  - **`components/`**: Contains React components such as `Header`, `Balance`, `IncomeExpenses`, `TranscationList`, and `AddTranscation`.
  - **`context/`**: Contains the global state management using the Context API.
  - **`App.js`**: The main component that brings everything together.
  - **`App.css`**: The CSS file for styling the components.

### Global State Management

The app uses the Context API for state management. The global state is provided by the `GlobalProvider` component in the `GlobalState` context.

### Customization

You can customize the app by modifying the components or styles in the `src/` directory.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
