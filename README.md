<!-- <!DOCTYPE html>  -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>rueAlgo</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
        }
        header {
            display: block;
            text-align: center;
        }
        .header-image {
            width: 100%;
            height: 40vh;
            object-fit: cover;
            object-position: center 48%;
        }
        h1 {
            text-align: center;
            color: #4a80f5;
            padding-top: 20px;
            font-weight: 800; /* Add font-weight property */
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
        .map-container {
            display: flex;
            width: 60%; /* Set width to 80% */
            margin: 0 auto; /* Center the container horizontally */
            height: calc(100vh - 63vh);
            margin-top: -1px;
        }
        .map-container iframe {
            width: 60%;
            height: 100%;
            border: none;
        }
        .map-content {
            width: 40%;
            padding: 20px;
            font-family: 'Arial', sans-serif;
            text-align: center;
#            font-size: 24px; /* Increase font size */
        }
        .map-content span {
            color: #4a80f5; /* Change color of "Contact us" */
            font-weight: 700; /* Add font-weight property */
    	    font-size: 28px; /* Increase font size */
    	    margin-bottom: 20px; /* Add space below the text */ 
       }
        .website-content {
            text-align: center;
            margin-bottom: 60px;
        }
        body {
            margin-bottom: 0;
            padding-bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <img src="photo2.jpg" alt="Office with people working" class="header-image">
    <h1>Online Retail of Name Brand Products</h1>
</header>

<!-- Your website content -->
<div class="website-content">    
    <p>Our deep expertise in online retail and global market insight empower us to effectively manage and sell products, ensuring optimal pricing, strategic placement, and targeted consumer reach.</p>
    <p>Trusted by brands across the spectrum, we uphold price and brand integrity, safeguard online reputations, and drive sales growth.</p>
    <p>We work closely with supply chain partners, facilitating their journey towards success in the realm of online retail.</p>
</div>

<!-- Map Section -->
<div class="map-container">
    <!-- Left side: Google Maps embed -->
    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2796.691951497211!2d-73.5549447!3d45.4961477!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4cc91af5718d4c33%3A0xf8210e1930cf408d!2s71%20Duke%20St%2C%20Montreal%2C%20QC%20H3C%200L6!5e0!3m2!1sen!2sca!4v1712811276486!5m2!1sen!2sca" frameborder="0" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    <!-- Right side: Text content -->
    <div class="map-content">
        <span>Contact us</span> <!-- Wrap "Contact us" in span element -->
        <p>9475-1898 Quebec Inc.</p>
        <p>404-71 Duke St., Montreal, QC H3C 0L5</p>
	<p><a href="https://wa.me/16135018255">+1-613-501 8255</a></p> <!-- Add WhatsApp link to the phone number -->
	<p><a href="mailto:ruealgo@mail.com">ruealgo@mail.com</a></p> 

<!--    <form action="mailto:ruealgo@mail.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Your Name">
        <input type="text" name="email" placeholder="Your Email">
        <textarea name="message" placeholder="Your Message"></textarea>
        <input type="submit" value="Send">
    </form>
-->
    </div>
</div>


</body>
</html>
