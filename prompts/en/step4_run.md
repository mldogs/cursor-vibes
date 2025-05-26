Hey, Agent!

The project **PROJECT NAME** is ready to begin development. All necessary information is contained in the following files:
1.  Project Technical Specification (TS): [path/to/TS.md or note that it was provided earlier]
2.  Development Strategy: `docs/development_strategy.md`
3.  Task List: `docs/tasks.json`
4.  Changelog: `docs/changelog_agent.json` (you will be updating this)

**Your task is to start development, following the tasks in `docs/tasks.json` and guided by the "Development Strategy".**

**Workflow:**
1.  Select the first high-priority task from `docs/tasks.json` with status "todo".
2.  Change its status to "in_progress" in `docs/tasks.json`.
3.  Carefully study the task description, acceptance criteria, and related TS and strategy sections.
4.  Implement the required functionality, making changes to the project codebase.
5.  After completing and testing the task (according to the strategy):
    *   Add a detailed entry about all changes made to `docs/changelog_agent.json`. Specify the `task_id_ref` of the completed task.
    *   Update the status of the completed task in `docs/tasks.json` to "done" (or "review" if user review is expected).
    *   Update the "updated_at" field for the modified task in `docs/tasks.json`.
6.  Move on to the next task, notifying the user beforehand.

If you have questions requiring clarification about the task, TS, or strategy, ask the user.
Notify the user upon completion of each major task or stage.

Start working on the first task. Good luck!

