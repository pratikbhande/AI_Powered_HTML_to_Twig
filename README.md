# HTML to Twig and SCSS Converter

This project provides a Streamlit-based web application that converts HTML files into Twig templates and extracts CSS styles into SCSS files. It leverages OpenAI's language model for intelligent content transformation and allows users to input HTML, CSS, and SCSS variables for streamlined output.

## Features

- **HTML to Twig Conversion**:
  - Converts HTML content into Twig templates.
  - Replaces static text with Twig variables.
  - Automatically generates reusable loops and conditional logic in Twig.

- **CSS to SCSS Conversion**:
  - Converts CSS styles into SCSS format.
  - Replaces hardcoded colors and fonts with SCSS variables.

- **Commented Twig Explanations**:
  - Outputs Twig templates with variable explanations in HTML comment format.

- **File Upload Options**:
  - Upload HTML, CSS, and SCSS variables files for processing.

- **Output Preview and Downloads**:
  - Displays the generated Twig and SCSS code directly in the app.
  - Provides download buttons for both outputs.

## Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.7+
- pip

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/html-twig-scss-converter.git
   cd html-twig-scss-converter
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

4. Open the app in your browser:
   - Default URL: `http://localhost:8501`

## Usage

1. Enter your OpenAI API key in the provided text field.
2. Upload the required files:
   - **HTML File**: The HTML file you want to convert.
   - **CSS File** (optional): An existing CSS file for conversion to SCSS.
   - **SCSS Variables File**: SCSS variables to be used for color and font substitutions.
3. Preview the outputs:
   - Twig and SCSS outputs are displayed in separate sections.
4. Download the results:
   - Use the download buttons to save the Twig and SCSS files.

## Example SCSS Variables File

```scss
$primary-color: #4CAF50;
$secondary-color: #2196F3;
$text-color: #333333;
$background-color: #F0F8FF;
```

## Technologies Used

- **Streamlit**: For building the web interface.
- **BeautifulSoup**: For parsing and manipulating HTML.
- **OpenAI API**: For generating Twig and SCSS outputs.

## Project Structure

```
.
├── app.py              # Main application script
├── requirements.txt    # Dependencies
├── README.md           # Documentation
```

## Contribution Guidelines

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch-name
   ```
5. Open a pull request.

## Acknowledgements

- [OpenAI](https://openai.com/) for providing the API used in this project.
- [Streamlit](https://streamlit.io/) for their user-friendly web app framework.

