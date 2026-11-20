# AI Expense Management Agent

## Project Overview
The **AI Expense Management Agent** is a Generative AI-based application developed using Python and Google Colab. It helps users record, categorize, monitor, and analyze their daily expenses. The system provides expense summaries, graphical visualizations, budget tracking, and AI-powered recommendations to help users manage their finances effectively and improve their saving habits.

## Features

- **Add Expenses:** Record daily expenses with descriptions, amounts, and dates.
- **Automatic Categorization:** Categorize expenses into Food, Travel, Shopping, Education, Healthcare, Entertainment, Utilities, and Others.
- **Expense Analysis:** Calculate total expenditure and category-wise spending.
- **Budget Tracking:** Monitor expenses against the monthly budget.
- **Data Visualization:** Display expense reports using pie charts and bar charts.
- **AI Recommendations:** Generate suggestions to reduce unnecessary expenses and improve savings.
- **AI Expense Assistant:** Ask questions about spending habits and receive AI-generated responses.
- **Export Reports:** Download expense records in CSV format.

## Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Google Gemini API (Optional)
- Generative AI

## Project Requirements

- Google Account
- Google Colab
- Python 3.x
- Internet connection
- Gemini API Key (Optional, for Generative AI features)

## Installation and Execution

### Step 1: Open Google Colab
Visit [Google Colab](https://colab.research.google.com/) and create a new notebook.

### Step 2: Upload the Project Code
Copy the Python code into Google Colab cells or upload the project notebook.

### Step 3: Install Required Libraries

```python
!pip install pandas matplotlib google-genai
```

### Step 4: Configure Gemini API (Optional)

To enable Generative AI-powered recommendations and responses, configure your Gemini API key in the notebook.

### Step 5: Run the Notebook
Execute all cells in sequence and use the interactive menu to manage your expenses.

## Sample Expense Records

| Expense Description | Amount (₹) | Category |
|---|---:|---|
| Lunch at Restaurant | 250 | Food |
| Petrol for Bike | 500 | Travel |
| Python Programming Book | 700 | Education |
| Shopping Clothes | 1,500 | Shopping |
| Movie Ticket | 300 | Entertainment |
| Doctor Consultation | 800 | Healthcare |
| Electricity Bill | 1,200 | Utilities |
| Dinner at Restaurant | 450 | Food |

## Available Operations

1. Add New Expense
2. View All Expenses
3. Analyze Expenses
4. Visualize Expenses
5. Get AI Budget Recommendations
6. Ask AI Expense Assistant
7. Change Monthly Budget
8. Export Expense Report
9. Exit

## Project Workflow

1. User enters daily expense details.
2. The system automatically categorizes each expense.
3. Expense records are stored in a Pandas DataFrame.
4. The system calculates total and category-wise expenditure.
5. Graphical reports display spending patterns.
6. The AI assistant provides budget recommendations and answers expense-related questions.
7. Users can export their expense records as a CSV file.

## Future Enhancements

- Integration with a database for permanent data storage.
- Development of a web-based user interface.
- Monthly and yearly expense reports.
- Expense prediction using Machine Learning.
- Integration with banking and payment applications.
- Personalized financial planning and saving recommendations.

## Limitations

- Expense records are stored temporarily in notebook memory.
- Data may be lost when the Google Colab runtime is restarted unless exported.
- Gemini API features require an API key.
- Expense categorization may require improvement for unusual descriptions.

## Author

**Project:** AI Expense Management Agent  
**Department:** CSE-AIML  
**Institution:** Parul Institute of Engineering and Technology (PIET), Parul University

## License

This project is developed for educational and academic purposes. You are welcome to explore, modify, and enhance the project.
