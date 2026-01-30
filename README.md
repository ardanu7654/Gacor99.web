# Gacor99.web
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GACOR99 - Portal Resmi Terpercaya</title>
    <link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@500;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Rajdhani', sans-serif;
            background: #000000; /* Hitam pekat agar warna neon kontras */
            background-image: radial-gradient(circle at center, #1a1a1a 0%, #000000 100%);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow-x: hidden;
        }

        .wrapper {
            width: 100%;
            max-width: 450px;
            padding: 20px;
            text-align: center;
        }

        /* Animasi Logo/Header */
        .header-box {
            margin-bottom: 30px;
        }

        .brand-name {
            font-size: 3rem;
            font-weight: 700;
            color: #fff;
            text-shadow: 0 0 10px #ff0000, 0 0 20px #ff0000, 0 0 30px #ff0000;
            margin: 0;
            letter-spacing: 5px;
        }

        .sub-brand {
            color: #ffd700; /* Warna Gold */
            font-size: 1.2rem;
            letter-spacing: 2px;
            margin-top: -5px;
            text-transform: uppercase;
        }

        /* Tombol Utama */
        .btn-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .btn {
            position: relative;
            padding: 18px;
            font-size: 1.5rem;
            font-weight: 700;
            text-decoration: none;
            text-transform: uppercase;
            border-radius: 8px;
            transition: 0.3s;
            border: none;
            cursor: pointer;
            overflow: hidden;
        }

        /* Animasi Berdenyut (Pulse) */
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.03); }
            100% { transform: scale(1); }
        }

        .login-btn {
            background: linear-gradient(90deg, #ff0000, #990000);
            color: white;
            box-shadow: 0 0 15px rgba(255, 0, 0, 0.6);
            animation: pulse 1.5s infinite ease-in-out;
        }

        .reg-btn {
            background: linear-gradient(90deg, #ffd700, #b8860b);
            color: black;
            box-shadow: 0 0 15px rgba(255, 215, 0, 0.6);
