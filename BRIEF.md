# 🎯 Repository Theme: Team Collaboration Using Git and GitHub

## 📑 Table of Contents

- [Overview](#-overview)
- [Prerequisites & Setup](#-prerequisites--setup)
- [Evaluation Criteria](#-evaluation-criteria)
- [Team Organization](#-team-organization)
- [Communication Channels](#-communication-channels)
- [Suggested Repository Structure](#%EF%B8%8F-suggested-repository-structure)
- [Team Responsibilities](#-team-responsibilities)
- [Recommended Workflow](#-recommended-workflow)
- [Handling Merge Conflicts](#-handling-merge-conflicts)
- [Troubleshooting](#-troubleshooting)
- [FAQ](#-faq)
- [Additional Resources](#-additional-resources)

## 📋 Overview

This project is a collaborative learning exercise focused on modern software development workflows using Git and GitHub. All students will contribute to a single shared repository, simulating a real-world team environment.

## 🔧 Prerequisites & Setup

### Required Knowledge

Before starting this project, you should have:

- **Basic Git Skills:**
  - Creating and switching branches
  - Making commits
  - Pushing and pulling changes
  - Basic understanding of merge conflicts
  
- **GitHub Account:**
  - Active GitHub account with verified email
  - Git configured with your name and email
  - SSH keys or personal access token set up (Or authenticated via VSCode. DON'T FORGET to logout before turning off your computer!!!)

### Required Tools

- **Git:** Version 2.30 or higher
- **Text Editor:** VS Code, Sublime Text, or your preferred editor
- **Terminal:** Command line access (Terminal, Git Bash, PowerShell)

### Getting Repository Access

1. Confirm your GitHub username with your instructor
2. Accept the repository invitation via email or GitHub notifications
3. Clone the repository to your local machine:

   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

4. Verify you can see the `pw25-27` branch:

   ```bash
   git fetch origin
   git branch -a
   ```

### Setting Up Your Environment

Ensure your Git configuration is correct:

```bash
# Set your name
git config --global user.name "Your Full Name"

# Set your email (use the one linked to your GitHub account)
git config --global user.email "your.email@example.com"

# Verify your settings
git config --list
```

> ⚠️ **Important:** All commits must be properly signed with your information. Anonymous or incorrectly attributed commits may not count toward your evaluation.

## ⭐ Evaluation Criteria

Your work will be assessed based on the following criteria:

### Content Quality (40%)

- **Accuracy:** Information is correct and well-researched
- **Clarity:** Explanations are clear and easy to understand
- **Completeness:** All required topics are covered adequately
- **Examples:** Includes practical examples, screenshots, or code snippets
- **Writing Quality:** Professional tone, proper grammar, well-structured

### Git/GitHub Practice (30%)

- **Commit Quality:**
  - Clear, meaningful commit messages
  - Follows conventional commit format [Follow Here](https://www.conventionalcommits.org/en/v1.0.0/)
  - Atomic commits (focused changes)
  - **Every team member must have commits** (authorship matters!)
  
- **Branch Management:**
  - Proper branch naming conventions
  - Clean branch history
  
- **Pull Request Quality:**
  - Descriptive title and description
  - Links to relevant issues
  - Proper target branch

### Collaboration (20%)

- **Code Reviews:**
  - Constructive feedback provided
  - Professional communication
  - Timely responses
  
- **Team Coordination:**
  - Evidence of planning and organization
  - Balanced contribution among team members
  - Effective use of GitHub features (Issues, Discussions, etc.)

### Documentation (10%)

- **File Organization:** Logical structure, easy to navigate
- **README Quality:** Clear overview and navigation
- **References:** Proper citations and sources

### Grading Scale

| Grade | Percentage | Criteria |
|-------|-----------|----------|
| **Excellent** | 90-100% | Exceeds all requirements, exceptional quality, exemplary collaboration |
| **Very Good** | 80-89% | Meets all requirements with high quality, good collaboration practices |
| **Good** | 70-79% | Meets most requirements, acceptable quality, adequate collaboration |
| **Satisfactory** | 60-69% | Meets minimum requirements, basic quality, limited collaboration evidence |
| **Needs Improvement** | Below 60% | Missing requirements, poor quality, or inadequate participation |

> 🎯 **Success Criteria:** To pass, your team must demonstrate meaningful contributions from all members, proper Git practices, and comprehensive coverage of assigned topics.

## 🧩 Team Organization

**Team Size:** All students divided into 2 groups

### Group 1: Project Management & GitHub Collaboration

Focus on collaboration tools and project management features

### Group 2: Git Best Practices & Development Workflow

Focus on Git discipline and healthy development practices

> **Important:** While teams are divided by focus areas, the repository structure should remain unified. The final result should appear as cohesive work without visible team boundaries.

## 💬 Communication Channels

Effective communication is crucial for successful collaboration. Use the following channels:

### Primary Communication

- **GitHub Issues:** For task planning, bug reports, and feature discussions
  - Use appropriate labels (e.g., `question`, `enhancement`, `documentation`)
  - Assign team members to relevant issues
  - Link issues in commits and PRs
  
- **GitHub Discussions:** For general questions, ideas, and team conversations
  - Use for brainstorming and decision-making
  - Document important decisions for future reference

### Pull Request Communication

- **PR Comments:** For code review feedback and suggestions
- **Review Threads:** For specific line-by-line discussions
- **PR Descriptions:** For explaining changes and providing context

### Team Coordination

- **Additional Channels:** Your instructor may provide additional communication tools (Slack, Discord, Teams)
- **Response Time:** Aim to respond to mentions and questions within 24 hours
- **Professional Etiquette:** Always be respectful, constructive, and professional

> 💡 **Best Practice:** Keep all project-related discussions in GitHub when possible. This creates a searchable history and keeps everyone informed.

## 🏗️ Suggested Repository Structure

```tree
.
├── .gitignore
├── README.md
├── CONTRIBUTING.md
├── introduction/
│   └── objectives.md
├── collaboration/
│   ├── issues_and_discussions.md
│   ├── pull_requests_and_reviews.md
│   ├── wiki_and_documentation.md
│   └── project_management.md
├── git_best_practices/
│   ├── branch_naming.md
│   ├── commit_messages.md
│   ├── tags_and_releases.md
│   ├── workflow_patterns.md
│   └── advanced_git.md
└── references/
    ├── glossary.md
    ├── sources.md
    └── practical_examples.md
```

> ⚠️ **Note:** This structure is a starting point. Teams should collaboratively decide whether to maintain or reorganize folders and files, practicing real project management.

### Essential Files

- **`.gitignore`:** Specify files to ignore (e.g., `.DS_Store`, editor configs, temporary files)
- **`README.md`:** Project overview, navigation, and quick start guide
- **`CONTRIBUTING.md`:** Guidelines for contributing to the project (optional but recommended)

## 🧠 Team Responsibilities

### Group 1 – Project Management & GitHub Collaboration

**Objective:** Explore and document how teams collaborate without writing code

**Topics to Cover:**

- **Issues:** Creation, labels, milestones, and task planning
- **Discussions:** Team communication and idea sharing
- **Pull Requests:** Review process, comments, and approval best practices
- **Wiki:** Project documentation and internal guides
- **Project Boards:** Visual progress management (Kanban, Scrum, etc.)

**Deliverables:**

- 3–5 markdown files with clear explanations and examples (screenshots encouraged)
- Practical guide on using GitHub's project management tools
- Each file must include real-world examples or use cases

---

### Group 2 – Git Best Practices & Development Discipline

**Objective:** Explain how Git maintains healthy, organized development

**Topics to Cover:**

- **Branch Naming Conventions:** `feature/`, `bugfix/`, `hotfix/`, etc.
- **Commit Message Best Practices:** Clear, consistent, and meaningful commits
- **Tags & Releases:** Version management and release strategies
- **Branching Models:** Git Flow, GitHub Flow, trunk-based development
- **Advanced Concepts:** Rebase, squash, cherry-pick (when appropriate)

**Deliverables:**

- 3–5 markdown files with clear explanations and examples (screenshots encouraged)
- Practical examples demonstrating proper Git workflows and commands
- Command-line examples with explanations of what each command does

## 🔄 Recommended Workflow

### 1. Branch Creation

Each group creates their feature branch from `pw25-27`:

```bash
# Make sure you're up to date
git fetch --all --prune
git switch pw25-27
git pull --rebase

# Create and switch to your feature branch
# Group 1:
git checkout -b feature/project-management-collaboration

# Group 2:
git checkout -b feature/git-best-practices

# Push your branch to remote
git push -u origin <your-branch-name>
```

**Branch Naming:**

- **Group 1:** `feature/project-management-collaboration`
- **Group 2:** `feature/git-best-practices`

### 2. Content Organization

- Organize content within shared folders (without indicating team ownership)
- Use the suggested structure or propose improvements collaboratively
- Create Issues for major tasks and link them to your work
- Use Project Boards to track progress (Optional)

### 3. Commit Regularly

- Make frequent commits with clear messages
- **EVERY team member MUST have commits** (Be aware of the commit Authoring Data!!!)
- Follow conventional commit format when possible

**Commit Message Format:**

```text
<type>: <short summary>

[optional body]

[optional footer]
```

**Examples:**

- `docs: add section about pull request reviews`
- `docs: create branch naming conventions guide`
- `fix: correct typo in commit messages documentation`
- `feat: add troubleshooting section with common issues`

**Common Types:**

- `docs:` - Documentation changes
- `feat:` - New content or sections
- `fix:` - Corrections or fixes
- `refactor:` - Restructuring content
- `style:` - Formatting changes

### 4. Self-Review and Validation

Before submitting your PR, validate your work:

**Content Checklist:**

- [ ] All required topics are covered
- [ ] Each file has at least 500 words
- [ ] Examples and screenshots are included
- [ ] No spelling or grammar errors
- [ ] All links work correctly
- [ ] Markdown renders properly

**Git Checklist:**

- [ ] All team members have commits
- [ ] Commit messages are clear and follow conventions
- [ ] No merge conflicts with target branch
- [ ] Branch is up to date with `pw25-27`

**Validation Commands:**

```bash
# Check your commit history
git log --oneline --graph

# Check which files changed
git diff pw25-27

# Verify all team members contributed
git shortlog -sn

# Update your branch with latest changes
git fetch origin
git merge origin/pw25-27
```

### 5. Pull Request Submission

**Target:** All PRs must target the `pw25-27` branch

**Steps to Create a PR:**

1. **Push your latest changes:**

   ```bash
   git push origin <your-branch-name>
   ```

2. **Open Pull Request on GitHub:**
   - Navigate to the repository
   - Click "Pull Requests" → "New Pull Request"
   - Base: `pw25-27` ← Compare: `<your-branch-name>`

3. **Use Draft PRs for work in progress:**
   - Click "Create Draft Pull Request" if not ready for review
   - Convert to "Ready for Review" when complete

**PR Template:**

```markdown
## Description
Brief summary of what this PR adds

## Topics Covered
- Topic 1
- Topic 2
- ...

## Team Contributions
List each team member and their contributions

## Checklist
- [ ] All deliverables complete
- [ ] Every team member has commits
- [ ] Content reviewed for quality
- [ ] No merge conflicts
- [ ] Ready for peer review

## Related Issues
Closes #issue-number (if applicable)
```

### 6. Code Review

**For Reviewers:**

- Review the other team's Pull Request thoroughly
- Provide constructive feedback and suggest improvements
- Practice professional review etiquette
- Use GitHub's review features (comments, suggestions, approval)
- Check for completeness, accuracy, and clarity

**Review Guidelines:**

✅ **Good Feedback:**

- "This section is clear, but could benefit from an example showing..."
- "Consider adding a screenshot here to illustrate the process"
- "Small typo on line 45: 'repositroy' → 'repository'"

❌ **Poor Feedback:**

- "This is wrong"
- "Bad explanation"
- "Needs more work"

**Review Process:**

1. Read through all changed files
2. Leave line-by-line comments where appropriate
3. Test any commands or instructions provided
4. Provide an overall summary review
5. Approve or request changes

### 7. Address Feedback

- Respond to all review comments
- Make requested changes in new commits
- Don't force-push; keep the review history
- Re-request review after addressing feedback
- Thank reviewers for their input

```bash
# Make changes based on feedback
git add .
git commit -m "docs: address review feedback on branching section"
git push origin <your-branch-name>
```

### 8. Merge

**Prerequisites:**

- At least one approval from the other team
- All conversations resolved
- No merge conflicts

**Merge Process:**

- After approval from reviewers, a team member performs the merge
- Target branch: `pw25-27`
- Use "Create a merge commit" as agreed with your instructor
- Delete the feature branch after merging (optional)

### 9. Release

**Final Step:** The WHOLE class collaborates to create a version release for the final state of the work

**Release Process:**

1. Ensure all PRs are merged to `pw25-27`
2. Review the complete project
3. Create a tag for the release:

    ```bash
    git switch pw25-27
    git pull --rebase
    git tag -a 1.0.0 -m "Final project release"
    git push --tags
    ```

4. Create a GitHub Release with release notes
5. Include a summary of contributions from both teams

> 💡 **Tip:** Consider creating milestone releases (0.1.0 for drafts, 1.0.0 for final) to practice version management.

## 🔀 Handling Merge Conflicts

Merge conflicts occur when Git cannot automatically merge changes. This is normal and expected in collaborative projects!

### Understanding Merge Conflicts

**When conflicts happen:**

- Two people edit the same line(s) in a file
- One person deletes a file while another modifies it
- Multiple people work on related content simultaneously

**Don't panic!** Merge conflicts are a normal part of collaboration and can be resolved systematically.

### Preventing Conflicts

**Best Practices:**

- Communicate with your team about who's working on what
- Pull latest changes frequently: `git pull --rebase`
- Work on different files when possible
- Make smaller, more frequent commits
- Use GitHub Issues to claim tasks before starting

### Resolving Merge Conflicts

#### Step 1: Identify the Conflict

When you try to merge or pull and get a conflict:

```bash
git pull origin pw25-27
# Auto-merging collaboration/issues_and_discussions.md
# CONFLICT (content): Merge conflict in collaboration/issues_and_discussions.md
# Automatic merge failed; fix conflicts and then commit the result.
```

Check which files have conflicts:

```bash
git status
# You will see:
# Unmerged paths:
#   (use "git add <file>..." to mark resolution)
#   both modified:   collaboration/issues_and_discussions.md
```

#### Step 2: Open the Conflicted File

Open the file in your editor. Git marks conflicts like this:

```markdown
## Pull Requests

<<<<<<< HEAD
Pull requests are a way to propose changes to the repository.
They allow team members to review code before merging.
=======
Pull requests (PRs) are GitHub's method for proposing and reviewing changes.
PRs enable collaborative code review and discussion.
>>>>>>> pw25-27
```

**Understanding the markers:**

- `<<<<<<< HEAD` - Your current changes
- `=======` - Divider between changes
- `>>>>>>> pw25-27` - Incoming changes from pw25-27 branch

#### Step 3: Resolve the Conflict

**Choose one of these approaches:**

1. **Keep your changes:**

   ```markdown
   ## Pull Requests
   
   Pull requests are a way to propose changes to the repository.
   They allow team members to review code before merging.
   ```

2. **Keep their changes:**

   ```markdown
   ## Pull Requests
   
   Pull requests (PRs) are GitHub's method for proposing and reviewing changes.
   PRs enable collaborative code review and discussion.
   ```

3. **Combine both (often the best approach):**

   ```markdown
   ## Pull Requests
   
   Pull requests (PRs) are GitHub's method for proposing and reviewing changes to the repository.
   They enable collaborative code review, discussion, and team approval before merging.
   ```

4. **Write something completely new:**

   ```markdown
   ## Pull Requests
   
   A pull request is a GitHub feature that facilitates code review and collaboration.
   When you open a PR, you're proposing your changes and requesting that someone
   review and merge them into the target branch.
   ```

**Remove all conflict markers** (`<<<<<<<`, `=======`, `>>>>>>>`)

#### Step 4: Mark as Resolved

After fixing all conflicts in the file:

```bash
# Stage the resolved file
git add collaboration/issues_and_discussions.md

# Check if all conflicts are resolved
git status
```

#### Step 5: Complete the Merge

Once all conflicts are resolved:

```bash
# Commit the merge
git commit -m "merge: resolve conflicts with pw25-27 branch"

# Push the changes
git push origin <your-branch-name>
```

### Getting Help with Conflicts

If you're stuck:

1. **Don't force anything** - never use `git push --force` without understanding why
2. **Ask for help** - tag a teammate or instructor in a GitHub Issue
3. **Communicate** - discuss the conflict with the person who made the other changes
4. **Document** - explain your resolution in the commit message

### Practice Scenario

**Simulating a conflict (for learning):**

```bash
# Create a test file
echo "Line 1" > test.md
git add test.md
git commit -m "docs: add test file"

# Create two branches
git branch branch-a
git branch branch-b

# Make different changes on each branch
git checkout branch-a
echo "Line 2 from branch A" >> test.md
git commit -am "docs: add line from branch A"

git checkout branch-b
echo "Line 2 from branch B" >> test.md
git commit -am "docs: add line from branch B"

# Try to merge - this will create a conflict!
git checkout branch-a
git merge branch-b
# Now resolve it!
```

## 🔧 Troubleshooting

Common issues and their solutions:

### Problem: "Your branch is behind" or "Your branch has diverged"

**Cause:** Remote branch has changes you don't have locally

**Solution:**

```bash
# Pull the latest changes
git pull origin <branch-name>

# If you have local commits that conflict, you may need to rebase
git pull --rebase origin <branch-name>
```

### Problem: Commit has wrong author name/email

**Cause:** Git config not set correctly

**Prevention:**

```bash
# Set your info globally
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

**Fix last commit:**

```bash
git commit --amend --author="Your Name <your.email@example.com>" --no-edit
```

> ⚠️ **Warning:** Only amend commits that haven't been pushed yet!

### Problem: Accidentally committed to wrong branch

**Solution:**

```bash
# Save your changes
git log  # Note the commit hash

# Undo the commit (keep changes)
git reset --soft HEAD~1

# Switch to correct branch
git checkout <correct-branch>

# Commit on the correct branch
git add .
git commit -m "your message"
```

### Problem: Need to undo last commit

**If not pushed yet:**

```bash
# Undo commit but keep changes
git reset --soft HEAD~1

# Undo commit and discard changes (careful!)
git reset --hard HEAD~1
```

**If already pushed:**

```bash
# Create a new commit that undoes the previous one
git revert HEAD
git push origin <branch-name>
```

### Problem: Accidentally deleted a file

**Solution:**

```bash
# If not committed yet
git restore <filename>

# If committed, find the file in history
git log -- <filename>
git checkout <commit-hash> -- <filename>
```

### Problem: Pull request has conflicts with target branch

**Cause:** Target branch (pw25-27) was updated after you created your branch

**Solution:**

```bash
# Update your local pw25-27
git fetch origin
git checkout pw25-27
git pull origin pw25-27

# Switch back to your feature branch
git checkout <your-branch>

# Merge or rebase with pw25-27
git merge pw25-27
# OR
git rebase pw25-27

# Resolve any conflicts
# Then push
git push origin <your-branch>
```

### Problem: "fatal: refusing to merge unrelated histories"

**Cause:** Trying to merge branches with no common history

**Solution:**

```bash
# Allow unrelated histories (use with caution)
git pull origin <branch> --allow-unrelated-histories
```

### Problem: Large file causing push to fail

**Cause:** GitHub has file size limits (100MB)

**Solution:**

```bash
# Remove the file from the last commit
git rm --cached <large-file>
git commit --amend -m "docs: remove large file"

# Add file to .gitignore
echo "<large-file>" >> .gitignore
git add .gitignore
git commit -m "chore: update gitignore"
```

### Problem: Need to undo all local changes

**Solution:**

```bash
# Discard all unstaged changes
git restore .

# Discard all changes including staged files
git reset --hard HEAD

# Get the branch to exactly match remote
git fetch origin
git reset --hard origin/<branch-name>
```

### Getting Help

When troubleshooting:

1. **Read the error message carefully** - Git errors are usually descriptive
2. **Check git status** - shows what state you're in
3. **Use git log** - understand your commit history
4. **Search the error** - someone has likely encountered it before
5. **Ask your team** - collaborate on solutions
6. **Create an Issue** - document the problem for instructor help
7. **Check documentation** - official Git and GitHub docs

**Useful commands for debugging:**

```bash
# See what's changed
git status
git diff

# See commit history
git log --oneline --graph --all

# See who changed what
git blame <filename>

# See details of a commit
git show <commit-hash>

# See all branches
git branch -a
```

## ❓ FAQ

### General Questions

**Q: What if I don't know anything about Git/GitHub?**

A: That's okay! This project is designed to help you learn. Start with the prerequisites section, watch some tutorials, and don't hesitate to ask questions. Learning by doing is the best approach.

---

**Q: How do I know which team I'm in?**

A: Your instructor will assign you to either Group 1 (Project Management & GitHub Collaboration) or Group 2 (Git Best Practices & Development Workflow).

---

**Q: Can I work on both team's topics?**

A: Focus on your assigned team's topics for the main deliverables. However, you're encouraged to review and provide feedback on the other team's work during the code review phase.

---

**Q: What if my team has unequal participation?**

A: Each team member MUST have commits. If someone isn't participating, communicate early with your instructor. Document efforts to include everyone via GitHub Issues and Discussions.

---

**Q: How many commits should I make?**

A: Quality over quantity, but aim for meaningful, regular commits. Each significant change should be its own commit. As a guideline, expect 5-10+ commits per person throughout the project.

---

### Technical Questions

**Q: Should we use `git merge` or `git rebase`?**

A: For this project, `git merge` is recommended as it preserves history and is easier to understand. Rebase can be discussed as an advanced topic in Group 2's documentation.

---

**Q: What if I accidentally push to the wrong branch?**

A: Don't panic! See the Troubleshooting section. Generally, you can revert changes with `git revert` or reset your branch. Ask for help if needed.

---

**Q: Can I delete my commits after pushing?**

A: Avoid deleting or force-pushing commits that others might have pulled. Instead, use `git revert` to undo changes. Only use force operations if you're absolutely sure no one has pulled your changes.

---

**Q: How do I test my Markdown before committing?**

A:

- Use VS Code's Markdown Preview (Ctrl/Cmd + Shift + V)
- Preview on GitHub by viewing your branch
- Use online tools like <https://dillinger.io/>
- Commit to your branch and check how it renders on GitHub

---

**Q: What file format should we use?**

A: All documentation should be in Markdown (.md) format. Markdown is GitHub's standard for documentation.

---

**Q: Can we include images/screenshots?**

A: Yes! Images and screenshots are encouraged. Store them in an `images/` or `assets/` folder and reference them in markdown:

```markdown
![Alt text](images/screenshot.png)
```

---

### Collaboration Questions

**Q: What if my team disagrees on something?**

A: Use GitHub Discussions or Issues to document the disagreement and vote on options. If you can't reach consensus, consult your instructor. Document the decision-making process.

---

**Q: How formal should our reviews be?**

A: Be professional and constructive, but friendly. Focus on the content, not the person. Provide specific, actionable feedback.

---

**Q: Can we split the work and never talk to each other?**

A: No! Collaboration is key. You must coordinate through Issues, Discussions, and reviews. Evidence of collaboration is part of your evaluation.

---

**Q: What if the other team's work overlaps with ours?**

A: Some overlap is natural and okay. Focus on your assigned perspective. During reviews, you can suggest ways to reduce redundancy or improve integration.

---

**Q: How should we divide the work?**

A: Create GitHub Issues for each task and assign team members. Ensure everyone contributes across different files. Don't just assign one file per person.

---

### Workflow Questions

**Q: When should I create a Pull Request?**

A: Create a draft PR early to show progress, then mark it ready for review when your team's work is complete and validated.

---

**Q: Who approves our Pull Request?**

A: The other team reviews and approves your PR. At least one approval is required before merging.

---

**Q: Can we merge before the other team is done?**

A: Follow the timeline provided by your instructor. Typically, both teams should complete their work and reviews before merging.

---

**Q: What if we find a bug after merging?**

A: Create an Issue documenting the bug, then create a new branch to fix it, and submit another PR. This is normal in real projects!

---

**Q: Should we create multiple PRs or one big PR?**

A: One PR per team containing all your work is the standard approach for this project. However, if your team wants to break it into smaller PRs (e.g., one per topic), discuss with your instructor.

---

### Grading Questions

**Q: How important are commit messages?**

A: Very important! They demonstrate your understanding of Git best practices and contribute to the "Git/GitHub Practice" portion of your grade (30%).

---

**Q: Will we be graded individually or as a team?**

A: Both. Team deliverables are graded as a group, but individual contributions are tracked through commits and participation in reviews.

---

**Q: What happens if I don't have any commits?**

A: You may receive a significantly reduced grade or fail the assignment. Every team member MUST contribute commits.

---

**Q: Can we revise after the final merge?**

A: Minor corrections might be allowed at instructor discretion, but plan to have everything complete by the merge deadline.

---

## 📚 Additional Resources

### Official Documentation

**Git:**

- [Official Git Documentation](https://git-scm.com/doc)
- [Pro Git Book (Free)](https://git-scm.com/book/en/v2)
- [Git Reference Manual](https://git-scm.com/docs)

**GitHub:**

- [GitHub Docs](https://docs.github.com/)
- [GitHub Skills - Interactive Tutorials](https://skills.github.com/)
- [GitHub Guides](https://guides.github.com/)

**Markdown:**

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Markdown Guide](https://www.markdownguide.org/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Learning Resources

**Interactive Tutorials:**

- [Learn Git Branching](https://learngitbranching.js.org/) - Visual, interactive Git tutorial
- [GitHub Learning Lab](https://lab.github.com/)
- [Katacoda Git Scenarios](https://www.katacoda.com/courses/git)

**Video Tutorials:**

- [Git & GitHub Crash Course (YouTube - Traversy Media)](https://www.youtube.com/watch?v=RGOj5yH7evk)
- [Git Tutorial for Beginners (YouTube - Programming with Mosh)](https://www.youtube.com/watch?v=8JJ101D3knE)
- [GitHub Training & Guides (Official)](https://www.youtube.com/githubguides)

**Articles & Guides:**

- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
- [GitHub Flow Guide](https://docs.github.com/en/get-started/quickstart/github-flow)
- [Oh Shit, Git!?!](https://ohshitgit.com/) - How to fix common Git mistakes

### Best Practices & Conventions

**Commit Messages:**

- [Conventional Commits](https://www.conventionalcommits.org/)
- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
- [The Art of the Commit](https://alistapart.com/article/the-art-of-the-commit/)

**Branching Strategies:**

- [Git Flow](https://nvie.com/posts/a-successful-git-branching-model/)
- [GitHub Flow](https://githubflow.github.io/)
- [Trunk-Based Development](https://trunkbaseddevelopment.com/)

**Code Review:**

- [Google's Code Review Guidelines](https://google.github.io/eng-practices/review/)
- [GitHub's Guide to Reviewing PRs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests)

### Tools & Extensions

**Git Clients:**

- [GitHub Desktop](https://desktop.github.com/) - Simple GUI for Git
- [GitKraken](https://www.gitkraken.com/) - Visual Git client
- [SourceTree](https://www.sourcetreeapp.com/) - Free Git GUI for Mac/Windows

**VS Code Extensions:**

- GitLens - Supercharge Git in VS Code
- Git Graph - View Git graph and perform actions
- Markdown All in One - Enhanced Markdown support
- Markdown Preview Enhanced - Better Markdown preview

**Online Tools:**

- [Dillinger](https://dillinger.io/) - Online Markdown editor
- [Excalidraw](https://excalidraw.com/) - Draw diagrams for documentation
- [Carbon](https://carbon.now.sh/) - Create beautiful code screenshots

### Cheat Sheets

**Git Commands:**

- [GitHub Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [Atlassian Git Cheat Sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)
- [GitLab Git Cheat Sheet](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)

**GitHub Features:**

- [GitHub Features Quick Reference](https://github.com/tiimgreen/github-cheat-sheet)
- [Awesome GitHub](https://github.com/phillipadsmith/awesome-github) - Curated list of GitHub resources

### Community & Support

**Forums & Q&A:**

- [Stack Overflow - Git Tag](https://stackoverflow.com/questions/tagged/git)
- [GitHub Community Forum](https://github.community/)
- [Reddit - r/git](https://www.reddit.com/r/git/)

**Keep Learning:**

- [GitHub Blog](https://github.blog/)
- [Git Rev News](https://git.github.io/rev_news/) - Git community newsletter
- [Dev.to - Git Tag](https://dev.to/t/git) - Community articles

### Advanced Topics (Optional)

For students interested in going deeper:

- [Git Internals](https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain)
- [Advanced Git Tutorials by Atlassian](https://www.atlassian.com/git/tutorials/advanced-overview)
- [GitHub Actions Documentation](https://docs.github.com/en/actions) - CI/CD with GitHub
- [Git Hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
- [Semantic Versioning](https://semver.org/)

---

## 📝 Final Submission Checklist

Before considering your work complete, verify the following:

### Content Requirements

- [ ] All assigned topics are covered comprehensively
- [ ] Each markdown file has at least 500 words
- [ ] Real-world examples are included
- [ ] Screenshots or diagrams illustrate key concepts
- [ ] Writing is clear, professional, and well-organized
- [ ] No spelling or grammatical errors
- [ ] All links are functional
- [ ] Markdown renders correctly on GitHub

### Git & GitHub Requirements

- [ ] Every team member has meaningful commits
- [ ] Commit messages follow conventional format
- [ ] Commits are authored correctly (name/email)
- [ ] Feature branch created from `pw25-27`
- [ ] Branch naming follows convention
- [ ] No merge conflicts with target branch
- [ ] Pull Request created targeting `pw25-27`
- [ ] PR has descriptive title and complete description
- [ ] PR links to relevant Issues (if applicable)

### Collaboration Requirements

- [ ] GitHub Issues created for major tasks
- [ ] Team discussions documented in Issues/Discussions
- [ ] Evidence of coordination and planning
- [ ] All team members participated in reviews
- [ ] Constructive feedback provided to other team
- [ ] Review comments addressed professionally
- [ ] At least one approval received from other team

### Repository Requirements

- [ ] Files organized logically in folders
- [ ] README.md provides clear navigation
- [ ] .gitignore file exists (if needed)
- [ ] CONTRIBUTING.md created (optional but recommended)
- [ ] No unnecessary files committed
- [ ] Repository structure makes sense

### Review & Quality Assurance

- [ ] Content reviewed by all team members
- [ ] Self-validation checklist completed
- [ ] Commands and examples tested
- [ ] Links verified
- [ ] Formatting consistent throughout
- [ ] Code blocks properly formatted
- [ ] Images display correctly

### Final Steps

- [ ] Draft PR converted to "Ready for Review"
- [ ] Team notified that work is ready
- [ ] Other team's feedback incorporated
- [ ] All review conversations resolved
- [ ] Final approval received
- [ ] Merged to `pw25-27` branch
- [ ] Feature branch deleted (optional)
- [ ] Contributed to final class release

---

## 🎉 Conclusion

This project is designed to simulate real-world collaborative software development. The skills you develop here—Git proficiency, clear communication, code review, and teamwork—are essential in the tech industry.

**Remember:**

- Collaboration is key
- Mistakes are learning opportunities
- Ask questions early and often
- Document your decisions
- Be professional and respectful
- Have fun learning together!

Good luck, and happy collaborating! 🚀

---

**Need Help?** Contact your instructor or create an Issue in the repository with the label `question`.
