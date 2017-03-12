# README

## :computer: Routes
Base URL: https://sharpfish-todo.herokuapp.com/
```
    Prefix Verb   URI Pattern                         Controller#Action
todo_items GET    /todos/:todo_id/items(.:format)     items#index
           POST   /todos/:todo_id/items(.:format)     items#create
 todo_item GET    /todos/:todo_id/items/:id(.:format) items#show
           PATCH  /todos/:todo_id/items/:id(.:format) items#update
           PUT    /todos/:todo_id/items/:id(.:format) items#update
           DELETE /todos/:todo_id/items/:id(.:format) items#destroy
     todos GET    /todos(.:format)                    todos#index
           POST   /todos(.:format)                    todos#create
      todo GET    /todos/:id(.:format)                todos#show
           PATCH  /todos/:id(.:format)                todos#update
           PUT    /todos/:id(.:format)                todos#update
           DELETE /todos/:id(.:format)                todos#destroy
 ```
