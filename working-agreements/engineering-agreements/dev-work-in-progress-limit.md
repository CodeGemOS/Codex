---
description: We agree to have no more than 3 pull requests open per person
---

# 🤹 Dev Work In Progress Limit

### **Why?**

Monitoring the number of Pull Requests (PRs) a developer has in progress is important for several reasons:

1. **Workload Management**: This can provide insights into a developer's workload. If a developer has too many PRs open simultaneously, it could indicate they are overworked or have problems managing their tasks effectively.
2. **Efficiency and Productivity**: Due to context switching, multiple PRs can slow down a developer's productivity. Focusing on a single task to completion is generally more efficient before moving on to the next.
3. **Quality Control**: Juggling many PRs could compromise the quality of work. When working on several things simultaneously, it's easier to miss details, make mistakes, or introduce bugs.
4. **Team Visibility**: Keeping track of how many PRs each team member has in progress helps to maintain transparency in the team's work and allows for better resource allocation and task distribution.
5. **Process Improvement**: If a developer consistently has too many PRs in progress, it could point to bottlenecks in the development process, like slow code reviews, unclear task prioritization, or inadequate planning.
6. **Predicting Delays**: A high number of in-progress PRs might indicate potential future delays in the project, especially if they are interdependent tasks.
7. **Developer Support**: Finally, monitoring PRs in progress can help identify developers who might need additional support or guidance, whether it helps with task management, technical mentoring, or dealing with blockers.

Thus, by monitoring the number of PRs in progress, managers can better understand their team's work patterns, identify potential issues early, ensure high-quality work, and effectively support their developers.

### **Recommendations**

If a team member reaches their WIP limit, they should prioritize completing their existing PRs before opening new ones. If a team member consistently exceeds the WIP limit, it may indicate that they are taking on too much work or that the team needs to reevaluate the workload distribution. Here we outline the potential causes of high WIP, their corresponding indicators, and possible solutions.



#### **Multitasking or Context Switching**

The developer is juggling multiple tasks at once, which can lead to the creation of numerous PRs.

Signs:

* Several PRs are in progress concurrently from the same developer.
* Frequent switching between tasks, with none reaching completion.

Recommendations:

* Encourage focus on one task at a time to completion.
* Implement a task management system to help developers prioritize their work.

#### **Insufficient Review Resources**

The lack of available reviewers delays PR reviews, causing a pile-up of open PRs.

Signs:

* PRs remain open for extended periods awaiting reviews.
* Reviewers are overloaded with too many PRs to review.

Recommendations:

* Allocate sufficient resources for code reviews.
* Implement a rotating review schedule to share the workload.

#### **Large or Complex PRs**

PRs are too large or complex, leading to prolonged review times and more open PRs.

Signs:

* PRs contain a large number of changes or complex code.
* Reviewers take longer to review and provide feedback due to the PR's size or complexity.

Recommendations:

* Encourage smaller, incremental changes to make PRs more manageable.
* Implement code complexity metrics and guidelines.

#### **Blocked Dependencies**

Open PRs depend on other tasks, features, or decisions that are still pending.

Signs:

* PRs are frequently blocked or put on hold.
* The PR description or comments reference dependencies on other tasks or decisions.

Recommendations:

* Improve project planning to identify and manage dependencies.
* Prioritize tasks and decisions that unblock PRs.

#### **Poor Prioritization**

Tasks are not prioritized effectively, leading to the developer working on less critical tasks first.

Signs:

* Important tasks are left open while less important tasks are worked on.
* PRs don't align with project priorities or sprint goals.

Recommendations:

* Implement a prioritization framework for tasks.
* Regularly review and adjust priorities as needed.

#### **Insufficient Test Coverage or Quality Issues**

PRs often require multiple review iterations due to bugs or insufficient test coverage.

Signs:

* Review feedback frequently includes bugs or requests for additional tests.
* PRs often require multiple revisions before they can be merged.

Recommendations:

* Implement strong testing guidelines and expectations.
* Provide training or resources to improve code quality.

#### **Lack of a Defined Process**

The team lacks a clear process for handling PRs.

Signs:

* Developers create new PRs inconsistently.
* There's confusion or disagreement about when and how to open a PR.

Recommendations:

* Define a clear process for PR creation, review, and merge.
* Regularly review and refine the process as needed.

#### **Inadequate Planning**

Development work isn't planned effectively, leading to the creation of multiple PRs instead of focusing on one.

Signs:

* PRs often include work that isn't closely related or should have been broken into smaller tasks.
* Developers seem unsure about what they should be working on next.

Recommendations:

* Improve task planning and breakdown in the planning stage.
* Implement a task management system to help developers stay organized.

A high number of open PRs can indicate various issues within a development team, from overtasking and insufficient review resources to complex PRs and inadequate planning. By understanding these potential causes and their signs, teams can implement effective PR management strategies to manage PRs more efficiently. This not only aids in maintaining a healthy workload for developers but also ensures a smooth and efficient development process, leading to high-quality output and
