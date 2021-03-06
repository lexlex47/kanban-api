# Kanban API

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/5e4dc0f3b34b4b1d8ba28d4fd3ee2b8e)](https://www.codacy.com/gh/lexlex47/kanban-api/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=lexlex47/kanban-api&amp;utm_campaign=Badge_Grade)


A task for Kanban Board API.

### Users

List: GET `GetUsers`

Create: POST `CreateUser`

Single: GET `GetUser`

Update: PATCH `UpdateUser`

Delete: DELETE `DeleteUser`

### Boards

List: GET `GetBoardsInUser`

Create: POST `CreateBoard`

Single: GET `GetBoard`

Update: PATCH `UpdateBoardName`

Delete: DELETE `DeleteBoard`

### Status

List: GET `GetStatusesInBoard`

Create: POST `CreateStatus`

Single: GET `GetStatus`

Update: PATCH `UpdateStatus`

Delete: DELETE `DeleteStatus`

### Tasks

List: GET `GetTasksInStatus`

Create: POST `CreateTask`

Single: GET `GetTask`

Update: PATCH `UpdateTask`

Delete: DELETE `DeleteTask`

Add: POST `AddUserToTask`

Add: POST `AddTagToTask`

Update: PATCH `UpdateTaskOrder`

### Comments

Create: POST `CreateComment`

Single: GET `GetComment`

Delete: DELETE `DeleteComment`

