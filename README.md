# Appliance Energy Consumption Website

A responsive website showcasing information about appliance energy consumption in the Australian market. This project was created as part of a web development lab exercise.

## Features

- Three responsive pages: Home, Televisions, and About Us
- Interactive navigation with active page highlighting
- Clean and modern UI with responsive design
- Hover effects for better user interaction
- Properly structured HTML5 and CSS3

## Pages

1. **Home** - Introduction to appliance energy consumption
2. **Televisions** - Information about TV energy consumption
3. **About Us** - Information about the project and its purpose

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [Vercel](https://vercel.com) for deployment

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
   ```
2. Open the project folder
3. Open `index.html` in your browser

## Deployment

This project is deployed on Vercel. Any changes pushed to the `main` branch will trigger an automatic deployment.

Live Demo: [https://your-project-name.vercel.app](https://your-project-name.vercel.app)

## Data Story

### Audience
The primary audiences for this data story are Australian consumers who are in the market for a new television. They are looking for clear, practical information to help them choose an energy-efficient model that will save them money on their electricity bills over the long term. It is also a useful source of data of various television models in Australia, providing a repository of information for those curious in the various technologies used in modern televisions, and providing comparable data points for analysis.

### What They Want to Know
*   Which TV brands offer the most energy-efficient models?
*   How does brand choice impact potential energy consumption and cost?
*   What do the energy star ratings mean in a practical sense?
*   Are there any standout brands for energy efficiency?

### Presentation Strategy
The story will be presented on the "Televisions" page of the website. It will feature a prominent, interactive bar chart showing the number of high-efficiency TV models offered by different brands. This visualization will be accompanied by explanatory text that guides the user through the findings, explaining what the data means for their purchasing decision and offering actionable advice.

## About the data

### Data Source
The data is derived from the Equipment Energy Efficiency (E3) program, which is a cross-jurisdictional program through which the Australian Government, states and territories and the New Zealand Government collaborate to deliver a single, integrated program on energy efficiency standards and energy labelling for equipment and appliances. The specific dataset is sourced from [data.gov.au](https://data.gov.au/dataset/ds-dga-44299853-159f-4553-8051-3583b4653513/details).

### Data Processing
The raw data was processed to count the number of television models per brand that meet a high energy efficiency standard (e.g., a high Star Rating). This involved filtering the dataset for televisions, grouping by the 'brand' column, and counting the number of models in each group. The result is a summarized CSV file (`tvBrandCount.csv`) used for the visualization.

### Privacy, Accuracy, and Limitations
*   **Privacy**: The dataset contains information about appliance models, not individuals. No personal or private information is used.
*   **Accuracy**: The data is sourced from official government records and is considered accurate at the time of publication. However, model availability and specifications can change.
*   **Limitations**: This visualization focuses on the *number* of efficient models per brand, not the average efficiency across a brand's entire product line. A brand with many models might appear prominently, but this doesn't guarantee that *all* their models are efficient. Consumers should always check the specific energy rating of an individual model before purchasing.

### Ethics
The data is presented to empower consumers to make informed, environmentally and financially sound decisions. The visualization aims to be a fair and accurate representation of the underlying public data, without showing undue preference for any single brand.

## GenAI Acknowledgement

This project was created with the assistance of an AI. The AI helped with:
- Initial project setup and structure
- HTML, CSS, and JavaScript implementation
- Responsive design implementation
- Deployment guidance

## Author

Lu Min Yeu

## License

This project is open source and available under the [MIT License](LICENSE).
