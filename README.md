<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Fantasy RPG Background</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
            background-color: #2C1810;
            background-image: 
                linear-gradient(rgba(44, 24, 16, 0.8), rgba(44, 24, 16, 0.8)),
                url("data:image/svg+xml,%3Csvg width='100' height='100' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noiseFilter'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.65' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noiseFilter)'/%3E%3C/svg%3E");
        }
        .parchment-frame {
            position: absolute;
            top: 10px;
            left: 10px;
            right: 10px;
            bottom: 10px;
            border: 15px solid transparent;
            border-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='30' height='30' viewBox='0 0 30 30'%3E%3Cpath d='M0,0 L10,0 C20,10 10,20 0,30 Z M30,0 L20,0 C10,10 20,20 30,30 Z' fill='%237B5E2C'/%3E%3C/svg%3E") 15 round;
            box-shadow: 0 0 20px rgba(0,0,0,0.5);
        }
        #content-iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>
    <div class="parchment-frame">
        <iframe id="content-iframe" src="YOUR_IFRAME_URL_HERE" frameborder="0" allowfullscreen></iframe>
    </div>
</body>
</html>
