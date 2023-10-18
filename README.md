# House Price Prediction with Linear Regression

## Overview

This is a machine learning project that predicts house prices using a linear regression model. The project includes a front-end built with HTML, CSS, and JavaScript, and a back-end powered by Flask in Python. The main server logic is implemented in `server.py`, while the front-end consists of `index.html` and other related files.

## Getting Started

### Prerequisites

- Python 3.x
- Flask (install via `pip install flask`)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/jayumap/House-Price-Prediction.git
    cd HOUSEPREDICT
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Project Structure

- **`server.py`**: This file contains the Flask server code that handles requests and serves predictions using the linear regression model.

- **`static/`**: This directory contains static files such as CSS and JavaScript.

- **`templates/`**: This directory holds HTML files. `index.html` is the main file for the front-end.

- **`model/`**: This directory can be used to store the trained machine learning model or any related files.

## Usage

1. Run the Flask server:

    ```bash
    python server.py
    ```

2. Open your web browser and go to `http://localhost:5000` to access the application.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and suggestions are highly appreciated.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to [Data Science University](https://www.datascienceuniversity.com/) for providing the dataset used in this project.

---

**Note:** Make sure to replace placeholders such as `your-username` with your actual GitHub username and update the project details accordingly.

This README provides a basic structure. Depending on the complexity of your project, you might want to include additional sections such as "Features," "Deployment," "Contributing Guidelines," etc.