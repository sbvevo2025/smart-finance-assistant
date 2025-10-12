**WEEK 8**
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

- "Spending at a Glance" section for spending analysis
- Total spending calculations from data
- Average transaction from data

- Top spending category from data
- Top category and spending amounts + percentages
- Seperate section for "Top Spending Category with details and percentages

- Actionable advice section
- Summary of spending analysis
- Basic insights into each transaction in data

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

**WEEK 9**
```markdown

### AI Collaboration #4
**Context**: Setting up a financial bot assistant as required of the assessment outline
**Prompt**: Help me create a system prompt for a friendly, professional financial advisor chatbot that can provide spending advice based on transaction analysis. The personality should be encouraging but practical.


**Result**: Descriptive financial bot assistant description reading "You are FinBot, a friendly and professional financial advisor. Your personality traits:
    - Encouraging but practical
    - Non-judgmental and supportive
    - Focuses on actionable advice
    - Explains financial concepts simply
    
    Your expertise:
    - Analyzing spending patterns from transaction data
    - Identifying budget optimization opportunities
    - Providing personalized savings recommendations
    - Offering practical money management tips
    
    Response style:
    - Start with empathy and understanding
    - Provide clear, step-by-step advice
    - Use examples when explaining concepts
    - End with an encouraging note or next steps"
**Reflection**: AI gave a detailed description of the FinBot AI, with the bot working correctly as planned

### AI Collaboration #5
**Context**: Implementing RAG system for financial document retrieval
**Prompt**: Help me set up a RAG system for financial documents and transaction data with keyword matching for different financial topics:
Setup
- RAG system setup
- Print setup message

Dictionaries
- Budgeting Strategies
- Savings Tips
- Spending Reduction Strategies
- Debt/Liability Management

Search Function
- Make question lowercase
- If question has "budget" words, return budgeting tips
- If question has "save" words, return savings tips
- If question has "spending" words, return spending tips
- If question has "debt" words, return debt tips
- Else --> return all tips

Personalised Advice Function
- Access to Data
- User Data Available:
 - Access top spending category
 - Message include "YOUR Top Spending is (Blank)"
 - Advice based on spending category
- Generate general tips
- Add personalised message
- Return response

Main Function
- Load transactions
- Analyse spending
- Return personalised advice
- Error --> return error message

FinBot Question
- Load user data from CSV
- Create context from spending info present
- AI reponse

Testing
- Setup system
- Test questions with RAG
- Test questions with FinBot

**Result**: A complete RAG implementation with appropriate financial information (budgeting strategies, savings tips, spending reduction, debt management) and keyword-based retrieval system that provides personalized advice based on transaction data.
**Reflection**: The RAG system successfully integrates financial knowledge with personalized spending insights, creating a responsive advice system.

### AI Collaboration #6
Context: Creating custom financial calculator tools for the finance assistant AI 
Prompt: Create a savings goal calculator function that takes current savings, monthly contribution, and target amount, then calculates time to reach goal. Format output for user-friendly display:

Savings Goal Calculator
- Check data is valid (exclude negative variables)
- Calculate months required to reach goal (interest included)
- If function takes too long --> cancel function and display error
- Show completion date
- Calculate total income and interest earned
- Format with timeline and additional tips

Budget Calculator
- Check percentages calculate total to 100%
- Calculate moeny for needs, wants and savings
- Calculate yearly totals
- Format output with categories and tips

Emergency Fund Calculator
- Check variables are positive
- Calculate target amount
- Show different savings timelines
- Format output with importance and steps

Register Tools
- Register all calculators to system
- If method fails, try alternate method
- Print success message with the tool names

Testing
- Test savings calculator with examples
- Test budget calculator with $4000 income
- Test emergency fund with $2500 expense
- Register all tools and print results


Result: Three extensive detail and comprehensive financial tools, with proper inputs, formulas and professionally formatt by AI.
Reflection: AI successfully created robust calculator tools that handle real financial calculations with proper error checking and user-friendly output formatting.

### AI Collaboration #7
Context: Creating a comprehensive Gradio user interface to integrate all finance assistant components
Prompt: Help me design a Gradio interface that combines CSV upload, spending analysis, chat functionality, and custom tools in a user-friendly layout suitable for a personal finance application:

User Interface
- Professional CSS style
- AI Chat History to be stored

File Processing Function
- Check if CSV file is uploaded
- Load and Clean CSV data
- Analyse data and spending patterns
- Generate recommendations
- Format into HTML

FinBot
- Textboxt to chat to AI
- Add user message to history
- Get AI response
- Update history
- Return response and update chat

Calculator Function
- Convert inputs to numericals
- Handle errors
- Return results in format

Create Interface
- Setup interface with professional layout
- Create various tabs for different features of financial assistant

Tab 1: Spending Analysis
- File upload option
- Display results
- Recommendations in textbox next to results
- Connect upload to processing function

Tab 2: Financial Bot (FinBot)
- Display chatbot interface
- Message textbox to enter input message
- Send and clear button
- Connects button to chat functions

Tab 3: Financial Calculators
- Savings calculator with inputs
- Budget calculator with slide
- Emergency fund calculator

Tab 4: About/Help Section
- Application description
- Usage instructions
- CSV format for samples

Launch Application
- Launch in browser

### AI Collaboration #8
Context: Creating comprehensive test suite to validate all finance assistant functions
Prompt: Create realistic test datasets for a finance assistant including normal spending data, edge cases, data quality issues, and business scenarios. Create assert statements to test data loading, spending analysis, and business insights with proper error handling and validation:

Test Datasets
- Data: Regular spending
- Edge Case: Refunds, zero amounts, negatives, large amounts
- Data Issues: Invalid dates, unidentifiable variables, missing values
- Business scenarios: High spending amounts and patterns
- Save as CSV files

Test Dataset Loading
- CSV with dollar signs to correctly function
- Missing columns --> show error
- Invalid file --> show error
- Mixed good/bad data --> should handle valid and invalid datasets

Test Analysis
- Totals and Averages to be calculated correctly
- Refunds --> handle as negative amounts
- Single Transaction --> works as one row
- Empty Data --> show error message

Test Business Insights
- High spending --> detect and notify user
- Example transaction insights (ex. coffee spending)
- Output format --> has correct insight sections
- Error handling --> shows error message

Run Tests
- Create Datasets
- Test and Load Datasets
- Run Analysis Tests
- Run Business Insights Test
- Print Results

Result: Complete testing framework with multiple test datasets, unit tests for all core functions, edge case handling, and professional test reporting that validates data loading, analysis calculations, and recommendation generation
Reflection: AI successfully created a robust testing suite that thoroughly validates all system components with realistic scenarios and proper error handling, demonstrating comprehensive quality assurance


Result: Professional multi-tab interface with spending analysis, financial chat, calculator tools, and about section featuring proper styling, responsive layout, and seamless integration of all system components
Reflection: AI successfully created a polished, user-friendly interface that effectively combines all the finance assistant features into a cohesive web application with professional styling and intuitive navigation
```

