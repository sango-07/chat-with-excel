# Chat with Excel/CSV

## Overview
"Chat with Excel/CSV" is an interactive web application built with Streamlit. This app enables users to interact with Excel or CSV files using AI-powered tools, providing an intuitive way to query and analyze data. Leveraging LangChain, the app integrates SQL querying and profiling tools to enhance user experience.

## Features
- **Interactive Queries**: Chat with your data to ask questions and retrieve insights in natural language.
- **Data Profiling**: Generate comprehensive reports on uploaded datasets with `ydata-profiling`.
- **File Compatibility**: Supports `.csv` and `.xlsx` file uploads.
- **Custom Styling**: User-friendly interface with enhanced visuals.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8 or above
- pip (Python package installer)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/sango-07/chat-with-excel.git
   cd chat-with-excel
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Upload an Excel or CSV file through the interface.
2. Interact with the file using natural language queries.
3. View data summaries and profiles directly in the app.

## Dependencies
The project relies on the following key libraries:
- **Streamlit**: For building the user interface.
- **LangChain**: For natural language data interaction.
- **Pandas**: For data manipulation.
- **ydata-profiling**: For generating detailed data profiles.

Refer to `requirements.txt` for the complete list of dependencies.

## File Structure
- **app.py**: Main application script.
- **requirements.txt**: List of dependencies.
- **README.md**: Project documentation.

## Contribution
Contributions are welcome! Feel free to fork the repository and create pull requests for enhancements or bug fixes.

## License
This project is licensed under the MIT License.

## Contact
For queries or support, please contact info.sangram@yahoo.com

