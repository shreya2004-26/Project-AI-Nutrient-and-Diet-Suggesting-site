# NutriDietFlow

NutriDietFlow is an advanced nutritional recommendation system powered by machine learning. The platform uses a Random Forest model to provide personalized dietary suggestions based on individual characteristics and preferences.

## Features

* Personalized calorie recommendations based on user characteristics
* Detailed macro and micronutrient breakdown
* Customized meal suggestions based on dietary preferences
* Support for multiple diet types and restrictions
* Consideration of medical conditions and food allergies
* Mobile-responsive web interface

## Technologies Used

* Python 3.x
* Flask
* scikit-learn (Random Forest model)
* pandas
* NumPy
* Bootstrap 5.3.3
* HTML/CSS
* JavaScript

## Installation

1. Clone the repository:
```bash
git clone https://github.com/lakshmi-official/Project-AI-NutrientDietFlow.git
cd NutriDietFlow
```



2. Run the application:
```bash
python main.py
```

3. Open your browser and navigate to `http://localhost:5000`

## Project Structure

```
NutriDietFlow/
├── static/
│   └── Project logo.png
│   └── final logo.png
├── templates/
│   ├── index.html
│   ├── about.html
│   └── developer.html
├── Data Sets/
│   ├── Final Data set.csv
│   ├── Micro and macro nutrients.csv
│   └── Meal suggestions.csv
├── model/
│   └── RandomForest1.pkl
├── main.py
├── README.md
└── requirements.txt
```

## Features in Detail

### User Input Parameters
* Age (15-100 years)
* Gender
* Weight (30-200 kg)
* Height (120-220 cm)
* Diet Preference (20+ options)
* Activity Level
* Weekly Activity Days
* Medical Conditions
* Food Allergies
* Health Goals

### Output
* Daily calorie recommendations
* Detailed nutrient breakdown including:
  * Macronutrients (protein, carbs, fat)
  * Micronutrients (vitamins and minerals)
* Personalized meal suggestions for:
  * Breakfast
  * Lunch
  * Dinner
  * Snacks

## Model Information

* Algorithm: Random Forest Regressor
* Accuracy: 97.5% (R² Score)
* Features: Multiple user characteristics and preferences
* Output: Personalized calorie and nutrient recommendations

## Developer

Developed by Rajyalakshmi, a Data Science student at VIT-AP University. Connect on:
* GitHub: [lakshmi-official](https://github.com/lakshmi-official)
* LinkedIn: [Rajyalakshmi Parasaram](https://www.linkedin.com/in/rajyalakshmi-parasaram-48052533a)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Important Note

While recommendations are based on scientific data and machine learning algorithms, they should not replace professional medical advice. Always consult healthcare providers before making significant dietary changes.