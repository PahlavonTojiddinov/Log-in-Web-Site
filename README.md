<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login page</title>
    <style>
        body{
    background-image: url(./lake-blue-moonlight-moon-wallpaper-preview.jpeg);        /* You need to download picture form this link https://lens.google.com/search?ep=cntpubb&hl=en-US&re=df&s=4&p=AbrfA8oOePe961aoPhUS7kidGF6N2BXG4302LxFTAwproVBGh_cTeW3EmDzE8Y17DpUw_vWK_zUdxW78qbzPNJmHwumlN4qWEHJREjQA25wgLsRNhO0O4Vs4G6YiQdYNIjq2YgVYybEfTsEeRfWKBOgT2hPLxaPKmxWshGWPC9OLfAwXUPHKKNMZl0lCe7_LEZsOOjy3CC9g6p5XGeB0iRRRZFXlVBHYislXbvle2BYPziNkV4F0J9p3iq6n0IGeGGEVMYFMbKNLBxxvKtUzPv347D3SDrokNFKaE1tPhfja5F8%3D#lns=W251bGwsbnVsbCxudWxsLG51bGwsbnVsbCxudWxsLG51bGwsIkVrY0tKREkwWWprd1kyTm1MVFJqWkdVdE5EaGhOQzFpWmpsbUxUa3pZV0ZoTlRaa1lUSXpaUklmVlRGSlVURmpjbWxOT1d0bE5FWXpjRVF5ZGpoaFkzTlBRMnBaY0hsQ1p3PT0iXQ== */
    /* And you must rename it to lake-blue-moonlight-moon-wallpaper-preview.jpeg*/
    background-repeat: no-repeat;
    background-size: cover;
}
.login-container{
    background-color: rgba(79, 79, 79, 0.8);
    width: 400px;
    height: 300px;
    margin: auto;
    margin-top: 250px;
    padding-top: 40px;
    box-sizing: border-box;
    
}
input{
    background-color: rgba(47, 47, 47, 0.8);
    display: block;
    width: 60%;
    height: 30px;
    font-size: 20px;
    margin: auto;
}
label{
    display: block;
    width: 60%;
    margin: auto;
    color: white;
    font-size: 20px;
    margin-top: 10px;
    /* background-color: blue; */
}
button{
    opacity: gray;
    border: 1px solid white;
    background-color: rgb(61, 61, 61);
    color: white;
    width: 62%;
    height: 40px;
    display: block;
    margin: auto;
    font-size: 20px;
    margin-top: 20px;
}
a {
    color: rgb(0, 0, 0);
    
}
.home{
    width: 100%;
    height: 50px;
    background-color: rgb(76, 78, 79);
}
.home{
    width: 100%;
    height: 50px;
    background-color: rgb(90, 90, 90);

}

    </style>
</head>
<body>

    <div class="login-container">
        <h1 style="color: white;text-align: center;">Sing In or <a href="#">Sing Up</a></h1>
        <form action="" class="login-form">
            <label for="username"></label>
            <input id="username" type="text" placeholder="Username">
            <label for="password"></label>
            <input type="password" id="password" placeholder="Password">
            <button type="submit">Login</button>
        </form>
    </div>

</body>
</html>
