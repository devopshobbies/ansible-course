# Key Notes Of This Session

## register
capture the output of a task and use their `return values` to debug issues.

## Return Values
every module generates output with specific value mentioned in the last section of the documentation of that module which can then be captured by `register`.

## ignore_errors
when set to `true` ansible ignores the tasks failure if accrued and will move on to the following tasks.

## become
when set to `true` ansible will execute a task(s) with sudo priviledge.