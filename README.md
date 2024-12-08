# Global Data- & Resourcepacks
# Description:
This mod is a small utility for modpack creators in 1.13+
Datapacks have to be copied into every world separately, this mod changes this.
It adds the possibility to define global Data- & Resourcepacks.
Additionally, you can choose whether they are required or optional. (Only in newer versions)

Besides Datapacks since 1.16 it does also allow you to force enable resource packs.

# Usage
Upon installing the mod & running the game at least once, you'll find a new configuration file in your "config" directory. In there you can list either folders or specific files, to be treated as data or resource packs. In recent versions you have to create these folders on your own, in older versions they were generated automatically.

The default configuration is capable of loading data packs from the resource packs folder. And uses following folders by default (please check your config file, those are different based on your version):
• global_packs/required_data
• global_packs/optional_data
• global_packs/required_resources
