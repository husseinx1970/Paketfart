<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paketfart - Snabbare än väntat</title>
    <style>
        /* Grundläggande styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }

        header {
            background-color: #000;
            text-align: center;
            padding: 50px 20px;
        }

        header img {
            max-width: 300px;
            height: auto;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #0073e6;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #005bb5;
        }

        section {
            padding: 40px 20px;
            text-align: center;
        }

        section h2 {
            color: #0073e6;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            color: white;
            background-color: #0073e6;
            text-decoration: none;
            border-radius: 5px;
        }

        .btn:hover {
            background-color: #005bb5;
        }

        /* Google Map styling */
        #map {
            width: 100%;
            height: 400px;
            margin-top: 20px;
        }

        /* Bildspel styling */
        #slideshow {
            position: relative;
            max-width: 600px;
            margin: 20px auto;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .slide {
            display: none;
        }

        .slide img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
    </style>
    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAmjJeFekLHc2v41GGiz-bxcoxGJDKx4pM"></script>
</head>
<body>
    <header>
        <img src="https://cvws-h2.icloud-content.com/B/AUYqWBM-p-T9h5p45MO6hqId6OQ7AfGjEwKYlErZDa5sfvbQvwdS9_DH/IMG_8956.JPEG?o=AhAfcd5lvzVfTpe_mmPS2NU5FZVVibjpfOjIPbbYCYXm&v=1&x=3&a=CAog0u2eRIMB248xPztgVxh1JE_kSOSOCL87sLvHdkGAZGMSbxDoguKkvjIY6N-9pr4yIgEAUgQd6OQ7WgRS9_DHaieP6c7lEUL4Ehnq0k52nWxc8Q4ZtbX-7Qh8-93SmOQqFvKITh87OBpyJ3tUMhv5ixalVS2nulYQuTxrbMbnosWlI2gA4A7hUTp7V32JMfBGXg&e=1734710620&fl=&r=7f1e9d0e-827e-4cbd-813a-0ad73ade096c-1&k=S3O6K5HTqD7NOUwO6kn6Uw&ckc=com.apple.photos.cloud&ckz=CMM-E95E9361-FC57-4095-A4BC-B493D90C553D&y=1&p=150&s=oERzHQq8pZ0EzuThchvXVs4s1kI" alt="Paketfart logotyp">
    </header>

    <nav>
        <a href="#tjanster">Tjänster</a>
        <a href="#om-oss">Om oss</a>
        <a href="#kontakt">Kontakt</a>
    </nav>

    <section id="tjanster">
        <h2>Våra tjänster</h2>
        <p>Vi erbjuder ett brett utbud av transporttjänster, inklusive snabba leveranser och säker hantering av paket.</p>
        
        <!-- Bildspel -->
        <div id="slideshow">
            <div class="slide">
                <img src="https://cvws-h2.icloud-content.com/B/AfYNZn-sqIeYQ2xsjgaLWCzXmB-iARtS-ReCVm5FqMVVGrqhFrlEwSwN/IMG_8962.JPEG?o=Au6gCJZA4O1M0u9dGfr7MFCX9GRP5HKWleMX7yNeNw1M&v=1&x=3&a=CAog5Vv4uO6z99Bp_kOAYQH0_3IS1DYN6nA8-5OJMbRdMrISbxCwuq-kvjIYsJeLpr4yIgEAUgTXmB-iWgREwSwNaifBowl31DAn6-mDd8xuGEu7HTVEqwhL1CxwOmycO35zK3zrbLcnn-FyJ6X9khE9WXH7oXptfDn9SUF7cfq9ZmUVOqX2SyD_X9IJvBhnKGpFwg&e=1734709791&fl=&r=5fe58eff-338d-4403-9ff8-423e7708f0d3-1&k=aASS7yT8COVDr5vJfDe6aQ&ckc=com.apple.photos.cloud&ckz=CMM-A9DDB19D-6FFF-40BC-A675-92C85289666D&y=1&p=150&s=Ct2U6y2TsWpozJMTX8DLEUislhI" alt="Bild 1">
            </div>
            <div class="slide">
                <img src="https://cvws-h2.icloud-content.com/B/AXmuUb4RL6INnUCk0Uoxd6RLX_dyAb4iKrxzZNnvwXdUUvrk46jHQruN/IMG_8963.PNG?o=Ap02wy7v31-MoIlJ4YDNbP_K7bO3WQJZPUSClutvKuR7&v=1&x=3&a=CAogpHmIlYd6RKkjytIdTsGzrY9l6-cg082VQATZWuPLv6wSbxCd1qykvjIYnbOIpr4yIgEAUgRLX_dyWgTHQruNaicLF2Wk_aII-bxAdhlOqx9TeL5FkYtvyL5tK_krQxxhrkz7IMpkwDlyJw3uNxM10guPbz8yyZKMkOiFWEz1lblUdFUlwwrGJMjBnB8hPbxVrA&e=1734709746&fl=&r=f6fe3c0f-011c-4831-b660-52a73c573a46-1&k=EHYu774ZICS2uuu-uWF4ow&ckc=com.apple.photos.cloud&ckz=CMM-73AF0733-2DD5-4DD3-8248-C6F63A0D32BE&y=1&p=150&s=52aNEzSOipCPy-U9-uwWALA30ho" alt="Bild 2">
            </div>
            <div class="slide">
                <img src="https://cvws-h2.icloud-content.com/B/AUW3f80CAdDmD5A_wh0-VrmNg355AZOTHJ2npg8coIpHmUBXhSg4YWg_/IMG_8965.JPEG?o=AvteyfWae1qkVQwGvApXr-wt6p4RU9b5_g1i_Y1syc37&v=1&x=3&a=CAogWoidwtgj7SfyYGNJo9SrEJnP7WmfYOOsb8X_B_gsW84SbxD7zqmkvjIY-6uFpr4yIgEAUgSNg355WgQ4YWg_aieb9hBr8wvE-AbKJ4ZD80L8lmOk9W4p3uE2Y2lLuwiRvO2iy_7mb4lyJ0Ze5oXqW_Va2TYGfok9oWNEK1y_Byf9Ec1NcYlUdlFUnLCtW8um0w&e=1734709695&fl=&r=4a81ce6c-9023-4c2d-a6f4-cedd1da6725c-1&k=YhzdHsVW47JtVqiFqK9bwA&ckc=com.apple.photos.cloud&ckz=CMM-95BFAD07-506C-463C-B0A1-8C59C2A1AF42&y=1&p=150&s=bJqvgNgNDIR6_kXOwq6QGsmKp2U" alt="Bild 3">
            </div>
        </div>
    </section>

    <section id="om-oss">
        <h2>Om oss</h2>
        <p>Paketfart är ett svenskt transportföretag som specialiserar sig på snabba och säkra leveranser. Vi når alla delar av Sverige med pålitlig service.</p>
    </section>

    <section id="kontakt">
        <h2>Kontakta oss</h2>
        <p>E-post: <a href="mailto:info@paketfart.se">info@paketfart.se</a></p>
        <p>Telefon: +46 790574975</p>
        <div id="map"></div>
    </section>

    <footer>
        <p>&copy; 2024 Paketfart. Alla rättigheter förbehållna.</p>
    </footer>

    <script>
        function initMap() {
            const location = { lat: 57.740508, lng: 12.078441 };
            const map = new google.maps.Map(document.getElementById("map"), {
                zoom: 15,
                center: location,
            });
            const marker = new google.maps.Marker({
                position: location,
                map: map,
            });
        }
        window.onload = initMap;

        let currentSlide = 0;
        const slides = document.querySelectorAll('.slide');

        function showSlide(index) {
            slides.forEach((slide, i) => {
                slide.style.display = i === index ? 'block' : 'none';
            });
        }

        function nextSlide() {
            currentSlide = (currentSlide + 1) % slides.length;
            showSlide(currentSlide);
        }

        setInterval(nextSlide, 5000);

        // Google Maps
        function initMap() {
            const location = { lat: 57.740508, lng: 12.078441 };
            const map = new google.maps.Map(document.getElementById("map"), {
                zoom: 

15,  
                center: location,  
            });  
            new google.maps.Marker({  
                position: location,  
                map: map,  
            });  
        }  

        window.onload = initMap;  
    </script>  
    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAmjJeFekLHc2v41GGiz-bxcoxGJDKx4pM"></script>  
</body>  
</html>  
