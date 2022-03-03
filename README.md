# Git hooks - The Article :rocket: 

## What are? Where they live? What they feed on? :confounded:	

### :crown: **Git**

Before we talk about git hooks, we need to understand what is git. Git is a free and open source distributed version control system (VCS) designed to handle everything from small to very large projects with speed and efficiency. It is very popular among developers and most open source projects use this tool. If you want to read more about git please check this awesome explanation from [[Git] Getting Started - What is it?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F).

### :tractor: **Hooks** :warning::warning::warning:

As [this awesome tutorial](https://www.atlassian.com/git/tutorials/git-hooks) from Atlassian explained:
> Git hooks are scripts that run automatically every time a particular event occurs in a Git repository. They let you customize Git’s internal behavior and trigger customizable actions at key points in the development life cycle.

It allows custom actions to be performed at any stage of the versioning control process. Ex:

- Prevent unwanted code to be commit in the repo.
- Standardize commit messages and branch naming.

As [the hooks documentation](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks) from git explained:
> There are two groups of these hooks: client-side and server-side. Client-side hooks are triggered by operations such as committing and merging, while server-side hooks run on network operations such as receiving pushed commits. You can use these hooks for all sorts of reasons.






## References

* [Atlassian CI/CI Git Hooks](https://www.atlassian.com/continuous-delivery/continuous-integration/git-hooks)
* [Git (VCS) page](https://git-scm.com/)
