<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# BrowserWrapped 🎯

## Basic Details

### Team Name: Ding and Dong

### Team Members
- Team Lead: Devak Deepak - Toc H Institute of Science and Technology
- Member 2: Jeevan Varghese Vinu - Toc H Institute of Science and Technology

## Project Description

BrowserWrapped turns your own browser history into a Spotify-Wrapped-style recap — your most visited sites, your unique sites, an AI-generated "browsing personality," and a completely unnecessary animated race between your top 3 domains.

## The Problem (that doesn't exist)

Nobody has ever finished their year wondering exactly which three websites they visit the most, or whether their browsing habits reveal a deep personality trait. And yet, here we are.

## The Solution (that nobody asked for)

We built a slick, dark-mode, Spotify-inspired Flutter app that reads your local browsing history through a Python backend, crunches it into rankings and stats, sends a slice of it off to an AI to diagnose your "browsing personality," and — because regular bar charts are for cowards — animates your top 3 most-visited sites racing each other across the screen, with the winner dramatically crossing the finish line.

## Technical Details

### Technologies/Components Used

For Software:

Languages: Dart, Python
Frameworks: Flutter (frontend), Python backend module (python -m backend)
Libraries: Flutter Material widgets, custom AnimationController-driven animation mixins (staggered split-reveal table entrance, multi-lane race animation)
APIs: Google Gemini API (primary) with OpenRouter as a fallback, for generating the "browsing personality" archetype
Tools: Flutter SDK, Dart, Git

For Hardware:

N/A — this is a software-only project
Implementation

For Software:

Installation
bash
# Clone the repository
git clone <your-repo-url>
cd BrowserWrapped

# Install Flutter dependencies
flutter pub get

# Set up the Python backend
cd backend
pip install -r requirements.txt
Run
bash
# Run the Python backend (from the backend directory)
python -m backend --help

# Run the Flutter app (from the project root)
flutter run
Project Documentation

For Software:

Screenshots (Add at least 3)

<img width="1262" height="707" alt="image" src="https://github.com/user-attachments/assets/cf944c8e-7ca1-4dc3-a4b5-417a0fbc66c5" />
(Add screenshot 1 here with proper name) Add caption explaining what this shows

![Screenshot2](Add screenshot 2 here with proper name) Add caption explaining what this shows

![Screenshot3](Add screenshot 3 here with proper name) Add caption explaining what this shows


## Team Contributions
- Devak Deepak: Backend 
- Jeevan Varghese Vinu: Frontend

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



