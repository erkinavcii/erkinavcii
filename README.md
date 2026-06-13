# Hi there, I'm Ali Erkin Avcı 👋

<p align="center">
  <a href="https://github.com/erkinavcii">
    <img src="https://readme-typing-svg.demolab.com?font=Outfit&size=22&pause=1000&color=4A7C59&center=true&vCenter=true&width=600&lines=AI+%26+Data-Driven+Software+Engineer;Full-Stack+Developer+%26+Mobile+Architect;Intelligent+Automation+%26+RPA+Builder;Passionate+about+Zero-Knowledge+Cryptography" alt="Typing SVG" />
  </a>
</p>

---

## 🚀 About Me

I am a Computer Engineering graduate passionate about architecting secure, intelligent, and highly automated software systems. My development philosophy spans across the full spectrum: from **Zero-Knowledge Cryptographic Protocols** and **Deep-Learning Vision Models (MediaPipe)** to **Sensor-Fusion Mobile Applications** and **Automated RPA bots** (bypassing Cloudflare/Turnstile protection). 

I thrive on bridging the gap between raw hardware signals, offline-first architectures, and modern cloud infrastructures (Next.js/Supabase/FastAPI). I specialize in designing systems that require zero-server-cost hosting models, local AI execution (LM Studio), and custom system-level API hook integrations.

---

## 🛠️ Technology Ecosystem

| Category | Technologies |
| :--- | :--- |
| **Languages** | Python, TypeScript, Dart/Flutter, Kotlin, C#, C++, SQL, HTML/CSS |
| **AI, ML & NLP** | Google Gemini API, Local LLMs (LM Studio, Llama/Mistral), Sentence-Transformers, UMAP, MediaPipe Iris Tracking, Vosk Speech Recognition |
| **Web Frameworks** | Next.js 14-16 (App Router), React 18, FastAPI, ASP.NET Core, Streamlit, PWA, CustomTkinter, PySide |
| **Mobile & Desktop** | Flutter (Riverpod), Android SDK (Jetpack Compose, Kotlin, MVI), Win32 API, PyInstaller |
| **Databases & ORMs** | PostgreSQL, MongoDB (Motor Async), SQLite, Supabase RLS, Prisma, Drizzle ORM |
| **RPA & Automation** | Playwright Stealth, PyAutoGUI, Tesseract OCR, Voicemeeter virtual routing, n8n Workflow automation, Telegram Bot API |
| **Security & Network** | RSA-4096 Cryptography, AES-256-GCM, WebRTC (STUN-first VoIP media signaling), DTLS-SRTP, Challenge-Response Handshakes |

---

## 📂 Featured Projects Directory

### 🔐 Cybersecurity & Cryptography

<table>
  <tr>
    <td width="50%">
      <h3>🔐 <a href="https://github.com/erkinavcii/HybridP2P-Messenger">HybridP2P-Messenger</a></h3>
      <p><b>Zero-Knowledge End-to-End Encrypted (E2EE) Messenger</b></p>
      <ul>
        <li><b>Hybrid Cryptography:</b> Employs RSA-4096 and AES-256-GCM to establish military-grade E2EE text & files.</li>
        <li><b>Signature-Based Auth:</b> Prevents API abuse and replay attacks via RSA-PSS signature verification headers on every stateful request.</li>
        <li><b>STUN-First VoIP:</b> Direct WebRTC UDP voice/video calls bypassing server media streams. Falls back to zero-knowledge TURN routing when symmetric NATs are detected.</li>
        <li><b>Group Forward Secrecy:</b> Shared Group Symmetric Key architecture with dynamic cryptographic rekeying (rotation) upon member additions/removals at <i>O(1)</i> upload scale.</li>
        <li><b>Privacy-First UX:</b> RAM-only Ephemeral Chat and View-Once media modes. Files are stored as encrypted blobs and deleted from disk instantly upon download.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Flet_(Flutter)-02569B?style=flat-square&logo=flutter&logoColor=white" />
        <img src="https://img.shields.io/badge/WebCrypto-JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
      </p>
    </td>
  </tr>
</table>

### 📱 Mobile & Cross-Platform

<table>
  <tr>
    <td width="50%">
      <h3>🛡️ <a href="https://github.com/erkinavcii/FamilyPulse">FamilyPulse</a></h3>
      <p><b>Safety Tracking App for Children, Elderly & Neurodivergent Individuals</b></p>
      <ul>
        <li><b>Live Mapping:</b> Dynamic OpenStreetMap rendering utilizing <i>flutter_map</i> with active connection indicators and stale-location warnings (>30 min delay).</li>
        <li><b>Multi-Mode GPS:</b> WorkManager periodic background tasks (~15m interval) + aggressive foreground tracking service (~3m interval).</li>
        <li><b>Smart Geofencing:</b> Safe Zones (50m–1km radius) with a 30m hysteresis buffer to prevent border-bounce notification spam.</li>
        <li><b>Remote Bypass:</b> Remote audio unmute and system DND bypass to locate lost phones.</li>
        <li><b>ML Vitals & Reports:</b> Bento-style health dashboard tracking smartwatch heart rate anomalies against age/weight baselines.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
        <img src="https://img.shields.io/badge/Riverpod-764ABC?style=flat-square&logo=redux&logoColor=white" />
        <img src="https://img.shields.io/badge/Firebase_Auth_/_Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
        <img src="https://img.shields.io/badge/OSM-7EBC43?style=flat-square&logo=openstreetmap&logoColor=white" />
      </p>
    </td>
    <td width="50%">
      <h3>🏃‍♂️ <a href="https://github.com/erkinavcii/Running_Tracker">Running Tracker (Kinetics)</a></h3>
      <p><b>GPS-Anchored Sensor Fusion Running Coach</b></p>
      <ul>
        <li><b>Sensor Fusion:</b> Smooths 1Hz hardware GPS location checks using high-frequency (50Hz) accelerometer values.</li>
        <li><b>Drift Mitigation:</b> Eliminates smartphone integration drift errors by using GPS as the distance source of truth, reserving the accelerometer for instant start detection and visual UI speed interpolation.</li>
        <li><b>Detailed Telemetry:</b> Logs real-time speed, distance, and 3-axis G-force magnitude to local CSV logs for run reviews.</li>
        <li><b>Gamified Roadmaps:</b> Achievement engines, speed gradient maps, and world-record benchmark comparisons.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
        <img src="https://img.shields.io/badge/Riverpod-764ABC?style=flat-square&logo=redux&logoColor=white" />
        <img src="https://img.shields.io/badge/Sensors_Plus-0175C2?style=flat-square&logo=dart&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

### 🧠 AI & Intelligent Automation

<table>
  <tr>
    <td width="50%">
      <h3>📈 <a href="https://github.com/erkinavcii/Pulsify">Pulsify</a></h3>
      <p><b>AI-Powered Operations Dashboard & Assistant for SMEs</b></p>
      <ul>
        <li><b>Turkish NLP:</b> Real-time AI chatbot executing CRUD orders, checking inventory, and detecting shipment delays via natural language processing.</li>
        <li><b>Automated Executive Reporting:</b> Google Gemini API generates consolidated operation summaries, customer sentiment metrics, and stock warnings.</li>
        <li><b>Cargo Delay Detection:</b> Real-time shipment log scanning and proactive alert queues.</li>
        <li><b>Slick Dashboard:</b> Styled React interface utilizing Zustand state and fully async Motor MongoDB routing.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/React_/_TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
      </p>
    </td>
    <td width="50%">
      <h3>📞 <a href="https://github.com/erkinavcii/WhatsappAssistant">WhatsApp IVR Automation</a></h3>
      <p><b>VoIP Desktop Interactive Voice Response RPA Bot</b></p>
      <ul>
        <li><b>RPA Screen Vision:</b> PyAutoGUI computer-vision template matching intercepts incoming WhatsApp Desktop calls.</li>
        <li><b>OCR Caller ID:</b> Tesseract OCR reads caller name from screen pixels.</li>
        <li><b>Local NLP/STT:</b> Vosk offline Turkish speech recognition handles voice menu choices without keyboard input.</li>
        <li><b>Virtual Audio Routing:</b> Bypasses microphone-speaker loopback echo by managing Voicemeeter Banana hardware channels dynamically.</li>
        <li><b>Telegram Pipeline:</b> Automatically records, converts, and uploads call audio along with a caller screenshot to Telegram.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/PyAutoGUI_/_OCR-43B02A?style=flat-square&logo=selenium&logoColor=white" />
        <img src="https://img.shields.io/badge/Voicemeeter-Sanal-F05032?style=flat-square&logo=git&logoColor=white" />
        <img src="https://img.shields.io/badge/Telegram_API-26A69A?style=flat-square&logo=telegram&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🎙️ <a href="https://github.com/erkinavcii/SesliAsistan">SesliAsistan</a></h3>
      <p><b>Conversational Real Estate Lead Persuasion Agent</b></p>
      <ul>
        <li><b>Local LLMs:</b> Conversational AI integrating Llama/Mistral locally via LM Studio, running personalized lead follow-ups.</li>
        <li><b>Gemini Live Integration:</b> Live voice persuasion module using Gemini Live V2 APIs for human-sounding customer negotiation.</li>
        <li><b>Stateful Objection Management:</b> Scripted logical gates handling price, location, and urgency objections.</li>
        <li><b>Reporting Pipeline:</b> Outputs JSON conversation logs and generates daily conversion analytics.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/LM_Studio-000000?style=flat-square&logo=openai&logoColor=white" />
        <img src="https://img.shields.io/badge/Gemini_Live_V2-8E75B2?style=flat-square&logo=google&logoColor=white" />
      </p>
    </td>
    <td width="50%">
      <h3>🕵️ <a href="https://github.com/erkinavcii/IDataBot">IDataBot</a></h3>
      <p><b>Stateful iDATA Visa Appointment Tracker</b></p>
      <ul>
        <li><b>Anti-Bot Bypassing:</b> Integrates <code>playwright-stealth</code> to bypass Cloudflare, Turnstile, and Akamai barriers using human-like mouse movements.</li>
        <li><b>Persistent Login Session:</b> Cookie storage logic avoids re-authenticating on every launch.</li>
        <li><b>Self-Healing Workflows:</b> Detects server timeout errors or page refreshes, automatically resets form selectors, and continues scanning.</li>
        <li><b>Sound Alerts:</b> Triggers specific multi-tone Windows system sound alerts when a visa slot opens.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Playwright_Stealth-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/XPath_Selectors-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
      </p>
    </td>
  </tr>
</table>

### 🏡 Web Platforms & E-Commerce

<table>
  <tr>
    <td width="50%">
      <h3>🔑 <a href="https://github.com/erkinavcii/CevizWebsitesi">Ceviz Bahçesi (D2C)</a></h3>
      <p><b>Direct-to-Consumer Organic Walnut E-Commerce & Logistics</b></p>
      <ul>
        <li><b>Serverless Database:</b> Connects Neon.tech PostgreSQL with Next.js API Routes to achieve a zero-cost server hosting model.</li>
        <li><b>Real-Time Inventory:</b> Automatic variant stock calculations (e.g., 500g/1kg/5kg packages) with low-stock threshold triggers.</li>
        <li><b>n8n Orchestration:</b> Automation pipelines firing SMS (Netgsm), invoices (Paraşüt API), and real-time order alerts to Telegram.</li>
        <li><b>Secure Payments:</b> Integrates sandbox & production Iyzico 3D Secure checkout.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/Neon_Postgres-00E5FF?style=flat-square&logo=postgresql&logoColor=black" />
        <img src="https://img.shields.io/badge/n8n_Automations-FF6C37?style=flat-square&logo=n8n&logoColor=white" />
        <img src="https://img.shields.io/badge/Iyzico_Pay-24B3A8?style=flat-square&logo=stripe&logoColor=white" />
      </p>
    </td>
    <td width="50%">
      <h3>🏠 <a href="https://github.com/erkinavcii/CustomerRegistration">AvcıVilla (HiringCalendar)</a></h3>
      <p><b>Vacation Villa Reservation & Availability Hub</b></p>
      <ul>
        <li><b>iCal Sync Motor:</b> A zero-dependency custom parser syncing Airbnb, Booking.com, and VRBO calendars in real-time, built around core Node.js SSR streams.</li>
        <li><b>Supabase RLS:</b> Table-level security ensuring public visitors only see blocked calendar dates, while client metadata, reservation notes, and rental pricing are kept admin-only.</li>
        <li><b>WhatsApp Lead Generator:</b> Computes totals dynamically and constructs preset booking request chat templates.</li>
        <li><b>Analytics Admin Panel:</b> Tracks seasonal occupancies, booking stats, and multi-currency income estimations.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/CSS_Variables-1572B6?style=flat-square&logo=css3&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

### ⚙️ Desktop Utilities & Game Internals

<table>
  <tr>
    <td width="50%">
      <h3>👁️ <a href="https://github.com/erkinavcii/Study-Tracker">Smart Focus Assistant</a></h3>
      <p><b>Computer-Vision Screen Attention Tracker</b></p>
      <ul>
        <li><b>Eye/Iris Tracking:</b> Computes real-time screen-attention metrics via local webcam streams using MediaPipe Iris mesh.</li>
        <li><b>Active App Filters:</b> Hooks Windows OS active window titles, matching them against whitelists (work) and blacklists (distractions).</li>
        <li><b>Focus Ratio:</b> Aggregates screen visual alignment and window checks into a live productivity score.</li>
        <li><b>Telemetry DB:</b> Logs work sessions, focus ratios, and distraction events to SQLite.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/MediaPipe-00C7B7?style=flat-square&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
        <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" />
      </p>
    </td>
    <td width="50%">
      <h3>👾 Metin2 Native Hook Injector</h3>
      <p><b>Game Client Memory Interceptor & Automated Player</b></p>
      <ul>
        <li><b>DLL Injection:</b> Custom C++ injector loading a custom DLL into the game process space.</li>
        <li><b>Message Loop Subclassing:</b> Redirects the game's message procedures using <code>WM_BRIDGE_PULSE</code>, allowing Python command scripts to execute functions safely on the game thread.</li>
        <li><b>VTable Hooking:</b> Scans memory offsets to hook singletons (<code>g_pNetworkStream</code>) and function pointers (<code>pSendRawPacket</code>, <code>pSendOnClickPacket</code>).</li>
        <li><b>Raw Byte Manipulation:</b> Directly constructs little-endian structured payload packets (e.g., 5-byte target selection packets) and transmits them down the game's C++ connection layer.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
        <img src="https://img.shields.io/badge/Win32_API-0078D4?style=flat-square&logo=windows&logoColor=white" />
        <img src="https://img.shields.io/badge/Python_Bridge-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Reverse_Engineering-8A2BE2?style=flat-square&logo=git&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>⏱️ <a href="https://github.com/erkinavcii/WindowsShuttimer">AutoOff (ShutTimer)</a></h3>
      <p><b>Fluent Win11 styled Smart PC Shutdown Overlay</b></p>
      <ul>
        <li><b>Aggressive Overlays:</b> Displays a full-screen, top-level warning dialog with sirens 60s before shutting down, allowing quick aborts.</li>
        <li><b>WinAPI Sleep Workaround:</b> Uses PowerShell execution hooks to bypass standard Windows hibernation bugs, ensuring clean sleep states.</li>
        <li><b>Hardware Monitors:</b> Network speed tracking and CPU utilization triggers to shut down PC only after heavy downloads or rendering jobs finish.</li>
        <li><b>CustomTkinter Theme:</b> Implements system-matching dark/light Fluent UI.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/CustomTkinter-4A7C59?style=flat-square&logo=react&logoColor=white" />
        <img src="https://img.shields.io/badge/Win32_Process-0078D4?style=flat-square&logo=windows&logoColor=white" />
      </p>
    </td>
    <td width="50%">
      <h3>🎵 <a href="https://github.com/erkinavcii/LyraApp-Pair">LyraApp</a></h3>
      <p><b>Material 3 Online/Offline Music Player for Android</b></p>
      <ul>
        <li><b>MVI Pattern:</b> Implements strict Model-View-Intent data flow with clean separate contract interfaces.</li>
        <li><b>Local/Cloud Sync:</b> Connects with backend REST APIs for online playback, caching audio tracks locally for offline use.</li>
        <li><b>Jetpack Compose UI:</b> Fluent audio visualizers, dynamic backgrounds, and custom playback controls.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
        <img src="https://img.shields.io/badge/Android_Jetpack_Compose-3DDC84?style=flat-square&logo=android&logoColor=white" />
        <img src="https://img.shields.io/badge/MVI_Architecture-000000?style=flat-square&logo=diagrams.net&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

<details>
  <summary>🎓 <b>Other Academic & Classic Repositories</b></summary>

*   **[Fatura-Takip-Uygulamas-Billing-Tracker-PWA-](https://github.com/erkinavcii/Fatura-Takip-Uygulamas-Billing-Tracker-PWA-)**: Serverless Progressive Web App designed to track monthly or recurring bills with local browser storage and notification alerts. *(HTML / JS / PWA)*
*   **[deprem-bot](https://github.com/erkinavcii/deprem-bot)**: Real-time Turkish earthquake alert tracking bot broadcasting magnitude-filtered alerts to chat hooks. *(Python)*
*   **[KariyerKapisiBot](https://github.com/erkinavcii/KariyerKapisiBot)**: Automated session manager tracking application updates on the Turkish Government career gate website. *(Python)*
*   **[Turkcellgygy5-kotlin-bankac-l-k](https://github.com/erkinavcii/Turkcellgygy5-kotlin-bankac-l-k)**: Kotlin mobile banking application console template developed for Turkcell GYGY Bootcamp. *(Kotlin)*
*   **[OopLab](https://github.com/erkinavcii/OopLab)** & **[CustomerRegistration](https://github.com/erkinavcii/CustomerRegistration)**: Practical OOP system layouts, WinForms, and database registration schemas in .NET Core. *(C#)*
*   **[AygazYapayZeka](https://github.com/erkinavcii/AygazYapayZeka)**: Presentation resources and code tutorials for the Aygaz AI Literacy program. *(Jupyter Notebook)*
</details>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=erkinavcii&show_icons=true&theme=radical&hide_border=true" alt="Ali Erkin's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=erkinavcii&layout=compact&theme=radical&hide_border=true" alt="Top Languages" width="48%" />
</p>

---

## 📫 Connect with Me

<p align="left">
  <a href="https://www.linkedin.com/in/alierkinavci/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:alierkinavci20@hotmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>
