# Ex.08 Design of Interactive Image Gallery
## Date:24/12/2024

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>6 Star Images Page</title>

    <style>
        /* Apply custom font and background styles */
        body {
            font-family: Arial, sans-serif; /* Using a basic system font */
            margin: 0;
            padding: 0;
            background-color: #f5deb3; /* Light Gold Background Color */
            color: #fff;
            text-align: center;
            min-height: 100vh; /* Ensures the body covers full viewport height */
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        /* Header styling */
        h1 {
            font-size: 2.5rem;
            color: #fff;
            margin-top: 50px;
            font-weight: 700;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7); /* Shadow for better text visibility on the background */
        }

        /* Title above the star images */
        .title {
            background-color: #007BFF; /* Blue background for the title */
            color: #fff;
            padding: 20px;
            font-size: 2rem;
            font-weight: bold;
            margin-top: 20px;
            text-align: center;
            border-radius: 5px;
        }

        /* Container to hold the star images */
        .container {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin-top: 40px;
            flex-wrap: wrap;
        }

        /* Individual star styles */
        .star {
            margin: 20px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            padding: 10px;
            background-color: rgba(255, 255, 255, 0.7); /* Semi-transparent white background for the stars */
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            width: 300px; /* Set a larger size for each image */
            text-align: center;
        }

        /* Make image rectangular with no border */
        .star img {
            width: 100%; /* Make the image fill the width of the container */
            height: 200px; /* Fixed height for rectangular shape */
            object-fit: cover; /* Ensures the image covers the container area */
        }

        /* Star name styling */
        .star-name {
            margin-top: 10px;
            font-size: 1.2rem;
            font-weight: 600;
            color: #007BFF; /* Blue color for the star names */
        }

        /* Hover effect for each star image */
        .star:hover {
            transform: scale(1.1);
            box-shadow: 0 12px 20px rgba(0, 0, 0, 0.3);
        }

        /* Footer styling */
        footer {
            background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent black background */
            color: #fff;
            padding: 15px;
            position: relative;
            bottom: 0;
            width: 100%;
            text-align: center;
            font-size: 1rem;
            font-weight: 600;
        }

        footer span {
            font-size: 0.9rem;
            font-weight: normal;
        }

        /* Responsiveness: Center images on smaller screens */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .star img {
                width: 100%;
                height: 150px; /* Adjust the height for small screens */
            }
        }
    </style>
</head>
<body>

    <!-- Title Section at the top -->
    <div class="title">
        Welcome to the 6 Star Gallery
    </div>

    <h1>6 Star Images</h1>

    <div class="container">
        <div class="star">
            <img src="a1.png" alt="Star 1"> <!-- Replace with your image path -->
            <div class="star-name">Star 1</div>
        </div>
        <div class="star">
            <img src="a2.png" alt="Star 2"> <!-- Replace with your image path -->
            <div class="star-name">Star 2</div>
        </div>
        <div class="star">
            <img src="a3.png" alt="Star 3"> <!-- Replace with your image path -->
            <div class="star-name">Star 3</div>
        </div>
        <div class="star">
            <img src="a4.png" alt="Star 4"> <!-- Replace with your image path -->
            <div class="star-name">Star 4</div>
        </div>
        <div class="star">
            <img src="a7.png" alt="Star 5"> <!-- Replace with your image path -->
            <div class="star-name">Star 5</div>
        </div>
        <div class="star">
            <img src="a6.png" alt="Star 6"> <!-- Replace with your image path -->
            <div class="star-name">Star 6</div>
        </div>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 <span>Developed and Designed by Aaron Alex</span></p>
    </footer>

</body>
</html>


```

## OUTPUT:

![image](https://github.com/user-attachments/assets/22edd4ad-a669-4a4a-9969-04e6c78040be)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
