# flask_presidents_app

This is a Flask web application that provides information about the Presidents of the United States. The application displays a list of presidents and detailed information about each president.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- List of all U.S. Presidents
- Detailed information about each president
- Links to Wikipedia entries for each president
- Responsive design

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/presidents_app.git
   cd presidents_app
   ```

2. Create a virtual environment and activate it:

   ```sh
   python -m venv .venv
   source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:

   ```sh
   python presidents.py
   ```

2. Open your web browser and navigate to `http://localhost:666`.

## Project Structure

presidents_app/ ├── .gitignore ├── freeze.py ├── modules.py ├── presidents.csv ├── presidents.py ├── README.md ├── requirements.txt ├── pycache/ ├── build/ │ ├── index.html │ ├── president/ │ ├── static/ ├── static/ │ ├── css/ │ │ └── main.css ├── templates/ │ ├── base.html │ ├── index.html │ └── president.html

- `presidents.py`: Main Flask application file.
- `modules.py`: Contains helper functions for the application.
- `presidents.csv`: CSV file containing data about U.S. Presidents.
- `templates/`: Contains HTML templates for the application.
- `static/`: Contains static files such as CSS.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
