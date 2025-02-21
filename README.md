# Kenyan Economy Crisis Risk Model

This project is a web-based adaptation of the "Kenyan Economy Crisis FIS" project, originally developed in MATLAB. It uses fuzzy logic to model the risk of an economic crisis in Kenya based on two key inputs: default risk and economic growth. The web app features an interactive interface where users can adjust sliders to see real-time updates of the crisis risk, accompanied by a 3D surface plot visualization.

## Features

* **Interactive Sliders**: Adjust default risk (0 to 1) and economic growth (-5% to 5%) using HTML5 range sliders.
* **Real-time Crisis Risk Calculation**: The crisis risk is computed and displayed instantly as the sliders are moved.
* **3D Surface Plot**: A Plotly.js-powered 3D surface plot visualizes the relationship between default risk, economic growth, and crisis risk.
* **Marker on Plot**: A red marker highlights the current slider values and corresponding crisis risk on the surface plot.
* **Client-side Computation**: All computations are performed in the browser using JavaScript, eliminating the need for a server.

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/kenyan-economy-crisis-model.git
   cd kenyan-economy-crisis-model
   ```

2. **Open the HTML File**:
   * Open index.html in a modern web browser (e.g., Chrome, Firefox).

**Note**: The project uses Plotly.js, which is loaded via a CDN in the HTML file. An internet connection is required to load the library. For offline use, download Plotly.js and host it locally by updating the script reference in index.html.

## Usage

1. **Adjust the Sliders**:
   * **Default Risk Slider**: Ranges from 0 to 1 (e.g., 0.5 represents a 50% default risk).
   * **Economic Growth Slider**: Ranges from -5% to 5% (e.g., -2% represents negative growth, 3% represents positive growth).

2. **View Real-time Updates**:
   * The crisis risk value updates instantly below the sliders as you adjust the inputs.
   * The red marker on the 3D surface plot shifts to reflect the current slider values and crisis risk.

3. **Interpret the Surface Plot**:
   * **X-axis**: Economic growth.
   * **Y-axis**: Default risk.
   * **Z-axis**: Crisis risk.
   * The plot visually demonstrates how different combinations of default risk and economic growth influence the crisis risk.

## Technology Stack

* **HTML5**: Structures the web page and sliders.
* **CSS**: Provides basic styling for the interface.
* **JavaScript**: Implements the fuzzy logic system and manages real-time updates.
* **Plotly.js**: Enables the interactive 3D surface plot.

## Contributing

Contributions are welcome! To contribute to the project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```

3. Make your changes and commit them with descriptive messages:
   ```bash
   git commit -m "Add feature-name"
   ```

4. Push your changes to your fork:
   ```bash
   git push origin feature-name
   ```

5. Submit a pull request to the main repository.

## Potential Contribution Areas

* Enhancing the fuzzy logic model with additional rules or fuzzy sets.
* Improving the user interface and experience (UI/UX).
* Optimizing the performance of the fuzzy logic computations.
* Adding more economic factors to the model.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

* The original "Kenyan Economy Crisis FIS" project, developed in MATLAB by Daddison (@cadaces254), which served as the inspiration for this web adaptation.
* Plotly.js for providing powerful interactive visualization tools.
* The open-source community for the resources and libraries that made this project possible.
