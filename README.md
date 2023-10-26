# Task-bot 🤖📋
Discord bot which you can add tasks to other server users via ephimeral messages.

## Work in progress 🚧
The bot is still in development but if you are interested and want to test it, reach me out!

### Ephimeral Messages?
----
Ephimeral messages are only visible by the user that executes the command and only bots can send them.

---
## Command List
### Admin Commands
* ###### help-admin [link]

> Display a permanent message with the admin commands, an image can be included

----
* ###### admin-task-access [role]

> Gives admin access to a specified role

----
* ###### new_task [to] [project] [task] [subtasks] [status] [description] [link]

[![Image from Gyazo](https://i.gyazo.com/ed256a2d9b162b193dfb2a260055400b.gif)](https://gyazo.com/ed256a2d9b162b193dfb2a260055400b)

> Set a task to a user, only admin roles and this user can check this task. Description and link are optional arguments.
Using ; you will create more subtasks 

----
* ###### edit_task [to] [project] [task] [subtasks] [status] [description] [link]

[![Image from Gyazo](https://i.gyazo.com/54406683b4d82d75635d633b15723571.gif)](https://gyazo.com/54406683b4d82d75635d633b15723571)

> Replace any argument specified to the new one, a user must be specified

----
* ###### edit_subtask [id] [subtask] [newtext]

[![Image from Gyazo](https://i.gyazo.com/fd5d0b7c3c1e08521ea42d4ed555f2cc.gif)](https://gyazo.com/fd5d0b7c3c1e08521ea42d4ed555f2cc)

> Replace the subtask specified by a new text 

----
* ###### delete_task [id]

[![Image from Gyazo](https://i.gyazo.com/217f67a63e57c9e1d0dd7dc410de173f.gif)](https://gyazo.com/217f67a63e57c9e1d0dd7dc410de173f)

> Delete the current task by id, users will no longer see this task.

----
### User Commands
* ###### help [link]

[![Image from Gyazo](https://i.gyazo.com/99021dd1fdc8b64acf5cbf4c09997277.gif)](https://gyazo.com/99021dd1fdc8b64acf5cbf4c09997277)

> Display a permanent message with the available commands, an image can be included

----
* ###### list [project] [status]

[![Image from Gyazo](https://i.gyazo.com/55211b5f5e2816b4ce57715ea505b7fa.gif)](https://gyazo.com/55211b5f5e2816b4ce57715ea505b7fa)

> List all your current tasks, filtered by project or status

----
* ###### complete_task [id]

[![Image from Gyazo](https://i.gyazo.com/06d7861d28f3840a2932d8f2e1f7f413.gif)](https://gyazo.com/06d7861d28f3840a2932d8f2e1f7f413)

> Set the task status to green (done)

----
* ###### complete_subtask [id] [subtask] [emoji]

[![Image from Gyazo](https://i.gyazo.com/63a40605d236101bcc634f1fbb1699d3.gif)](https://gyazo.com/63a40605d236101bcc634f1fbb1699d3)

> Mark a subtask with an emoji

----
* ###### remind_task [id] [day] [hour] [minutes]

> Set a countdown to remind you of a task via private message

----
* ###### schedule_msg [id] [day] [hour] [minutes]

> Set a countdown to send you message via private message
