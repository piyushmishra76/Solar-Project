Solar Project

html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Solar System</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="solar-system">
      
        <div class="sun"></div>

       
        <div class="orbit orbit1">
            <div class="planet planet1"></div>
        </div>
        <div class="orbit orbit2">
            <div class="planet planet2"></div>
        </div>
        <div class="orbit orbit3">
            <div class="planet planet3"></div>
        </div>
        <div class="orbit orbit4">
            <div class="planet planet4"></div>
        </div>
        <div class="orbit orbit5">
            <div class="planet planet5"></div>
        </div>
        <div class="orbit orbit6">
            <div class="planet planet6"></div>
        </div>
        <div class="orbit orbit7">
            <div class="planet planet7"></div>
        </div>
        <div class="orbit orbit8">
            <div class="planet planet8"></div>
        </div>
    </div>
</body>
</html>



css

        body {
            margin: 0;
            padding: 0;
            background: radial-gradient(circle, #000020, #000010);
            overflow: hidden;
        }

        .solar-system {
            position: relative;
            width: 100vw;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .sun {
            width: 100px;
            height: 100px;
            background: radial-gradient(circle, #ffcc00, #ff9900);
            border-radius: 50%;
            box-shadow: 0 0 50px #ffcc00;
        }

        .orbit {
            position: absolute;
            border: 1px dashed rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            animation: rotate 10s linear infinite;
        }

        .planet {
            position: absolute;
            top: 0;
            left: 40%;
            transform: translateX(-50%);
            width: 20px;
            height: 20px;
            background: radial-gradient(circle, #0077ff, #0055aa);
            border-radius: 50%;
        }


        .orbit1 {
            width: 150px;
            height: 150px;
        }

        .orbit2 {
            width: 250px;
            height: 250px;
            animation-duration: 15s;
        }

        .orbit3 {
            width: 350px;
            height: 350px;
            animation-duration: 20s;
        }
        .orbit4 {
            width: 450px;
            height: 450px;
            animation-duration: 25s;
        }
        .orbit5 {
            width: 550px;
            height: 550px;
            animation-duration: 35s;
        }
        .orbit6 {
            width: 650px;
            height: 650px;
            animation-duration: 55s;
        }
        .orbit7 {
            width: 750px;
            height: 750px;
            animation-duration: 60s;
        }
        .orbit8 {
            width: 850px;
            height: 850px;
            animation-duration: 65s;
        }

        .planet1 {
            background: radial-gradient(circle, grey,grey);
        }

        .planet2 {
            background: radial-gradient(circle, brown, brown);
        }

        .planet3 {
            background: radial-gradient(circle, lightblue, lightblue);
        }
        .planet4 {
            background: radial-gradient(circle, red, red);
        }
        .planet5 {
            background: radial-gradient(circle, yellow, brown , red);
        }
        .planet6 {
            background: radial-gradient(circle, yellow, grey);
        }
        .planet7 {
            background: radial-gradient(circle, cyan, cyan);
        }
        .planet8 {
            background: radial-gradient(circle, darkblue, darkblue);
        }


        @keyframes rotate {
            from {
                transform: rotate(0deg);
            }

            to {
                transform: rotate(360deg);
            }
        }

