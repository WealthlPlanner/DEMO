<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preggie Govender - Digital Business Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #f0f0f0;
            display: flex;
            height: 100vh;
            animation: fadeIn 3s ease-in-out;
        }

        .left-side, .right-side {
            flex: 1;
            color: white;
            padding: 20px;
            animation: fadeInUp 4s ease-in-out;
        }

        .left-side {
            background-color: #000000;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }

        .right-side {
            background-color: #001f3d;
        }

        .container {
            background: #002b53;
            padding: 30px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.3);
            border-radius: 8px;
            text-align: center;
            max-width: 950px;
            margin: 0 auto;
            animation: fadeInUp 4s ease-in-out;
        }

        h1, h2 {
            color: #e0e0e0;
        }

        p {
            color: #dcdcdc;
        }

        .contact-info, .section {
            background: #004785;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }

        .contact-info a {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
        }

        .services-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 20px;
        }

        .service-item {
            flex: 1;
            background: #004785;
            padding: 20px;
            border-radius: 5px;
            color: #ffffff;
            box-sizing: border-box;
            min-width: 280px;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #006b97;
            color: #ffffff;
            border-radius: 5px;
            text-decoration: none;
        }

        .button:hover {
            background-color: #005f87;
        }

        .meeting-form {
            background: #004785;
            padding: 15px;
            border-radius: 5px;
        }

        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #004785;
            border-radius: 4px;
            background: #003e58;
            color: #f0f0f0;
        }

        button {
            background: #006b97;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }

        button:hover {
            background: #005f87;
        }

        #financial-advice {
            text-align: center;
            max-width: 600px;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <div class="left-side">
        <h1>Preggie Govender</h1>
        <h2>Chief Inspiration Officer</h2>
    </div>

    <div class="right-side">
        <div class="container">
            <div class="contact-info" id="contact">
                <p><strong>Contact Me</strong></p>
                <p>Email: <a href="mailto:preggie@preggiegovender.com">preggie@preggiegovender.com</a></p>
                <p>Cell: <a href="tel:+27825511433">082 551 1433</a></p>
            </div>

            <div class="section" id="financial-advice">
                <h2>Financial Advice</h2>
                <ul>
                    <li>Life Assurance</li>
                    <li>Investments</li>
                    <li>Retirement Planning</li>
                    <li>Estate Planning</li>
                </ul>
            </div>

            <div class="linkedin">
                <h2>Connect with Me</h2>
                <p><a href="https://www.linkedin.com/in/preggie-govender-mr-g-30a97040/" target="_blank" class="button">Connect on LinkedIn</a></p>
            </div>

            <footer>
                <p>&copy; 2025 Preggie Govender. All rights reserved.</p>
                <p>Disclaimer: This website is for informational purposes only and does not constitute professional financial or real estate advice.</p>
            </footer>
        </div>
    </div>
</body>
</html>
