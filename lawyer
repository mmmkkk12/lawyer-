<!DOCTYPE html><html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>עו"ד יפה אודל</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f9f9f9;
            direction: rtl;
            text-align: center;
        }
        header {
            border: 5px solid gold;
            margin: 20px;
            padding: 20px;
            border-radius: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }
        header h1 {
            margin: 0;
            font-size: 36px;
            color: #333;
        }
        header p {
            font-size: 20px;
            color: #666;
            margin-top: 10px;
        }
        header .address {
            margin-top: 10px;
            font-size: 18px;
            color: #444;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            margin: 20px;
        }
        .service-box {
            background: white;
            border: 2px solid gold;
            padding: 30px 10px;
            border-radius: 15px;
            font-size: 20px;
            font-weight: bold;
            color: #333;
            cursor: pointer;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
            transition: 0.3s;
        }
        .service-box:hover {
            transform: scale(1.05);
            box-shadow: 0 0 15px rgba(0,0,0,0.3);
        }
        .service-box.active {
            background-color: gold;
            color: white;
        }
        .contact-methods {
            display: none;
            margin: 30px auto;
        }
        .contact-method {
            margin: 10px;
            padding: 20px;
            border-radius: 10px;
            color: white;
            font-size: 20px;
            font-weight: bold;
            text-decoration: none;
            display: block;
        }
        .phone { background-color: #007BFF; }
        .whatsapp { background-color: #25D366; }
        .email { background-color: #FF3B30; }
        footer {
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>עו"ד יפה אודל</h1>
        <p>מתמחה בתחום הנדל"ן, ענייני משפחה, ייפוי כוח מתמשך, מכתבי התראה</p>
        <div class="address">אברבנאל 3, חולון</div>
    </header><div class="services">
    <div class="service-box" onclick="showContact(this, 'חוזה מכירה')">חוזה מכירה</div>
    <div class="service-box" onclick="showContact(this, 'חוזה קנייה')">חוזה קנייה</div>
    <div class="service-box" onclick="showContact(this, 'חוזה השכרה')">חוזה השכרה</div>
    <div class="service-box" onclick="showContact(this, 'צוואה')">צוואה</div>
    <div class="service-box" onclick="showContact(this, 'ירושה')">ירושה</div>
    <div class="service-box" onclick="showContact(this, 'ייפוי כוח מתמשך')">ייפוי כוח מתמשך</div>
    <div class="service-box" onclick="showContact(this, 'מכתב התראה')">מכתב התראה</div>
    <div class="service-box" onclick="showContact(this, 'ענייני משפחה')">ענייני משפחה</div>
</div>

<div id="contactMethods" class="contact-methods">
    <h2>לקבלת הצעת מחיר ב:</h2>
    <a id="phoneLink" class="contact-method phone" href="#">טלפון</a>
    <a id="whatsappLink" class="contact-method whatsapp" href="#">וואצאפ</a>
    <a id="emailLink" class="contact-method email" href="#">מייל</a>
</div>

<footer>
    <h2>ליצירת קשר ב:</h2>
    <a class="contact-method phone" href="tel:0526245202">טלפון</a>
    <a class="contact-method whatsapp" href="https://wa.me/972526245202">וואצאפ</a>
    <a class="contact-method email" href="mailto:yafitkata26@gmail.com">מייל</a>
</footer>

<script>
    function showContact(element, service) {
        document.querySelectorAll('.service-box').forEach(function(box){
            box.classList.remove('active');
        });
        element.classList.add('active');
        document.getElementById('contactMethods').style.display = 'block';

        document.getElementById('phoneLink').href = 'tel:0526245202';
        document.getElementById('whatsappLink').href = 'https://wa.me/972526245202?text=' + encodeURIComponent('הי אשמח לקבל הצעת מחיר ל' + service);
        document.getElementById('emailLink').href = 'mailto:yafitkata26@gmail.com?subject=%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8&body=' + encodeURIComponent('הי אשמח לקבל הצעת מחיר ל' + service);
    }
</script>

</body>
</html>
