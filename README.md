The HIFI Harmonic Frequencizer 5000

Overview

The HIFI Harmonic Frequencizer 5000 is a standalone, interactive web application designed to serve as a visualizer for 6-band stereo equalizer presets. It features a premium, vintage hi-fi aesthetic, complete with realistic-looking knobs and a real-time EQ curve display.

This project was built to provide audiophiles and music lovers with a beautiful and intuitive tool to see how different EQ settings shape the sound of their music. It was developed iteratively, with features and presets carefully calibrated based on established audio science principles to ensure a high-quality, safe, and musical experience for any capable sound system.

Live Demo
https://msxada.github.io/Frequencizer-5000-5.0/

Features
Interactive 6-Band Equalizer: Six distinct, circular knobs representing the key frequency bands of the audio spectrum.

Realistic Vintage Design: A dark, premium theme with gold accents, 3D-effect knobs, and a clean layout inspired by classic hi-fi equipment.

Real-Time EQ Curve Visualizer: An SVG-based graph, powered by D3.js, that smoothly animates to show the shape of the sound curve for each selected preset.

Comprehensive Preset Library: A dropdown menu filled with a wide variety of presets for different genres and listening situations, all carefully tuned for a refined audio experience.

Responsive Layout: The interface gracefully adapts to different screen sizes, from mobile devices to large desktop monitors.

Standalone & Portable: The entire application is contained within a single index.html file, making it easy to run locally or host anywhere.

Technology Stack

HTML5: For the core structure and content.

CSS3: For custom styling, animations, and layout.

Tailwind CSS: Utilized for its utility-first framework to rapidly build and style the responsive interface.

Vanilla JavaScript (ES6+): For all interactivity, knob logic, preset management, and DOM manipulation.

D3.js: A powerful JavaScript library used to render the dynamic and smooth SVG-based EQ curve visualizer.

Google Fonts: The 'Inter' font is used for clean, crisp, and consistent typography across all elements.

Equalizer Band Specifications
The Frequencizer features six bands, each with a specific adjustment range designed for precise and musical control:

20 Hz (Sub-Bass): +/- 12dB

120 Hz (Bass): +/- 9dB

400 Hz (Lower Mids): +/- 6dB

2 kHz (Presence): +/- 6dB

6 kHz (Treble): +/- 9dB

16 kHz (Air): +/- 12dB

Preset Library & Philosophy
The following presets have been carefully calibrated to provide a safe and effective starting point for enhancing your listening experience. They are designed to work well with high-quality audio systems that include a dedicated subwoofer, ensuring that adjustments complement, rather than conflict with, a properly set up system.

Standard Presets
Fuller Bass & Warmth: Adds mid-bass punch and warmth, ideal for systems with capable subwoofers.

Energetic & Forward: Brings vocals and lead instruments to the front without harshness. Perfect for detailed speaker systems.

Crisp Vocals & Detail: Enhances vocal clarity and instrumental detail by focusing on upper-mid frequencies.

Smooth & Relaxed: Gently tames the upper frequencies for a non-fatiguing, laid-back listen, ideal for extended sessions.

Late Night Listening: A refined loudness curve that adds fullness at low volumes without creating boominess.

Genre Presets
Rock: Adds punch to drums and crunch to guitars. The sub-bass is slightly tamed to ensure bass lines remain tight and fast.

Pop: Clean, deep sub-bass and crisp, clear highs for a modern, polished sound.

Jazz: A focus on natural timbre and instrumental clarity. A light touch lets the recording breathe.

Metal: A controlled mid-scoop for powerful, chugging guitars, with tight, fast bass that doesn't get muddy.

Acoustic: Brings out natural body and string detail. A slight sub-bass cut tightens the sound and prevents unwanted room boom.

Classical: A pure setting to respect the recording's dynamics, with a hint of "air" for spaciousness.

Electronic/Dance: Deep, powerful sub-bass shaped by the EQ for impact, with exciting highs.

R&B: Smooth, deep bass, warm and present vocals, and crisp hi-hats for a soulful, engaging sound.

Rap: Hard-hitting bass that remains tight and articulate, ensuring lyrical clarity is never compromised.

Country: Prioritizes vocal clarity and the natural twang of guitars, with a balanced and honest presentation.

Funk & Soul: Punchy, articulate bass lines and crisp, detailed horns and cymbals to drive the rhythm.

Special Presets
Fuzz Muff: A heavy, saturated sound, refined for clarity and tight bass response.

Vibe-o-Matic 5000: A unique harmonic coloration with alternating boosts and cuts for a wavy, vintage feel.

How To Use
Download the index.html file from this repository.

Open the file in any modern web browser like Chrome, Firefox, Safari, or Edge.

The application will run instantly. Use the dropdown menu to select a preset and observe the changes in the knobs and the EQ curve visualizer.

This file is completely self-contained and requires no additional setup or installation.
