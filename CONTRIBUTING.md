# Contributing Guidelines
1. Fork the repository.
2. Create a new branch.
3. Submit a pull request.
For more details, contact the maintainer at gaoyue49@example.com.
# Contributing to Web3 Airdrop Filter

Thank you for your interest in contributing to the Web3 Airdrop Filter project! We're excited to have you join in making this project more efficient and user-friendly for discovering and filtering Web3 airdrops.

## Contribution Process

1. **Open or Review Issues**
   - Before starting your contribution, please check for any existing issues or feature requests in the [Issues section](https://github.com/your-username/web3-airdrop-filter/issues) to avoid duplicating effort. If your idea isn't covered, feel free to open a new issue!

2. **Fork the Repository**
   - Click the "Fork" button in the top right corner of the repository to create a copy of the project under your GitHub account.

3. **Clone Your Fork**
   - Clone your fork to your local machine using the following command:
     ```bash
     git clone https://github.com/your-username/web3-airdrop-filter.git
     cd web3-airdrop-filter
     ```

4. **Create a New Branch**
   - Create a new branch for your feature or bug fix:
     ```bash
     git checkout -b feature/my-new-feature
     ```

5. **Make Your Changes**
   - Make the necessary changes in your branch. Ensure that you follow the code style guidelines outlined below.

6. **Commit Your Changes**
   - Commit your changes with a clear message describing what you've done:
     ```bash
     git add .
     git commit -m "feat: add new eligibility filter"
     ```

7. **Push Your Changes**
   - Push your changes to your remote fork:
     ```bash
     git push origin feature/my-new-feature
     ```

8. **Create a Pull Request**
   - Go to the original repository and create a pull request (PR) from your branch. Make sure to select the `main` branch (or `master`, if that's used) for merging.

---

## Commit Guidelines

To make the project history clearer, please use the following commit message format:

- `feat:` New feature or enhancement
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code style changes (no functional change)
- `refactor:` Refactor code (no functional change)
- `test:` Adding or modifying tests
- `chore:` Changes related to build or tooling

### Example Commit:
```bash
git commit -m "feat: add filter for high-value airdrops"
