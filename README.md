<html lang="en" dir="ltr">

<head>
    <meta charset="utf-8">
    <title>LOGIN PAGE</title>
   
</head>

<body>

    <form class="box" action="home.html" method="post">
        <h1>Login</h1>
        <input type="text" name="" placeholder="Username">
        <input type="password" name="" placeholder="Password">
        <input type="submit" name="" value="Login"> 
    </form>


</body>

</html>
<style>
    body {
        margin: 0;
        padding: 0;
        font-family: sans-serif;
        background-size: cover;
        background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTz3xD1rvnhG0lZMB65l8NJeERr5tDNu_5JFk4g_eo7YgVvWzk1")
    }
    
    .box {
        width: 300px;
        padding: 40px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        text-align: center;
    }
    
    .box h1 {
        color: white;
        text-transform: uppercase;
        font-weight: 500;
    }
    
    .box input[type="text"],
    .box input[type="password"] {
        border: 0;
        background: none;
        display: block;
        margin: 20px auto;
        text-align: center;
        border: 2px solid #3498db;
        padding: 14px 10px;
        width: 200px;
        outline: none;
        color: white;
        border-radius: 24px;
        transition: 0.25s;
    }
    
    .box input[type="text"]:focus,
    .box input[type="password"]:focus {
        width: 280px;
        border-color: #2ecc71;
    }
    
    .box input[type="submit"] {
        border: 0;
        background: none;
        display: block;
        margin: 20px auto;
        text-align: center;
        border: 2px solid #2ecc71;
        padding: 14px 40px;
        outline: none;
        color: white;
        border-radius: 24px;
        transition: 0.25s;
        cursor: pointer;
    }
    
    .box input[type="submit"]:hover {
        background: #2ecc71;
    }
</style>  

