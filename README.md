



🌌 The Oracle: Gesture-Controlled Portfolio Terminal
The Oracle is a sophisticated, interactive web terminal and portfolio experience powered by Computer Vision. It pushes the boundaries of traditional Human-Computer Interaction (HCI) by allowing users to navigate digital realms through real-time hand tracking, eliminating the need for a mouse or keyboard. It blends a mystical "occult" aesthetic with cutting-edge web technologies.
🔮 Key Features
Touchless Control: Seamless UI navigation via webcam-based hand tracking.
Real-time Hand Tracking: Powered by MediaPipe Hands for high precision and ultra-low latency.
Audio Feedback: Procedural sound generation using the Web Audio API that reacts dynamically to user interactions.
Modular Architecture:
AURA: Manipulate textual manifests using "pinch" gestures.
ARCHITECT (Inception): Construct 3D structures in real-time using virtual blocks.
SOLARIS: Explore the solar system with intuitive palm-based zoom and rotation.
🛠️ Technology Stack
Frontend: HTML5, CSS3 (Tailwind CSS), JavaScript (ES6+).
AI/Vision: MediaPipe Hands for 21-point hand landmark detection.
3D Engine: Three.js for high-performance rendering of spatial scenes.
Audio: Web Audio API for real-time synthesis and acoustic feedback.
🚀 Installation & Usage
The project is client-side only and requires no server-side dependencies.
Clone the repository:
Bash
git clone https://github.com/your-username/the-oracle.git


Open index.html in a modern web browser (Chrome or Edge recommended for optimal camera support).
Grant webcam permissions when prompted.
Commence the Ritual: Position your hand in view of the camera and begin navigating.
🖐️ Operational Manual (Gestures)
Gesture
Action
Technical Principle
Index Finger (Cursor)
Move cursor
Tracks Landmark 8 (Index Tip)
Hover (Dwell)
Activate buttons
Time-based accumulation (Progress fill)
Pinch
Grab / Inject data
Euclidean distance between points 4 & 8
Open Palm
Rotate / Zoom
Palm normal vector & depth calculation

📱 Mobile Preview
The system includes intelligent device detection. Since gesture control requires specific processing power and screen real estate, mobile users are automatically presented with a high-fidelity static preview.jpg to ensure a consistent visual experience across all platforms.
📜 License & Vision
This project is created for experimental and artistic purposes.
"The future is not seen, it is felt through the ether."

Engineering Highlights (Optional addition for recruiters)
Iframe Bridge: Uses a custom communication layer via postMessage API to sync hand coordinates between the main terminal and isolated modules.
Linear Interpolation (Lerp): Implements mathematical smoothing to filter camera noise and ensure fluid cursor movement.

