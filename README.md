# NUI-Orin-presentation
NUI ORIN presentation
🌌 The Oracle Terminal
The Oracle je interaktivní webový terminál ovládaný gesty rukou v reálném čase. Kombinuje mystickou estetiku s moderními technologiemi jako Computer Vision (MediaPipe) a 3D grafika (Three.js). Projekt umožňuje uživateli prozkoumávat různé "dimenze" (moduly) bez dotyku klávesnice nebo myši.

🔮 Klíčové Funkce
Touchless Control: Kompletní navigace v UI pomocí sledování ruky přes webkameru.

Real-time Hand Tracking: Využívá MediaPipe Hands pro nízkou latenci a vysokou přesnost.

Audio Feedback: Procedurální generování zvuku (Web Audio API), které reaguje na interakci uživatele.

Modulární Architektura:

AURA: Manipulace s textovými manifesty pomocí gesta "pinch".

ARCHITECT (Inception): Stavba 3D struktur v prostoru pomocí virtuálních kostek.

SOLARIS: Průzkum solárního systému s ovládáním zoomu a rotace dlaní.

🛠️ Použité Technologie
Frontend: HTML5, CSS3 (Tailwind CSS), JavaScript (ES6+).

AI/Vision: MediaPipe Hands pro detekci 21 klíčových bodů ruky.

3D Engine: Three.js pro vykreslování komplexních scén v modulech Architect a Solaris.

Audio: Web Audio API pro dynamické syntezátory.

🚀 Instalace a Spuštění
Projekt nevyžaduje žádnou instalaci závislostí na straně serveru (běží kompletně v prohlížeči).

Naklonuj repozitář:

Bash

git clone https://github.com/tvuj-uzivatel/the-oracle.git
Otevři soubor index.html v moderním webovém prohlížeči (Chrome nebo Edge doporučeny kvůli podpoře kamery).

Povol přístup k webkameře.

Ritual Begin: Zaměř ruku na obrazovku a začni navigovat.

🖐️ Gesta (Manuál)
Gesto	Akce
Ukazováček (Cursor)	Pohyb kurzoru po obrazovce.
Hover (Setrvání)	Aktivace tlačítek a otevírání portálů.
Pinch (Sevření prstů)	Uchopení objektů (v modulu Architect) nebo injekce dat (v modulu Aura).
Plocha dlaně	Rotace 3D prostředí nebo ovládání zoomu.

EXPORTOVAT DO TABULEK

📱 Mobilní Preview
Projekt obsahuje inteligentní detekci mobilních zařízení. Na zařízeních s malým displejem se automaticky zobrazí statický preview.jpg, protože ovládání gesty vyžaduje větší plochu a specifický výkon pro Computer Vision.

📜 Licence
Tento projekt je vytvořen pro experimentální a umělecké účely.

"The future is not seen, it is felt through the ether."

Chceš do README přidat ještě něco specifického?
Mohu například doplnit:

Sekci o tom, jak přidat vlastní modul do iframe.

Více technických detailů o tom, jak funguje postMessage komunikace mezi terminálem a moduly.

GIFy/Obrázky přímo z tvého projektu.
