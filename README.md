# branchingTest
branching strategy Test

### What are the branching strategies?
- a branching strategy is something a software development team uses when interacting with a version control system for writing and managing code. 
As the name suggests, the branching strategy focuses on how branches are used in the development process

- Docs
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
https://docs.github.com/en/get-started/quickstart/github-flow


### VSCODE extention: 

```sh
- git graph
Git Graph extension for Visual Studio Code
View a Git Graph of your repository, and easily perform Git actions from the graph.
```

### Useful commands/Install dependencies:  

```sh
- install virtualenv if u dont have yet
py -m pip install virtualenv

- run the code below
py -m virtualenv venv

- activate env
. venv\scripts\activate

- install requirements
pip install -r requirements.txt

- List installed modules
pip freeze
it tells you which modules you've installed with pip install and the versions of these modules that you are currently have installed on your computer

- Unistall installed modules
pip uninstall <packagename>
pip uninstall -y <packagename>
uninstall ALL
pip uninstall -y (pip freeze)

```
### Python Unit Testing:  

```sh
https://www.javatpoint.com/python-unit-testing
https://docs.python.org/3/library/unittest.html

```
### Python Tutorial:  

```sh
https://www.w3schools.com/python/default.asp
https://www.tutorialsteacher.com/python/decorators
```

### TODO:  

```sh
first step for u to understand branching
im following this documentation
https://docs.github.com/en/get-started/quickstart/github-flow

- Create a branch
feature/my-first-todo

- Make changes
create a python file 
- unittest (Basic example)
https://docs.python.org/3/library/unittest.html

- try to follow TDD(Test-driven development)
https://www.guru99.com/test-driven-development.html
 - add your unittest
 - make sure u have the required return/response thru assert  

- Commit and push 
Commit and push your changes to your branch. 
Give each commit a descriptive message to help you and future contributors understand what changes the commit contains. 
For example, fix typo or increase rate limit.

By committing and pushing your changes, you back up your work to remote storage. This means that you can access your work from any device. It also means that your collaborators can see your work, answer questions, and make suggestions or contributions.

Continue to make, commit, and push changes to your branch until you are ready to ask for feedback.

- Create a PR(pull request)
Create a pull request to ask collaborators for feedback on your changes. Pull request review is so valuable that some repositories require an approving review before pull requests can be merged. If you want early feedback or advice before you complete your changes, you can mark your pull request as a draft. For more information, see "Creating a pull request."

When you create a pull request, include a summary of the changes and what problem they solve. You can include images, links, and tables to help convey this information. If your pull request addresses an issue, link the issue so that issue stakeholders are aware of the pull request and vice versa. If you link with a keyword, the issue will close automatically when the pull request merges. For more information, see "Basic writing and formatting syntax" and "Linking a pull request to an issue."

pull request body

In addition to filling out the body of the pull request, you can add comments to specific lines of the pull request to explicitly point something out to the reviewers.

pull request comment

Your repository may be configured to automatically request a review from specific teams or users when a pull request is created. You can also manually @mention or request a review from specific people or teams.

If your repository has checks configured to run on pull requests, you will see any checks that failed on your pull request. This helps you catch errors before merging your branch. For more information, see "About status checks."

Address review comments
Reviewers should leave questions, comments, and suggestions. Reviewers can comment on the whole pull request or add comments to specific lines. You and reviewers can insert images or code suggestions to clarify comments. For more information, see "Reviewing changes in pull requests."

You can continue to commit and push changes in response to the reviews. Your pull request will update automatically.

- Merge your pull request
github page

- Delete your branch
github page

- Git graph
fetch into local branch



https://www.w3schools.com/python/default.asp
```
