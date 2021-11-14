# todo-django-api
This is a basic REST API for adding, updating, deleting todos. Used Django Rest Framework.

## Endpoints

### Base URL
> [https://todo-drf.herokuapp.com/api/](#)

### Get a list of all todos (GET)
> [https://todo-drf.herokuapp.com/api/task-list/](#)

### Get a todo with the specific identifier (GET)
> [https://todo-drf.herokuapp.com/api/task-detail/{id}/](#)

### Create a todo (POST)
> [https://todo-drf.herokuapp.com/api/task-create/](#)

Body Params:
title - Title of the todo.
completed - Accepts true/false.

### Update a todo with the specific identifier (POST)
> [https://todo-drf.herokuapp.com/api/task-update/{id}/](#)

Body Params:
title - Title of the todo.
completed - Accepts true/false.

### Delete a todo with the specific identifier (DELETE)
> [https://todo-drf.herokuapp.com/api/task-delete/{id}/](#)
