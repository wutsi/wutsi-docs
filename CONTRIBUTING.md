# CONTRIBUTING
The following is a set of guidelines for contributing to Wutsi and its packages. 
These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## How to Contribute
### Setup your Environment
[Environment Setup](Setup.md)

### Contribute to the code
- Never commit straight to master
- All changes must be via Pull Request
- Pull request must be reviewed and approved by peers
- Pull Request approved are merged by their owners
- All Pull Request are automatically deployed by the CI/CD to Test and Prod environment. 
- The owner of the PR must make sure that the deployment is successful, If not he must revert his change and fix it. 

#### Pull Requests Guideline
Each pull request must include
- The link the story
- A short description

#### Coding Style
- Kotlin Code style is enforced by [klint](https://ktlint.github.io/)
- Dart Code style by [Dart Compiler](https://dart.dev/guides/language/effective-dart/style)

#### Code Coverage
- Backend code coverage must be at **85%+**

