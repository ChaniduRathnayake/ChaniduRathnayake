<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0f3d3e,100:00d4aa&height=200&section=header&text=Chanidu%20Rathnayake&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Cyber%20Security%20%E2%80%A2%20Blue%20Team%20%E2%80%A2%20Builder&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="header"/>
</p>

<p align="center">
  <a href="https://github.com/ChaniduRathnayake">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=900&color=00D4AA&center=true&vCenter=true&width=620&lines=Securing+smart+hospitals+with+ML-driven+SIEM;Building+network+tools+for+Windows;Breaking+things+in+CTFs+to+learn+how+to+fix+them;Cyber+Security+%40+SLIIT+%F0%9F%87%B1%F0%9F%87%B0" alt="typing"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ChaniduRathnayake&label=Profile%20views&color=00d4aa&style=for-the-badge" alt="views"/>
  <img src="https://img.shields.io/github/followers/ChaniduRathnayake?label=Followers&style=for-the-badge&color=0f3d3e&logo=github" alt="followers"/>
  <img src="https://img.shields.io/badge/Location-Sri%20Lanka-0f3d3e?style=for-the-badge&logo=googlemaps&logoColor=white" alt="location"/>
</p>

---

### 🛡️ About me

```yaml
name:        Chanidu Rathnayake
role:        Cyber Security undergraduate @ SLIIT
focus:       [ SIEM / IDS, Network Security, ML for Security, Reverse Engineering ]
building:    MediSIEM  →  next-gen SIEM/IDS for smart hospitals (research project R26-CS-008)
shipping:    NetUse    →  network monitor + per-app firewall for Windows
playing:     CTFs, Android APK reversing, crypto from scratch
motto:       "Understand the attack. Build the defence."
```

---

### 🚀 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏥 <a href="https://github.com/ChaniduRathnayake/MediSIEM">MediSIEM</a></h3>
      <p>Multi-service <b>SIEM/IDS for hospital networks</b>. Ingests Wazuh HIDS alerts and live network flows, then ranks them with <b>CAAP</b> (Clinically Aware Alert Prioritization): Random Forest + Isolation Forest + K-Means, blended with clinical-criticality and temporal context into a 0–10 <b>Clinical Alert Score</b>. An exploit against an ICU ventilator at night outranks the same exploit on an idle admin PC.</p>
      <img src="https://img.shields.io/badge/Wazuh-005571?style=flat-square&logo=wazuh&logoColor=white"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
      <img src="https://img.shields.io/badge/MERN-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>📡 <a href="https://github.com/ChaniduRathnayake/NetUse">NetUse</a></h3>
      <p>A <b>network monitor and per-app firewall for Windows 10/11</b>. See which apps use your connection, how much and where they connect, then block any of them with one switch. Includes a 30-day traffic "time machine", per-app data limits, app/website routing across networks, and a VPN kill switch — no driver required.</p>
      <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
      <img src="https://img.shields.io/badge/WPF-0078D4?style=flat-square&logo=windows&logoColor=white"/>
      <img src="https://img.shields.io/badge/Windows%20Firewall-0078D6?style=flat-square&logo=windows11&logoColor=white"/>
      <br/><br/>
      <a href="https://github.com/ChaniduRathnayake/NetUse/releases/latest"><img src="https://img.shields.io/badge/⬇%20Download-latest-00d4aa?style=for-the-badge"/></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 <a href="https://github.com/ChaniduRathnayake/ML-Model">CAAP IoMT IDS</a></h3>
      <p>The ML pipeline behind MediSIEM: trains three models on IoMT pcap-derived flows (ARP spoofing, MQTT DDoS, SYN floods…) and serves predictions through a Flask AI server to the SOC dashboard.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
      <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 <a href="https://github.com/ChaniduRathnayake/DES-Tool">DES-Tool</a></h3>
      <p>The <b>Data Encryption Standard implemented from scratch</b> in Python, with ECB and CBC modes, a menu-driven CLI and built-in performance monitoring (time, CPU, memory). Built for learning how block ciphers really work.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Cryptography-222222?style=flat-square&logo=letsencrypt&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🚩 <a href="https://github.com/ChaniduRathnayake/PathTravesalCTF">Path Traversal CTF</a> · <a href="https://github.com/ChaniduRathnayake/CTF">CTF</a></h3>
      <p>Multi-stage web CTF challenges built around path traversal and file-disclosure bugs — written to teach how these vulnerabilities are found and exploited.</p>
      <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/>
      <img src="https://img.shields.io/badge/Web%20Security-cc0000?style=flat-square&logo=owasp&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/ChaniduRathnayake/ISPM">SecureAware</a> · 📱 <a href="https://github.com/ChaniduRathnayake/androidcrack">androidcrack</a></h3>
      <p><b>SecureAware</b>: an information-security awareness platform (React + TypeScript + Node). <b>androidcrack</b>: hands-on Android APK reverse engineering with apktool and Smali patching.</p>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
      <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white"/>
    </td>
  </tr>
</table>

---

### 🧰 Tech stack

<p align="center"><b>Languages</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=python,cs,ts,js,php,java,c,bash,powershell&theme=dark" alt="languages"/>
</p>

<p align="center"><b>Web & Backend</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,mongodb,flask,tailwind,vite,html,css&theme=dark" alt="web"/>
</p>

<p align="center"><b>Security, Infra & Tools</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=linux,kali,docker,windows,dotnet,git,githubactions,sklearn,vscode&theme=dark" alt="tools"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Wazuh-005571?style=for-the-badge&logo=wazuh&logoColor=white"/>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=gnu&logoColor=white"/>
  <img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white"/>
  <img src="https://img.shields.io/badge/apktool-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>
</p>

---

### 📊 GitHub stats

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ChaniduRathnayake&theme=tokyonight" alt="profile details"/>
</p>

<p align="center">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ChaniduRathnayake&theme=tokyonight" alt="stats"/>
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ChaniduRathnayake&theme=tokyonight" alt="most commit language"/>
</p>

<p align="center">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ChaniduRathnayake&theme=tokyonight" alt="repos per language"/>
  <img width="49%" src="https://streak-stats.demolab.com?user=ChaniduRathnayake&hide_border=true&theme=tokyonight&ring=00D4AA&fire=00D4AA&currStreakLabel=00D4AA" alt="streak"/>
</p>

---

<p align="center">
  <i>Currently: finishing the MediSIEM research (SLIIT · R26-CS-008) and shipping new NetUse features.</i><br/>
  <i>Open to cybersecurity internships, SOC / blue-team roles and research collaborations.</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4aa,50:0f3d3e,100:0d1117&height=110&section=footer" width="100%" alt="footer"/>
</p>
