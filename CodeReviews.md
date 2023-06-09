# Code Reviews

## Introduction

Code reviews are methodical assesments of code designed to identify bugs, increase code quality, and help developers learn the source code. Code reviews are a critical part of the software development process. They are also a key part of the Scrum methodology. In Scrum, the team reviews the code written by each team member and then compares the actual code with the code written by the team member. This helps the team to improve their code review skills and to improve their productivity.

Karl E. Wiegers, software engineer and author of many books, stated, " Peer review is one of the most powerful software quality tools available. After experiencing the benefits of peer reviews for nearly fifteen years, I would never work in a team that did not perform them".

![Code Review Image][def]


# Good practices for code reviews
1.	**Create a code review checklist** – a set of rules that all coders follow during this process. Stops more bugs in code. Provides more effective code reviews.
2.	**Take your time** – should not be inspecting more than 500 lines of code per hour. We took our time at the start of this project to avoid confusion. Decided to review bugs in our code at a slower rate to make sure we got to the bottom of it.
3.	**Team members should annotate source code before the review.** - You can help your teammates understand what you're attempting to do by giving them more background on why you want to update the source code.
4.	**Only pull and push bit by bit** - By doing this, the process will move more quickly, and you can see precisely what code snippets are being committed to GitHub. We done this by adding each of our sections at a time to visual studio code and then adding, pushing, and committing it to GitHub.
5.	**When faced with an error, justify your reasoning for your solution?** - We all understood there were many ways to fix a problem when we encountered them. But before making a change, we all needed to understand why this approach would be better to the alternatives. It's critical to share your arguments since they may help someone else who has an issue like yours in the future.
6.	**Establishing a process to fix defects.** - Making use of a code review tool is an excellent technique to develop a process. By doing this, all team members have access to updates, can log bugs found, and can collaborate on improvements.
7. **Use constructive criticism and choose your language carefully**: For example, saying "I didn't see where these variables were initialized." is likely to ellicit a constructive response, whereas saying "You didn't initialize these variables." is likely to ellicit a defensive response.

# What to look for in a code review

* **Design**: Is the code well-designed and appropriate for your system?

* **Functionality**: Does the code behave as the author likely intended? Is the way the code behaves good for its users?

* **Complexity**: Could this code be made simpler? Would another developer be able to easily understand and use this code when they come across it in the future?

* **Tests**: Does the code have correct and well-designed automated tests?

* **Naming**: Did the developer choose clear names for variables, classes, methods, etc.?

* **Comments**: Are the comments clear and useful?

* **Style**: Does the code follow our style guides?

* **Documentation**: Did the developer also update any relevant documentation?

# Common Pitfalls

1. **Not reviewing code frequently enough**: Code reviews should be done on a regular basis to catch issues early on.

2. **Being overly critical**: Code reviews should be constructive and focused on improving the code, not criticizing the developer. Being overly critical can demotivate team members and lead to a toxic work environment.

3. **Not using automated tools**: Automated tools can help catch issues in the code that may be missed during manuel reviews. Failing to use these tools can lead to issues going unnoticed.

4. **Reviewing to much code at once**: Code reviews should be done in small chunks to avoid becoming overwhelmed. This will also help catch issues sooner.

5. **Failing to enforce standards**: Code reviews are a great way to enforce coding standards. Failing to enforce these standards can lead to inconsistent code.

# Possible benefits of code reviews

* Less time spent performing rework
* Increased programming productivity
* Better techniques learned from other developers
* Reduced unit testing and debugging time
* Less debugging during integration and system testing
* Exchanging of information about components and overall system with other team members




[def]: data:image/png;base64,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