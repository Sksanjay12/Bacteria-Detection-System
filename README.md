This is a webpage to show the bacteria level, Purity level and Water level in a particular residential area.
 <!DOCTYPE html>
 <html lang="en" public="file:///C:/Users/sksan/OneDrive/Documents/HTML%20webpage.html">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karpagam Institute of Technology</title>
    <style>
        /* Add styles here */
        .ticker {
            background-color: #333;
            color: #fff;
            padding: 10px;
            font-size: 18px;
            font-weight: bold;
            overflow: hidden;
        }
        .ticker marquee {
            margin: 0;
            padding: 0;
        }
    </style>
 </head>
 <body>
    <div class="ticker">
        <marquee behavior="scroll" direction="left">
            Breaking News: Karpagam Institute of Technology launches new courses! 
            Admissions open for 2024 batch! 
            Scholarships available for meritorious students!
        </marquee>
    </div>
    <h1>Karpagam Institute of Technology</h1>
    <!-- Rest of the website content -->
    <script>
        // No JavaScript required for this example
    </script>
</body>
</html>





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bacteria Detector</title>
    <style>
        /* Add styles here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .title-page {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        .home-page {
            margin-top: 50px;
            padding: 20px;
        }
    </style>
</head>
<body>
    <!-- Title Page -->
    <div class="title-page">
        <h1>Bacteria Detector</h1>
        <p>Real-time Data</p>
    </div>

    <!-- Home Page -->
    <div class="home-page" text-align="center">
        <h2>Welcome to our web page</h2>
        <p>Seerapalayam Municipal Drinking Water Bacterial Testing and Purifying System.</p>
        <button>Learn More</button>
    </div>
</body>
</html>



<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3917.7279769191036!2d76.97599437267927!3d10.908265956752887!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3ba85ae942396eef%3A0xf18c9eb8f29896d8!2sKarpagam%20Institute%20of%20Technology!5e0!3m2!1sen!2sin!4v1727431055425!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electrochemical Biosensor</title>
    <style>
        /* Add styles here */
    </style>
</head>
<body>
    <h1>Bacteria Detector</h1>
    <h2>Real-time Data</h2>
    <div class="data-container">
        <div class="location-data" text-align="center">
            <h3>Location:</h3>
            <p id="longitude">Longitude: 0° 0' 0"</p>
            <p id="latitude">Latitude: 0° 0' 0"</p>
            <p id="Purity Level">Purity Level: 927 CFU/mL</p>
        </div>
        <div class="radar-data">
            <h3>Bacteria Data:</h3>
            <p id="Water Level">Water Level: 6457 litres.</p>
            <p id="Water Level">Bacteria Level: 1 MPN/100ml</p>
        </div>
    </div>
    <h1>Karpagam Institute of Technology</h1>
    <script>
        // Simulate real-time data updates
        setInterval(() => {
            const longitude = Math.floor(Math.random() * 180) + '° ' + Math.floor(Math.random() * 60) + '\' ' + Math.floor(Math.random() * 60) + '"';
            const latitude = Math.floor(Math.random() * 180) + '° ' + Math.floor(Math.random() * 60) + '\' ' + Math.floor(Math.random() * 60) + '"';
            const altitude = Math.floor(Math.random() * 10000) + ' meters';
            const dopplerValue = Math.floor(Math.random() * 100) + ' m/s';
            const radarValue = Math.floor(Math.random() * 100) + ' dBm';
            document.getElementById('longitude').innerHTML = 'Longitude: ' + longitude;
            document.getElementById('latitude').innerHTML = 'Latitude: ' + latitude;
            document.getElementById('altitude').innerHTML = 'Altitude: ' + altitude;
            document.getElementById('doppler-value').innerHTML = 'Doppler Value: ' + dopplerValue;
            document.getElementById('radar-value').innerHTML = 'Radar Value: ' + radarValue;
        }, 1000); // Update every 1 second
    </script>
