<!DOCTYPE html>
<html>
<head>
    <title>Marinduque - Heart of the Philippines</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
        }
        body { background: #f0f0f0; }

        /* BANNER / HEADER - PERFECT FIT & ARTISTIC */
        .banner {
            width: 100%;
            min-height: 85vh; /* Sakto lang sa screen, hindi sobrang haba */
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('https://images.unsplash.com/photo-1542281286-9e0a16bb7366');
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 20px;
        }

        /* ARTISTIC FONT STYLE */
        .banner h1 {
            font-size: clamp(40px, 10vw, 80px); /* Aayos ng size depende sa screen */
            font-weight: bold;
            letter-spacing: 8px; /* Malalayo ang letters para artistic */
            text-shadow: 
                3px 3px 0px #8B0000, 
                5px 5px 10px rgba(0,0,0,0.7);
            font-family: 'Times New Roman', serif; /* Mas elegante tignan */
            text-transform: uppercase;
        }
        .banner .heart {
            color: #FF0000;
            font-size: clamp(30px, 8vw, 60px);
            margin-right: 15px;
            text-shadow: 2px 2px 5px black;
        }
        .banner p {
            font-size: clamp(14px, 3vw, 22px);
            opacity: 0.9;
            margin-bottom: 5px;
            font-style: italic;
        }

        /* NAVIGATION MENU */
        .navbar {
            background: #8B0000;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 12px 25px;
            display: inline-block;
            transition: background 0.3s;
        }
        .navbar a:hover, .navbar a.active {
            background: #B22222;
            border-radius: 8px;
        }

        /* CONTENT AREA - PERFECT WIDTH */
        .container {
            width: 92%;
            max-width: 900px;
            margin: 30px auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        .welcome h2 {
            color: #8B0000;
            font-size: 28px;
            margin-bottom: 10px;
        }
        .divider {
            height: 3px;
            background: linear-gradient(to right, #8B0000, #FFD700);
            margin-bottom: 20px;
        }
        .welcome p {
            font-size: 17px;
            line-height: 1.8;
            color: #333;
            text-align: justify;
        }
    </style>
</head>
<body>

    <!-- BANNER AREA -->
    <div class="banner">
        <h1><span class="heart">❤️</span> MARINDUQUE</h1>
        <p>The Heart of the Philippines</p>
        <p>Home of the Authentic Moriones Festival</p>
    </div>

    <!-- NAVIGATION BAR -->
    <div class="navbar">
        <a href="index.html" class="active">HOME</a>
        <a href="history.html">HISTORY</a>
        <a href="moriones.html">MORIONES</a>
        <a href="factcheck.html">FACT CHECK</a>
        <a href="about.html">ABOUT</a>
        <a href="lifestyle.html">LIFE STYLE</a>
    </div>

    <!-- MAIN CONTENT -->
    <div class="container">
        <div class="welcome">
            <h2>Welcome to Marinduque!</h2>
            <div class="divider"></div>
            
            <p>
                Ang Marinduque ay isang pulong probinsya na matatagpuan sa rehiyon ng MIMAROPA. Ito ay tinaguriang "Heart of the Philippines" dahil sa hugis nito na parang puso at dahil nasa gitna ito ng arkipelago.
            </p>
            <p>
                Kilala ang probinsyang ito hindi lamang sa ganda ng kalikasan kundi pati na rin sa mayamang kultura at kasaysayan. Dito ipinagdiriwang ang sikat na Moriones Festival tuwing Mahal na Araw.
            </p>
            <p>
                Pindutin ang **HISTORY** sa menu bar upang makita ang kwento at detalye ng anim na bayan ng Marinduque.
            </p>
        </div>
    </div>

</body>
</html>
