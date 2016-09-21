# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
The primary purpose of a backend is to save and store user information so that it
can be accessed by the user in future sessions.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
the server
```

Which layer in the MVC pattern communicates with the model?

```bash
the controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Views only represent what the user sees, such as HTML, CSS, JavaScript etc. Views
merely interprets what is given to it by the controller; it provides no concept
or representation of back end structure.
```

What does C.R.U.D stand for?

```bash
Create
Read
Update
Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
// your response here
```

List at least 5 standard actions that C.R.U.D corresponds to?

```bash
create
index
show
Update
destroy
```

A user action fires a `GET` request for `/persons/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
The user fires the GET request to the client
The client interprets the request and passes it along to the server
The server sends a POST request to the controller, and passes along the info request as a string
The controller takes the request and passes it to the model
The model finds the requested info and sends it to the controller
The controller looks over the request and sends it to the server
The server makes sure its correct and sends it to the client
The client completes the transaction by returning the request to the initial user
```

What is the command to generate a new rails-api app?

```bash
rails commandsapp
```

What is the command to start an instance of a rails server?

```bash
bundle exec rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
db:drop
db:create
db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
```
