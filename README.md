- 👋 Hi, I’m @Rokiay
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
<!DOCTYPE html>  <html lang="ar">  
<head>  
  <meta charset="UTF-8">  
  <title>تسجيل الدخول</title>  
  <style>  
    body {  
      background: #f0f2f5;  
      font-family: Arial;  
      display: flex;  
      justify-content: center;  
      align-items: center;  
      height: 100vh;  
    }  
    .login-box {  
      background: white;  
      padding: 40px;  
      border-radius: 10px;  
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);  
      width: 300px;  
    }  
    input {  
      width: 100%;  
      padding: 10px;  
      margin: 10px 0;  
      border-radius: 6px;  
      border: 1px solid #ddd;  
    }  
    button {  
      width: 100%;  
      background: #1877f2;  
      color: white;  
      padding: 10px;  
      border: none;  
      border-radius: 6px;  
      font-size: 16px;  
    }  
    .error {  
      color: red;  
      text-align: center;  
      display: none;  
    }  
  </style>  
</head>  
<body>  <div class="login-box">  
  <h2 style="text-align:center;">تسجيل الدخول</h2>  
  <input type="text" id="username" placeholder="الإيميل أو الاسم">  
  <input type="password" id="password" placeholder="كلمة السر">  
  <div class="error" id="error">المعلومات خاطئة</div>  
  <button onclick="login()">دخول</button>  
</div>  <script>  
  function login() {  
    const user = document.getElementById("username").value;  
    const pass = document.getElementById("password").value;  
    const correctUser = "admin";  
    const correctPass = "1234";  
  
    if (user === correctUser && pass === correctPass) {  
      // هنا يمكن تسجل الدخول ف Google Sheet أو ترسلو لرابط خاص  
      window.location.href = "https://your-secret-link.com";  
    } else {  
      document.getElementById("error").style.display = "block";  
    }  
  }  
</script>  </body>  
</html>

<!---
Rokiay/Rokiay is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
