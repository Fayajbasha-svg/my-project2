<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub Multiple Accounts</title>

<link href="https://fonts.googleapis.com/css2?family=Anton&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:#efefef;
    font-family:'Anton', sans-serif;
    min-height:100vh;
    position:relative;
}

.container{
    padding:40px;
}

.github-logo{
    position:absolute;
    top:30px;
    right:80px;
    text-align:center;
}

.github-logo img{
    width:250px;
}

.text{
    margin-top:150px;
    line-height:0.9;
}

.black{
    color:#000;
}

.green{
    color:#31c34d;
}

.text h1{
    font-size:140px;
    letter-spacing:2px;
}

.line1{
    width:620px;
    height:6px;
    background:#b5df1f;
    margin:10px 0;
}

.circle{
    display:inline-block;
    border:8px solid #b5df1f;
    border-radius:50%;
    padding:0 20px;
}

.projects{
    display:flex;
    align-items:flex-start;
    gap:20px;
}

.projects h1{
    font-size:140px;
}

.arrow{
    position:absolute;
    right:120px;
    bottom:80px;
}

.arrow .line{
    width:8px;
    height:140px;
    background:#b5df1f;
    transform:rotate(35deg);
    margin-left:80px;
}

.arrow .line2{
    width:8px;
    height:120px;
    background:#b5df1f;
    transform:rotate(-55deg);
    margin-top:-90px;
}
</style>
</head>

<body>

<div class="github-logo">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png">
    <h1 style="font-size:100px;">GitHub</h1>
</div>

<div class="container">

    <div class="text">

        <h1 class="black">MANAGING</h1>

        <div class="line1"></div>

        <h1 class="green">MULTIPLE</h1>

        <div>
            <span class="circle">
                <h1 class="black">GITHUB</h1>
            </span>

            <h1 class="black" style="display:inline;">
                ACCOUNTS FOR
            </h1>
        </div>

        <div class="projects">
            <h1 class="green">MULTIPLE</h1>
            <h1 class="black">PROJECTS</h1>
        </div>

    </div>

</div>

<div class="arrow">
    <div class="line"></div>
    <div class="line2"></div>
</div>

</body>
</html>
