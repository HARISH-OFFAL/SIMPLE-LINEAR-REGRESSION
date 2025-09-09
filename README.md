# SIMPLE-LINEAR-REGRESSION
This project provides a basic implementation of a simple linear regression model using Python, `scikit-learn`, `pandas`, and `matplotlib`. The model predicts salary based on years of experience. It is a fundamental project designed to demonstrate the end-to-end process of a machine learning workflow.

## Project Structure

- `simple_linear_regression.py`: The main Python script that builds, trains, and evaluates the linear regression model.
- `salary_data.csv`: The dataset used for training and testing the model.
- `README.md`: This file, explaining the project.
- `requirements.txt`: Lists the Python libraries required to run the project.

## Prerequisites

Before running the script, ensure you have Python 3 installed. You can check your version by running `python --version` or `python3 --version` in your terminal.

## Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name
    ```

2.  **Install dependencies**:
    Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    # For Windows
    venv\Scripts\activate
    # For macOS/Linux
    source venv/bin/activate
    ```
    Install the required libraries using `pip`:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Run the script**:
    ```bash
    python simple_linear_regression.py
    ```

2.  **Output**:
    The script will print the model's coefficients (intercept and slope) to the console and display two plots showing the regression line on both the training and testing data.

    ```text
    Intercept (b0): 25321.58
    Coefficient (b1): 9427.64

    Predicted salary for 12 years of experience: $138,442.23
    ```

## Dependencies

The project relies on the following Python libraries:
*   `numpy`
*   `pandas`
*   `matplotlib`
*   `scikit-learn`

These are automatically installed when you run `pip install -r requirements.txt`.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
