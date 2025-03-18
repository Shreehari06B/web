<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buttons Example</title>
    <style>
        button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            background-color: #4CAF50;
            color: white;
        }

        button:hover {
            background-color: #45a049;
        }

        .btn-danger {
            background-color: #f44336;
        }

        .btn-danger:hover {
            background-color: #e53935;
        }

        .btn-info {
            background-color: #2196F3;
        }

        .btn-info:hover {
            background-color: #1976D2;
        }
    </style>
</head>

<body>
    <h1>Button Examples</h1>

    <!-- Simple Button -->
    <button onclick="alert('Button clicked!')">Click Me</button>

    <!-- Button with different styles -->
    <button class="btn-danger" onclick="alert('Danger button clicked!')">Danger</button>
    <button class="btn-info" onclick="alert('Info button clicked!')">Info</button>

    <!-- Submit Button (used in forms) -->
    <form>
        <input type="submit" value="Submit" />
    </form>
</body>

</html>
