# Git and GitHub practice

You will work on this project together as a team. You will practice cloning, pulling, committing, pushing changes to GitHub, creating pull requests (PR), merging and resolving merge conflicts and more.

## Team name

Come up with a team name for your team. Do not spend more than 5 minutes on this. This is for fun only and will be used today only (unless you want to continue to use it later).

## Instructions

- Clone this repo to your local machine
- Assign each **features** and **bugs** below to team members.
- Work on one task at a time
  - For each task, follow the steps below:
    1. Create a new branch
    2. Complete the task
    3. Using git, _add_, _commit_, and _push_ your changes
    4. Create a PR on GitHub and share the link with the team to review
    5. Once done with a task, start from step 1 for other tasks

### Branch Naming Convention

- your initials, followed by two dashes (--), a random task number, a meaningful short name
- each separated with a dash, all lowercase, no space

  - e.g. If John Smith is working on a task to change the title of the document, a proper branch name is

  - `js--0001-change-title`

## Tasks

You will work on all of these tasks individually. Once done, create a PR, share the URL link to your PR to your team members and ask them to review it.

NOTE:

- Each task from 1-8 should be completed by one person. Before starting to work on any of these tasks, talk to your team members to decide who is doing what. Do not move on to task 9 or bugs before completing these 8 tasks.
- Do NOT start on task 9 before completing task 8.
- One person should complete task 8. Once this task is completed, the person needs to create a PR, ask the rest of the team to review and approve, once approved, merge that specific branch to the **main** branch.
- Only after task 8 is merged to main branch, start on task 9.
- Each person will work on task 9 by doing the following:
  - After the task 8 is merged to main branch, checkout your local branch to main again
    - `git checkout main`
  - Pull the latest changes that should include the changes from task 8.
    - `git pull`
  - Create a new branch and complete task 9 for yourself.

### Features

1. Change the title of the page from document to something else.

2. Add a `<nav>` element and add links inside the `<nav>` element as an unordered list. Make sure there are at least three links with one of them being your team name.

3. Add a title and a short paragraph to `<header>` element to describe what this page is about. Use semantic HTML and proper elements. There is no text provided, be creative. Use appropriate content.

4. There are the names of the book titles given in the `<main>` element however we would like to make it an ordered list.

5. There is a text given in between commented sections. Create a proper table using that text as a content.

6. Change the input type button in the form to use button element instead.

7. Make the link about Wikipedia page in the footer to open in a new tab.

#### Choose one person to complete task 8 before moving onto the task 9.

8. Create an HTML file and name it your team name. Inside the HTML page:
   - add boilerplate for HTML 5
   - Inside the `<head>`, change the title to your team name
   - Inside the `<body>`, add a header, probably level 1, with the team name as the content.

#### Everybody will do this task. Start only after the previous step is completed.

9. Add info about you to the team page. Add at least a header anything other than level 1 that contains your name and a short paragraph about yourself in a paragraph element.

### Bugs

Note: Continue on this section once the features above are completed. Choose one bug per person.

10. There is an image in the character selection but not displaying correctly.

11. I cannot change my character selection from Dwarf to Elf. It selects both of them.

12. Clicking the email should direct to sending an email but there is a bug and it is not working properly.

13. Clicking the phone number should direct to making a call but there is a bug and it is not working properly.
