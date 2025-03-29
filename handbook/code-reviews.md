# Code Reviews

## Introduction

Code reviews are a key quality control practice used to identify bugs, ensure consistency, and promote shared ownership of code. They help development teams catch issues early and foster collaboration and learning. In this section, we will explore effective code review practices, common mistakes to avoid, and provide useful references to industry standards.

## Why Code Reviews Matter

Code reviews are beneficial for several key reasons:

- **Early Bug Detection:** Catching issues early significantly reduces costs and avoids problems reaching production.
- **Knowledge Sharing:** Encourages developers to learn from each other and improves overall team skills.
- **Consistent Coding Standards:** Ensures adherence to coding conventions, resulting in a more maintainable codebase.
- **Improved Design Quality:** Collaboration leads to more robust and scalable solutions.

## Common Code Review Techniques

- **Pair Programming:** Two developers collaborate directly; one writes the code, and the other reviews it in real-time, enabling immediate feedback.
- **Over-the-Shoulder Reviews:** Informal reviews where one developer walks through their code with another, encouraging quick feedback and discussion.
- **Tool-Assisted Reviews:** Utilise platforms like GitHub or GitLab for asynchronous and structured feedback directly integrated with version control.

## Best Practices

- **Review in small chunks:** Keep pull requests small (ideally under 400 lines) to ensure focused and thorough reviews.
- **Set clear expectations:** Use documented coding standards and review checklists to align reviewers.
- **Give constructive feedback:** Focus on clarity, design, and logic, not on personal preferences or style.
- **Use automated tools for routine checks:** Let linters and formatters handle style so reviewers can focus on architecture and logic.
- **Review promptly:** Aim to provide feedback within 24 hours to keep the team moving.
- **Praise good code:** Highlight well-written, readable, or elegant code to reinforce good habits.
- **Ask questions instead of making demands:** Phrase feedback as suggestions where possible, e.g. "Have you considered...?"

## Practices to Avoid

- **Overlooking the purpose:** Reviews should focus on things like logic, readability, and maintainability.
- **Giving vague feedback:** Elaboration is necessary to prevent reviewers from being confused and lost. It is important to be specific and helpful.
- **Delaying reviews unnecessarily:** Waiting days to review blocks progress and kills momentum. When you are busy with coding, others should be informed.
- **Being overly critical or personal:** There is no need for personal feedback to be dealt. The criticism should focus on the code only, not the coder.
- **Approving without reviewing:** The entire process is undermined if the code is not approved first.
- **Focusing only on style:** The review should be focused on the value of the criticism more than the presentation.
- **Rewriting the code in comments:** Avoid suggesting complete rewrites unless necessary, focus on meaningful improvements.

## Real-World Challenges

Implementing effective code reviews can encounter several challenges:

- **Time Constraints:** Developers may feel pressed for time, compromising the thoroughness of reviews.
- **Resistance to Feedback:** Some team members may struggle to accept feedback constructively.
- **Reviewer Consistency:** Varying levels of diligence among reviewers can cause inconsistencies and reduce review effectiveness.

## Code Review Checklist

Use this checklist for each code review to ensure comprehensive coverage:

- [ ] **Functionality:** Does the code function correctly and meet requirements?
- [ ] **Readability:** Is the code clearly written and understandable?
- [ ] **Maintainability:** Can this code be easily maintained or extended?
- [ ] **Standards:** Does the code adhere to agreed coding standards and best practices?
- [ ] **Error Handling:** Are errors and exceptions handled appropriately?
- [ ] **Security:** Is the code secure against common vulnerabilities?
- [ ] **Performance:** Is the code optimised and free from obvious inefficiencies?
- [ ] **Documentation:** Is the code sufficiently documented and commented?
- [ ] **Testing:** Are there adequate tests covering the new functionality, and do they pass successfully?

## Continuous Improvement

Regularly improve the code review process by:

- Soliciting team feedback on review effectiveness.
- Monitoring key review metrics, such as defect rates and review completion time.
- Adapting processes based on project complexity, team size, and ongoing feedback.

## Resources for Further Reading

1. [Google Engineering Practices – Code Reviews](https://google.github.io/eng-practices/review/)
2. [Atlassian – Why code reviews matter](https://www.atlassian.com/agile/software-development/code-reviews)
3. [GitLab Docs – Code Review Guidelines](https://docs.gitlab.com/development/code_review/)