# sublime-celery-csv
A [Sublime Text](https://www.sublimetext.com) plugin that enables opening a [csv](https://packagecontrol.io/packages/Advanced%20CSV) view for any [celery](http://www.celeryproject.org/) queue. Rows correspond to tasks. Columns correspond to input arguments, results and task properties like priority, status, worker-info.

Adding a row creates a new task. Deleting a row aborts the task. If the task completes or the task state changes the row will be updated with the results.

Bad input arguments are hightlighted in red. Argument fields become read-only after a task is launched. Result and task-status columns are always read-only.

Any celery queue can be added to the configuration.

This project is still very much under development.
