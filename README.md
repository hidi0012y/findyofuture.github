<!DOCTYPE html>
<html>
<head>
    <title>FIND YOUR FUTURE SUCKERS</title>
    <style>
      .submit-button {
            padding: 10px 20px;
            background-color: #3b5998;
            color: #fff;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .submit-button:hover {
            background-color: #2a4379;

        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            max-width: 600px;
            padding: 20px;
            background-color: #eaf2ff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        h1 {
            margin-top: 0;
            color: #3b5998;
        }

        .result {
            margin-top: 20px;
            font-size: 18px;
            color: #3b5998;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>FIND YOUR FUTURE SUCKERS</h1>
        
        <form onsubmit="event.preventDefault(); showResult();">
            <label for="name">Enter Your Name:</label>
            <input type="text" id="name" name="name" required>
            <button type="submit-button">Show Result</button>
        </form>

        <div id="result" class="result"></div>
    </div>

    <script>
        function showResult() {
            var name = document.getElementById("name").value;
            var resultElement = document.getElementById("result");
            resultElement.textContent =name + " bro you are not getting any bitches dude";
        }
    </script>
</body>
</html>
