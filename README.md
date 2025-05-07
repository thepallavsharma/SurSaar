🎵 SurSaar - Bollywood Guitar Song Finder 🎸
SurSaar is a Flutter-powered mobile app that helps guitarists find Bollywood songs they can play based on selected chords and capo position. Whether you're a beginner or intermediate player, SurSaar suggests songs that match your playing comfort using basic music theory.

🔑 Features
🎶 Get Bollywood songs based on selected root chord and capo fret

🔁 Adjusts chord progression dynamically according to capo position

📋 Displays song metadata: artist, difficulty, strumming pattern, and more

🎸 Beginner- and intermediate-friendly song collection

🎥 Includes YouTube tutorial links (if available)

🌈 Interactive UI with smooth animations and chip-based chord displays

🚀 Tech Stack
Flutter for UI

BLoC pattern for clean state management

Custom music theory logic to calculate capo-adjusted chords

Responsive design optimized for mobile devices

📂 Folder Structure
bash
Copy
Edit
lib/
├── blocs/             # BLoC logic
├── models/            # Song data model
├── repositories/      # Song source and filtering logic
├── screens/           # UI screens including Home and Details
├── widgets/           # Reusable UI components like SongList
└── main.dart          # Entry point
🛠️ Getting Started
Clone the repo

bash
Copy
Edit
git clone https://github.com/yourusername/sursaar.git
cd sursaar
Install dependencies

bash
Copy
Edit
flutter pub get
Run the app

bash
Copy
Edit
flutter run
✨ Future Enhancements
Dark mode toggle

Add lyrics view and search

Expand song database with genres and capo charts

Offline storage with local database
