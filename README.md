<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Side Navigation Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
        }

        .sidenav {
            height: 100%;
            width: 200px;
            position: fixed;
            top: 0;
            left: 0;
            background-color:rgb(114, 207, 223);
            padding-top: 20px;
        }

        .sidenav a {
            display: block;
            color: #f2f2f2;
            padding: 15px;
            text-decoration: none;
            text-align: center;
        }
        .sidenav a:hover {
            background-color: #d1e9a4;
            color: white;
            text-decoration: none;
            text-align: center;
        }

        .main-content {
            margin-left: 220px;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="sidenav">
        <a href="#home" class="active">Home</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </div>

    <div class="main-content">
        <h1>This Page Belongs to Ecommerce</h1>
        <p>Ecommerce or "electronic commerce" is the trading of goods and services online. The internet allows individuals and businesses to buy and sell an increasing amount of physical goods, digital goods, and services electronically.</p>

    </div>
</body>
</html>
