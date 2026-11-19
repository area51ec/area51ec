<!-- markdownlint-disable MD033 -->

<div align="center">

<img src="assets/header.svg" alt="Area51 · Security Research" width="100%">

![Typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&pause=2000&color=3DDC97&center=true&vCenter=true&width=640&height=40&lines=Breaking+auth+libraries+in+isolated+labs;Coordinated+disclosure+with+maintainers;Wi-Fi+%E2%80%A2+BLE+%E2%80%A2+IoT+%E2%80%A2+3G%2F4G%2F5G;Curious+about+how+things+fail)

[![Email](https://img.shields.io/badge/Email-info@area51.ec-0B2A22?style=flat-square&logo=gmail&logoColor=3DDC97)](mailto:info@area51.ec)
![Location](https://img.shields.io/badge/Guayaquil-Ecuador-134E3F?style=flat-square&logo=googlemaps&logoColor=C8F5E1)
![Disclosure](https://img.shields.io/badge/Disclosure-Coordinated-1F7A62?style=flat-square&logo=letsencrypt&logoColor=C8F5E1)

</div>

---

<div align="center">
  <h2>⌁ Whoami</h2>
</div>

<div align="center">

**Joseph Páez** — security researcher and technology tinkerer from Ecuador.
I build isolated labs, reproduce issues in authentication libraries for Node.js (JWT, OAuth2, Passport),
and report them to maintainers and vendors through coordinated disclosure. Labs go public once a fix is out.
Trained in telecommunications engineering, I explore networks and radio (Wi-Fi, Bluetooth/BLE, IoT, mobile networks)
and how they come together in smart cities.

</div>

---

<div align="center">
  <h2>⌁ Signal Scan</h2>
</div>

<div align="center">
<img src="assets/signal.svg" alt="Signal scan: JWT, OAuth2, Passport, Wi-Fi, BLE, ESP32, 3G/4G/5G, MikroTik" width="760">
</div>

<div align="center">

| Band | On my radar |
| :---: | :---: |
| Auth & AppSec | ![JWT](https://img.shields.io/badge/JWT-04110D?style=flat-square&logo=jsonwebtokens&logoColor=3DDC97) ![OAuth2](https://img.shields.io/badge/OAuth2-0B2A22?style=flat-square&logo=auth0&logoColor=3DDC97) ![Node.js](https://img.shields.io/badge/Node.js-134E3F?style=flat-square&logo=nodedotjs&logoColor=C8F5E1) |
| Web | ![HTML5](https://img.shields.io/badge/HTML5-04110D?style=flat-square&logo=html5&logoColor=3DDC97) ![CSS3](https://img.shields.io/badge/CSS3-0B2A22?style=flat-square&logo=css&logoColor=3DDC97) ![JavaScript](https://img.shields.io/badge/JavaScript-134E3F?style=flat-square&logo=javascript&logoColor=C8F5E1) ![PHP](https://img.shields.io/badge/PHP-04110D?style=flat-square&logo=php&logoColor=3DDC97) ![Laravel](https://img.shields.io/badge/Laravel-0B2A22?style=flat-square&logo=laravel&logoColor=3DDC97) ![Vue](https://img.shields.io/badge/Vue-134E3F?style=flat-square&logo=vuedotjs&logoColor=C8F5E1) |
| Offensive tooling | ![Metasploit](https://img.shields.io/badge/Metasploit-04110D?style=flat-square&logo=metasploit&logoColor=3DDC97) ![Nmap](https://img.shields.io/badge/Nmap-0B2A22?style=flat-square&logo=gnubash&logoColor=3DDC97) ![Wireshark](https://img.shields.io/badge/Wireshark-134E3F?style=flat-square&logo=wireshark&logoColor=C8F5E1) |
| Wireless | ![Wi-Fi](https://img.shields.io/badge/Wi--Fi-04110D?style=flat-square&logo=wifi&logoColor=3DDC97) ![Bluetooth](https://img.shields.io/badge/Bluetooth%20%2F%20BLE-0B2A22?style=flat-square&logo=bluetooth&logoColor=3DDC97) ![Aircrack-ng](https://img.shields.io/badge/Aircrack--ng-134E3F?style=flat-square&logo=gnometerminal&logoColor=C8F5E1) |
| Networking & telecom | ![MikroTik](https://img.shields.io/badge/MikroTik-04110D?style=flat-square&logo=mikrotik&logoColor=3DDC97) ![Cisco](https://img.shields.io/badge/Cisco-0B2A22?style=flat-square&logo=cisco&logoColor=3DDC97) ![Mobile](https://img.shields.io/badge/3G%20%2F%204G%20%2F%205G-134E3F?style=flat-square&logo=5g&logoColor=C8F5E1) |
| Detection | ![Snort](https://img.shields.io/badge/Snort-04110D?style=flat-square&logo=snort&logoColor=3DDC97) ![Suricata](https://img.shields.io/badge/Suricata-0B2A22?style=flat-square) ![Zeek](https://img.shields.io/badge/Zeek-134E3F?style=flat-square) |
| IoT | ![ESP32](https://img.shields.io/badge/ESP32-04110D?style=flat-square&logo=espressif&logoColor=3DDC97) ![MicroPython](https://img.shields.io/badge/MicroPython-0B2A22?style=flat-square&logo=micropython&logoColor=3DDC97) ![Linux](https://img.shields.io/badge/Linux-134E3F?style=flat-square&logo=linux&logoColor=C8F5E1) |
| Smart cities | ![Smart City](https://img.shields.io/badge/Smart%20City-04110D?style=flat-square&logo=openstreetmap&logoColor=3DDC97) ![Traffic](https://img.shields.io/badge/Adaptive%20Traffic-0B2A22?style=flat-square&logo=googlemaps&logoColor=3DDC97) ![Sensors](https://img.shields.io/badge/Sensor%20Networks-134E3F?style=flat-square&logo=espressif&logoColor=C8F5E1) |

</div>

---

<div align="center">
  <h2>⌁ Security Research</h2>
</div>

| Work | What it is |
| --- | --- |
| [**passport-jwt-265**](https://github.com/area51ec/passport-jwt-265) | Lab for passport-jwt#265: `issuer`, `audience` and `algorithms` silently dropped from `jsonWebTokenOptions` |
| [**DefinitelyTyped#75902**](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/75902) | Typings for `@types/passport-jwt` that reject that misconfiguration at compile time |
| **Coordinated disclosure** | Several reports in progress with maintainers and vendors, published after the fix |
| **Detection engineering** | Snort, Suricata and Zeek rules, plus incident response playbooks for IT/OT environments |

---

<div align="center">
  <h2>⌁ Community</h2>
</div>

- **Founder of the Area51 community** for security and technology: in-person talks and, during the pandemic, webinars with security experts from Colombia, Chile, Bolivia, Ecuador, Spain, Argentina, Mexico, Peru, Costa Rica and England
- **Collaborator at The Hacking Day**, Ecuador chapter
- **Collaborator at Campus Party**
- Official distributor of **0xWord** security books in Ecuador

---

<div align="center">
  <h2>⌁ Training</h2>
</div>

<div align="center">

![Telecom](https://img.shields.io/badge/Engineering-Telecommunications-04110D?style=for-the-badge&logo=wifi&logoColor=3DDC97)
![MTCNA](https://img.shields.io/badge/MikroTik-MTCNA%20(2013)-0B2A22?style=for-the-badge&logo=mikrotik&logoColor=3DDC97)
![MTCTCE](https://img.shields.io/badge/MikroTik-MTCTCE%20(2013)-134E3F?style=for-the-badge&logo=mikrotik&logoColor=C8F5E1)
![ISO 27001](https://img.shields.io/badge/ISO%2FIEC%2027001-Lead%20Auditor%20training-1F7A62?style=for-the-badge&logoColor=C8F5E1)

</div>

---

<div align="center">
  <h2>⌁ Building</h2>
</div>

<div align="center">

| Project | Signal |
| :---: | :---: |
| Voice assistant for hotels | Embedded voice device with sensors |
| Smart traffic lights (smart city) | Adapt to traffic, weather and emergency routes |
| Electronic invoicing | Direct integration with Ecuador's tax authority (SRI) |

</div>

---

<div align="center">
  <h2>⌁ Stack</h2>
</div>

<div align="center">

[![Stack](https://skillicons.dev/icons?i=html,css,js,nodejs,ts,php,laravel,vue,py,docker,postgres,linux,bash,git&theme=dark)](https://skillicons.dev)

</div>

---

<div align="center">

<sub>All testing is done on my own equipment and networks, or with explicit authorization.</sub>

<img src="assets/footer.svg" alt="" width="100%">

</div>
