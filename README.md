<!DOCTYPE html>
<html lang="am">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ንጋት የዜማ መሳሪያዎች | Nigat Melody</title>
    <style>
        :root {
            --sunrise-gradient: linear-gradient(45deg, #ff512f, #dd2476, #ffd700);
            --glass-bg: rgba(255, 255, 255, 0.1);
            --text-color: #ffffff;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }

        body {
            background: #0a0a0a;
            color: var(--text-color);
            overflow: hidden;
        }

        /* Full Screen Background Image */
        .main-bg {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.9)), 
                        url('YOUR_IMAGE_URL_HERE'); /* Add your background photo link here */
            background-size: cover;
            background-position: center;
            z-index: -1;
        }

        /* --- PAGE 1: WELCOME --- */
        #welcome-page {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            transition: transform 0.8s ease-in-out;
        }

        .logo-glow {
            font-size: 4rem;
            background: var(--sunrise-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: bold;
            margin-bottom: 10px;
            filter: drop-
