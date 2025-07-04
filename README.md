# MedicalCrew
This project leverages advanced AI agents to assist doctors in diagnosing medical conditions and recommending treatment plans based on patient-reported symptoms and medical history. The solution uses Streamlit for the user interface and crewAI library to define and manage AI agents and tasks.

## Features
- **Symptom Analysis:** Collects patient symptoms and medical history.
- **Preliminary Diagnosis:** Provides a preliminary diagnosis with a list of possible conditions.
- **Treatment Recommendations:** Offers detailed treatment plans tailored to individual patient needs.
- **Document Generation:** Generates a downloadable document with diagnosis and treatment recommendations.

## Installation
1. Clone the repository:

```bash
git clone https://github.com/venoM33XA/MedicalCrew
cd MedicalCrew
```
2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate   
```

3. Install the dependencies:

```bash
pip install -r requirements.txt
```

4. Set up environment variables:

- Create a .env file in the project directory with the following content:
```bash
OPENAI_API_KEY=your_openai_api_key
SERPER_API_KEY=your_serper_api_key
GROQ_API_KEY=your_groq_api_key
```

## Usage
1. Run the Streamlit app:

```bash
streamlit run app.py
```

2. Use the application:

- Open the provided local URL in your web browser.
- Enter the patient's gender, age, symptoms, and medical history.
- Click the "Get Diagnosis and Treatment Plan" button.
- View and download the generated diagnosis and treatment plan.

## Project Structure
- **app.py:** The main application script that defines the Streamlit UI and integrates the AI agents.
- **requirements.txt:** A list of required Python packages.
- **.env:** Environment variables for API keys (not included in the repository).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for more details.

