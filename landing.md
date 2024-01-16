---
title: Kursinformationen
layout: landing
description: <p>Yoga für Erwachsene</p><p>Yoga für Teenager</p><p>Fragen & Anmeldungen:yoga.bei.verena@gmail.com oder unter 05144/560670</p>
image: assets/images/Yoga_für_Teeanger_new2.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- Add Swiper CSS -->
    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css">


<style>
	body {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

	.container {
        display: flex;
        flex-wrap: wrap; /* Allow items to wrap to the next line on small screens */
        justify-content: space-between; /* Space the divs evenly */
        max-width: 1500px; /* Set a maximum width for the container */
        margin: 5px auto; /* Center the container on the page with some margin */
    }

        /* Style for each div */
    .box {
        box-sizing: border-box;
        width: 48%; /* Set the width of each div, leaving some space for margin */
        padding: 5px;
        margin: 2px; /* Add a small margin between divs */
        border: 1px solid #ccc; /* Add a border for better visibility */
    }

	.swiper-container {
        width: 50%; /* Set maximum width to 75% */
        margin: auto; /* Center the container */
		height: 500px;
		overflow: hidden;
        margin-bottom: 5px;
    }

    .swiper-slide img {
        width: 100%;
        height: auto; /* Make the height responsive while maintaining aspect ratio */
        max-height: 500px; /* Set a maximum height to prevent images from becoming too large */
        object-fit: cover;
    }

	.swiper-pagination {
            position: absolute;
            bottom: 10px;
            left: 50%;
            transform: translateX(-50%);
    }
/* Media query for smaller screens */
    @media (max-width: 600px) {
        .swiper-container {
            width: 70%; /* Adjust width for smaller screens */
            margin: auto;
            margin-bottom: 5px;
        }
    }

/* Optional: Remove margin for small screens */
    @media (max-width: 400px) {
        body {
            margin-bottom: 0;
        }
    }

 /* Styling for the independent image */
    .independent-image {
        position: absolute; /* Set position to absolute */
        top: 70%; /* Center vertically */
        left: 45%; /* Center horizontally */
        transform: translate(-50%, -50%); /* Center the image precisely */
        max-width: 50%;
        height: auto; /* Maintain aspect ratio */
        max-height: 60vh; /* Set a maximum height relative to the viewport */
        width: auto; /* Allow the width to adjust based on the height */
    }

 /* Media query for smaller screens */
    @media (max-width: 400px) {
        .independent-image {
            max-height: 60vh; /* Adjust maximum height for smaller screens */
            max-width: 50%; /* Adjust maximum width for smaller screens */
        }
    }

 </style>

 <body>
    <div class="container">
        <!-- First div -->
        <div class="box">
            <h2>Yoga für Erwachsene</h2>
			<p>Informationen zu Räumlichkeiten und Zeit folgen in Kürze</p><p>Kurs: 10 Einheiten à 75 min. für Euro 150,-</p>
            <p>Hatha Yoga ist eine Jahrtausende alte Technik, die Körper, Geist und Seele harmonisiert.
			Klassische Yogastellungen (Asanas), sanfte Atemübungen, Entspannungs- und Meditationstechniken  und Wahrnehmungsschulung fördern gleichzeitig Stärke und Flexibilität, schenken Ausgeglichenheit, führen zu mehr Vitalität und schulen die Konzentrationsfähigkeit.
			Die Yogastunden sind für Anfänger und Fortgeschrittene gleichermaßen geeignet. Yoga zu praktizieren bedeutet, sich Zeit für sich zu nehmen. Hier gibt es keinen Leistungsvergleich, jeder Mensch ist einzigartig. Yoga lehrt uns, eins zu sein mit sich, seine Grenzen wahrzunehmen und auszudehnen, auch in der Anspannung zu entspannen. Ganz nach dem Motto: „Alles kann, nichts muss“. Dadurch wird Stress abgebaut, innere Ruhe empfunden, ein klarer Geist entwickelt und frische Energie aufgebaut.
			Nutze diese Möglichkeiten für dich und komme vorbei - ich freue mich auf dich!</p>
			<p>Der Kurs ist von den Krankenkassen als Präventionskurs zertifiziert und wird dementsprechend bezuschusst.</p>
        </div>
        <!-- Second div -->
        <div class="box">
            <h2>Yoga für Teenager</h2>
			<p>Für alle zwischen 13 und 17 Jahren</p><p>Kurs: 10 Einheiten à 60 min. für Euro 110,-</p>
            <p>Yoga tut dem Körper und der Seele gut - in jedem Alter!
			Aber gerade für Teenager kann Yoga eine große Unterstützung sein.
			Denn Yoga ist kein Wettbewerb. Hier geht es nicht darum, sich mit anderen zu vergleichen. Im Yoga geht es ausschließlich um dich selbst.
			Jeder Körper ist einzigartig, auch in seinen Fähigkeiten.
			Durch kräftigende und dehnende Körperübungen wird der gesamte Körper mobilisiert und die Körperaufrichtung gestärkt. Neue Bewegungsmuster sind gut für das Gehirn und fördern den sich im Wachstum befindlichen Körper. Durch Körperwahrnehmung wird das eigene Wohlfühlen und Sorgen für den Körper gefördert.
			Sanfte Atemübungen, Meditation und Entspannung können Stress verringern.
			Yoga kann auch eine prima Ergänzung für andere Sportarten sein, denn es fördert die Fähigkeit zur Konzentration, Fokussierung und Achtsamkeit. Fähigkeiten, die auch im Schulalltag oder bei anderen Herausforderungen eines Teenager-Lebens eine große Hilfe darstellen.
			Yoga bildet also einen Grundstein für ein zufriedenes Leben als selbstbewusster Mensch - und macht dazu noch richtig viel Spaß!
			Neugierig geworden? Dann komm vorbei! </p>
        </div>
    </div>

<!-- Independent Image -->
<img class="independent-image" src="assets/images/ybv7.png" alt="Independent Image">

<!-- Swiper -->
<div class="swiper-container">
    <div class="swiper-wrapper">
        <!-- Add your images here -->
        <div class="swiper-slide"><img src="assets/images/ybv5-ezgif.com-jpg-to-webp-converter.webp" alt="ybv2"></div>
        <div class="swiper-slide"><img src="assets/images/ybv3-ezgif.com-jpg-to-webp-converter.webp" alt="ybv3"></div>
    	<!-- Add more slides as needed -->
    </div>
</div>

<!-- Add Swiper JS -->
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
<!-- Initialize Swiper -->
<script>
    var swiper = new Swiper('.swiper-container', {
        slidesPerView: 1,
        spaceBetween: 10,
        autoplay: {
            delay: 3000, // Set the delay between slides in milliseconds (3 seconds in this example)
            disableOnInteraction: false, // Continue autoplay even when the user interacts with the swiper
        },
        pagination: {
            el: '',
        },
    });
</script>

<center>
	<p>Fragen & Anmeldungen: yoga.bei.verena@gmail.com oder unter 05144/560670</p>
</center>
</body>


