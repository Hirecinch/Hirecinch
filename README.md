<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .container {
            display: flex;
            align-items: center; /* Vertically align content */
            justify-content: space-between; /* Create space between text and image */
        }

        .text {
            flex: 1; /* Allow the text to grow and take available space */
            padding: 20px;
        }

        .image {
            flex: 1; /* Allow the image to grow and take available space */
            padding: 20px;
        }

        /* Additional styles for image size */
        .image img {
            max-width: 100%; /* Ensure the image doesn't exceed the container width */
            height: auto; /* Maintain the aspect ratio of the image */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="text">
            <p>Your text goes here. You can add as much text as you need, and the container will adjust accordingly.</p>
        </div>
        <div class="image">
            <img src="your-image.jpg" alt="Your Image">
        </div>
    </div>
</body>
</html>
