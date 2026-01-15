# babylon.js-dungeon
First person dungeon crawler made in babylon.js

## Project Structure

```
babylon.js-dungeon/
├── src/                    # Source code
│   ├── core/              # Core game engine functionality
│   ├── systems/           # Game systems (input, physics, AI)
│   ├── entities/          # Game entities (player, enemies, items)
│   ├── scenes/            # Game scenes (menu, gameplay, pause)
│   ├── ui/                # User interface components
│   └── utils/             # Utility functions and helpers
├── assets/                 # Game assets
│   ├── models/            # 3D models
│   ├── textures/          # Texture files
│   ├── sounds/            # Audio files
│   └── materials/         # Material definitions
├── public/                 # Static files
│   ├── css/               # Stylesheets
│   ├── js/                # Compiled JavaScript
│   └── index.html         # Main HTML entry point
├── docs/                   # Documentation
├── package.json            # Project configuration
└── tsconfig.json          # TypeScript configuration
```

## Getting Started

This is the basic project architecture. Implementation details will be added in future development phases.

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

## Architecture Overview

### Core
Contains the fundamental game engine components including initialization, game loop, and scene management.

### Systems
Modular game systems such as:
- Input handling
- Physics and collision detection
- AI and pathfinding
- Inventory management
- Audio management

### Entities
Game objects including:
- Player character
- Enemies and NPCs
- Items and pickups
- Environmental props

### Scenes
Different game states:
- Main menu
- Gameplay scene
- Pause menu
- Game over screen

### UI
User interface elements:
- HUD (health, inventory, minimap)
- Menus and dialogs
- Interactive elements

### Utils
Helper functions and utilities for common tasks like math operations, data loading, and general helpers.

## License

ISC
