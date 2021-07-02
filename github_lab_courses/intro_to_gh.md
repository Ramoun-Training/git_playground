# Introduction to GitHub

- [link of the course](https://lab.github.com/githubtraining/introduction-to-github)

## What you'll build

![final build](https://user-images.githubusercontent.com/821071/120042632-79aaa600-bfd8-11eb-81c0-3c0b31776e9a.gif)

- Completed [source repository](https://github.com/githubtraining/github-slideshow-demo/)
- Interactive [slideshow](https://githubtraining.github.io/github-slideshow-demo/) deployed to GitHub Pages

## What you'll learn

### We'll answer common questions like

- [x] What is GitHub?
- [x] How does one use GitHub?
- [x] What are issues and pull requests?
- [x] How do you create a branch and a commit?
- [ ] How do you use GitHub Pages?

### And when you're done you'll be able to

- [x] Communicate in issues
- [x] Manage notifications
- [x] Create branches
- [ ] Make commits
- [ ] Introduce changes with pull requests
- [ ] Deploy a web page to GitHub pages

## Projects used

This makes use of the following open source projects. Consider exploring these repos and maybe even making contributions!

- [reveal.js](https://github.com/hakimel/reveal.js): A framework for creating presentations using HTML
- [Jekyll](https://github.com/jekyll/jekyll): a simple, blog-aware, static site generator.

## Git

**Git** is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.

## GitHub

**GitHub** uses Git, the most popular open source version control software, to track every contribution and contributor to your project--so you know exactly where every line of code came from.

**At its heart, GitHub is a collaboration platform.**

## Why Use GitHub?

- for collabration with teamns on projects.
- for open source projects.

## Github Styles

- fewer commits with lots of changes.
- [x] more commits with fewer changes (better).

## Exploring GitHub Repository

### More Features

The video covered some of the most commonly-used features (issues, PRs ...etc). Here are a few other items you can find in GitHub repositories:

- **Project boards**: Create Kanban-style task tracking board within GitHub.
- **Wiki**: Create and store relevant project documentation.
- **Insights**: View a drop-down menu that contains links to analytics tools for your repository including:
  - **Pulse**: Find information about the work that has been completed and the work that’s in-progress in this project dashboard.

  - **Graphs**: Graphs provide a more granular view of the repository activity including who contributed to the repository, who forked it, and when they completed the work.

### Special Files

In the video you learned about a special file called the `README.md`. Here are a few other special files you can add to your repositories:

- **`CONTRIBUTING.md`**: The `CONTRIBUTING.md` is used to describe the process for contributing to the repository. A link to the `CONTRIBUTING.md` file is shown anytime someone creates a new issue or pull request.

- **`ISSUE_TEMPLATE.md`**: The `ISSUE_TEMPLATE.md` is another file you can use to pre-populate the body of an issue. For example, if you always need the same types of information for bug reports, include it in the issue template, and every new issue will be opened with your recommended starter text.

## Github Issues

Issues are suggested improvements, tasks or questions related to the repository. Issues can be created by anyone (for public repositories), and are moderated by repository collaborators. Each issue contains its own discussion thread. You can also categorize an issue with labels and assign it to someone.

a place where you can have conversations about bugs in your code, code review, and just about anything else
where discussions and instructions take place. where pull requests are where changes can be made.

- people can report bugs.
- open a discussion thread.
- request features.
- ask questions.
- review code.
- have an idea.

**Issue titles**:  are like email subject lines. They tell your collaborators what the issue is about at a glance. For example, the title of this issue is `Getting Started with GitHub`.

### Using GitHub issues

Issues are used to discuss ideas, enhancements, tasks, and bugs. They make collaboration easier by:

- Providing everyone (even future team members) with the complete story in one place.
- Allowing you to cross-link to other issues and pull requests.
- Creating a single, comprehensive record of how and why you made certain decisions.
- Allowing you to easily pull the right people and teams into a conversation with `@-mentions`.

### Assign Issues

**Unassigned issues** don't have owners to look after them. When you’re assigned to an issue or pull request, it tells repository visitors and contributors that you'll be facilitating the conversation or task :muscle:.

**After self-assigning issues**: :tada: You're now the proud manager of this issue! Now that you've assigned yourself, people who drop by know that they're welcome to participate, but you'll be carrying this issue across the finish line. :sunglasses:.

### Closing Issues

Now that you’ve completed the tasks in this issue, it's time to close it! Closing an issue tells other contributors that this particular conversation or task has come to an end.

> **Note**: Issues can be reopened after closing.

## Github Pull Requests

Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum.

- show others changes you are proposing (in form of a chain of commits) so they can review and test them.
- other teamates can make imporvements (by adding their code the branch).
- once the team has signed off on the changes, you can incorprate new code into the project (using Merge).

## Managing Notifications

### Watching/Not Watching Projects

allows you to stay up to date on what is happening on that project.

you recieve a notification when a new:

- issue
- pull request
- comment

is added to the repo. Also when an issue is closed or a PR is merged.

if you chooses `Not Watching` option: you'll still recieve notifications if you `@-mention`ed indvidually or as part of a group.

You'll also recieve notification if you commented on an issue or pull request when there's activity in the thread.

`Ignore` will ignore everything.

> **Note**: through github account settings, you can set whether you recieve notifications via email or online.

### How to silence or unmute specific conversations

1. Go to the issue or pull request
2. Under "Notifications", click the Unsubscribe button on the right to silence notifications or Subscribe to unmute them

You'll see a short description that explains your current notification status.

### How to customize notifications in Settings

1. Click your profile icon
1. Click Settings
1. Click Notifications from the menu on the left and [adjust your notification preferences](https://help.github.com/articles/managing-notification-delivery-methods/)

### Repository notification options

- **Watch**: You'll receive a notification when a new issue, pull request or comment is posted, and when an issue is closed or a pull request is merged
- **Not watching**: You'll no longer receive notifications unless you're `@-mentioned`
- **Ignore**: You'll no longer receive any notifications from the repository

### How to review notifications for the repositories you're watching

1. Click your profile icon
1. Click **Settings**
1. Click **Notification** from the menu on the left
1. Click on the [things you’re watching](https://github.com/watching) link
1. Select the Watching tab
1. Click the Unwatch button to disable notifications, or Watch to enable them

> **Note**: you can also access watching list from the notifcations tab by clicking on **managing notifcation** (on the bottom left corner) then **watched repos**.

## Staring

if you are interested in a project and want to find easily again you should star it.

> **Note**: you won't get notificationis from stared projects. These are like bookmarks.

## Explore

helps you find new projects easily on github (may be to contribute to or to make use of).

## GitHub Pages

GitHub Pages allow you to serve a static site from a repository

### Enable GitHub Pages

1. Click on the Settings tab in this repository
1. Scroll down to the "GitHub Pages" section
1. From the "Source" drop down, select main branch

> **Note**: Even though you'll see an option to choose a theme, do not apply a theme at this point. We've protected the code so you can't make unintended changes. You'll have the opportunity to apply a theme when the course is completed.
<<<<<<< HEAD
=======

## Introduction to GitHub flow

People use different workflows to contribute to software projects, but the simplest and most effective way to contribute on GitHub is the GitHub flow.

### What is GitHub Flow

is a light weigh workflow that allows you to experiment with ideas safely without fear of comprmoising a project.

### Key Concepts of GH Flow

#### Branching

everything on github lives on a branch.

Branches are an important part of the GitHub flow because they allow us to separate our work from the main branch. In other words, everyone's work is safe while you contribute.

##### Tips for using branches

A single project can have hundreds of branches, each suggesting a new change to the `main` branch.

The best way to keep branches organized with a team is to keep them **concise** and **short-lived**. In other words, _**a single branch should represent a single new feature or bug fix**_. This reduces confusion among contributors when branches are only active for a few days before they’re merged into the `main` branch.

when you are ready to add a new feature or fix an issue, you create a new branch on the project.

![branc1](/images/branch1.png)

The branch will look exactly like master at first but any changes you make will only be reflected in your branch.

Such a new branch is often called a `feature` branch and you should give yours a descriptive name.

when you make changes to files in your project, you'll commit those changes to the `feature` branch.

when you are ready to start a discussion about your changes, you open a PR (a PR doesn't need to be a perfect work of art, it is meant to be a starting point that will be further refined and polished through the efforts of the project team).

when the changes in the PR are approved, the `feature` branch is merged on to the master branch and the issue is closed.

![branch2](/images/branch2.png)

### Summary of Github Flow

1. Create a Branch
   1. Navigate to the `​Code​` tab.
   2. Click `​Branch`: `master​` in the drop-down.
   3. In the field, enter a name for your branch.
   4. Click `​Create branch`: `<name>`​ or press the “Enter” key to create your branch.
