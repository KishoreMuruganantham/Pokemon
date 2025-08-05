# PokéVerse  
_Explore. Battle. Evolve. The Pokémon Universe Awaits!_

![PokéVerse Banner](https://i.redd.it/egrnbbpkdxcd1.png)

Welcome to **PokéVerse** – your all-in-one, open-source Pokémon framework! Dive into the world of Pokémon data, mechanics, and gameplay with a robust, extensible platform built for fans, developers, and researchers.

---

## 🏗️ Tech Stack & Architecture

PokéVerse is a technically rich project inspired by the official games and powered by community-driven tools and modular design.

### **Core Language & Framework**
- **Ruby**: The backbone for all gameplay logic and scripting.
- **Pokemon Essentials v21.1**: Industry-standard toolkit for fan-made games, extended and hotfixed for stability.

### **Project Structure**

- `PBS/`
  - **abilities.txt**: Defines hundreds of Pokémon abilities, from classics like *Torrent* and *Drought* to the latest like *Libero* and *Dauntless Shield*. Each ability includes a name and gameplay description.
  - **items.txt**: Comprehensive item database, including Mega Stones, Key Items (e.g., Prison Bottle, Zygarde Cube), and evolution items. Organized by game generation (Gen 7, Gen 8).
  - **Gen 7 backup/abilities.txt & Gen 8 backup/abilities.txt**: Backup files for legacy abilities, supporting compatibility and easy upgrades.
  - **Gen 7 backup/items.txt & Gen 8 backup/items.txt**: Legacy and upgradeable item sets for smooth migration and custom ROM support.

- `Plugins/v21.1 Hotfixes/`
  - **meta.txt**: Plugin metadata, changelog, and credits. Ensures the stability and compatibility of the Essentials engine.
  - **Misc bug fixes.rb**: Ruby modules fixing core gameplay bugs (Pokédex UI, AI switching, event handling, phone contacts, map logic, animated sprites, locale issues).

- `LICENSE`
  - MIT License for full openness and commercial use.

### **Key Technical Features**

- **Modular Ruby Scripting**
  - All game logic (battle system, UI, item handling, special events) is written in Ruby, leveraging object-oriented patterns for maintainability and extensibility.
  - **Bug Fix Plugins**: Seamlessly integrated to patch engine issues without modifying the core codebase.

- **Data-Driven Design**
  - Pokémon abilities, items, and mechanics are defined via PBS (Pokémon Script) files. This allows for:
    - Easy editing and expansion
    - Versioned backups for each generation
    - Rapid prototyping of new features

- **Compatibility & Migration**
  - Gen 7/Gen 8 backups ensure you can update, revert, or port data between generations with minimal effort.

- **Key Items and Mega Evolution**
  - Detailed implementation for Mega Stones, custom items (Rotom Catalog, DNA Splicers), and advanced evolution mechanics.

- **Battle System & AI**
  - Hotfixes improve AI decisions, battle event handling, and complex form changes (e.g., Cramorant’s Gulp Missile, Rotom forms).

### **Development & Extensibility**

- **Community Plugins**: Easily add new features or fix existing ones.
- **Open Data Format**: Tweak game mechanics, add new Pokémon, moves, or items by editing simple text files.
- **Strong Foundation**: Built on an actively maintained engine, with plenty of room for custom scripts, UI themes, and gameplay extensions.

---

## 🚀 Features

- Full Generation 7 & 8 ability and item support
- Modular bug-fix plugin system
- Advanced battle mechanics
- Editable datasets for custom Pokémon, moves, and items
- Easy migration between game generations
- Open-source licensing for personal and commercial projects

---

## 📦 Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/KishoreMuruganantham/PokeVerse.git
    cd PokeVerse
    ```
2. **Install Ruby (if needed)**
3. **Setup Pokémon Essentials v21.1**
4. **Run or build your game with your favorite Essentials-compatible editor**

---

## 🖼️ Screenshots

| Home Page | Pokémon Details | Battle Simulator |
|:---------:|:--------------:|:----------------:|
| ![Home](https://www.nintendo.com/eu/media/images/06_screenshots/games_5/game_boy_advance_2/gba_pokemonrubyandsapphire/GBA_PokemonRubyAndSapphire_05.png) | ![Details](https://www.smogon.com/forums/attachments/pokemon-emerald-version-usa-europe-_105-png.314123/) | ![Battle](https://static1.cbrimages.com/wordpress/wp-content/uploads/2024/08/pokemon-frlf-double-battle.jpg) |

---

## 🧑‍💻 Contributing

We welcome contributions!  
Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## ❓ FAQ

**Q:** Is this project affiliated with Nintendo or Game Freak?  
**A:** No, PokéVerse is an independent, open-source project for educational and entertainment purposes.

**Q:** How can I request a new feature?  
**A:** Open an issue or join the discussions tab!

**Q:** Can I use PokéVerse for commercial purposes?  
**A:** Yes, PokéVerse is MIT licensed.

---

## 📬 Contact

- **GitHub:** [KishoreMuruganantham](https://github.com/KishoreMuruganantham)
- **LinkedIn:** [Kishore M](https://www.linkedin.com/in/kishore-m-13a7402a7/)
- **Email:** kishore.muruganantham@gmail.com

---

## ⭐️ Star & Share

If you like PokéVerse, please ⭐️ the repo and share with fellow Pokémon fans and developers!

---

## 🪪 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

> _PokéVerse: Explore. Battle. Evolve. The Pokémon Universe Awaits!_  
> _“Gotta catch ’em all!”_
