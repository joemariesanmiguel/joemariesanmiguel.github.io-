# joemariesanmiguel.github.io-
<!DOCTYPE html>
<html>
<head>
    <title>My First Website</title>
    <meta charset="UTF-8">
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #4facfe, #00f2fe);
            text-align: center;
            color: white;
            margin: 0;
            padding: 0;
        }
        header {
            padding: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: white;
            color: #4facfe;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ddd;
        }
        footer {
            margin-top: 50px;
            padding: 20px;
            background-color: rgba(0,0,0,0.2);
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Website</h1>
    <p>This website is hosted using GitHub!</p>
    <button onclick="showMessage()">Click Me</button>
</header>

<footer>
    <p>© 2026 My Website</p>
</footer>

<script>
    function showMessage() {
        alert("Hello! Thanks for visiting my website 😊");
    }
</script>

</body>
</html>
