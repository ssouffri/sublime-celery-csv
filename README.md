# sublime-celery-csv
A sublime plugin that enables opening a csv view for any celery queue. Rows correspond to tasks. Columns correspond to input arguments, results and task properties like priority, status, worker-info.

Adding a row creates a new task. Deleting a row aborts the task. If the task completes the row will be updated with the results.

Bad input arguments are hightlighted in red. Argument fields become read-only after a task is launched. Result and status columns are read-only.

Any celery queue can be added to the configuration.

This project is still very much under development.
