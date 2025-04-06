<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Bucket List</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://kit.fontawesome.com/YOUR-FONT-AWESOME-CODE.js" crossorigin="anonymous"></script>
</head>
<body>
    <div class="container">
        <header>
            <h1>My Personal Bucket List</h1>
            <p>A collection of dreams and goals I want to achieve!</p>
        </header>
        <section class="bucket-list">
            <div class="category">
                <h2><i class="fas fa-plane"></i> Travel</h2>
                <ul>
                    <li><i class="fas fa-check-circle"></i> Visit Japan</li>
                    <li><i class="fas fa-check-circle"></i> See the Northern Lights</li>
                    <li><i class="fas fa-check-circle"></i> Explore Machu Picchu</li>
                </ul>
            </div>
            <div class="category">
                <h2><i class="fas fa-lightbulb"></i> Skills</h2>
                <ul>
                    <li><i class="fas fa-star"></i> Learn a new language</li>
                    <li><i class="fas fa-star"></i> Master photography</li>
                    <li><i class="fas fa-star"></i> Play the guitar</li>
                </ul>
            </div>
            <div class="category">
                <h2><i class="fas fa-heart"></i> Life Goals</h2>
                <ul>
                    <li><i class="fas fa-check-circle"></i> Buy a dream house</li>
                    <li><i class="fas fa-check-circle"></i> Start a charity</li>
                    <li><i class="fas fa-check-circle"></i> Write a book</li>
                </ul>
            </div>
        </section>
    </div>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        .container {
            max-width: 600px;
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            margin-top: 20px;
        }
        header {
            text-align: center;
        }
        .bucket-list .category {
            margin-bottom: 20px;
        }
        .category h2 {
            background: #ff9800;
            color: white;
            padding: 10px;
            border-radius: 5px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            background: #fff3e0;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
            display: flex;
            align-items: center;
        }
        li i {
            margin-right: 10px;
            color: #ff9800;
        }
        @media (max-width: 600px) {
            .container {
                width: 90%;
            }
        }
    </style>
</body>
