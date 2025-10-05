
```markdown

### AI Collaboration #1
**Context**: Setting up a basic CSV as the starting phase of the assignment allowing the CSV information to be stored on the colab.
**Prompt**: Can you create a Data Loading and Cleaning Function for the transactions.csv with the below as a template, and using the pseudocode below:
- Read CSV file
- IF columns missing return "Invalid Data"
- Use columns (Date, Amount, Category, Description)

- Remove dollar signs from values
- Convert amount ot numeric values
- Convert refunds as negative values

# 🤖 AI Collaboration: Data Loading and Cleaning Function# Ask AI to help you create a robust data loading functiondef load_and_clean_transaction_data(file_path):
    """
    Load and clean transaction data for the Smart Finance Assistant

    🤖 AI Collaboration Prompt:
    "Create a function to load CSV transaction data with Date, Amount, Category,
    Description columns. Handle dollar signs in Amount, missing values, and
    data validation. Include clear business-focused error messages."

    Args:
        file_path: Path to CSV file or file object
    Returns:
        pandas.DataFrame: Cleaned transaction data
    """
    # Your AI-assisted implementation goes here
    # Replace this placeholder with AI-generated code
    pass# Test your function# clean_data = load_and_clean_transaction_data(df_sample)# print(clean_data)

Loads the CSV data
Cleans and validates the data
Shows basic information about the dataset
Handles any common data issues

**Result**: Working pandas code with data cleaning and summary statistics.
**Reflection**: AI provided excellent starting code for the assignment's foundations.

### AI Collaboration #2
**Context**: Building upon the CSV with categorisation of expenses
**Prompt**: Can you create a Spending Analysis Function for the transactions.csv and actually reference it with the below as a template and using this pseudocode: 

- Remove dollar signs from values
- Convert amount ot numeric values
- Convert refunds as negative values

- Find total spending
- Find average spending
- Group transactions by columns

# 🤖 AI Collaboration: Spending Analysis Function# Ask AI to help you create comprehensive spending analysisdef analyze_spending_patterns(df):
    """
    Analyze spending patterns and generate business insights

    🤖 AI Collaboration Prompt:
    "Create a function that analyzes spending by category, calculates percentages,
    identifies top spending areas, and generates actionable financial insights
    formatted for business presentation."

    Args:
        df: Cleaned transaction DataFrame
    Returns:
        dict: Analysis results and insights
    """
    # Your AI-assisted implementation goes here
    # Include: totals by category, percentages, business insights
    pass# Test your function# analysis = analyze_spending_patterns(clean_data)# print(analysis)

Calculate total spending by category
Find the top 5 spending categories
Calculate average spending per transaction
Identify any unusual transactions (very high or negative amounts) Each function should have clear business explanations and error handling.

**Result**: Professional and reliable code building upon the foundations of the CSV integration.
**Reflection**: Gemini provided a detailed response with its code closely matching the criteria I asked to be included.

### AI Collaboration #3
**Context**: Creating a spending/expenses report for personal financing.
**Prompt**: Can you create a Business Insights Generator building on the previous code for the transactions.csv and actually reference it with the below as a template and using this pseudocode:  




- Calculate categories with high spending
- Calculate percentage of each column spending
- Give suggestions for saving opportunities

- Create a output summary
- Include totals and averages
- Add categories and insights

# 🤖 AI Collaboration: Business Insights Generator
# Ask AI to help create professional financial recommendations

def generate_financial_recommendations(analysis_data):
    """
    Generate actionable financial recommendations based on spending analysis

    🤖 AI Collaboration Prompt:
    "Based on spending analysis data, create professional financial
    recommendations. Include specific savings opportunities, spending
    pattern observations, and actionable advice formatted for a
    personal finance app user."

    Args:
        analysis_data: Dictionary with spending analysis results
    Returns:
        str: Formatted recommendations report
    """
    # Your AI-assisted implementation goes here
    # Focus on actionable, user-friendly advice
    pass

# Test your function
# recommendations = generate_financial_recommendations(analysis)
# print(recommendations)

**Result**: Highly well put together code with expenses categories and notes on spending activity.
**Reflection**: The code provided by Gemini closely matched with what I asked, with professional observations delving into various tasks.
```
---

✅ **Remember**: Document your AI collaboration throughout your project development. Each entry should show learning and improvement, not just successful interactions. Show how you direct AI like a junior developer to create business-appropriate solutions.

