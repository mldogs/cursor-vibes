Hey, Agent!

Based on the previously approved Technical Specification (TS) for the project **PROJECT NAME** and the agreed "Development Strategy" (`docs/development_strategy.md`), please create a detailed list of tasks for implementing the entire project.

Save these tasks in `docs/tasks.json` as a JSON array. Each task must have the following structure:

{
  "task_id": "TASK-[PROJ_PREFIX]-XXX", // Where [PROJ_PREFIX] is a short unique project prefix (e.g., AIA for AI Assistant), and XXX is a sequential number.
  "task_name": "Clear and concise task name",
  "description": "Detailed description of what needs to be done for this task. Break down into subpoints if necessary.",
  "status": "todo", // Initial status for all tasks
  "priority": "medium", // Possible values: "high", "medium", "low". Determine based on importance and sequence.
  "module": "Name of the main module, component, or stage from `docs/development_strategy.md` this task belongs to",
  "related_tz_section": "Number or name of the TS section this task corresponds to (if applicable)",
  "related_strategy_point": "Number or name of the point from `docs/development_strategy.md` this task corresponds to (if applicable)",
  "acceptance_criteria": [
    "Specific, measurable acceptance criterion 1 (e.g., 'Feature X implemented and covered by tests')",
    "Specific, measurable acceptance criterion 2"
  ],
  "dependencies": ["TASK-[PROJ_PREFIX]-YYY"], // Array of task IDs that must be completed before this one (if any). Leave empty if none.
  "estimated_effort": "medium", // Optional effort estimate: "small", "medium", "large", "xlarge".
  "notes_for_agent": "Any specific instructions, tips, or reminders for you (the AI agent) regarding this task (optional).",
  "assigned_to": "Cursor Agent",
  "created_at": "YYYY-MM-DDTHH:MM:SSZ", // Current date and time in ISO 8601 format
  "updated_at": "YYYY-MM-DDTHH:MM:SSZ"  // Current date and time in ISO 8601 format
}


Decompose the project into tasks so that each is sufficiently atomic for execution and verification. Ensure that the tasks cover all functional and non-functional requirements from the TS and align with the proposed strategy.

The result of your work should be the file `docs/tasks.json`.

