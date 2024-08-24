<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>To-Do List</h1>
        <form id="todoForm">
            <input type="text" id="todoInput" placeholder="Add a new task..." required>
            <button type="submit">Add Task</button>
        </form>
        <ul id="todoList"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>
