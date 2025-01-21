
![Banner 1](https://github.com/user-attachments/assets/392bcbbd-174d-4cbe-a7af-4f7643e90b7a)

Welcome to the repository for **The Atlas Six**, an immersive RPG game where choices shape the destiny of a diverse group of characters navigating a mystical world. This document will guide you through the structure, features, and current state of the project. Dive in if you dare, and may your journey be as enigmatic as the forces that bind the characters of **The Atlas Six**.

---

## Table of Contents

- [Project Vision](#project-vision)
- [Game Features](#game-features)
- [Character Overview](#character-overview)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Installation Guide](#installation-guide)
- [Development Setup](#development-setup)
- [Notes and Tips](#notes-and-tips)
- [Contributing](#contributing)
- [License](#license)

---

## Project Vision

>[!Caution]
>The Atlas Six is a desktop only game. Currently the project is not open-source. I have left the contribution procedure as I plan to make it open-source after public release.

The **Atlas Six** is a story-driven RPG set in a world of magic, ancient mysteries, and alliances that are not always what they seem. The journey revolves around the choices made by the player and the evolving relationships within the party. At the heart of the game, you'll find the **Atlas Six**—a group of heroes bound by a common fate, though each of them carries their own burdens.

In a world where secrets lie behind decisions made, one thing is certain: not all allies are as trustworthy as they seem, and the line between friend and foe is often blurred. Will you forge an alliance, uncover the truth, or destroy everything in your path?

---


## Game Features

- **Branching Storylines**: Your choices will shape the narrative, leading to different outcomes.
- **Dynamic Character Interactions**: Develop relationships with members of the **Atlas Six** and influence the course of the game.
- **Combat System**: Engage in fast-paced battles with mechanics like quick attack decisions and combos.
- **Mini-Games**: Combat is not always won on the battlefield. Your mind often finds itself at war with tests, riddles and mini games, changing the course of your story.
- **Interactive NPCs**: Converse with NPCs to uncover the truth but beware: the truth is not always pretty.

---
## Character Overview

Each member of the **Atlas Six** has a distinct background, personality, and role to play in the unfolding drama. However, not all is as it seems. Who can you trust when the darkness looms closer? 

### The Atlas Six

| Name      | Role         | Description                                             |
|-----------|--------------|---------------------------------------------------------|
| Player      | ???          | This is your character. You choose to play however you want.                |
| Maylyn      | Archer       | Known as "The Eye" for her exceptional accuracy. She often tends to tease you but your friendship is parellel to the Sun and Moon.|
| Jade    | Healer       | A nurturing healer with a deep connection to water magic. She sees you as the family she adores.|
| Ryan | Titan          | A formidable warrior and general but most importantly your close friend.        |
| Aiyana    | Phoenix          | Your strategist, mentor and even former enemy. You are Aiyana's greatest student|
| The Sixth Atlas     | ???   | A friend or foe you shall encounter in the Known World. Based on your decisions.|

>[!Note]
> Other characters will be revealed through the progression of the game. Trust is earned, not freely given.


---
## Technologies Used

| Technology            | Description                                          |
|-----------------------|------------------------------------------------------|
| HTML                  | Structure of the game content and pages              |
| CSS                   | Styling for UI and animations                        |
| JavaScript            | Game logic, event handling, and animation control    |
| Firebase              | User authentication for sign-in and sign-up          |
| IntersectionObserver  | Animation performance optimization                   |

---


## File Structure

The project follows this File structure:
```txt
+---Audio  
|   +---Effects  
|       Contains sound effects used in the game, such as attack sounds, environmental noises, and action-based audio cues.
|   +---Music 
|       Contains music used in the game.

+---Errors XD  
|      A folder for debugging or logging errors during development. This stores screenshots, logs, or test files related to issues encountered. Also just a funny place to store bugs

+---Images  
|   +---Assets  
|   |   +---Actions  
|   |       Images representing player or enemy actions, such as attack animations or interaction visuals.  
|   |   +---EnemyAttacks  
|   |       Visuals for enemy attack animations or effects.  
|   |   +---Icons  
|   |       Small graphical elements, such as ability icons, status effects, or inventory indicators.  
|   |   +---Skills  
|   |       Artwork for various skills available to the characters, showcasing their abilities.  
|   |   +---Stats  
|   |       Graphics representing character or enemy stats like health, mana, or charisma.  
|   +---Banners  
|       Larger images used for promotional materials within the game.  
|   +---Character Profile Background  
|       Background visuals for character profiles or menu screens that highlight character details.  
|   +---Characters  
|   |   +---Classes  
|   |       Character designs or concept art based on their classes, e.g., warrior, mage, healer.  
|   |   +---Outfits  
|   |       Variations of character appearances, such as alternate outfits or armor sets.  
|   +---Choices  
|       Visual representations for player decision points, emphasizing the branching storyline.  
|   +---Cut Images  
|       Cropped or trimmed images used in specific parts of the UI.  

+---Old-Code  
|       Deprecated or backup code from earlier versions of the game. Useful for referencing previous implementations or restoring older features.

+---out  
|       A folder for build outputs, storing compiled or packaged game files for distribution or testing. Currently inlcudes Lines counted in the workspace.

+---Videos  
|       Contains cinematic sequences, cutscenes, or instructional videos integrated into the game.


```

---

## Installation Guide

To get started with the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/The-Atlas-Six.git

- Or Download the .zip folder and extract all the files.
Navigate into the project folder:

cd The-Atlas-Six
Open the index.html file in your browser to play the game.


## Development Setup

For developers looking to contribute or set up the game environment:

1. Ensure you have a code editor such as [Visual Studio Code](https://code.visualstudio.com/).
2. If you are planning to use Firebase, make sure to set up Firebase Authentication and configure the API keys in the `js/firebase.js` file.
3. If you want to implement Tauri for desktop packaging, follow the instructions in the Tauri setup documentation for proper C++ dependencies.

---

## Notes and Tips

- The game utilizes complex branching paths, so any changes to the storyline JSON structure should be tested thoroughly.
- Ensure all animations and interactive UI elements are optimized for low-end PCs (4GB RAM, i3 processors).
- Keep an eye on performance when implementing complex combat mechanics and memory mini-games.
- The current file size is approximately **900MB** due to assets like images and sounds; consider using compression tools if needed.

---

## Contributing

If you want to contribute to the game, feel free to fork the repository, submit pull requests, or report issues. Here's how you can get involved:

1. Fork the repository
2. Create a new branch for your feature or fix
3. Commit your changes
4. Submit a pull request with a detailed explanation of your contributions

---

## License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute the game as long as proper credit is given. See the `LICENSE` file for more details.

---

## End of Document
> [!Tip]
> The road is never easy but one we must walk. A Passion over Pain product.

For questions or support, contact the me at **[Email](mailto:tinomhedziso21@gmail.com)**.

---




