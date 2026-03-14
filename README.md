# toyooka
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LINE Official Page</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }
        h1, h2 {
            color: gold;
        }
        .button {
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            display: inline-block;
            margin: 5px 0;
        }
        .line-add {
            background-color: green;
            color: white;
        }
        .copy-save {
            background-color: gold;
            color: black;
        }
        .profile-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid gold;
        }
        .qr-section {
            margin-top: 20px;
        }
        .instructions {
            margin: 10px 0;
            background: #333;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Welcome to My LINE Official Page</h1>
    <img src="profile_image_url" alt="Profile Image" class="profile-image" />

    <h2>Add Me on LINE</h2>
    <a href="https://lin.ee/yCeyO2h" class="button line-add">Add me on LINE</a>

    <h2>LINE ID</h2>
    <p>@toyookayuto</p>

    <h2>How to save my contact</h2>
    <a href="#" class="button copy-save">Copy</a>
    <a href="#" class="button copy-save">Save</a>

    <div class="qr-section">
        <h2>QR Code</h2>
        <img src="qr_code_image_url" alt="QR Code" />
        <div class="instructions">
            <p>1. Open the LINE app.</p>
            <p>2. Tap on 'Add Friends'.</p>
            <p>3. Select 'QR Code'.</p>
            <p>4. Scan the QR code above.</p>
            <p>5. Add me as a friend!</p>
        </div>
    </div>
</body>
</html>
