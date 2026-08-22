# 🚀 SIH 2026 Problem Statement Matchmaker

A helpful tool designed to help your Smart India Hackathon (SIH) 2026 team easily pick the right problem statement. 

Instead of reading through hundreds of problem statements manually, your team answers a 30-question form about your skills and interests. Then, you use an AI (like Google Gemini) to compare your team's answers against the big list of problem statements to find the Top 10 best matches for you.

## 📁 What Are These Files?
* `index.html` - The website code for the questionnaire form.
* `questionnaire.csv` - The file that holds the 30 questions shown on the website.
* `problem_statements.csv` - The complete, master list of all SIH 2026 Problem Statements.

## 🛠️ Step-by-Step Guide: How to Use This

### Step 1: Put the Website Online
To let your team fill out the form, you need to host the website on GitHub Pages. It is free and very easy to do.
1. Create a public repository on your GitHub account.
2. Upload all three files (`index.html`, `extended_questionnaire.csv`, and `problem_statements.csv`) into that repository.
3. In your GitHub repository, click on the **Settings** tab.
4. On the left side menu, click on **Pages**.
5. Under the "Build and deployment" section, look for "Branch". Change it from `none` to `main` (or `master`), and click **Save**.
6. Wait about 2 to 3 minutes. GitHub will give you a link to your live website (it will look something like `https://nothinormuch.github.io/SIH_2026_Questionaire/`).

### Step 2: Get Your Team's Answers
1. Send the GitHub Pages website link you just created to all your teammates.
2. Ask them to read and answer all the questions on the site.
3. When they click the submit button at the bottom, a file named `Answers_[Their Name].csv` will automatically download to their computer.
4. Ask everyone to send their downloaded answer files to you (the Team Lead).

### Step 3: Find Your Perfect Problem Statement
Now that you have everyone's answers, it is time to let the AI do the hard work.
1. Gather all the `Answers.csv` files from your teammates.
2. Open an AI chatbot (see our recommendation below).
3. Upload all the team's `Answers.csv` files AND the `problem_statements.csv` file into the chat.
4. Copy and paste the magic prompt below to get your results!

## 🤖 Which AI Should You Use?

To get the best results, you need an AI that lets you upload multiple files at once and is good at reading a lot of data.

🏆 **Top Recommendation: Google Gemini**
* **Why:** Gemini is very good at reading multiple CSV files at the same time. It can easily compare your team's answers with the heavy `problem_statements.csv` list without getting confused or forgetting details.

**Alternative:** ChatGPT or Claude (just make sure you use a version that allows file uploads).

### 📝 The Magic Prompt

Upload your files to the AI, then copy and paste this exact message:

> I am participating in the Smart India Hackathon (SIH) 2026.
> 
> I have uploaded some CSV files to this chat:
> 1. My teammates' answer files. These show our team's coding skills, preferences, and interests.
> 2. The full list of SIH 2026 problem statements (problem_statements.csv).
> 
> Please act as a hackathon mentor. Read through my team's answers to understand what we are good at. Then, compare our skills with the big list of problem statements. 
> 
> Give me the Top 10 problem statements that fit our team the best. For each recommendation, give me the PS Number, the Title, and 2 short sentences explaining exactly why it matches our team's skills.

---

## 🤔 Why I Made This Repo
If you are anything like me, looking at the massive list of SIH problem statements is completely overwhelming. My team and I were struggling to pick just one problem statement to work on. Everyone had slightly different skills, different interests, and reading through hundreds of statements one by one was taking way too much time. We just couldn't agree on what to choose.

I created this project to solve that exact problem. Instead of guessing or arguing, I wanted a way for everyone to just write down what they are good at, and let an AI find the perfect middle ground for the whole team. I hope it saves your team as much time and stress as it saved mine! Good luck with the hackathon!
