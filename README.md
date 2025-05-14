# Diet Recommendation System

**Its a dummy project**

## Overview
The **Diet Recommendation System** leverages **Gemini API** and **nutritional data analysis** to provide personalized diet plans based on user attributes. It takes inputs like age, gender, weight, height, and activity level to compute **daily calorie intake** and **optimal macronutrient distribution**.

## Features
- **AI-Powered Recommendations**: Uses **Gemini API** for generating diet plans.
- **Personalized Diet Suggestions**: Based on user demographics and health goals.
- **Nutritional Analysis**: Provides breakdown of **calories, proteins, carbs, and fats**.
- **Easy-to-Use Interface**: Simple input mechanism for user data.
- **Scalable & Extensible**: Can be integrated with fitness apps.

## Tech Stack
- **Python**
- **Gemini API** (for diet recommendation generation)
- **Pandas & NumPy** (for data handling)
- **Flask** (for API integration)
- **Matplotlib** (for data visualization)

## Installation
Follow these steps to set up the project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jainrahul0807/Diet_Recommendation_System.git
   cd Diet_Recommendation_System
   ```
2. **Create a Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # Windows: env\Scripts\activate
   ```
3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Set Up Gemini API Key**:
   - Obtain an API key from **Google AI Gemini API**.
   - Store it in a `.env` file as follows:
     ```
     GEMINI_API_KEY=your_api_key_here
     ```

## Usage
1. **Run the Application**:
   ```bash
   python Diet_Recommendation.py
   ```
2. **Input User Details**:
   - Gender
   - Weight (kg)
   - Height (cm/Feet)
   - Food Preference(Veg, Non-Veg, Both)
3. **Receive AI-Generated Diet Plan**:
   - Suggested **calorie intake**.
   - Recommended **protein, carbs, and fat** intake.
   - AI-generated food recommendations.

## Dataset
- `food.csv`: Contains food items and nutritional values.
- `nutrition_distribution.csv`: Defines nutrient proportions for various diet types.

## Future Enhancements
- **Add BMI-based recommendations**.
- **Enhance API response accuracy** using **more user parameters**.
- **Integrate with a mobile application**.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
For queries or contributions, contact **Rahul Jain** at jainrahul0807@gmail.com.

