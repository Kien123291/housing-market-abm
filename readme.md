# Housing Market Agent-Based Model (ABM)

This project simulates a simplified housing market using an Agent-Based Model (ABM) to explore dynamics of rent pricing, household decision-making, and landlord behavior. It is developed in Python via a Jupyter Notebook and draws from real-world rent data.

## Overview
The model features two key types of agents:
- **Households**: Each household has traits like income, rent sensitivity, and housing preferences. They evaluate units based on affordability and amenity.
- **Landlords**: Landlords manage housing units, adjust rents based on demand, and attempt to minimize vacancy.

Each unit exists within a neighborhood with a defined amenity level. Agents interact in a simulated environment where rents adjust over time, vacancies shift, and households may move based on satisfaction and costs.

## Data Used
- **FMR Dataset** (Fair Market Rent by HUD): Used to set initial rents and derive rent growth rates by room type and state.
- Additional synthetic values are generated for variables not available in public datasets (e.g., household mobility, amenity preferences).

## Key Features
- Assigns average rent by unit size and state using real data.
- Simulates rent increase dynamics over time.
- Models household movement based on utility.
- Visualizes agent behavior and rent trends.

## How to Run
1. Open `Project3_ABM.ipynb` in Jupyter.
2. Run each cell from top to bottom.
3. Modify model parameters to experiment with different dynamics.

## Future Improvements
- Add demographic diversity (e.g., race, education).
- Integrate spatial layout for more realistic neighborhoods.
- Include construction or demolition behaviors.
- Calibrate against more granular datasets (e.g., census tracts).

## License
MIT License.

---

Feel free to build upon or customize this model to explore more complex urban housing dynamics.

