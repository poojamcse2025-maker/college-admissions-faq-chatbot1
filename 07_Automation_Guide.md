# Automation: Log unanswered questions into Notion
Tools: Make (free plan) + Notion.
1. Notion: create database "Unanswered Questions" with columns Question (title), Date, Status (New/Answered), Category.
2. Make: new scenario -> trigger **Webhooks > Custom webhook** (or Google Form / Gmail trigger if the chatbot can't call a webhook).
3. Add module **Notion > Create a Database Item**; map Question <- webhook text, Date <- now, Status <- "New".
4. Chatbot step: when it outputs `ESCALATE:`, the student copies the question into a short Google Form (or the webhook URL) which triggers the scenario.
5. Test with 3 questions and screenshot the Notion rows for submission.
