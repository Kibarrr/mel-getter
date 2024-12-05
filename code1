<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enter Your Name</title>
    <script>
        function greetUser() {
            var userName = document.getElementById("name").value;
            var message = "";

            if (userName) {
                if (userName === "Melyssa") {
                    message = "Welcome, Melyssa!";
                } else {
                    message = "You are NOT welcomed.";
                }
            } else {
                message = "Please enter your name.";
            }

            // Display the message in an alert box or as text on the page
            document.getElementById("greetingMessage").innerText = message;
        }
    </script>
</head>
<body>
    <h1>Welcome! Please enter your name:</h1>
    <form onsubmit="event.preventDefault(); greetUser();">
        <label for="name">Your Name: </label>
        <input type="text" id="name" name="name" required>
        <button type="submit">Submit</button>
    </form>

    <!-- Display the greeting message here -->
    <p id="greetingMessage"></p>
</body>
</html>
