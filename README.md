<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>CryptoBath</title>
    <style>
        @keyframes slideIt {
            0% {
                background-image: url(img/3.png);
            }
            20% {
                background-image: url(img/4.png);
            }
            40% {
                background-image: url(img/5.png);
            }
            60% {
                background-image: url(img/6.png);
            }
            80% {
                background-image: url(img/Bitcoin-backgrounds.png);
            }

        }
        body {
            min-height: 100vh;
            background-image: url("img/maxresdefault.jpg");
            background-size: cover;
            background-position: center center;
            animation: slideIt 8s infinite;
        }
        a {
            background-color: deeppink;
            background-image: url("img/3.png");
            background-size: cover;
            width: 250px;
            height: 250px;
            float: left;
            margin: 175px;
            padding: 15px;
            text-align: center;
            color:lightsalmon;/*farge på text */
            transition: 1s;
        }
        a:hover {
            background-color: greenyellow;
            transform: scale(1.1);
        }
        h1 {
            text-align: center;
        }
        @keyframes move {
            0% {
                background-position: 0 0;
                transform: scale(1);
            }
            50% {
                background-position: 4000% 4000%;
                transform: scale(1.3);
            }
            100% {
                background-position: -4000% -4000%;
                transform: scale(1);
            }
        }
        h1 {
            text-align: center;
            font-family: 'Passion One';
            font-size: 12rem;
            background-image: url("http://cryptocurrencybitcoinnews.com/wp-content/uploads/2016/01/bitcoin-cryptocurrency-hack.jpg");
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: move steps(30) 6s infinite;
        }

    </style>
</head>
<body>
<h1><b>CryptoBath</b></h1>
<a href="mining.html"><b>Mining</b></a>
<a href="prices.html"><b>Prices</b></a>
<a href="guides.html"><b>Guides</b></a>
<a href="news.html"><b>News</b></a>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CryptoBath</title>
    <style> body {
        margin: 0;
        background-color: #f2f2f2;
    }
    nav {
        background-color: #444059;
    }
    nav a {
        display: inline-block;
        color: #b4b3bd;
        font-family: "Open sans", Helvetica, Arial, sans-serif;
        padding: 22px 12px 22px 12px;
        font-size: 18px;
        text-decoration: none;
    }
    nav a:hover {
        color: white;
    }
    .active {
        color: white;
        border-bottom: 4px solid orangered;
    }</style>
</head>
<body>
<nav>
    <a href="index_1.html"><b>Forsiden</b></a>
    <a href="prices.html"><b>Prices</b></a>
    <a href="news.html"><b>News</b></a>
    <a href="guides.html"><b>Guides</b></a>
</nav>
<h1>A MINERS LIFE</h1>
<p>There are miners all over the world</p>
<h2>Mining Keywords</h2>
    <li>relaxed</li>
    <li>rich</li>
    <li>Cryptocurrency universe</li>
<img src="img/last%20ned.jpeg" width="400" height="350">
<p> <big>MINERS</big><p><p><a href="https://bitcointalk.org/index.php?topic=1707546.0"><b>Equailhash</b></a>
<p></p>
<a href="https://bitcointalk.org/index.php?topic=1433925.0"><b>Ethash</b></a>
</body>
</html>
