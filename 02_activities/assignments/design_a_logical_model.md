# Assignment 1: Design a Logical Model

## Question 1
Create a logical model for a small bookstore. 📚

At the minimum it should have employee, order, sales, customer, and book entities (tables). Determine sensible column and table design based on what you know about these concepts. Keep it simple, but work out sensible relationships to keep tables reasonably sized. Include a date table. There are several tools online you can use, I'd recommend [_Draw.io_](https://www.drawio.com/) or [_LucidChart_](https://www.lucidchart.com/pages/).
![ERD 1 SQL Assignment](https://github.com/user-attachments/assets/f78f70b8-426c-48ec-b368-44a7deae9161)

## Question 2
We want to create employee shifts, splitting up the day into morning and evening. Add this to the ERD.
![ERD 2 SQL Assignment](https://github.com/user-attachments/assets/9e41107e-d576-4951-af58-ada357fa9ea1)

## Question 3
The store wants to keep customer addresses. Propose two architectures for the CUSTOMER_ADDRESS table, one that will retain changes, and another that will overwrite. Which is type 1, which is type 2?
type 1 - limited information about customers addresses - just last one
type 2 - all addresses available - active and not active
_Hint, search type 1 vs type 2 slowly changing dimensions._
![Type 1 custom_adress](https://github.com/user-attachments/assets/7f1380dd-9159-4b6a-80d3-9d82d1613444)
![Type 2 custom_adress](https://github.com/user-attachments/assets/aee3f3c6-bd34-4096-84a6-413c901b2850)

Bonus: Are there privacy implications to this, why or why not?
```
Your answer...
```yes sure - it's private confidantial information and shoul be kept according to all corporate and legal rules with limited accsess, as option - non-pesonalised or encrypted format

## Question 4
Review the AdventureWorks Schema [here](https://i.stack.imgur.com/LMu4W.gif)

Highlight at least two differences between it and your ERD. Would you change anything in yours?
```
Your answer...
```
1/ AdventureWorks Schema is very detailed comparing to my 
2/ it's production-oriented, my scheme is sales-oriented

# Criteria

[Assignment Rubric](./assignment_rubric.md)

# Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `September 28, 2024`
* The branch name for your repo should be: `model-design`
* What to submit for this assignment:
    * This markdown (design_a_logical_model.md) should be populated.
    * Two Entity-Relationship Diagrams (preferably in a pdf, jpeg, png format).
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sql/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `model-design`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-4-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
