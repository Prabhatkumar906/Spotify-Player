🎵 Music Player System (C++ LLD)

This is a C++ implementation of a basic Music Player System, inspired by a system design / LLD lecture series.
The idea was to understand how to structure a real project using OOP, clean code, and some commonly used design patterns.

The project supports things like playing songs, managing playlists, handling different playback modes, and switching devices.
The focus is more on architecture than UI.

📌 Features

Add and manage songs and playlists

Play, pause, next, previous

Playback modes: normal, repeat, shuffle

Device selection using a simple factory

Facade class to control the overall player

Folder-based modular structure

📁 Folder Structure
MusicPlayerApplication/
│── core/
│── device/
│── enums/
│── external/
│── factories/
│── managers/
│── models/
│── strategies/
│── main.cpp
│── MusicPlayerApplication.hpp
│── MusicPlayerFacade.hpp
│── UML.pdf


This structure helped me keep the code cleaner and understand how larger applications are usually organized.

🛠 Tech Used

C++ (OOP + STL + basic patterns)

Concepts: Factory, Strategy, Facade, Abstraction, Interfaces

VS Code / g++ compiler

▶️ How to Run
g++ -std=c++17 main.cpp -o music_player
./music_player

📝 Notes

This project was mainly built for practicing Low Level Design and improving how I think about classes, relationships, and responsibilities.
It’s not a full production app — but it’s a good reference for LLD, especially for interviews.

👍 Contribution / Improvements

If you have suggestions (better design patterns, improvements, refactoring ideas), feel free to open an issue or PR.
