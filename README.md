<html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Login Page</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') no-repeat center center/cover;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .login-box {
      width: 350px;
      padding: 30px;
      border-radius: 16px;
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.25);
      color: #fff;
    }

    .login-box h2 {
      text-align: center;
      margin-bottom: 25px;
      font-size: 28px;
    }

    .input-box {
      margin-bottom: 18px;
    }

    .input-box input {
      width: 100%;
      padding: 12px 15px;
      border-radius: 30px;
      border: none;
      outline: none;
      background: rgba(255, 255, 255, 0.3);
      color: #fff;
      font-size: 14px;
    }

    .input-box input::placeholder {
      color: #eee;
    }

    .options {
      display: flex;
      justify-content: space-between;
      font-size: 13px;
      margin-bottom: 20px;
    }

    .options label {
      cursor: pointer;
    }

    .options a {
      color: #fff;
      text-decoration: none;
    }

    .options a:hover {
      text-decoration: underline;
    }

    button {
      width: 100%;
      padding: 12px;
      border-radius: 30px;
      border: none;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      background: #ffffff;
      color: #333;
    }

    button:hover {
      background: #f1f1f1;
    }

    .register {
      text-align: center;
      margin-top: 15px;
      font-size: 14px;
    }

    .register a {
      color: #fff;
      font-weight: bold;
      text-decoration: none;
    }

    .register a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="login-box">
    <h2>Login</h2>

    <div class="input-box">
      <input type="text" placeholder="Username" />
    </div>

    <div class="input-box">
      <input type="password" placeholder="Password" />
    </div>

    <div class="options">
      <label>
        <input type="checkbox" /> Remember me
      </label>
      <a href="#">Forgot Password?</a>
    </div>

    <button>Login</button>

    <div class="register">
      Don't have an account? <a href="#">Register</a>
    </div>
  </div>

</body>
</html>
