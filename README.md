317
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <link href="sec.css" rel="stylesheet" type="text/css">
</head>
<body>
<div class="wrapper">
    <form action="/chaos/EvilEmail.html"method="post">
        <div class="loginBox">
        <div class="loginBoxCenter">
            <p><label for="username">电子邮箱：</label></p>
            <p><input type="email" id="email" name="email" class="loginInput"
            autofocus="autofocus" required="required" autocomplete="off"
            placeholder="请输入电子邮箱"value=""/></p>
            <p>
                <label for="password">密码：</label>
                <a class="forgetLink" href="chongzhi.html">修改密码？</a>
            </p>
            <p>
                <input type="password" id="password" name="password" class="loginInput"
                require="require" placeholder="请输入密码" value=""/>
            </p>
</div>
        <div class="loginBoxButtons">
            <input id="remember" type="checkbox" name="remember"/>
            <label for="remember">记住登录状态</label>
            <button class="loginBtn">登录</button>
        </div>
     </div>
    </form>
</div>
</body>

</html>
