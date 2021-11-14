# todo-django-api
This is a basic REST API for adding, updating, deleting todos. Used Django Rest Framework.

## Endpoints

[https://todo-drf.herokuapp.com/api/task-list] - Returns a list of Todos.


    path('task-detail/<str:pk>/', views.taskDetail, name='task-detail'),
    path('task-create/', views.taskCreate, name='task-create'),
    path('task-update/<str:pk>/', views.taskUpdate, name='task-update'),
    path('task-delete/<str:pk>/', views.taskDelete, name='task-delete'),
