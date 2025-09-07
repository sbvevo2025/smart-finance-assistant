# 📓 Developer's Diary – Example Entries

This file shows sample entries for your **Developer’s Diary**. You must include **weekly AI Evidence Packages** (Weeks 8–12). Each entry should have:
- **Artifact**: a screenshot, GIF, or snippet of your AI interaction
- **Context**: one-sentence description of your goal
- **Reflection**: short analysis of what happened, what you did, and what you learned

---

## Example Entry 1 – Debugging Code
**Artifact:** Screenshot of ChatGPT suggesting a loop to sum transactions.

**Context:** I wanted to calculate total expenses from a list of numbers.

**Reflection:** The AI’s first code used `sum(expenses)` but forgot to check for empty lists. I tested with `[]` and got an error. I added a condition to return 0 when the list is empty. This showed me AI can give correct logic but I need to think about edge cases.

---

## Example Entry 2 – Feature Extension
**Artifact:** Screenshot of Gemini generating code for a savings goal calculator.

**Context:** I wanted my Finance Assistant to show how long it would take to reach a savings goal.

**Reflection:** The AI generated one large function. I broke it into two smaller ones (`calculate_months_to_goal` and `print_summary`). This made testing easier. I learned that splitting AI code into smaller functions improves readability and testing.

---

## Example Entry 3 – UI Enhancement
**Artifact:** Screenshot of Gradio interface after adding a file upload button.

**Context:** I wanted to let users upload their own CSV file instead of hardcoding the data.

**Reflection:** The AI generated a Gradio `File` input component. At first it gave me `file.read()` which didn’t work in Colab. I changed it to `file.name` after testing. I learned I need to adapt AI’s code to the Colab environment.

---

## Example Entry 4 – Testing
**Artifact:** Snippet of AI suggesting `unittest` code.

**Context:** I asked the AI to create tests for my `budget_balance` function.

**Reflection:** The AI gave me a full `unittest` class. This was more advanced than I needed, so I simplified it to `assert` statements. I realised that even simple tests are powerful, and I can still learn from AI’s more complex suggestions.

---

✅ Remember: each week, add at least one entry like these to your **Developer’s Diary**.

