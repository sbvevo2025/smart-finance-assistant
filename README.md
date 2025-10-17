# 📊 Sean Boland - Smart Finance Assistant

Welcome to your project repository for the **ISYS2001 Final Programming Project**. This repo provides a starting point for building your **Smart Finance Assistant**.

---

## 📖 Project Overview
In this project, you will design and implement a **Smart Finance Assistant** using:
- Python (Google Colab)
- [hands-on-ai](https://pypi.org/project/hands-on-ai/) (chat, RAG, agent tools)
- [Gradio](https://www.gradio.app/) (to create a simple app interface)

Your Assistant should include:
- **Chat**: a finance-oriented personality bot
- **RAG**: retrieval from CSV or other documents
- **Agent Tool**: one custom tool (e.g., budget calculator, currency converter)
- **Gradio UI**: a simple interface tying everything together
- **Tests**: a Testing Section in your notebook

---

## Purpose of Smart Finance Assistant

The Smart Finance Assistant is an AI-powered financial assistant application that helps individuals understand their spending, while giving personalised financial guidance.


## Key Features
- 📊 **Transaction Analysis:** Uploading a CSV file containing transaction data and giving detailed spending breakdowns
  
- 🤖 **AI Financial Advisor:** An proficient AI assistant for personalised financial advice and information
  
- 📈 **Spending Insights:** Insights given to the user to identify spending habits and methods for savings opportunities
  
- 🧮 **Financial Calculators:** Planned savings goals, budgeting, and emergency funds
  
- 🔍 **RAG System:** Retrieves relevant information from a base to reference, enhancing AI responses
  
- 🎯 **Gradio UI:** Gradio implementation with a user-friendly interface for easy interaction

---

## Sample Transactions

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
The transaction file should include these columns:
- **Date:** Transaction date (DD-MM-YYYY)
- **Amount:** Transaction amount can include or dollar signs ($)
- **Category:** Spending categories (groceries, transport, eating-out, etc.)
- **Description:** General description of transaction

---

## Step-By-Step Guide for Smart Finance Assistant

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

## 📂 Suggested Repo Layout
You may adapt this structure or create your own. Clarity and organisation are graded in the rubric.

```
/README.md            ← this file
/assignment.pdf       ← official assignment specification
/starter_notebook.ipynb  ← scaffold notebook with six-step method
/example_diary.md     ← sample Developer’s Diary entries
/data/                ← your CSVs or sample datasets
/tests/               ← your test scripts or asserts
/ai-conversations/    ← weekly AI Evidence Packages (screenshots, notes)
/docs/                ← pseudocode, design notes, planning docs
```

---

## 🚀 Getting Started
1. Open the `starter_notebook.ipynb` in Google Colab.
2. Follow the **six-step methodology**:
   1. Understand the problem
   2. Identify inputs and outputs
   3. Work the problem by hand
   4. Write pseudocode
   5. Convert to Python
   6. Test with a variety of data
3. Add at least one **meaningful GitHub commit per week** (Weeks 8–12).
4. Document AI use in your **Developer’s Diary** (`/ai-conversations/` folder or a markdown file).

---

## ✅ Submission Requirements
- Colab Notebook with full project implementation
- GitHub repository with:
  - Notebook, README, and Developer’s Diary
  - Weekly AI Evidence Packages (Weeks 8–12)
  - Meaningful commit history
- Developer’s Diary entries that include:
  - **Artifact**: screenshot or snippet of AI use
  - **Context**: your goal
  - **Reflection**: what worked, what didn’t, what you learned

---

## 📊 Assessment Criteria (Summary)
- **Functionality** – chatbot, RAG, tool, and UI integrated (30%)
- **Testing & Debugging** – clear tests, meaningful edge cases (20%)
- **AI Collaboration & Progress** – AI evidence + weekly commits (20%)
- **Business Relevance** – meaningful finance problem (15%)
- **Clarity & Reflection** – repo organisation, README, diary (15%)

For the full rubric, see `assignment.pdf`.

---

## 📚 Resources

- **hands-on-ai Package**: [GitHub Repository](https://github.com/michael-borck/hands-on-ai)
- **Documentation**: [DeepWiki Guide](https://deepwiki.com/michael-borck/hands-on-ai)
- **For AI Assistants**: Share [this LLM context file](https://github.com/michael-borck/hands-on-ai/blob/main/LLM.txt) with ChatGPT/Claude/Copilot for better code suggestions

---

## 💡 Tips
- Keep your commits small and descriptive.
- Use AI as a coding partner, not a crutch.
- Remember: **undocumented AI use = misconduct**.

Good luck, and have fun building your Finance Assistant! 🎉

---

## 📜 License

The template code in this repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

You are free to license your own work (your project code) under any license you choose.
