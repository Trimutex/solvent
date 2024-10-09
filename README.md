# solvent

A method of breaking down all of your tasks into a single framework.


# why?

There are often many tasks to attend to in your life, and organizing them 
can be annoying. As such, I've decided to share my method of task management.


# how to use

> note: GitHub doesn't allow a forked repository to be private, so unless you
> want to tell everyone about your current task list, you need to create it
> yourself. Feel free to take this markdown README with you as a self-reminder
> of the structure or to tell others!

Begin by simply creating your own private repository! The key to this method
is using the `projects` feature. You can organize current tasks by using
this feature.

## projects

Break down big plans into simple pieces with projects. Three columns are used
for managing the projects:

### todo

These are blocked, todo, and needs-research.

### in-progress

These are only in-progress issues.

### completed

These are completed, abandoned, and dropped.

## issues

Issues are broken up by labels as topics.

### topic/single-issue

A lone issue that needs to be dealt with, unrelated to any big projects.

### topic/multi-issue

Use checkboxes to break down an issue in a project to small steps.

### topic/sub-issue

Issues that are a part of a project.

### topic/idea

A non-concrete idea for something that needs to be done in the future.

## issue status

With these labels, the issue status is kept track of.

### status/todo

These are issues that can be freely picked from to continue work on a project.

### status/needs-research

These are issues that need to be researched before deciding what to do with it.

### status/blocked

These are issues which need progress from other issues in order to be worked on.

### status/in-progress

These are issues which are currently being worked on.

### status/completed

These are issues which have been fully completed in the project.

### status/abandoned

These are issues which have lost the spark for it.

### status/dropped

These are issues which have been dropped due to becoming unnecessary


# rest of the repository

There's basically nothing in this repository though, what can I do with it?
The short answer here is: whatever you want! Expand on the idea as much or as
little as you need. Feel free to create PRs on this original repository to
help others with ideas too!

## example
If you begin to find that you want to keep track of some specific files as
part of an ongoing task, then do this:

1. create a branch in the repo
2. add those files in a commit
    - this could be as simple as a `documents` directory and adding it there
    - personal note: I recommend keeping the root directory clean here
3. create a merge request into your own main branch
4. mention the issue with `closes #[commit number]`
5. merge the branch and now you have a link to where the file came from
