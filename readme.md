<!--suppress HtmlDeprecatedAttribute -->
<br/>

<div align="center">
	<img height="200" src="https://raw.githubusercontent.com/PokeAPI/media/master/logo/pokeapi.svg?sanitize=true" alt="PokeAPI Logo">
    <h1>PokéGuillardi</h1>
    <p>A Pokédex web app built with vanilla HTML, CSS, and JavaScript, powered by the <a href="https://pokeapi.co/">PokéAPI</a>.</p>
    <p>
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
        <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
    </p>
</div>

---

## Overview

PokéGuillardi is a lightweight, responsive Pokédex that lets you search and browse all Pokémon using data from the [PokéAPI](https://pokeapi.co/). No frameworks, no dependencies — just plain HTML, CSS, and JavaScript.

---

## Screenshots

### Desktop

![web](https://user-images.githubusercontent.com/63321040/189497702-10cb6e33-d8d9-4489-bafa-7e461cb6bd45.png)

### Mobile

![mobile](https://user-images.githubusercontent.com/63321040/189497727-8f287824-bb3f-41d9-9fb7-5c29258a783f.png)

---

## Features

- Search any Pokémon by **name** or **Pokédex number**
- Navigate through the entire Pokédex with **Prev / Next** buttons
- Displays **animated Gen V sprites** with fallback to the default sprite for newer Pokémon
- Fully **responsive** — works on both desktop and mobile
- Loads Pokémon data asynchronously with proper **error handling**

---

## Tech Stack

| Technology | Version |
|---|---|
| HTML | 5 |
| CSS | 3 |
| JavaScript | ES6+ |
| PokéAPI | v2 |

---

## Project Structure

```
pokedex/
├── src/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   ├── images/
│   │   └── pokedex.png
│   └── favicons/
│       └── favicon.png
└── readme.md
```

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/JoseGu1llardi/pokedex.git
   ```
2. Open `src/index.html` in your browser — no build step needed.

---

## API

All Pokémon data is fetched from the [PokéAPI](https://pokeapi.co/):

```
GET https://pokeapi.co/api/v2/pokemon/{name or id}
```

---

<div align="center">
    <p>Made by <a href="https://github.com/JoseGu1llardi">Guillardi</a></p>
</div>
