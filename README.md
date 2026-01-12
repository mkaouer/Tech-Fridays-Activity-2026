# Tech Friday Activity: Build Your Personal Portfolio Website with Gen-AI

**Theme:** Usage of Gen-AI for Building Your Own GitHub Personal Website

**Duration:** 1 Hour (Engagement Hour)

**Target Audience:** High School Students

---

## Introduction

Welcome to Tech Friday! In this hands-on activity, you will create your very own professional portfolio website using the power of Generative AI. A portfolio website is an essential tool for showcasing your skills, projects, and achievements to colleges, scholarship committees, and future employers. By the end of this session, you will have a personalized website that you can continue to update and improve.

This activity uses two cutting-edge AI tools from Google: **Google Gemini** for reasoning and content generation, and **Jules** for agentic programming. Together, these tools will help you transform your resume into a beautiful, functional website without writing a single line of code from scratch.

---

## Prerequisites

Before you begin, make sure you have the following:

| Requirement | Description |
|-------------|-------------|
| **Google Account** | You will need a Google account to access both Gemini and Jules. If you don't have one, you can create one for free at [accounts.google.com](https://accounts.google.com). |
| **GitHub Account** | GitHub is where your website code will be stored and hosted. Create a free account at [github.com](https://github.com) if you don't already have one. |
| **Your Resume** | Have a digital copy of your resume ready (PDF, Word document, or plain text). This will be the source material for your website content. |

---

## Part 1: Generate Your Website Content with Google Gemini

In this first part, you will use Google Gemini to analyze your resume and generate professional content for your portfolio website. Gemini is an AI assistant that excels at understanding documents and creating high-quality written content.

### Step 1.1: Access Google Gemini

Open your web browser and navigate to [gemini.google.com](https://gemini.google.com). Sign in with your Google account when prompted. Once signed in, you will see a chat interface where you can interact with Gemini.

### Step 1.2: Upload Your Resume

Look for the attachment icon (it looks like a paperclip or a plus sign) near the text input area. Click on it and select your resume file from your computer. Gemini can read PDF files, Word documents, and plain text files. After uploading, you should see your file attached to the conversation.

### Step 1.3: Generate Content for Each Section

Now you will ask Gemini to create content for the different sections of your portfolio website. Copy and paste each of the following prompts into Gemini, one at a time. After each response, copy the generated text into a separate document (like Google Docs or Notepad) so you can use it later.

**Prompt 1: About Me Section**

```
Based on my attached resume, write a professional "About Me" section for my portfolio website. 
The section should be 2-3 paragraphs long, written in first person, and should:
- Introduce who I am
- Highlight my passion for technology and learning
- Mention my key strengths and interests
- Be engaging and suitable for a high school student's portfolio
```

**Prompt 2: Skills Section**

```
Based on my resume, create a list of my top 5 skills for my portfolio website. 
For each skill, provide:
- The skill name
- A confidence percentage (between 50% and 95%)
- A brief one-sentence description of my proficiency

Format the output as a simple list.
```

**Prompt 3: Education Section**

```
Based on my resume, write content for the Education section of my portfolio. 
Include:
- School name
- Years attended
- A brief description of relevant coursework or achievements

Format it so it can be easily added to a website.
```

**Prompt 4: Experience/Activities Section**

```
Based on my resume, create content for the Experience section of my portfolio. 
This can include jobs, internships, volunteer work, or extracurricular activities.
For each entry, include:
- Position/Role title
- Organization name
- Time period
- A brief description of responsibilities and achievements
```

**Prompt 5: Services/What I Do Section**

```
Based on my resume and interests, suggest 4 services or areas of expertise I could offer. 
For each one, provide:
- A title (e.g., "Web Design", "Data Analysis", "Graphic Design", "Tutoring")
- A brief 1-2 sentence description

These should reflect skills that a high school student might realistically have.
```

After completing all prompts, you should have a document with all the content you need for your website. Keep this document open for the next part.

---

## Part 2: Build Your Website with Jules

Now that you have your content ready, it's time to use Jules to create your website. Jules is an AI coding agent that can understand your instructions and make changes to code automatically. It integrates directly with GitHub, so your changes will be saved to your repository.

### Step 2.1: Access Jules and Connect GitHub

Open a new browser tab and go to [jules.google.com](https://jules.google.com). Sign in with your Google account. When prompted, click **Connect to GitHub account** and follow the authorization steps. This allows Jules to access and modify repositories on your behalf.

### Step 2.2: Fork the Portfolio Template

Before Jules can work on your website, you need to create your own copy (called a "fork") of the portfolio template. You can do this directly through GitHub:

1. Open a new tab and go to [https://github.com/mkaouer/vcard-personal-portfolio](https://github.com/mkaouer/vcard-personal-portfolio)
2. Click the **Fork** button in the top-right corner of the page
3. On the "Create a new fork" page, you can rename the repository to something like `my-portfolio` or keep the default name
4. Click **Create fork**
5. Wait for GitHub to create your copy of the repository

Now you have your own version of the portfolio template in your GitHub account!

### Step 2.3: Connect Your Repository to Jules

Go back to the Jules tab. In the repository selector dropdown, find and select your newly forked repository (it should appear as `your-username/vcard-personal-portfolio` or `your-username/my-portfolio`). Make sure the `master` or `main` branch is selected.

### Step 2.4: Customize Your Website with Jules

Now comes the exciting part! You will give Jules instructions to update the website with your personal information. Use the following prompts, replacing the placeholder text in brackets with your actual information.

**Task 1: Update Basic Information**

Copy and paste this prompt into Jules, filling in your details:

```
Please update the index.html file with my personal information:

1. Change the name "Richard hanrick" to "[YOUR FULL NAME]"
2. Change the title "Web developer" to "[YOUR DESIRED TITLE, e.g., 'Student Developer' or 'Aspiring Engineer']"
3. Change the email "richard@example.com" to "[YOUR EMAIL ADDRESS]"
4. Change the phone number "+1 (213) 352-2795" to "[YOUR PHONE NUMBER or remove this section]"
5. Change the birthday "June 23, 1982" to "[YOUR BIRTHDAY]"
6. Change the location "Sacramento, California, USA" to "[YOUR CITY, STATE]"
7. Update the page title from "vCard - Personal Portfolio" to "[YOUR NAME] - Portfolio"

Make sure to update all instances where these values appear.
```

Click **Give me a plan**. Jules will analyze the code and show you what changes it plans to make. Review the plan, and if it looks correct, click **Approve** to let Jules make the changes.


**Task 2: Update the About Me Section**

After the first task is complete, start a new task with this prompt:

```
Please update the "About me" section in index.html. Replace the existing two paragraphs 
in the about-text section with the following content:

[PASTE YOUR "ABOUT ME" CONTENT FROM GEMINI HERE]
```

Review and approve the plan.

**Task 3: Update the Skills Section**

```
Please update the "My skills" section in index.html. Replace the existing skills 
(Web design, Graphic design, Branding, WordPress) with my skills:

[PASTE YOUR SKILLS FROM GEMINI HERE, formatted like:]
- Skill 1: XX%
- Skill 2: XX%
- Skill 3: XX%
- Skill 4: XX%
- Skill 5: XX%

Update both the skill names and the percentage values in the progress bars.
```

**Task 4: Update Education and Experience**

```
Please update the Resume section in index.html:

For the Education timeline, replace the existing entries with:
[PASTE YOUR EDUCATION CONTENT FROM GEMINI HERE]

For the Experience timeline, replace the existing entries with:
[PASTE YOUR EXPERIENCE CONTENT FROM GEMINI HERE]
```

**Task 5: Update the Services Section**

```
Please update the "What i'm doing" section in index.html. Replace the existing 
four service items with:

[PASTE YOUR SERVICES/WHAT I DO CONTENT FROM GEMINI HERE]
```

### Step 2.5: Create a Branch and Push Changes

After each task, Jules will create the changes on a new branch. Once you have completed all your customizations:

1. Jules will show you a summary of all changes made
2. Click **Create branch** to save your changes
3. Jules will provide a link to create a Pull Request on GitHub
4. Go to GitHub and merge the Pull Request into your main branch

---

