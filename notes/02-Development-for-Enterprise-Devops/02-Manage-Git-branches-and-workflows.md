Notes on Git Branching for Continuous Delivery:

1. **Git Branching Workflows**:
   - **Trunk-Based Development**: Main branch serves as the development trunk, with short-lived feature branches.
   - **Feature Branch Workflow**: Develop features in dedicated branches, using pull requests for discussions and code review.
   - **Forking Workflow**: Each developer works in their forked repository, contributing back via pull requests.

2. **Implementing Feature Branches**:
   - **Purpose**: Isolate development of features to avoid disturbing the main codebase.
   - **Process**: 
     - Create a branch for each feature.
     - Make commits to this branch.
     - Use pull requests for code review before merging into the main branch.
   - **Benefits**: Encapsulates feature development, allows for continuous integration on the main branch, and leverages pull requests for collaboration and review.

3. **Forking a Repo**:
   - **Use Case**: Ideal for open-source projects or when contributors do not have write access to the main repository.
   - **Process**:
     - Developers fork the main repository, creating their server-side copy.
     - Work is done in the forked repository and contributed back via pull requests.
   - **Benefits**: Maintains a central codebase's integrity while allowing contributions from a broad developer base.

4. **Branch Workflow Types**:
   - **Centralized vs. Distributed**: Choice between workflows depends on team size, project complexity, and collaboration needs.
   - **Considerations**: Scalability, undoing mistakes, cognitive overhead, and alignment with team culture.

5. **Branching for Continuous Delivery**:
   - **Main Branch**: Always ready to release, protected with policies, and changes through pull requests only.
   - **Feature Branch**: For new features or bug fixes, changes merged only through pull requests, named descriptively.
   - **Branch Naming Examples**: `feature/feature-name`, `bugfix/description`, `hotfix/description`.
   - **Pull Requests**: Essential for code review, automated checks, and merging code into the main branch.

6. **GitHub Flow**:
   - A simplified workflow emphasizing collaboration through pull requests and commits to branches without affecting the main branch.
   - Steps include creating a branch, making changes, committing, opening a pull request, discussing and reviewing code, and merging.

7. **Fork Workflow**:
   - Suited for projects with external contributors.
   - Developers fork the repository, make changes in their fork, and contribute back through pull requests to the original repository.

8. **Git Branch Model for Continuous Delivery**:
   - Emphasizes a ready-to-ship main branch with feature branches and pull requests to manage changes, ensuring a steady flow to production.

9. **Lab Exercises**:
   - Cover cloning a repository, making commits, reviewing history, and working with branches using Visual Studio Code, demonstrating Git's flexibility and integration with development tools.

10. **Summary**:
    - Effective Git branching strategies enhance collaboration, streamline the development process, and support continuous delivery by ensuring the main branch remains deployable at all times.