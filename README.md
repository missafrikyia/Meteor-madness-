🌍 Meteor Madness: Ants to the Rescue

Category: NASA Space Apps Challenge 2025
Team: MamaSpaceTeam
Location: Pointe-Noire, Republic of Congo
Languages: French 🇫🇷 • English 🇬🇧 • Lingála 🇨🇩


---

🚀 Project Overview

Meteor Madness: Ants to the Rescue is an educational and interactive web simulation designed to help users visualize asteroid impact risks and understand how small deflection maneuvers can prevent catastrophic collisions with Earth.

The project gamifies planetary defense: users play as “ants” defending Earth by launching rockets and shields against incoming asteroids while simultaneously using a NASA-inspired simulation panel to test kinetic deflection strategies (Δv).

The interface is multilingual (French, English, Lingála) to ensure accessibility for African and international audiences.


---

🛰️ NASA & USGS Data Integration

The project uses real NASA data and APIs to ensure educational realism and eligibility for Global Award consideration:

Source	Description	Link

NASA APOD API	Displays the Astronomy Picture of the Day as a live dynamic banner, refreshed daily.	https://api.nasa.gov/planetary/apod
NASA NEO Close Approach Data (JPL)	Provides data on near-Earth objects, their size, velocity, and orbital distance.	https://ssd-api.jpl.nasa.gov/doc/cad.html
USGS Earth Datasets	Referenced for topographic and oceanic modeling (crater size, tsunami reach).	https://www.usgs.gov/


Fallback open datasets (OpenStreetMap + Unsplash images) are used when APIs are temporarily unavailable.


---

💡 Features

🌐 Multilingual Interface: French, English, and Lingála (Central Africa).

🪐 NASA Integration: Real APOD banner and educational Δv simulation.

🧮 Physics-based Models: Calculates impact energy (Joules → TNT equivalent), crater diameter, and tsunami propagation.

🗺️ Interactive Map: Built with Leaflet.js — users can click anywhere on Earth to simulate impact zones.

🧠 Educational Simulation: Demonstrates how kinetic impactors (like NASA’s DART mission) can alter an asteroid’s trajectory.

🎮 Gamified Experience: Users can fire, shield, or launch rockets to defend Earth in a dynamic space defense mini-game.



---

🧩 Technical Stack

Frontend: HTML5, CSS3, JavaScript (Vanilla)

Map Engine: Leaflet.js + OpenStreetMap

APIs: NASA APOD API, NASA NEO API

Physics Calculations: Simplified educational models for energy, crater radius, and tsunami reach

Responsive Design: Compatible with desktop and mobile browsers



---

🌊 Simulation Parameters

Variable	Description	Example Value

Diameter (m)	Asteroid size	200
Velocity (km/s)	Impact speed	15
Δv (mm/s)	Deflection change	1.0
Days	Time before impact	30
Output	Energy, crater diameter, tsunami distance	20 Mt TNT → crater 2.8 km



---

🔬 Scientific References

NASA Planetary Defense Coordination Office

DART Mission Technical Data

USGS Impact and Seismic Modeling Guidelines

Shoemaker-Levy 9, Tunguska, and Chelyabinsk event impact physics



---

🧠 AI Use Disclosure

This project used AI tools (ChatGPT & Miss AfrikyIA) to:

Generate multilingual text translations (French, English, Lingála)

Optimize JavaScript syntax and front-end layout

Create educational explanations and impact formulas


No NASA logos, mission identifiers, or visual branding elements were used.


---

📽️ Demo Video (≤ 30 sec)

The video demonstrates:

1. Loading the live NASA APOD image


2. Switching between French, English, and Lingála


3. Running a kinetic impact simulation (Δv = 1.5 mm/s)


4. Visualizing a simulated tsunami reach on the world map


5. Quick gameplay scene showing Earth defended by “ants”




---

🧭 Future Development

Integration of real-time NASA NEO feed (JSON endpoint)

Improved tsunami propagation model (using bathymetric USGS layers)

AI-based prediction assistant: “AntBot” for adaptive deflection strategies

Mobile-friendly version for schools and STEM programs in Africa



---

👩🏾‍🚀 Credits

Project Lead: Laetitia Fila

Developers: Heaven & Hamilton (MamaSpaceTeam)

Mentor AI: Miss AfrikyIA

Special Thanks: NASA Space Apps 2025 organizers
