github fundemental machine test
learning github workflow

Here are simple, interview-ready answers written in clean, natural English:

### 1. What is GitHub?

GitHub is a cloud-based hosting service for Git repositories. It allows developers to store, share, track, and collaborate on code projects from anywhere.

---

### 2. Difference between Git and GitHub?

* **Git:** A local command-line tool installed on your computer for version control and tracking code history.
* **GitHub:** An online platform that hosts Git repositories in the cloud and provides team collaboration tools.

---

### 3. What is a Remote Repository?

A remote repository is a version of your project hosted on the internet or a network server (such as GitHub, GitLab, or Bitbucket) rather than on your local computer.

---

### 4. What does `git clone` do?

`git clone` downloads an existing remote repository from a server (like GitHub) to your local machine, automatically setting up tracking branches and the `origin` remote link.

---

### 5. Difference between `git push` and `git pull`?

* **`git push`:** Uploads committed local changes from your computer to the remote repository.
* **`git pull`:** Fetches the latest updates from the remote repository and immediately merges them into your local branch.

---

### 6. What is Forking?

Forking creates a personal, independent copy of another user’s repository under your own GitHub account. It allows you to experiment or make changes without modifying the original project.

---

### 7. What is a Pull Request (PR)?

A Pull Request is a feature on GitHub where you notify repository maintainers that you have pushed changes to a branch/fork and request them to review and merge your code into the target branch.

---

### 8. What does `git remote -v` display?

It lists all configured remote connections along with their short names and corresponding URLs for fetching (`fetch`) and pushing (`push`).

---

### 9. Why is GitHub important in DevOps?

GitHub serves as a central source code repository and integrates directly with CI/CD pipelines (such as GitHub Actions, Jenkins, and Docker). It automates testing, code review, security scanning, and deployments.

---

### 10. Explain the standard GitHub workflow.

1. Create a new branch from `main`.
2. Make code edits locally, then stage and commit them (`git add`, `git commit`).
3. Push the branch to GitHub (`git push`).
4. Open a Pull Request for review.
5. Review, run automated tests, and resolve conflicts.
6. Merge the Pull Request into `main` and delete the feature branch.

---

### 11. What happens if two developers push changes to the same repository?

If both developers update the same branch:

* The first developer’s push succeeds.
* The second developer's push is rejected by Git because their local branch is behind remote.
* The second developer must run `git pull`, resolve any merge conflicts locally, commit, and then push again.

---

### 12. Why is Pull Request approval important?

PR approval ensures code quality, prevents bugs and security vulnerabilities from reaching production, and guarantees that team members review and agree on architectural changes before merging.

---

### 13. What is the purpose of the `origin` keyword?

`origin` is the default alias (nickname) that Git assigns to the remote repository URL from which the project was cloned or where changes are pushed.

---

### 14. Difference between Local and Remote Repository?

* **Local Repository:** Located on your personal computer; operations (commit, branch, log) work completely offline.
* **Remote Repository:** Hosted on a shared server or cloud platform (like GitHub); requires an internet connection to sync changes across team members.

---

### 15. Purpose of `git log --oneline`?

It shows commit history in a clean, compact view where each commit appears on a single line with its shortened commit hash and commit message.
