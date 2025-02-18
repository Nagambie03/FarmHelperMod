FarmHelperMod

FarmHelperMod is a Minecraft auto-farm mod designed for Fabric. It automates the harvesting and replanting of crops—including wheat, carrots, potatoes, beetroots, pumpkins, melons, sugar cane, and bamboo—while also offering auto-movement to cover large farm areas.
Features

    Automated Harvesting & Replanting:
    Harvests fully grown crops and replants them automatically.

    Special Handling for Specific Crops:
        Sugar Cane & Bamboo: Only the upper stems are harvested, leaving the base intact for regrowth.
        Pumpkins, Melons, Bamboo: Switches to an axe automatically for efficient breaking.

    Auto-Movement:
    Scans a defined radius for fully grown crops and auto-walks toward them if they're out of immediate range.

    Customizable Delay & Range:
    Includes adjustable replant delays and scanning ranges based on the player's movement.

Installation

    Requirements:
        Minecraft (version 1.21.4)
        Fabric Loader (version 0.16.10)
        Fabric API (version 0.113.0+1.21.4)

    Download:
    Download the latest jar file from the Releases section.

    Installation:
    Place the downloaded jar file into your Minecraft mods folder.

Usage

    Toggling the Mod:
    Press the = key (or the key you have bound) to toggle the auto-farm on and off.

    Auto-Movement:
    The mod automatically scans for fully grown crops within a specified radius and moves your character towards them if they're not in range.

    Crops Handled:
        Wheat, Carrots, Potatoes, Beetroots: Harvested and replanted.
        Pumpkins & Melons: Harvested using an axe and replanted.
        Sugar Cane & Bamboo: Only the upper stems are broken so that the base remains to regrow.

Building

    Clone the Repository:

git clone https://github.com/yourusername/FarmHelperMod.git

Import into your IDE:
Use IntelliJ IDEA or Eclipse with the Fabric Loom plugin installed.

Build:
Run the gradle build task:

    ./gradlew build

    The compiled jar will be located in the build/libs folder.

Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Credits

    Fabric API
    Minecraft Community  
