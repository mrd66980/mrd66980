<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تسجيل الدخول إلى شبكة Wi-Fi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
        }
        .login-container h2 {
            margin-bottom: 20px;
            color: #333;
        }
        .login-container input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .login-container button {
            width: 100%;
            padding: 10px;
            background-color: #28a745;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .login-container button:hover {
            background-color: #218838;
        }
        .login-container a {
            color: #007bff;
            text-decoration: none;
            font-size: 14px;
        }
        .login-container a:hover {
            text-decoration: underline;
        }
        .logo {
            width: 100px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <!-- شعار الشبكة -->
        <img src="logo.png" alt="شعار الشبكة" class="logo">
        <h2>تسجيل الدخول إلى شبكة Wi-Fi</h2>
        <!-- حقل اسم المستخدم -->
        <input type="text" placeholder="اسم المستخدم" required>
        <!-- حقل كلمة المرور -->
        <input type="password" placeholder="كلمة المرور" required>
        <!-- زر تسجيل الدخول -->
        <button type="submit">تسجيل الدخول</button>
        <!-- رابط نسيت كلمة المرور -->
        <a href="#">نسيت كلمة المرور؟</a>
    </div>
</body>
</html>
