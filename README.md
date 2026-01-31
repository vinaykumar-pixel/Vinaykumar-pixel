<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vinaykumar-pixel</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            height: 100vh;
            background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') 
                        no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .login-box {
            width: 320px;
            padding: 30px;
            background: rgba(255, 255, 255, 0.25);
            backdrop-filter: blur(12px);
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }

        .login-box h2 {
            margin-bottom: 20px;
            color: #fff;
        }

        .login-box input {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border: none;
            border-radius: 20px;
            outline: none;
        }

        .options {
            display: flex;
            justify-content: space-between;
            font-size: 14px;
            color: #fff;
            margin: 10px 0;
        }

        .login-box button {
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 20px;
            background: #ffffff;
            font-size: 16px;
            cursor: pointer;
            margin-top: 10px;
        }

        .login-box p {
            color: #fff;
            margin-top: 15px;
            font-size: 14px;
        }
    </style>
</head>

<body>

    <div class="login-box">
        <h2>Login</h2>

        <input type="text" placeholder="Username">
        <input type="password" placeholder="Password">

        <div class="options">
            <label>
                <input type="checkbox"> Remember me
            </label>
            <span>Forgot Password?</span>
        </div>

        <button>Login</button>

        <p>Don’t have an account? <b>Register</b></p>
    </div>

</body>
</html>
