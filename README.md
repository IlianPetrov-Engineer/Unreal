<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
This project was created as a university assignment for my Unreal Engine course. The goal of the project was to learn how to use the engine. For simplicity, the project required me to create a "walking simulator" with some interaction. In order to fulfil the requirements, I created a quest systems, which included location and gathering quest. On top of that, I implemented a simple inventory system to keep track of items. Every system was build using blueprints. 

<img width="2549" height="1425" alt="Screenshot 2026-08-18 154356" src="https://github.com/user-attachments/assets/746b21c2-4dd1-46b1-988a-2b1a105766eb" />
<img width="1274" height="713" alt="Screenshot 2026-07-05 144720" src="https://github.com/user-attachments/assets/a6b430dd-44fa-4fed-b2d3-7904a59e0d33" />
<img width="1270" height="712" alt="Screenshot 2026-07-05 144740" src="https://github.com/user-attachments/assets/cccc4914-8a04-4ffa-a267-9b87d7cb235d" />

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![UnrealEngine][Unreal.img]][Unreal-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* **Unreal Engine 5.7.4**
* **Visual Studio 2022 (or later) with ***Game development with C++*****  

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage
Open the project in the Unreal Editor, load **"Main"** and press the play button. This would skip the tittle screen. 

**Controls:**
* W / A / S / D - movement
* Mouse - look around

**Systems:**
* Quests - two kinds of quest:
  - Location quests - completed ones the player reaches a certain places by passing through a trigger
  - Gather quests - completed ones the player has collected a certain amount of items
 
* Inventory - stores, adds and subtracts collected items

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[Unreal.img]: https://img.shields.io/badge/Unreal%20Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white
[Unreal-url]: https://www.unrealengine.com/
