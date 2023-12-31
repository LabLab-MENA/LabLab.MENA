<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css?family=Roboto:400,700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-image: url('https://cdn.discordapp.com/attachments/1113041676403998801/1120098316265455757/webinar.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            display: flex;
            height: 100vh;
            align-items: center;
            justify-content: center;
        }

        h1, h2, p {
            margin-bottom: 15px;
        }

        .container {
            width: 100%;
            max-width: 700px;
            padding: 30px;
            background-color: rgba(240, 249, 255, 0.9);
            box-shadow: 0 4px 12px 0 rgba(0, 0, 0, 0.2);
            border-radius: 5px;
        }

        .date-time {
            background-color: #0b3d91;
            color: #fff;
            padding: 7px;
            margin-bottom: 15px;
            text-align: center;
            border-radius: 5px;
            font-weight: 500;
            font-size: 14px;
        }

        .btn {
            display: inline-block;
            background-color: #0b3d91;
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 20px 10px 0;
            border-radius: 5px;
            transition: background-color 0.2s;
            font-weight: 700;
        }

        .btn:hover {
            background-color: #072a5d;
        }

        .button-container {
            text-align: center;
        }
    </style>
    <title>Webinar Registration</title>
</head>
<body>
<div class="container">
    <h1>Discover the Future of AI-Powered Startups</h1>
    <p>Join our exclusive webinar for AI enthusiasts and AI-driven founders.</p>
    <div class="date-time">
        21st of June 2023, 1:30 PM Saudi Arabia Time (GMT +3)
    </div>
    <p>In this insightful webinar, you will:</p>
    <ol>
        <li>Explore the benefits of adopting AI in your startup.</li>
        <li>Gain insights into accessing cutting-edge AI technologies for success.</li>
        <li>Learn how GAIA Accelerator supports AI-focused startups.</li>
        <li>Enhance your startup's AI-powered innovation.</li>
    </ol>
    <div class="button-container">
        <a href="https://forms.monday.com/forms/921233bb504c3edd746d29b5109e1fea?r=use1" class="btn"
           target="_blank">Register for Webinar</a>
        <a href="https://gaia.newnative.ai/" class="btn" target="_blank">Visit GAIA's Website</a>
    </div>
</div>
<script>
    window.onload = function () {
        document.querySelector('.Header-link').style.display = 'none';
    };
</script>
</body>
</html>
