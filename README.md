
# Nutritionist Generative AI Doctor

This AI-driven web application empowers users to assess the healthiness of their food through image uploads. Utilizing Google Gemini Pro and Streamlit, the application provides detailed nutrient information and health assessments, making nutrition management more accessible and efficient.

## Features

- **Image Upload**: Users can easily upload food images for analysis.
- **Health Assessments**: The application provides detailed assessments of food healthiness, including nutritional information.
- **Advanced Image Analysis**: Integrates Google Generative AI for sophisticated image analysis, ensuring accurate assessments.
- **User-Friendly Interface**: Built with Streamlit, the app offers a smooth and intuitive user experience.
- **Secure API Management**: Uses Python Dotenv for secure handling of API keys, ensuring user data safety.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/roadrash99/CalorieAdvisor.git
    cd CalorieAdvisor
    ```

2. **Install Required Packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure Environment Variables**:
    - Create a `.env` file in the root directory.
    - Add your API keys as follows:
      ```plaintext
      GOOGLE_API_KEY=your_google_api_key
      GEMINI_API_KEY=your_gemini_api_key
      ```

## Usage

1. **Run the Application**:
    ```bash
    streamlit run app.py
    ```

2. **Upload Food Image**:
   - Click on the upload button to submit a food image for analysis.

3. **View Results**:
   - The application will display a health assessment along with detailed nutrient information.

## Tech Stack

- **Backend**: Python
- **Frontend**: Streamlit
- **APIs**: Google Gemini Pro, google-generativeai
- **Security**: Python Dotenv for API key management

