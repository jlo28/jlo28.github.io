
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Test Web Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 100px;
      background-color: #f5f5f5;
    }

    h1 {
      color: #333;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      background-color: #007BFF;
      color: white;
      border: none;
      border-radius: 8px;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #0056b3;
    }

    #message {
      margin-top: 20px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h1 id="main-title">Welcome to My Test Page</h1>
  <button onclick="changeText()">Click Me!</button>
  <p id="message"></p>

  <script>
    function changeText() {
      const title = document.getElementById('main-title');
      title.style.color = 'green';
      document.getElementById('message').textContent = 'You clicked the button!';
    }
  </script>

</body>
</html>
