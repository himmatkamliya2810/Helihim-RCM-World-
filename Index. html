
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Helihim RCM World</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header, footer { background-color: #0074D9; color: white; padding: 15px; text-align: center; }
        nav { background-color: #f4f4f4; padding: 10px; text-align: center; }
        nav a { margin: 0 15px; text-decoration: none; color: #333; font-weight: bold; }
        section { padding: 20px; }
        .language-selector { position: absolute; top: 10px; right: 10px; }
    </style>
</head>
<body>
    <header>
        <h1>Helihim RCM World</h1>
        <div class="language-selector">
            <select onchange="changeLanguage(this.value)">
                <option value="en">English</option>
                <option value="hi">हिन्दी</option>
                <option value="gu">ગુજરાતી</option>
            </select>
        </div>
    </header><nav>
    <a href="#home" data-key="home">Home</a>
    <a href="#about" data-key="about">About</a>
    <a href="#products" data-key="products">Products</a>
    <a href="#contact" data-key="contact">Contact</a>
</nav>

<section id="home">
    <h2 data-key="home">Welcome to Helihim RCM World</h2>
    <p data-key="home_desc">Your trusted network marketing partner for health and wellness products.</p>
</section>

<section id="about">
    <h2 data-key="about">About Us</h2>
    <p data-key="about_desc">Helihim RCM World is committed to empowering individuals through business and quality products.</p>
</section>

<section id="products">
    <h2 data-key="products">Our Products</h2>
    <p data-key="products_desc">We offer a wide range of health, wellness, and personal care products. Online ordering coming soon!</p>
</section>

<section id="contact">
    <h2 data-key="contact">Contact Us</h2>
    <p data-key="contact_desc">Reach out via email or phone. We’re here to help you grow with us!</p>
</section>

<footer>
    <p>&copy; 2025 Helihim RCM World. All rights reserved.</p>
</footer>

<script>
    const translations = {
        hi: {
            home: "होम",
            home_desc: "आपका भरोसेमंद नेटवर्क मार्केटिंग साथी स्वास्थ्य और वेलनेस उत्पादों के लिए।",
            about: "हमारे बारे में",
            about_desc: "हेलीहिम आरसीएम वर्ल्ड का लक्ष्य लोगों को व्यापार और गुणवत्तापूर्ण उत्पादों के माध्यम से सशक्त बनाना है।",
            products: "उत्पाद",
            products_desc: "हम स्वास्थ्य, वेलनेस और व्यक्तिगत देखभाल उत्पादों की विस्तृत श्रृंखला पेश करते हैं। ऑनलाइन ऑर्डरिंग जल्द ही आ रही है!",
            contact: "संपर्क करें",
            contact_desc: "ईमेल या फोन के माध्यम से संपर्क करें। हम आपकी सफलता में सहायता के लिए यहां हैं!"
        },
        gu: {
            home: "હોમ",
            home_desc: "તમારો વિશ્વાસૂ નેટવર્ક માર્કેટિંગ ભાગીદાર આરોગ્ય અને વેલનેસ ઉત્પાદનો માટે.",
            about: "અમારા વિશે",
            about_desc: "હેલીહિમ આરસીએમ વર્લ્ડ લોકો ને વ્યાપાર અને ગુણવત્તાવાળા ઉત્પાદનો દ્વારા સશક્ત બનાવે છે.",
            products: "ઉત્પાદનો",
            products_desc: "અમે આરોગ્ય, વેલનેસ અને પર્સનલ કેર ઉત્પાદનો ની વિશાળ શ્રેણી પ્રદાન કરીએ છીએ. ઑનલાઇન ઓર્ડરિંગ ઝડપથી આવી રહી છે!",
            contact: "સંપર્ક કરો",
            contact_desc: "ઇમેઇલ અથવા ફોન દ્વારા અમારો સંપર્ક કરો. અમે તમારી સફળતામાં મદદ કરવા અહીં છીએ!"
        }
    };

    function changeLanguage(lang) {
        const keys = document.querySelectorAll('[data-key]');
        keys.forEach(el => {
            const key = el.getAttribute('data-key');
            if (translations[lang] && translations[lang][key]) {
                el.innerText = translations[lang][key];
            }
        });
    }
</script>

</body>
</html>
