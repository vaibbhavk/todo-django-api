# todo-django-api
This is a basic REST API for adding, updating, deleting todos. Used Django Rest Framework.

## Endpoints

### Base URL
https://todo-drf.herokuapp.com/api/

### Get a list of all todos
https://todo-drf.herokuapp.com/api/task-list

### Get a todo with the specific identifier
https://todo-drf.herokuapp.com/api/task-detail/{id}


    path('task-create/', views.taskCreate, name='task-create'),
    path('task-update/<str:pk>/', views.taskUpdate, name='task-update'),
    path('task-delete/<str:pk>/', views.taskDelete, name='task-delete'),
