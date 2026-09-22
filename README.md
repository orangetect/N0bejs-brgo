<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NextGen AI Robot</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0b0f19;
            color: #ffffff;
            line-height: 1.6;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background: rgba(15, 23, 42, 0.8);
            border-bottom: 1px solid #1e293b;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #00f2fe;
            letter-spacing: 2px;
        }

        nav a {
            color: #94a3b8;
            text-decoration: none;
            margin-left: 20px;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #00f2fe;
        }

        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 100px 20px;
            background: radial-gradient(circle at center, #1e1b4b 0%, #0b0f19 70%);
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            max-width: 600px;
            font-size: 18px;
            color: #94a3b8;
            margin-bottom: 30px;
        }

        .btn {
            padding: 12px 30px;
            font-size: 16px;
            color: #0b0f19;
            background: #00f2fe;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            font-weight: bold;
            box-shadow: 0 0 15px rgba(0, 242, 254, 0.4);
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 0 25px rgba(0, 242, 254, 0.7);
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 80px 50px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .card {
            background: #1e293b;
            padding: 30px;
            border-radius: 12px;
            border: 1px solid #334155;
            transition: border-color 0.3s;
        }

        .card:hover {
            border-color: #00f2fe;
        }

        .card h3 {
            color: #00f2fe;
            margin-bottom: 15px;
        }

        .card p {
            color: #94a3b8;
            font-size: 14px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #0f172a;
            color: #64748b;
            font-size: 14px;
            border-top: 1px solid #1e293b;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">ROBO-AI</div>
        <nav>
            <a href="#home">Home</a>
            <a href="#features">Features</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Autonomous AI Robotics</h1>
        <p>Empowering the future with advanced artificial intelligence, natural language processing, and real-time autonomous systems.</p>
        <button class="btn">Explore System</button>
    </section>

    <section class="features" id="features">
        <div class="card">
            <h3>Neural Processing</h3>
            <p>High-speed visual recognition and neural computational framework built for dynamic real-time environments.</p>
        </div>
        <div class="card">
            <h3>Adaptive Learning</h3>
            <p>Self-improving machine learning algorithms that adapt to complex operational tasks effortlessly.</p>
        </div>
        <div class="card">
            <h3>Cyber Security</h3>
            <p>Encrypted data streams and secure cloud connections ensuring maximum protocol safety.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 ROBO-AI Systems. All rights reserved.</p>
    </footer>

</body>
</html>
