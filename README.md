### Rest API TODO App With TypeScript , Express
You can clone the repo and run it with npm and try it with postman.

```bash
	npm install
	npm start    //  http://localhost:3000/  
```

- POST   

```HTTP
	http://localhost:3000/todos
```

- GET
```HTTP
	http://localhost:3000/todos
	
	{
 		"text": "First todo text "
	}
```

- PATCH ( UPDATE )

```HTTP
	http://localhost:3000/todos/id
```

- DELETE
```DELETE
	http://localhost:3000/todos/id
```
