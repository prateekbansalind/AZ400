### Git Hooks: Minimalistic Notes

- **Definition:** Git hooks are scripts that Git executes before or after events such as `commit`, `push`, and `receive`. They are used for automating workflows and improving code quality.
  
- **Types:** 
  - **Pre-commit:** Runs before a commit is finalized.
  - **Pre-push:** Executes before a push operation.
  - **Post-receive:** Triggered after receiving code on the server side.

- **Customization:** 
  - Located in `.git/hooks` of a Git repository.
  - Modify or add scripts to automate tasks (e.g., syntax check, linting).

- **Usage:** 
  - **Automation:** Run tests, lint code, check for commit message format.
  - **Security:** Prevent sensitive data from being committed.
  - **Workflow Enforcement:** Ensure code review policies, update tickets/tasks.

- **Setup Example:**
  1. Navigate to your repo's `.git/hooks` directory.
  2. Create or edit a hook script (e.g., `pre-commit`).
  3. Make the script executable: `chmod +x pre-commit`.
  4. Write your script to perform desired checks or tasks.

- **Common Practices:** 
  - Use pre-commit hooks for client-side checks.
  - Utilize post-receive hooks for deployment or notification actions on the server side.

