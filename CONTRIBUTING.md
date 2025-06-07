# Contributing to The Hazzard Continuum

First off, thank you for considering contributing! We are thrilled you're interested in helping build a more logical and human-centric future. This project is a community effort, and every contribution is valued.

## How Can I Contribute?

There are many ways to contribute, from writing code to proposing new ideas. Here’s how to get started.

### Proposing Changes to the Standard (RFCs)

The Hazzard Continuum is defined by a formal Request for Comments (RFC) document. If you have an idea to change or improve the core standard (the calendar, time, or temperature systems), we have a process for that.

1.  **Start a Discussion:** Open an "Issue" on GitHub first. Describe your idea and the problem it solves. This allows the community to discuss the idea before you invest time in a formal proposal.
2.  **Write a Formal Proposal:** If the idea gains traction, you can write a formal proposal. You can find a template in `standard/proposals/`.
3.  **Submit a Pull Request:** Create a new file in the `standard/proposals/` directory and submit it as a Pull Request. This will be the central place for the community to review and comment on the specific changes.

### Reporting Bugs or Suggesting Enhancements

-   **Reporting Bugs:** If you find a bug in the application, please open an "Issue" using the "Bug Report" template. Provide as much detail as possible, including steps to reproduce the bug.
-   **Suggesting Enhancements:** If you have an idea for a new feature or an improvement to the app, open an "Issue" using the "Feature Request" template.

### Your First Code Contribution

Ready to write some code? Here’s how to set up your development environment and submit your changes.

1.  **Fork the Repository:** Click the "Fork" button at the top right of this page.
2.  **Clone Your Fork:**
    ```bash
    git clone https://github.com/YOUR-USERNAME/continuum.git
    cd continuum
    ```
3.  **Create a New Branch:** Choose a descriptive branch name.

    ```bash
    # For a new feature
    git checkout -b feature/my-awesome-feature

    # For a bug fix
    git checkout -b fix/fix-that-annoying-bug
    ```

4.  **Make Your Changes:** The code for the web app is located in the `apps/webapp` directory. Make your changes there.
5.  **Commit Your Changes:** Write a clear and concise commit message.
    ```bash
    git commit -m "feat: Add a new visualization for the day arc"
    ```
6.  **Push to Your Fork:**
    ```bash
    git push origin feature/my-awesome-feature
    ```
7.  **Open a Pull Request:** Go to the original repository on GitHub and open a new Pull Request. The pull request template will guide you through providing the necessary information.

### Style Guides

-   **Code:** We use Prettier to maintain a consistent code style. Please ensure your code is formatted before committing.
-   **Git Commits:** We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification for our commit messages. This helps keep the commit history clean and readable.

Thank you again for your interest in The Hazzard Continuum!
