---
Name: "002 Github Fork and Pull"
Level: Beginner
Type: Support
Date: 2019-10-05
Contact: https://twitter.com/dfirscience
Website: https://dfir.science
---

## 002 Github Fork and Pull
When using Github or similar sites, you will typically (clone)[https://help.github.com/en/articles/cloning-a-repository] repositories. That means that you make a copy of the code on your computer.
We copy code onto our computers so we can use the programs or use the code in our code.

Cloning is an excellent way to keep your software up-to-date. Since your local copy is connected with the
developer's remote copy, you can fetch any updates whenever you want.

However, an excellent coding community doesn't just use other people's code. We also *contribute* back
changes to the code that will be useful. For example, if you are using some software, and you find
a bug, you will probably fix the bug. However, this fix is only on your local copy. With tools like
git, it is easy to share that fix with the original developer.

To contribute to projects, Github uses a 'Fork and Pull' workflow. (Forking)[https://help.github.com/en/articles/fork-a-repo] is making a copy of someone else's repository. You make changes to your copy, and
then send the original developer your changes with a 'Pull Request'.

While it seems a little bit complicated, it is a very powerful method of collaboration. Developers do
not have to give contributors direct access to make code changes, and contributors are not restricted by
the original developers.

#### Note
**Do not download and run random code from the Internet without checking what they do.** Some code
is designed to harm your computer or data. Do not run code without checking how it works.

### Resources
* (Github Fork and Pull Workflow)[https://gist.github.com/Chaser324/ce0505fbed06b947d962]

## Challenge
1. Fork *this* repository
2. Clone your forked repository to your local computer
3. Create a file called "FORK" in the repository
4. Commit and push your changes to Github
5. Create a pull request to https://github.com/jijames/ProgrammingChallenges

### Expected Results
* A new repository in your account called "ProgrammingChallenges"
* A local copy of ProgrammingChallenges linked to your account
* A file called FORK saved locally and committed to ProgrammingChallenges
* A pull request sent to jijames/ProgrammingChallenges that contains your FORK file