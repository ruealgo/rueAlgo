<!-- <!DOCTYPE html> -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Retail Website</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        header {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .header-image {
            width: 100%;
            height: 43vh;
            object-fit: cover;
            object-position: center 47%; /* Adjusted for your specific needs */
        }
        h1 {
            text-align: center;
            color: #333;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #333;
        }
        /* Add styles for your map container */
        .map-container {
            width: 100%;
            height: 400px; /* Adjust the height as needed */
        }
    </style>
</head>
<body>

<header>
    <img src="photo2.jpg" alt="Office with people working" class="header-image">
    <h1>Welcome to My Retail Website</h1>
    <nav>
        <ul>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- Your website content -->
<p>Our deep expertise in online retail and global market insight empower us to effectively manage and sell products, ensuring optimal pricing, strategic placement, and targeted consumer reach.</p>
<p>Trusted by brands across the spectrum, we uphold price and brand integrity, safeguard online reputations, and drive sales growth.</p>
<p>We work closely with supply chain partners, facilitating their journey towards success in the realm of online retail.</p>

<!-- Map Section -->
<div class="map-container">
    <!-- Replace the src attribute's URL with your actual map iframe URL -->
<!--    <iframe src="https://www.google.ca/maps/place/71+Duke+St,+Montreal,+QC+H3C+0L6/@45.4961477,-73.5549447,17z/" frameborder="0" style="border:0; width: 100%; height: 100%;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>  -->

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2796.691951497211!2d-73.5549447!3d45.4961477!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4cc91af5718d4c33%3A0xf8210e1930cf408d!2s71%20Duke%20St%2C%20Montreal%2C%20QC%20H3C%200L6!5e0!3m2!1sen!2sca!4v1712811276486!5m2!1sen!2sca" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>

</body>
</html>
