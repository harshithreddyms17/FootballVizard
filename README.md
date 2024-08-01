# Euro 2020 FootballVizard

Welcome to the **Euro 2020 FootballVizard**! This web application allows you to visualize and compare various football statistics from the Euro 2020 tournament.

## Features

- **Team Lineups**: View lineup images for two teams.
- **Passing Network Analysis**: Display visual representations of passing networks.
- **Heat Map**: Analyze player activity with heat maps.
- **Shot Map**: See where shots were taken with shot maps.

## Getting Started

To use the Euro 2020 FootballVizard:

1. **Select Teams**:
   - Use the "Choose a Team" dropdown menu to select your team.
   - Use the "Opponent Team" dropdown menu to select the opposing team.

2. **Display Stats**:
   - Click the "Display Stats" button to update and view the relevant images based on the selected teams.

## File Structure

- `index.html`: Main HTML file with the application layout and functionality.
- `static/index.css`: Stylesheet for custom styling.
- `static/images/lineups/`: Directory containing team lineup images.
- `static/images/PassingNetwork/`: Directory containing passing network analysis images.
- `static/images/HeatMaps/`: Directory containing heat map images.
- `static/images/Shotmaps/`: Directory containing shot map images.

## Code Overview

- **HTML**: Defines the structure of the page, including headers, dropdown menus, and image placeholders.
- **CSS**: Provides styling for visual elements.
- **JavaScript**:
  - `displayImage()`: Dynamically updates image sources based on selected teams.
  - `changeCountry()`: Populates the opponent team dropdown based on the selected country.

### JavaScript Functions

- **`displayImage()`**: 
  - Retrieves the selected team and opponent.
  - Updates image sources for team lineups, passing network, heat map, and shot map.

- **`changeCountry()`**:
  - Updates the opponent team dropdown based on the selected country.
  - Allows users to choose from relevant opponents for the selected team.

## Contributing

We welcome contributions! If you would like to contribute to this project:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request with a description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **Euro 2020**: For the exciting football tournament data and stats.
- **Google Fonts**: For the Pacifico font used in the application.

Feel free to explore and modify the project as needed. Enjoy visualizing Euro 2020 stats!

---

For any questions or feedback, please open an issue on the [GitHub repository](https://github.com/Atrix21/FootballProject).
