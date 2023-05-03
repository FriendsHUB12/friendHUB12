<!DOCTYPE html>
<html>
<head>
  <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #ff00ee;
    }
    
    .container {
      width: 500px;
      padding: 20px;
      margin: 0 auto;
      background-color: #eeff00;
      border: 1px solid #cccccc;
      border-radius: 5px;
      margin-top: 150px;
    }
    
    h2 {
      text-align: center;
    }
    
    input[type="email"],
    input[type="password"] {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }
    input[type="email"],
    input[type="password"] {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }
    
    button {
      background-color: #0d00ff;
      color: rgb(255, 255, 255);
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      cursor: pointer;
      width: 100%;
    }
    
    button:hover {
      opacity: 0.8;
    }
    marquee{
        font-size: 35px;
        font-weight: 900;
        background-color: aquamarine;
    }
  </style>
</head>
<body>
    <marquee behavior="alternate">Hey, This is Akash HUB</marquee>
  <div class="container">
    <h2>Login</h2>
    <form action="full site.html" method="post">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email address">

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Enter your password">

      <button type="submit">Login</button>
    </form>
  </div>
</body>
</html>
