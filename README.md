# Banking Data Generator

This project generates random banking transaction data and stores it in a PostgreSQL database. The data includes various merchant categories and card types.

## Setup

1. **Clone the repository:**
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Create and activate a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Set up the PostgreSQL database:**
    Ensure you have PostgreSQL installed and running. Update the database connection details in `app.ipynb` if necessary.

2. **Run the Jupyter Notebook:**
    ```sh
    jupyter notebook app.ipynb
    ```

3. **Generate and store data:**
    Execute the cells in the Jupyter Notebook to generate random banking transaction data and store it in the PostgreSQL database.

## Data is visualized with grafana cloud


