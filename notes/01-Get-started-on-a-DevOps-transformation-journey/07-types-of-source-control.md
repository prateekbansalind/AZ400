Notes on Source Control Systems - Git and TFVC:

1. **Source Control Overview**:
   - Source control is essential for managing code changes and collaboration in software development.
   - It offers version tracking, collaboration, disaster recovery, and experimentation benefits.

2. **Centralized vs. Distributed Version Control**:
   - **Centralized Source Control**: Features a single central copy of the project (e.g., TFVC, CVS, Subversion). It's suitable for large codebases and environments where audit trails and access control are critical.
   - **Distributed Version Control (DVCS)**: Each developer has a complete copy of the project repository (e.g., Git, Mercurial). Best for small codebases, open source projects, distributed teams, and supports offline development.

3. **Git and TFVC**:
   - **Git**: A distributed version control system that facilitates distributed development, branching, merging, and pull requests. It is community-driven, supports trunk-based development, and integrates well with CI/CD pipelines.
   - **Team Foundation Version Control (TFVC)**: A centralized version control system part of Azure DevOps that supports large codebases and offers two workflow models: server workspaces and local workspaces.

4. **Choosing Between Git and TFVC**:
   - Choose Git for distributed development, flexibility, community support, and integration with modern development practices like trunk-based development and pull requests.
   - Choose TFVC for centralized version control with strong access control, audit trails, and support for large binary files.

5. **Working with Git**:
   - Git operations include clone, commit, push, and pull, allowing developers to manage code changes effectively.
   - Visual Studio Code and other IDEs provide integrated support for Git, offering tools for versioning, branching, and collaborating.

6. **Objections to Using Git**:
   - Concerns include overwriting history, handling large files, and the learning curve. Solutions like Git LFS (Large File Storage) and security rules in Azure Repos address these issues.

7. **Best Practices for Source Control**:
   - Commit early and often, avoid committing personal or sensitive files, update regularly, and link code changes to work items.
   - Use meaningful commit messages and follow team conventions for a consistent development process.

8. **Summary**:
   - Understanding and choosing the right source control system—centralized (TFVC) or distributed (Git)—is crucial for efficient development workflows.
   - Git offers flexibility and is widely adopted for distributed development, while TFVC provides a robust solution for centralized control.
   - Proper source control practices enhance collaboration, ensure code quality, and support agile and DevOps methodologies.


[lab exercise](https://learn.microsoft.com/en-us/training/modules/describe-types-of-source-control-systems/7-describe-working-git-locally)