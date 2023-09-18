# myatsite
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Webpage</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            height: 80px;
            background-color: white;
            border-bottom: 2px solid black;
            box-shadow: 0 8px 6px -6px rgba(0, 0, 0, 0.5);
        }

        /* Logo Box */
        .logo-box {
            position: absolute;
            top: 0;
            right: 0;
            width: 80px;
            height: 80px;
            background-color: black;
        }

        /* Content Container */
        .content-container {
            height: 800px;
            background-color: grey;
            padding: 20px;
        }

        /* White Boxes */
        .white-box {
            width: 200px;
            height: 200px;
            background-color: white;
            margin: 20px;
            display: inline-block;
            vertical-align: top;
        }

        /* Footer */
        footer {
            width: 100%;
            height: 80px;
            background-color: white;
            border-top: 2px solid black;
            text-align: center;
            position: absolute;
            bottom: 0;
        }

        footer h1 {
            margin-top: 25px;
        }
    </style>
</head>
<body>
    <nav>
        <div class="logo-box"></div>
    </nav>
    <div class="content-container">
        <div class="white-box"></div>
        <div class="white-box"></div>
        <div class="white-box"></div>
        <div class="white-box"></div>
    </div>
    <footer>
        <h1>Copyright Current Year</h1>
    </footer>
</body>
</html>
