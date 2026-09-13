# Workout Plan Generator

A Streamlit-based web application that generates personalized workout plans using the GROQ AI API, leveraging the Langchain library for AI-powered functionality.

---

## Features

* Select from seven distinct muscle groups: Chest, Shoulder, Triceps, Back, Biceps, Legs, and Abs
* AI-powered workout plan generation using the GROQ AI API and Langchain library
* Simple and intuitive user interface built with Streamlit, allowing for easy navigation and customization
* Integration with environment variables for secure storage of API keys

---

## Tech Stack

* **Streamlit** for building the web application
* **Langchain** (`langchain-core`, `langchain-community`, `langchain-groq`) for AI-powered functionality
* **GROQ AI API** for workout plan generation
* **Python 3.8+** as the primary programming language
* **pip** for package management
* **python-dotenv** for environment variable management

---

## Getting Started

### Prerequisites

* Python 3.8+
* A GROQ API key

### Installation

1. Clone the repository and navigate to the project directory:
   ```bash
   git clone <repository-url>
   cd workout-planner
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up environment variables by creating a `.env` file in the project root and adding your GROQ API key:
   ```
   GROQ_API_KEY="your_groq_api_key_here"
   ```

---

## Usage

1. Start the Streamlit application: `streamlit run app.py`
2. Open a web browser and navigate to the application URL (typically `http://localhost:8501`)
3. Select your preferred muscle groups and generate a personalized workout plan

---

## Project Structure

* `app`: Contains the Streamlit application code, including the Langchain helper (`app/langchain/helper.py`)
* `requirements.txt`: Lists the required packages for installation
* `settings.py`: Stores application settings and configuration
* `.env`: Stores environment variables, including the GROQ API key

---

## Contributing

To contribute to the Workout Plan Generator, please follow these steps:
1. Fork the repository and create a new branch for your feature or bug fix
2. Ensure all changes are thoroughly tested and documented
3. Submit a pull request with a clear description of your changes
4. Participate in code reviews and address any feedback or concerns
5. Once your pull request is merged, update the `requirements.txt` file and `README.md` as necessary to reflect your changes
