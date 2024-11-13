# Pokémon TCG Pack Opening Simulator

This project simulates opening booster packs from the Pokémon Trading Card Game, specifically focusing on collecting cards from the Mewtwo, Pikachu, and Charizard collections.

## Features

* **Realistic Simulation:** Employs real-world card distributions and rarities to mimic the actual pack-opening experience.
* **Targeted Collections:** Allows you to track your progress towards completing the Mewtwo, Pikachu, and Charizard sets.
* **Cost Tracking:** Calculates the total money invested based on the number of packs opened.
* **Progress Visualization:** Displays real-time updates on packs opened, collection sizes, and money spent.
* **Easy to Use:** Simply run the `get_entire_collection()` function to begin the simulation and track your collection journey.

## How it works

The project uses pandas DataFrames to store card data and simulates pack openings using probability-based selection. The `get_pack_[pack_name]()` functions generate individual packs, while `get_entire_collection()` orchestrates the process until all collections are complete.

## Usage

1. Run the code cells in the provided Colab notebook to load data and define functions.
2. Execute `get_entire_collection()` to start the simulation.
3. Observe the progress and results displayed during the simulation.
4. **To reset your collection and start a new simulation, execute the `reset()` function.** 

## Disclaimer

This project is purely for entertainment and educational purposes. It does not offer real-world purchasing or trading functionality.

## Contributing

Feel free to fork the repository and contribute enhancements or bug fixes. Pull requests are welcome!
