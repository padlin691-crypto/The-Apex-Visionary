<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Apex Visionary - Media Hub</title>
    <style>
        body {
            background-color: #050505;
            color: white;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            text-align: center;
        }

        .header {
            margin-bottom: 40px;
        }

        /* Container Logo */
        .logo-container {
            margin-bottom: 15px;
        }

        .logo-container img {
            max-width: 180px; /* Ukuran logo */
            height: auto;
            filter: drop-shadow(0 0 10px rgba(0, 150, 255, 0.5));
        }

        h1 {
            font-size: 1.8rem;
            letter-spacing: 4px;
            text-transform: uppercase;
            margin: 10px 0;
            background: linear-gradient(to right, #fff, #888);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .container {
            width: 90%;
            max-width: 500px;
        }

        /* Desain Tombol TV */
        .station-card {
            background: #111;
            border: 1px solid #333;
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 20px;
            transition: 0.3s;
            text-decoration: none;
            display: block;
            position: relative;
            overflow: hidden;
        }

        .ns-tv { border-left: 5px solid #ff004c; }
        .vams-tv { border-left: 5px solid #00f2ff; }

        .station-card:hover {
            transform: translateY(-5px);
            background: #1a1a1a;
        }

        .station-name {
            font-size: 1.5rem;
            font-weight: bold;
            margin-bottom: 10px;
            display: block;
        }

        .ns-tv .station-name { color: #ff004c; text-shadow: 0 0 10px rgba(255, 0, 76, 0.5); }
        .vams-tv .station-name { color: #00f2ff; text-shadow: 0 0 10px rgba(0, 242, 255, 0.5); }

        .btn-enter {
            background: transparent;
            border: 1px solid #555;
            color: #ccc;
            padding: 8px 20px;
            border-radius: 5px;
            text-transform: uppercase;
            font-size: 0.8rem;
            letter-spacing: 1px;
        }

        footer {
            margin-top: 50px;
            font-size: 0.7rem;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="header">
        <div class="logo-container">
            <img src="logo.png" onerror="this.src='logo.jpg'; this.onerror=this.src='https://via.placeholder.com/150?text=Apex+Logo';" alt="Logo Apex">
        </div>
        <h1>The Apex Visionary</h1>
    </div>

    <div class="container">
        <a href="https://padlin691-crypto.github.io/NS-TV-Visionary/" class="station-card ns-tv">
            <span class="station-name">NS TV</span>
            <button class="btn-enter">Enter Station</button>
        </a>

        <a href="https://padlin691-crypto.github.io/VAMS-TV-Visionary/" class="station-card vams-tv">
            <span class="station-name">VAMS TV</span>
            <button class="btn-enter">Enter Station</button>
        </a>
    </div>

    <footer>
        &copy; 2026 THE APEX VISIONARY - ALL RIGHTS RESERVED
    </footer>

</body>
</html>
