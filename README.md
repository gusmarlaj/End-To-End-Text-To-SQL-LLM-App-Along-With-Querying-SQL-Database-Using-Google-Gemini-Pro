# Gemini SQL Query Retrieval

This repository contains a Streamlit application that utilizes Google's Generative AI (Gemini) to convert English questions into SQL queries. It also demonstrates a simple SQLite database interaction to retrieve data based on the generated SQL query.

## Getting Started

To get started with this project, you'll need to follow these instructions:

### Prerequisites

- Python 3.6 or higher
- Ensure you have `pip` installed.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git

2. Navigate to the project directory

    ```bash
   cd your-repository

4. Install the required Python packages

   ```bash
   pip install -r requirements.txt

6. Create a [.env] file in the root directory and add your Google API

   ```bash
   GOOGLE_API_KEY=your-api-key-here

### Running the application

Once you've completed the installation, you can run the Streamlit application:

   ```bash
   streamlit run app.py

### Installation

   -Upon running the application, you'll be presented with a text input field labeled "Input".
   -Enter your English question related to SQL queries in the input field.
   -Click on the "Ask the question" button.
   -The application will generate the corresponding SQL query based on your question and retrieve data from the SQLite database accordingly.
   -The response will be displayed below the input field.


