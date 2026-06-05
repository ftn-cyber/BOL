<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Security Warning</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:linear-gradient(135deg,#0a0a0a,#300000,#000);
    color:white;
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    overflow:hidden;
}

.container{
    text-align:center;
    padding:40px;
    border:2px solid #ff0000;
    border-radius:25px;
    background:rgba(0,0,0,0.85);
    box-shadow:
        0 0 20px #ff0000,
        0 0 40px #ff0000;
    max-width:700px;
    width:90%;
}

.warning-logo{
    font-size:100px;
    color:#ff0000;
    text-shadow:0 0 20px red;
    animation:pulse 1.5s infinite;
}

h1{
    font-size:50px;
    color:#ff3b3b;
    text-shadow:0 0 15px red;
    margin-bottom:15px;
}

.line{
    width:100%;
    height:3px;
    background:red;
    margin:20px 0;
    box-shadow:0 0 10px red;
}

p{
    color:#ddd;
    font-size:18px;
    line-height:1.8;
}

.creator{
    margin-top:25px;
    color:#ff3b3b;
    font-size:18px;
    text-shadow:0 0 10px red;
}

@keyframes pulse{
    0%{
        transform:scale(1);
    }
    50%{
        transform:scale(1.1);
    }
    100%{
        transform:scale(1);
    }
}

@media(max-width:768px){
    .warning-logo{
        font-size:80px;
    }

    h1{
        font-size:38px;
    }

    p{
        font-size:16px;
    }
}
</style>
</head>

<body>

<div class="container">

    <div class="warning-logo">⚠️</div>

    <h1>SECURITY WARNING</h1>

    <div class="line"></div>

    <p>
        Sistem mendeteksi aktivitas yang memerlukan perhatian.
        Pastikan keamanan akun dan data Anda tetap terjaga.
    </p>

    <p class="creator">
        Dibuat oleh: Mr.Z10I18J50
    </p>

</div>

</body>
</html>
