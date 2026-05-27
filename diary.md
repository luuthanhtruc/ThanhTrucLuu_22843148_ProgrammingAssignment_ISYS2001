# 📓 Developer's Diary – AI Collaboration 

This file shows entries for my **Developer's Diary**. 
## Week 9 – AI Collaboration Evidence

---

## Entry 1 – Improving AI Connection Testing

### Artifact
Week 9 AI conversation evidence

### Context
Week 9 I worked on the testing of the AI connection of the Smart Finance Assistant. I would have preferred the output to be prettier and more professional and at the same time have the code be simple enough to be taken up by a beginner-level project.

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

### Reflection

Suggestions provided by AI made the code more readable and enhanced the display of the console output. I also got to know that small format enhancements can give a project a more professional touch and make it easier to comprehend.

The problem that I had faced was the failure of the external AI service not to connect in some instances. Due to this, I subsequently inserted fallback responses to enable the assistant to still give financial advice in case the AI connection went dead.

## Entry 2 – Defining the Finance Problem

### Artifact

Week 9 AI conversation evidence 

### Context

I wanted to identify a clear financial problem to the Smart Finance Assistant rather than develop an ambiguous chatbot. I wanted to target the awareness of budgeting and spending among the students of the university.

### Prompt

“Help me brainstorm specific personal finance problems that could be solved with a CSV analysis tool. I'm interested in helping people with budgeting and spending awareness.”

### AI Response Summary

The AI proposed some plausible financial issues that could be resolved through CSV transaction analysis, including the identification of overspending, monitoring subscriptions, analyzing savings, and monitoring spending habits.

The AI was also used to rephrase the project concept to a specific and realistic problem statement to assist university students with their monthly budgets.

### Example Improvement

I would like to assist university students to manage their monthly budgets through analyzing their bank transaction CSV files. The system ought to recognize areas where users exceed their expenditures, allocate expenditures and spending against budget constraints and give straightforward suggestions on means of enhancing the financial management.

### Reflection

This discussion assisted me to downsize the project scope and target a more practical finance issue. My concept was too widespread and vague before I worked with AI. The AI assisted me in cogitating more on the target users, the real financial issues that they have to manage, and how the assistant can offer valuable feedback rather than a generic answer.

Another lesson I got was that it is best to define the business problem first before coding it up so that when it comes time to design the system features, this becomes much easier.

## Week 10 – AI Collaboration Evidence

## Entry 3 – Identifying System Inputs and Outputs

### Artifact
Week 10 AI conversation evidence 

### Context
This week I concentrated on the design of the Smart Finance Assistant core. My question was what financial data the system would gather and what would be the most valuable outputs to assist users with their budgeting decisions.

### Prompt
“For a personal finance assistant that analyzes CSV transaction data, what are the most valuable inputs I should collect and outputs I should provide? Consider both technical data processing and business value for the user.”

### AI Response Summary
The project had instrumental system inputs and outputs as was proposed by the AI. It advised gathering transaction information including dates, amounts and category, description and budget restraints to aid financial analysis.

The AI was also able to propose meaningful outputs such as:
- spending summaries,
- overspending detection,
- spending trends,
- budgeting insights,
- and customized financial advice.

This discussion led to refining the system into a system that is a budgeting assistant that helps university students to spend in a better way in case they have monthly expenses.

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

This discussion made me realize more clearly how financial data inputs relate to meaningful business outputs thereof. The point that the AI made me think more before discussing the technical aspect of this project is that I primarily considered the technical aspect before I was able to dedicate time to thinking about what information would be beneficial to users.

Another thing I also learned was that the earlier the design of inputs and outputs, the easier it would be to organize the financial analysis functions within the development process.

---

## Entry 4 – Creating Realistic Financial Examples

### Artifact: Week 10 AI conversation evidence 

### Context: I would have liked to make some real financial test cases to showcase the Smart Finance Assistant and demonstrate it. I was interested in learning more about how the data about transactions could be analyzed to produce meaningful budgeting information.

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
This exercise allowed me to have a more insight into the calculation of financial insights using transaction data. It was also easier to manually go through the examples to learn how the Smart Finance Assistant will behave with CSV files and produce spending analysis.

It was also my experience that actual examples can make the project look so much more realistic and believable than disturbing random or too simple data would make the project look like. The large purchase and refund case studies were particularly helpful since they demonstrated the impact of unusual transactions on financial summaries and budgeting information.

---

## Week 11 – AI Collaboration Evidence

### Entry 5 – Improving Spending Analysis Logic

**Artifact:** Week 11 AI conversation evidence 

**Context:** I wanted to better the logic of spending analysis to allow the Smart Finance Assistant to address more realistic financial data scenarios.

**My Prompt:**  
"Review my pseudocode for analyzing spending data from a CSV. Are there any edge cases I'm missing? What business logic should I add to make this more valuable for personal finance insights?"

**AI Response Summary:**  
The AI proposed to add validation of such issues as empty CSV files, transaction occurring twice, refunds, improper date formats, missing columns, and transactions with zero values. It also suggested inclusion of more sophisticated business logic such as comparison of budgets, subscription, analysis of spending patterns and estimation of saving.

**My Critique/Improvement:**  
I found that my initial pseudocode was much too connoted with simple arithmetic and was insufficient with actual financial data issues. I added logic support to manage refunds, duplicate transactions and other more useful financial insight functionality such as subscription overviews and trend spending analysis.I realized my original pseudocode focused too much on basic calculations and not enough on real-world financial data problems. I updated the logic to include refund handling, duplicate transaction checks, and more useful financial insight features like subscription tracking and spending trend analysis.

**Result:**  
The new spending analysis system proved to be more realistic and practical. The Smart Finance Assistant is now able to work with messy CSV more reliably, and provide more meaningful budgeting insights to the user than simply tallying totals.

**Reflection:**  
The endeavor allowed me to learn that actual financial information is so often not smooth and needs a great deal more verification than I had initially anticipated. Another thing I learned is the addition of business-oriented logic which would help provide the project with a much more realistic feeling of a real financial assistant rather than a simple CSV calculator.

---

### Entry 6 – Building the Python Spending Analysis Function

**Artifact:** Week 11 AI conversation evidence 

**Context:** I wanted to convert my spending analysis pseudocode into a proper Python function that could process CSV transaction data automatically.

**My Prompt:**  
"I'm implementing a Smart Finance Assistant. Based on my pseudocode, please create a Python function that analyzes spending data from a CSV file. The code should handle real-world CSV data issues, include clear comments, use professional variable names, format output for business presentation, and include basic error handling."

**AI Response Summary:**  
The AI generated a Python function that loads and validates CSV transaction data, cleans financial values, separates spending and refunds, calculates spending summaries, and generates readable financial insights. It also helped simplify the code into a cleaner and shorter version while keeping the important financial calculations and error handling.

**My Critique/Improvement:**  
The earliest edition of the code was useful but excessively lengthy and hard to read. I have made the structure less complicated, better formatted the output of the financial report and omitted the redundant commentaries but retained the critical business calculations and error management.

**Result:**  
The result was a clean and more professional create a spending or spending analysis functionality that has the capability to receive CSV data of transactions, create financial summaries, and some insights to be handed to the AI assistant. The last one was more comprehensible and appeared much more professional.

**Reflection:**  
This exercise assisted me in getting a deeper comprehension of how to translate planning and pseudocode into code. I also learnt that readability and structure are crucial in business programming as users require an understanding of financial information in an informative and professional way.

## Week 12 - AI conversation 
### Entry 7 – Having a more professional approach to AI Connection errors

**Artifact:** Week 12 AI conversation 

**Context:** I had the desire to enhance the trustworthiness of Smart Finance Assistant following the RAG system which showed an error when establishing a connection during the generation of financial advice.

**My Prompt:**  
"The Smart Finance Assistant successfully generated the spending analysis report, but the RAG system returned a connection error when calling `rag.ask()`. How can I improve the system to handle this situation more professionally?"

**AI Response Summary:**  
The AI told me that the CSV analysis and creation of financial reports were functioning properly and it was the connection of the external AI service that was causing the issue and not my financial analysis code.The AI explained that the CSV analysis and financial report generation were working correctly, and that the problem was caused by the external AI service connection rather than my financial analysis code.

The AI suggested improving the system by adding:
- better error handling,
- fallback responses,
- and an offline financial advice mode.

It also recommended displaying useful financial advice even when the AI service is temporarily unavailable.

**My Critique/Improvement:**  
Initially, the system just showed a message of connection error, and so the assistant would not feel good whenever the service of the AI failed. I edited the program to allow it to still provide simple financial advice without halting using fallback responses.

I also enhanced the messages on the consoles to make the way of interpreting the errors look more professional and comprehensible to the users.

**Result:**  
The Smart Finance Assistant was getting much better and stable. However, it means that the system can give very simple financial advice even in the event the external AI service goes dead, using the results of the analysis of spending.

This gave the project more of the appearance of a genuine application rather than an in-classroom demonstration.

**Reflection:**  
This experience made me learn that AI systems rely on external services which at times would fall unexpectedly. Personally, I had been much more interested up to this time in getting the financial analysis to work and not so much in the question of reliability and user experience when failures occur.

I also came to learn that it is not just the addition of features that makes good software design, but how to deal with the problems in the graceful way that leaves the system to operate even in the event of a failure.



---

✅ **Remember**: Document your AI collaboration throughout your project development. Each entry should show learning and improvement, not just successful interactions. Show how you direct AI like a junior developer to create business-appropriate solutions.

