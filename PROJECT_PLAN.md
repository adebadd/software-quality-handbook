# Project Plan

This plan outlines the tasks, timelines, and responsibilities for developing our Software Quality Assurance Handbook.

## Task Breakdown

| Task                                   | Assigned Members                 | Days     | Branch                           |
|----------------------------------------|----------------------------------|----------|----------------------------------|
| Create Repository and Project Plan     | Abdul Badmos                     | Day 1    | `feature/project-plan`           |
| Handbook Structure & Introduction      | Otito, Abdul Akhtar              | Days 1-3 | `feature/introduction`           |
| Task Estimation Research               | Abdul Badmos, Abdul Akhtar       | Days 1-2 | `feature/task-estimation`        |
| Task Estimation Writing & Diagrams     | Abdul Badmos, Abdul Akhtar       | Days 3-5 | `feature/task-estimation`        |
| Code Reviews Research                  | Olatunde Hassan, Otito           | Days 1-2 | `feature/code-reviews`           |
| Code Reviews Writing & Diagrams        | Olatunde Hassan, Otito           | Days 3-5 | `feature/code-reviews`           |
| DevOps Integration Research            | Olatunde Hassan, Abdul Badmos    | Days 1-2 | `feature/devops-integration`     |
| DevOps Integration Writing & Diagrams  | Olatunde Hassan, Abdul Badmos    | Days 3-5 | `feature/devops-integration`     |
| Compile, Edit, & Proofread Handbook    | All members                      | Days 6-7 | `feature/final-edits`            |
| Team Reflection & Contributions        | All members                      | Day 7    | `feature/reflection`             |

## Collaboration Guidelines
- Each task will have a dedicated feature branch.
- Two or more members will collaborate on each task.
- All contributions are peer-reviewed via pull requests before merging to `main`.

# Team Reflection and Contributions

## What Went Well

- Abdul Badmos: Clear division of tasks at the start of the project allowed everyone to work independently without confusion.
- Abdul Mannan Akhtar: Everyone contributed to reviewing and proofreading at least one other section, which improved the overall quality.
- Otito Ukachhukwu: Communication on GitHub through comments and reviews was professional and helpful.
- Olatunde Hassan: Each team member followed the trunk-based development process effectively, using branches and pull requests as required.

## What Could Be Improved

- Abdul Badmos: Earlier syncing could have helped avoid small formatting inconsistencies across sections.
- Abdul Mannan Akhtar: A few tasks required clarification mid-way through and could have benefited from a short team catch-up or checklist in the README.
- Otito Ukachukwu: Reviewing diagrams and link accessibility could have been included in the initial review checklist to avoid late-stage edits.
- Olatunde Hassan: Some team members were slow to push their branches early in the week, which delayed feedback loops.

## Lessons Learned

- Abdul Badmos: Using a clear project plan from the beginning made it easier to manage deadlines and responsibilities.
- Abdul Mannan Akhtar: Having two contributors per topic ensured a second layer of review, which improved the quality of every section.
- Otito Ukachukwu: GitHub's branching and pull request system helped maintain clarity and collaboration while working in parallel.
- Olatunde Hassan: Regularly previewing markdown and diagrams in VS Code helped catch visual issues early.

## Development Process Evaluation

This handbook project gave us a structured way to practise collaborative software documentation, estimation, and version control. Everyone contributed meaningfully, and we followed the trunk-based development model with active pull requests and feedback. We would adopt a similar workflow for future team-based technical writing.

## Observations and Process Improvements

In some cases, force-pushes were used on shared branches (for example - `feature/final-edits`). This introduced risks such as potential overwrites or lost formatting, which we encountered with the Code Reviews section. In the future, we would avoid force-pushing to collaborative branches and instead use safer alternatives like `--force-with-lease` when absolutely necessary.

A few pull requests and commits lacked detailed descriptions. This made it harder to track the intent behind some changes. Going forward, we would ensure commit messages and PR descriptions clearly explain what was changed and why, to improve collaboration and traceability.

We would also benefit from introducing a final checklist or review phase before merging into `main` to catch minor formatting or consistency issues earlier.
