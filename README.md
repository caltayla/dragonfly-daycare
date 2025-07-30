# dragonfly-daycare
childcare and home help




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Simple Button Message</title>
  <style>
    #message {
      display: none;
      margin-top: 10px;
      color: green;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <button onclick="showMessage()">Click Me</button>
  <div id="message">Hello! You clicked the button.</div>

  <script>
    function showMessage() {
      document.getElementById("message").style.display = "block";
    }
  </script>

</body>
</html>
