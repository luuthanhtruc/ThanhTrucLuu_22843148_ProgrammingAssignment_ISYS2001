# 📓 Developer's Diary – AI Collaboration Guide

This file shows sample entries for your **Developer's Diary**. You must document your AI collaboration throughout the project development. Each entry should have:
- **Artifact**: a screenshot, GIF, or snippet of your AI interaction
- **Context**: one-sentence description of your goal
- **Reflection**: analysis of what happened, what you learned, and how you improved the solution

**Key Principle**: You're directing AI like a junior developer - always review, critique, and improve their suggestions.

---


## Week 9 – AI Collaboration Evidence

---

## Entry 1 – Improving AI Connection Testing

### Artifact
Week 9 AI conversation evidence

### Context
Week 9 I focused on improving the AI connection testing part of the Smart Finance Assistant. I wanted the output to look cleaner and more professional while still keeping the code simple enough for a beginner-level project.

### Prompt
“I am creating a Smart Finance Assistant and writing code to test the AI connection. I want a shorter, cleaner, and more aesthetic version of the code.”

### AI Response Summary
The AI suggested simplifying the connection testing process by reducing unnecessary comments, improving console messages, and adding a cleaner fallback system when the AI service is unavailable.

### Example Improvement

```python
print("🔄 Connecting to AI...\n")

if "Error" in str(response):
    print("⚠️ AI unavailable — switching to offline mode.\n")
```

Reflection

The AI suggestions made the code easier to read and improved the appearance of the console output. I learned that small formatting improvements can make a project feel more professional and easier for users to understand.

One issue I encountered was that the external AI service sometimes failed to connect. Because of this, I later added fallback responses so the assistant could still provide financial advice even if the AI connection failed.

## Entry 2 – Defining the Finance Problem

### Artifact

Week 9 AI conversation evidence 

### Context

I wanted to define a clear financial problem for the Smart Finance Assistant instead of creating a generic chatbot. My goal was to focus on budgeting and spending awareness for university students.

### Prompt

“Help me brainstorm specific personal finance problems that could be solved with a CSV analysis tool. I'm interested in helping people with budgeting and spending awareness.”

### AI Response Summary

The AI suggested several realistic financial problems that could be solved using CSV transaction analysis, such as overspending detection, subscription tracking, savings analysis, and spending habit monitoring.

The AI also helped rewrite the project idea into a more specific and realistic problem statement focused on helping university students manage their monthly budgets.

### Example Improvement
I want to help university students manage their monthly budgets by analyzing their bank transaction CSV files. The system should identify categories where users overspend, compare spending against budget limits, and provide simple recommendations to improve financial control.

### Reflection

This discussion helped me narrow the project scope and focus on a more realistic finance problem. Before using AI, my idea was too broad and unclear. The AI helped me think more about the target users, the actual financial challenges they face, and how the assistant could provide useful insights instead of generic responses.

I also learned that defining the business problem clearly before coding makes it easier to design the system features later.

## Week 10 – AI Collaboration Evidence

## Entry 3 – Identifying System Inputs and Outputs

### Artifact
Week 10 AI conversation evidence 

### Context
This week I focused on planning the core structure of the Smart Finance Assistant. I wanted to understand what financial data the system should collect and what outputs would provide the most useful budgeting insights for users.

### Prompt
“For a personal finance assistant that analyzes CSV transaction data, what are the most valuable inputs I should collect and outputs I should provide? Consider both technical data processing and business value for the user.”

### AI Response Summary
The AI suggested important system inputs and outputs for the project. It recommended collecting transaction details such as dates, amounts, categories, descriptions, and budget limits to support financial analysis.

The AI also suggested useful outputs including:
- spending summaries,
- overspending detection,
- spending trends,
- budgeting insights,
- and personalized financial recommendations.

The discussion helped refine the system into a budgeting assistant focused on helping university students better manage their monthly spending.

### Example Improvement
- Inputs:

CSV file containing bank transaction data
(columns: Date, Amount, Category, Description)

Student budget limits for different spending categories
(e.g., food, entertainment, transport)

Selected time period for analysis
(weekly or monthly)

- Outputs:

Monthly spending summary by category

Overspending detection compared to budget limits

Simple financial recommendations for improving budgeting habits
### Reflection

This conversation helped me better understand the relationship between financial data inputs and meaningful business outputs. Before this discussion, I was mainly thinking about the technical side of the project, but the AI helped me focus more on what information would actually be useful for users.

I also learned that designing clear inputs and outputs early makes it easier to structure the financial analysis functions later in development.

---

## Entry 4 – Creating Realistic Financial Examples

### Artifact: Screenshot of debugging session with Claude about handling messy CSV data.

### Context: I wanted to create realistic financial examples for testing and demonstrating the Smart Finance Assistant. My goal was to better understand how transaction data could be analyzed to generate useful budgeting insights.

### Prompt:

“Give me 3 realistic examples of Australian transaction data with different scenarios (normal spending, refunds, large purchases). Show me how to manually calculate meaningful financial insights from each scenario.”

### AI Response Summary

The AI generated three realistic financial scenarios involving:

normal student spending,
refund transactions,
and large purchases.

For each example, the AI provided:

sample CSV-style transaction data,
manual financial calculations,
spending percentages,
average transaction values,
and financial insights explaining spending behavior.

These examples helped demonstrate how transaction analysis can produce useful financial recommendations and spending awareness insights.

### Example Improvement:
Total Spending:
$72.30 + $1,850.00 + $16.20 + $31.50 + $14.90
= $1,984.90

Electronics Spending Percentage:
($1,850.00 ÷ $1,984.90) × 100 ≈ 93%

Insight:
The laptop purchase heavily impacted monthly spending,
representing approximately 93% of total expenses.

### Reflection: 
This activity helped me better understand how financial insights are calculated from transaction data. Manually working through the examples made it easier to understand how the Smart Finance Assistant should process CSV files and generate spending analysis.

I also learned that realistic examples make the project feel much more practical and believable compared to using random or overly simple data. The refund and large purchase examples were especially useful because they showed how unusual transactions can affect financial summaries and budgeting insights.

---

## Week 11 – AI Collaboration Evidence

### Entry 5 – Improving Spending Analysis Logic

**Artifact:** Week 11 AI conversation evidence 

**Context:** I wanted to improve the spending analysis logic so the Smart Finance Assistant could handle more realistic financial data situations.

**My Prompt:**  
"Review my pseudocode for analyzing spending data from a CSV. Are there any edge cases I'm missing? What business logic should I add to make this more valuable for personal finance insights?"

**AI Response Summary:**  
The AI suggested adding validation for issues such as empty CSV files, duplicate transactions, refunds, invalid date formats, missing columns, and zero-value transactions. It also recommended adding more advanced business logic including budget comparison, subscription detection, spending trend analysis, and savings estimation.

**My Critique/Improvement:**  
I realized my original pseudocode focused too much on basic calculations and not enough on real-world financial data problems. I updated the logic to include refund handling, duplicate transaction checks, and more useful financial insight features like subscription tracking and spending trend analysis.

**Result:**  
The updated spending analysis system became more realistic and practical. Instead of only calculating totals, the Smart Finance Assistant can now handle messy CSV data more reliably and generate more meaningful budgeting insights for users.

**Reflection:**  
This activity helped me understand that real financial data is often inconsistent and requires much more validation than I originally expected. I also learned that adding business-focused logic makes the project feel much more like a real financial assistant instead of just a simple CSV calculator.

---

### Entry 6 – Building the Python Spending Analysis Function

**Artifact:** Week 11 AI conversation evidence 

**Context:** I wanted to convert my spending analysis pseudocode into a proper Python function that could process CSV transaction data automatically.

**My Prompt:**  
"I'm implementing a Smart Finance Assistant. Based on my pseudocode, please create a Python function that analyzes spending data from a CSV file. The code should handle real-world CSV data issues, include clear comments, use professional variable names, format output for business presentation, and include basic error handling."

**AI Response Summary:**  
The AI generated a Python function that loads and validates CSV transaction data, cleans financial values, separates spending and refunds, calculates spending summaries, and generates readable financial insights. It also helped simplify the code into a cleaner and shorter version while keeping the important financial calculations and error handling.

**My Critique/Improvement:**  
The first version of the code was functional but too long and difficult to read. I simplified the structure, improved the formatting of the financial report output, and reduced unnecessary comments while still keeping the important business calculations and error handling.

**Result:**  
I ended up with a cleaner and more professional spending analysis function that can process CSV transaction data, generate financial summaries, and prepare insights for the AI assistant. The final version was easier to understand and looked much more polished.

**Reflection:**  
This task helped me better understand how to turn planning and pseudocode into a working implementation. I also learned that readability and structure are important in business programming because users need financial information presented clearly and professionally.
## AI Collaboration Best Practices I've Learned

### 🎯 Effective Prompting Strategies
1. **Always provide business context**: "I'm building a finance assistant for..."
2. **Specify data structure**: "My CSV has columns X, Y, Z with these data types..."  
3. **Request professional formatting**: "Format output for business presentation"
4. **Ask for comments**: "Include clear comments explaining the business logic"

### 🤔 Critique Questions I Always Ask
- "Does this handle edge cases like negative amounts or missing data?"
- "Are the variable names clear for a business context?"
- "How would I explain this code to a non-technical manager?"
- "What assumptions is this code making about my data?"

### 🔄 Iterative Improvement Process
1. **Get basic working code** from AI
2. **Test with real data** and find issues  
3. **Ask AI to fix specific problems** with context
4. **Simplify complex solutions** for maintainability
5. **Add business-appropriate formatting** and error handling

### 📊 Business Value Focus
- Always connect code back to business decisions
- Format outputs for non-technical users
- Include actionable insights, not just data summaries
- Consider the end user's needs and context

---

## 📝 Documentation Template for Your Entries

Use this format for consistent diary entries:

```markdown
### Entry [Number] – [Descriptive Title]
**Artifact:** [Screenshot/code snippet/GIF of AI interaction]

**Context:** [One sentence: what you were trying to achieve]

**My Prompt:** "[Your exact prompt to AI]"

**AI Response Summary:** [Brief description of what AI provided]

**My Critique/Improvement:** [How you modified or improved the AI's suggestion]

**Result:** [What you ended up with and why it's better]

**Reflection:** [What you learned about AI collaboration, business programming, or problem-solving]
```

---

✅ **Remember**: Document your AI collaboration throughout your project development. Each entry should show learning and improvement, not just successful interactions. Show how you direct AI like a junior developer to create business-appropriate solutions.

