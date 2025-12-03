🎵 Music Player System (Spotify LLD in C++)

A low-level design and C++ implementation of a Spotify-like Music Player, demonstrating Object-Oriented Programming, SOLID principles, and popular design patterns (Factory, Strategy, Facade).
This project is inspired by system design practices and professionally structured for scalability and extensibility.

✨ Features

🎶 Manage songs, playlists, and user music libraries

▶️ Playback control: Play, Pause, Next, Previous

🔁 Playback strategies: Repeat, Shuffle, Sequential

📱 Device-based streaming using Factory Pattern

🎛️ Facade interface for controlling the entire Music Player

🧱 Modular and extensible folder structure

🏗 Implements LLD, UML design, and clean architecture

🧩 Tech Stack

Language: C++

Concepts Used:

Object-Oriented Programming

Design Patterns (Factory, Strategy, Facade)

Abstraction, Encapsulation, Polymorphism

SOLID Principles

Tools: VS Code, Git/GitHub

📁 Project Structure
MusicPlayerApplication/
│
├── core/               # Core logic & base classes
├── device/             # Device-related playback components
├── enums/              # Enum definitions for states & types
├── external/           # External services (if any)
├── factories/          # Factory pattern implementations
├── managers/           # Managers for playlist, queue, devices
├── models/             # Song, Playlist, User models
├── strategies/         # Playback strategies (shuffle, repeat)
│
├── MusicPlayerApplication.hpp
├── MusicPlayerFacade.hpp
├── DeviceFactory.hpp
├── main.cpp            # Entry point
└── UML.pdf             # Design diagram

🛠 Design Patterns Implemented
✔ Factory Pattern

Used for creating different types of audio output devices.

✔ Strategy Pattern

Used for selecting playback strategies such as:

Shuffle

Repeat

Sequential

✔ Facade Pattern

Provides a single interface (MusicPlayerFacade) to interact with the entire music player system.

🚀 How to Run

Clone the repository:

git clone https://github.com/Prabhatkumar906/Spotify-Player.git


Navigate into the project:

cd Spotify-Player/MusicPlayerApplication


Compile the code:

g++ -std=c++17 main.cpp -o music_player


Run the program:

./music_player

📄 UML Design

A UML diagram (UML.pdf) is included, showcasing the architecture, relationships, class hierarchies, and patterns used.

📌 Learning Outcomes

By building this project, you gain hands-on experience with:

Designing scalable systems

Understanding LLD (Low Level Design)

Writing clean, modular C++ code

Applying design patterns in real-world scenarios

Structuring a professional-grade project

⭐ If you like this project

Consider giving the repo a star ⭐ to support the work!
