# Functional Requirements

The functional requirements are loosely grouped by concept.

## Game Core

- FR101: The system shall provide a playable game environment that a user can navigate.
  - High priority
  - BR1

- FR102: The system shall feature a main menu.
  - High priority
  - BR1

- FR103: The system shall feature a pause menu accessible during gameplay.
  - High priority
  - BR1
  
- FR104: The main menu shall provide clear, clickable options to start the game.
  - High priority
  - BR1

- FR105: The system shall feature a settings menu accessible from the main and pause menus.
  - Low priority
  - BR1

## Contentstack Integration - Dynamic Content

- FR201: All non-player character (NPC) dialogue text shall be retrieved directly from Contentstack.
  - Medium priority
  - BR1

- FR202: The system shall dynamically load environmental textures and object sprites from Contentstack to construct game levels.
  - High priority
  - BR1

- FR203: The system shall dynamically load node game objects / levels from Contentstack.
  - Medium priority
  - BR1

- FR204: The system shall populate game environments with sprites, decorations, or other features managed within Contentstack.
  - Low priority
  - BR1

- FR205: The system shall feature a "Latest News" or "Patch Notes" section where all articles are managed and retrieved from Contentstack.
  - Low priority
  - BR1

## Stretch Goals

- FR401: The system shall feature an in-game economy with currency or items that can be gathered by the player.
  - Low priority
  - BR1

- FR402: A player shall be able to purchase skins or other items in the storefront using the in-game currency.
  - Low priority
  - BR1

- FR403: Upon acquiring a cosmetic item (e.g., a skin), the system must retrieve the associated game assets from Contentstack and apply them to the player's in-game model.
  - Low priority
  - BR1
  
- FR404: The system shall be capable of displaying a simple, dynamic in-game event (e.g., a "Happy Hour" banner, different graphics) that is triggered by a value managed in Contentstack.
  - Low priority
  - BR1

- FR405: The system shall display a navigable in-game storefront.
  - Low priority
  - BR1

- FR406: All items displayed in the storefront (e.g., names, descriptions, images, display cost) must be retrieved directly from the Contentstack environment.
  - Low priority
  - BR1

- FR407: The system must reflect updates made to the storefront content within Contentstack, allowing a Sales Engineer to demonstrate changes.
  - Low priority
  - BR1

# Non-functional Requirements

- NR1: The application must be a standalone executable that runs on Apple's macOS.
  - High priority
  - BR1

- NR2: The application's user interface, menus, and in-game assets must have a polished and professional visual design.
  - High priority
  - BR1

- NR3: The source code must be developed using a mainstream, well-documented game engine or technology that can be easily maintained by Contentstack's engineers.
  - High priority
  - BR1

- NR4: Navigation between the game, main menu, storefront, and news sections must be intuitive and seamless with minimal loading times.
  - Medium priority
  - BR1

- NR5: All private API keys or other credentials used to connect to the Contentstack environment must be stored securely and not be exposed in the final application build.
  - High priority
  - BR1

- NR6: The application should include a simple mechanism (e.g., a keyboard shortcut or debug menu) to reset or reload the demo's state for repeatable presentations by Sales Engineers.
  - Low priority
  - BR1
