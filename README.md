<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Women Safety Awareness</title>
</head>
<body>

<!-- Main Table Layout -->
<table width="100%" cellpadding="10" cellspacing="0" border="0">
  <tr>

    
    <td width="25%" bgcolor="#E91E63" valign="top" align="center">
      <img src="women-safety-awareness.png" alt="Safety Logo" width="150" height="150" style="border-radius:50%;"><br><br>
      <h2>Safety Awareness</h2>
    </td>

    <!-- Right Pane: Content -->
    <td width="75%" valign="top">

      <!-- Welcome Section -->
      <h2>Welcome</h2>
      <p>Welcome to the Women’s Safety Awareness portal. Learn practical safety tips, emergency contacts, and helpful resources to stay safe.</p>
      <hr>

      <h2>Safety Tips</h2>
      <ul>
        <li>Always share your location with family or friends.</li>
        <li>Avoid walking alone in dark or isolated areas.</li>
        <li>Keep your phone charged and accessible.</li>
        <li>Trust your instincts and avoid risky situations.</li>
        <li>Learn basic self-defense techniques.</li>
      </ul>
      <hr>

      <h2>Emergency Contacts</h2>
      <ul>
        <li>Local Police: 100</li>
        <li>Women Police Helpline: 1901</li>
        <li>National Emergency Number: 112</li>
        <li>National Women Helpline: 181</li>
      </ul>
      <hr>

      <h2>Resources</h2>
      <ul>
        <li><a href="https://www.unwomen.org" target="_blank">UN Women – Global Resources</a></li>
        <li><a href="https://womenshelpline.org" target="_blank">Women Helpline Info</a></li>
        <li><a href="https://www.womensafety.gov.in" target="_blank">India Women Safety Portal</a></li>
      </ul>
      <hr>

      
      <h2>Contact Me</h2>
      <p>Email: anilgiri36@gmail.com</p>
      <p>WhatsApp: <a href="https://wa.me/918379008152?text=Hello%20I%20want%20to%20learn%20more%20about%20women%20safety" target="_blank">📱 Send WhatsApp Message</a></p>

    </td>
  </tr>
</table>

<select onchange="setLang(this.value)">
  <option value="en">English</option>
  <option value="hi">Hindi</option>
  <option value="mr">Marathi</option>
</select>

<h3 id="welcome"></h3>
<p id="desc"></p>
<ul id="tips"></ul>
<p id="contact"></p>

<script>
const texts = {
  en:{
    welcome:"Welcome",
    desc:"Learn safety tips and emergency contacts.",
    tips:["Share location with family","Avoid dark isolated areas","Keep phone charged"],
    contact:"Email: anilgiri36@gmail.com | WhatsApp: <a href='https://wa.me/918379008152'>📱 Message</a>"
  },
  hi:{
    welcome:"स्वागत है",
    desc:"सुरक्षा टिप्स और आपातकालीन संपर्क जानें।",
    tips:["परिवार के साथ लोकेशन साझा करें","अंधेरी जगहों से बचें","फोन चार्ज रखें"],
    contact:"ईमेल: anilgiri36@gmail.com | व्हाट्सएप: <a href='https://wa.me/918379008152'>📱 संदेश</a>"
  },
  mr:{
    welcome:"स्वागत आहे",
    desc:"सुरक्षा टिप्स आणि आपत्कालीन संपर्क जाणून घ्या.",
    tips:["कुटुंबासोबत स्थान शेअर करा","अंधाऱ्या ठिकाणांपासून दूर राहा","फोन चार्ज ठेवा"],
    contact:"ईमेल: anilgiri36@gmail.com | व्हाट्सएप: <a href='https://wa.me/918379008152'>📱 संदेश</a>"
  }
};

function setLang(lang){
  document.getElementById("welcome").innerText = texts[lang].welcome;
  document.getElementById("desc").innerText = texts[lang].desc;
  document.getElementById("tips").innerHTML = texts[lang].tips.map(t=>`<li>${t}</li>`).join("");
  document.getElementById("contact").innerHTML = texts[lang].contact;
}

// Initialize default language
setLang('en');
</script>


 <footer style="margin: 20px 0; color: gray;">
 <p>© 2026 Anil Giri. All rights reserved.</p>
</footer>

 <marquee><b style="color: green;">A page created by Anil Giri</b></marquee>

</body>
</html>
