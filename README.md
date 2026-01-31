<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vinaykumar-pixel</title>

    <style>
        /* ALL CSS HERE */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .login-box {
            width: 320px;
            padding: 30px;
            backdrop-filter: blur(12px);
            background: rgba(255, 255, 255, 0.25);
            border-radius: 15px;
            text-align: center;
        }
    </style>
</head>

<body>

    <!-- ONLY PAGE CONTENT HERE -->
    <div class="login-box">
        <h2>Login</h2>

        <input type="text" placeholder="Username"><br><br>
        <input type="password" placeholder="Password"><br><br>

        <label>
            <input type="checkbox"> Remember me
        </label><br><br>

        <button>Login</button>
        <p>Don’t have an account? <b>Register</b></p>
    </div>

</body>
</html>
