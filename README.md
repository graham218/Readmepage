Hi there, I'm Aaryaveer Rajput👋

Learning ReactJS and working on building interactive UIs using Javascript and React. 

- 🔭 I’m currently working on React
- 🌱 I’m currently learning React
- 👯 I’m looking to collaborate on an ipen source project
- 📫 How to reach me: Email : aaryaveerrajput001@gmail.com
- 😄 Pronouns: He/Him


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- <link rel="stylesheet" href="index.css"> -->
</head>
<body>
    <style>
    .item{
        transition: 0.3s;
        color: blue;
        border: 2px solid black;
        float: left;
        padding: 20px;
        margin-left: 20px;
        color: blueviolet;
        background-color: aqua;
        border-radius: 10px;
        height: 30px;
        width: 40px;
        display: flex;
        flex-direction: row;
        flex: 25%;
    }
    
    .container:hover{
        cursor: pointer;
    }
    .container:hover > :not(:hover){
        opacity : 0.4;
    }
    </style>
    <div class="container">
        <div class="item">HEY</div>
        <div class="item">HI</div>
        <div class="item">HELLO</div>
        <div class="item">BYE</div>
    </div>

</body>
</html>
