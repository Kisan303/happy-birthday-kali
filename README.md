# Kale & Kali — Love You 3000

## 📖 About This Project
This project is a custom-built, interactive cinematic web experience designed to send a heartfelt, romantic birthday wish across the miles. It acts as a digital visual novel where the user clicks through a playful and emotional dialogue sequence between two characters (Kale and Kali). 

The experience transitions from lighthearted banter into a beautifully animated 3D birthday cake reveal, complete with interactive candles that can be blown out using the device's microphone, and ends with a meticulously designed digital envelope where the recipient can read a personalized letter and save a screenshot of their birthday wish.

## 🛠️ Tech Stack
This project is built purely with native web technologies to ensure it is lightweight, fast, and highly responsive across both mobile and desktop browsers without the need for external libraries or frameworks.
* **HTML5:** Semantic structure and layout.
* **CSS3:** Advanced animations, 3D CSS transforms (for the cake and envelope physics), custom particle systems, and responsive design.
* **Vanilla JavaScript:** State management, dialogue typewriter logic, and interactive DOM manipulation.
* **Web Audio API:** A custom-programmed synthesizer engine that generates ambient background chords, UI sound effects, and an acoustic guitar rendition of "Happy Birthday" entirely through code (no external `.mp3` files required).
* **MediaDevices API:** Microphone integration for the interactive candle-blowing feature.

## 📂 Directory Layout
Ensure the files are structured exactly like this for the website to load the character expressions properly:

```text
birthday-project/
│
├── index.html        # The main application file containing all HTML, CSS, and JS
├── README.md         # Project documentation
│
└── assets/           # Contains all character sprite images
    │
    ├── kale/         # Images must be named exactly as referenced in the code
    │   ├── kale_neutral.png
    │   ├── kale_happy.png
    │   └── ... 
    │
    └── kali/
        ├── kali_neutral.png
        ├── kali_laughing.png
        └── ...
