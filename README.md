# Prompt Library

This is a collection of prompts for various tasks, built with MkDocs and Material for MkDocs.

## Prerequisites

- **Python**: This project requires Python (version 3.x). You can download it from the [official Python website](https://www.python.org/downloads/). During installation on Windows, make sure to check the box that says "Add Python to PATH".

- **pip**: The Python package installer. It is usually included with Python installations. You can check if it's installed by running `pip --version`.

- **MkDocs**: This project uses MkDocs with the Material theme. The necessary packages are listed in `requirements.txt` and will be installed in the setup process.

## Setup and Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/zshn-dev/prompt-library.git
    cd prompt-library
    ```

2.  **Create a virtual environment and install dependencies:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3.  **Start the development server:**
    ```bash
    mkdocs serve
    ```
    Open your browser to [http://127.0.0.1:8000](http://127.0.0.1:8000) to see your documentation.

## Project Structure

-   `mkdocs.yml`: The configuration file for MkDocs.
-   `index.md`: The homepage for the documentation.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.
