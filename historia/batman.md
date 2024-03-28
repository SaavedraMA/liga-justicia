GitHub allows developers around the world to streamline their development pipelines and maintain a solid history of their projects even while collaborating with many other individuals and teams. However, Git can only take a team so far; it’s a tool that can be used effectively or ineffectively, depending on the workflow you choose to abide by as your project matures.

To get the most out of Git, you need to know which workflow works best for your goals and team members. Among many variations is the GitHub flow approach: a workflow that centers on simplicity and branch creation for new features. This workflow pulls ideas from the "Gitflow" model to leverage the full power of branching, but it leaves out the "develop" branch to make things quite a bit simpler. To make this model work for your project, your team will need to know when to make pull requests and why. You will also need to stick to the basic steps to ensure your project's history remains consistent over time.

Steps in the GitHub pull request workflow
Unlike the similar Gitflow model, there is no need to separate hotfixes from the rest of your feature development branches. Instead of appearing directly on the main branch, these too are developed on feature branches to be merged in later after careful review and testing. The result is a flexible and adaptive system that sticks to the following key steps:

1. Local feature creation
This is where the branching begins. Unlike some other workflows, the GitHub flow model depends on your project's main branch being deployable at all times. This means that any and all features you intend to develop should be worked on in their own branches and later integrated back into the main when they’re ready.
