# MERN-todo-backend
Node js backend todo list

## Index all Todos
'/todos'
## Add new
'todos/add'
## Edit
'todos/:id'

## EXAMPLE

## POST
endpoints: https://scoopy-do-backend.herokuapp.com/todos/add

{	
	"todo_title": "Test number 1",
	"todo_description": "Test number 1",
	"todo_responsible": "Nope",
	"todo_priority": "High",
	"todo_completed": false
}

## Update
endpoints: https://scoopy-do-backend.herokuapp.com/todos/update/:id

{	
	"todo_title": "Test number 1",
	"todo_description": "Test number 1 for update",
	"todo_responsible": "Nope",
	"todo_priority": "Low",
	"todo_completed": true
}
