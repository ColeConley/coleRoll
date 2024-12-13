
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirect Page</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: white;
        }
        .clickable-text {
            font-size: 2rem;
            font-weight: bold;
            text-decoration: underline;
            cursor: pointer;
            color: black;
        }
    </style>
</head>
<body>
    <div class="clickable-text" onclick="redirectToURL()">I Want to Roll</div>

    <script>
        function redirectToURL() {
            // Replace this URL with the desired one.
            window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";
        }
    </script>
</body>
</html>
