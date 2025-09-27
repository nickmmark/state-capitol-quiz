# state-capitol-quiz
web app to gamify my kids learning

Memorization is important but it can be frustrating and boring. To help my kids learn state capitols we decided to make game out of it.

You can play the game [here](https://nickmmark.github.io/state-capitol-quiz/).

🗺️ Our game has several modes:
* Easy: pick the state that is highlighted on a map (multiple choice)
* Intermediate: pick the correct state capital for a state shown on the map (multiple choice)
* Hard: type the state capital for a state shown on the map (free response)

Behind the scenes
* we are using the [Wikimedia US map SVG file](https://en.m.wikipedia.org/wiki/File:Blank_US_Map_(states_only).svg) and highlighting states
* the database includes regions so the multiple choice will include neighboring states
* the database includes names of other cities in the same state as "decoy answers" (this makes is MUCH harder)

## ⚙️ Settings
* choose how many answer choices there will be for multiple choice mode (5-8; default 6)
* choose to reveal the state capital when playing in states mode (easy); this is to help kids learn the state capitols as they learn states

## 🏗️ To do
* would be fun to make a version of this game for learning other countries geography

## 🐜 Bugs/issues
* it seems to have trouble cross loading the SVG file in iOS/Safari

## 🪪 License
* MIT License
