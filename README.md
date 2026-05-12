<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Cinematic Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #111;
            color: #fff;
        }
        .hero {
            height: 100vh;
            background: url('your-image.jpg') no-repeat center/cover;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            text-align: center;
        }
        .hero h1 {
            font-size: 4em;
            margin: 0;
            animation: fadeIn 3s;
        }
        .section {
            padding: 80px 20px;
            text-align: center;
        }
        .about, .gallery, .videos {
            max-width: 800px;
            margin: auto;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <section class="hero">
        <h1>Your Name</h1>
        <p>Your Cinematic Portfolio</p>
    </section>
    <section class="section about">
        <h2>About Me</h2>
        <p>Write a brief bio here...</p>
    </section>
    <section class="section gallery">
        <h2>Photography</h2>
        <p>Showcase your best photos here...</p>
    </section>
    <section class="section videos">
        <h2>Videos</h2>
        <p>Embed or link your videos here...</p>
    </section>
</body>
</html>
