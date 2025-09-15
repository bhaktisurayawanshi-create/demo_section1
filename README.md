<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My First Web Page</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
    h1 { color: #2c3e50; }
    p { color: #555; }
    button {
      padding: 10px 20px;
      background: #3498db;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover { background: #2980b9; }
  </style>
</head>
<body>
  <h1>Welcome to My Web Page</h1>
  <p>This is a simple HTML page with a clickable button.</p>
  <button onclick="alert('Hello! Thanks for visiting.')">Click Me</button>
</body>
</html>
