# Boston House Price Prediction Project

## Overview
This project aims to predict house prices in Boston using machine learning techniques. It utilizes a dataset containing various features such as crime rate, zoning information, and other socio-economic factors to predict the price of houses.

## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
```
├── app.py                   # Flask application for running the prediction API
├── templates                # HTML templates for web interface
│   ├── home.html            # Main HTML file for user interface
├── static                   # Static files such as CSS stylesheets
│   └── styles.css           # CSS styles for HTML templates
├── scaling.pkl              # Pickled scaler for scaling input data
├── regmodel.pkl             # Pickled regression model for house price prediction
└── README.md                # Documentation and project information
```

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Flask application:
   ```bash
   python app.py
   ```
2. Access the web interface by navigating to `http://127.0.0.1:5000` in your web browser.
3. Enter the required input parameters and click on the "Predict" button to get the predicted house price.

## Dependencies
- Flask
- NumPy
- Pandas
- Scikit-learn

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the [Apache License](LICENSE).

---

Feel free to customize this template according to your project's specific details. Let me know if you need further assistance or have any questions!