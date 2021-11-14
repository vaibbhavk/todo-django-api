# todo-django-api
This is a basic REST API for adding, updating, deleting todos. Used Django Rest Framework.

## Endpoints

### Basr URL

[https://todo-drf.herokuapp.com/api/task-list](https://todo-drf.herokuapp.com/api/task-list) - Returns a list of Todos.


[https://todo-drf.herokuapp.com/api/task-detail/{id}](https://todo-drf.herokuapp.com/api/task-detail/{id}) - Returns a todo with the given unique identifier.


    path('task-create/', views.taskCreate, name='task-create'),
    path('task-update/<str:pk>/', views.taskUpdate, name='task-update'),
    path('task-delete/<str:pk>/', views.taskDelete, name='task-delete'),
