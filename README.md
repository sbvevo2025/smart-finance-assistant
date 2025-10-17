# 📊 Sean Boland - Smart Finance Assistant

## Purpose of Smart Finance Assistant

The Smart Finance Assistant is an AI-powered financial assistant application that helps individuals understand their spending, while giving personalised financial guidance.


## 🔑 Key Features
- 📊 **Transaction Analysis:** Uploading a CSV file containing transaction data and giving detailed spending breakdowns
  
- 🤖 **AI Financial Advisor:** An proficient AI assistant for personalised financial advice and information
  
- 📈 **Spending Insights:** Insights given to the user to identify spending habits and methods for savings opportunities
  
- 🧮 **Financial Calculators:** Planned savings goals, budgeting, and emergency funds
  
- 🔍 **RAG System:** Retrieves relevant information from a base to reference, enhancing AI responses
  
- 🎯 **Gradio UI:** Gradio implementation with a user-friendly interface for easy interaction

---
## 📂 Repository Information

- **AI-Conversations:** Includes AI interactions and pseudocode given to AI to generate code

- **Six-Step Methodology:** Small file including the six-step methodology, nothing too fancy

- **Smart_Finance_Assistant:** Application for the Smart Finance Assistant, including all code and comments

- **Smart_Finance_Project:** Project overview including marking guide

- **Transactions.CSV:** The sample transactions/data relevant for the Smart Finance Assistant

---
## 📚 Sample Transactions

The **Sample Transactions** for the Smart Finance Assistant can be found within this repository labelled under **"transactions.csv"** and contains the following sample inputs below:

```
Date	Amount	Category	Description
01/08/2024	$45.50	Groceries	Woolworths Weekly Shop
02/08/2024	$12.00	Transport	Opal Card Top-up
03/08/2024	$89.95	Entertainment	Concert Tickets - Enmore Theatre
04/08/2024	$3.50	Coffee	Campus Cafe Flat White
05/08/2024	$120.00	Groceries	Coles Weekly Shop
06/08/2024	-$25.00	Refund	Returned Textbook - Co-op Bookshop
07/08/2024	$85.00	Dining	Birthday Dinner - The Rocks
08/08/2024	$15.95	Coffee	Starbucks Double Shot
09/08/2024	$67.80	Utilities	Electricity Bill - Origin Energy
10/08/2024	$4.20	Coffee	Campus Cafe Cappuccino
11/08/2024	$32.50	Transport	Uber to Airport
12/08/2024	$156.00	Groceries	Woolworths Fortnightly Shop
13/08/2024	$8.50	Coffee	Gloria Jeans Large Latte
14/08/2024	$95.00	Entertainment	Movies and Dinner - Event Cinemas
15/08/2024	$28.90	Dining	Lunch - Guzman y Gomez
16/08/2024	-$12.50	Refund	Coffee Shop Refund
17/08/2024	$45.00	Transport	Petrol - Caltex Woolworths
18/08/2024	$73.20	Groceries	IGA Local Shop
19/08/2024	$22.00	Entertainment	Netflix Monthly Subscription
20/08/2024	$5.80	Coffee	Local Cafe Americano

```
**The transaction file should include these columns:**
- **Date:** Transaction date (DD-MM-YYYY)
- **Amount:** Transaction amount can include or dollar signs ($)
- **Category:** Spending categories (groceries, transport, eating-out, etc.)
- **Description:** General description of transaction

---

## 🚀 Step-By-Step Guide for Smart Finance Assistant

**1.** Open notebook labelled **"smart_finance_assistant.ipynb"** and press the open **"open in colab"** button located at the top left of the page preview


**2.** With the colab notebook open, you may notice text comments above some code lines which were my additions to the project


**3.** Upload **"transactions.csv"** file if it isn't already uploaded by pressing the file icon button on the left hand side of the colab screen and then pressing the button with an up arrow on a page which enables file uploading


**4.** With the file uploaded run the install package as seen below:

```
!pip install gradio pandas hands-on-ai
```


**5.** Configure AI Connection with the password **isys2001-assignment-key** as seen below:

```
import os
from getpass import getpass

# Configure hands-on-ai server connection
os.environ['HANDS_ON_AI_SERVER'] = 'https://ollama.serveur.au'
os.environ['HANDS_ON_AI_MODEL'] = 'llama3.2'
os.environ['HANDS_ON_AI_API_KEY'] = getpass('Enter your API key: ')

print("🔑 Hands-on-AI configured successfully!")
```

**6.** Scroll down the colab page and run all the code boxes which include:
- **Sample Transaction Data Setup**
- **Foundation Data Processing Functions**
- **Advanced Features: Integrating AI Components**
- **RAG System for Financial Documents**
- **Custom Financial Tools**


**7.** After running all code boxes, run **Gradio UI Integration** which serves as the application for the Smart Finance Assistant

---
## 📍 Using the Assistant

**1.** Spending Analysis Tab
- Upload your CSV transaction file

- View automatic spending analysis and recommendations
  
- See category breakdowns and percentages

**2.** Financial Chat Tab
- Ask any financial questions
  
- Get personalized advice based on your spending patterns
  
- Receive step-by-step guidance

**3.** Calculators Tab
- Savings Goal Calculator: Plan how long to reach financial targets
  
- Budget Planner: Allocate income using the 50/30/20 rule
  
- Emergency Fund Calculator: Determine ideal emergency savings

**4.** About & Help Tab
- Detailed instructions and sample CSV format
  
- Information about features and usage

---

You are free to license your own work (your project code) under any license you choose.
