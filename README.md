# Restaurant Recommendation System 🍽️

## Overview
This project is a **Restaurant Recommendation System** designed to suggest restaurants based on user preferences, leveraging various data attributes such as cuisines, city, and aggregate ratings. The system utilizes data analysis and machine learning techniques to create a robust recommendation model that enhances user dining experiences by identifying the most suitable restaurant options.

## Project Objectives
- **Understand User Preferences**: Analyze different features such as cuisines, ratings, and locations to capture user preferences.
- **Restaurant Recommendations**: Suggest top restaurants using collaborative and content-based filtering approaches.
- **Improve Decision Making**: Provide meaningful insights through data exploration and visualization.

## Dataset
The project uses a dataset (`Dataset.csv`) containing various fields:
- **Restaurant Name**: The name of the restaurant.
- **City**: Location of the restaurant.
- **Cuisines**: Type of cuisines offered.
- **Aggregate Rating**: Overall user rating for the restaurant.
- **Country Code**: Country identification code.
- **Price Range**: Average price range for meals at the restaurant.

## Key Features
1. **Data Preprocessing**:
   - Cleaning and transforming the dataset.
   - Handling missing values and standardizing fields like `City` and `Cuisines`.

2. **Exploratory Data Analysis (EDA)**:
   - Analysis of top cuisines and restaurant distribution across cities.
   - Identifying popular restaurants and understanding rating patterns.

3. **Recommendation Engine**:
   - Implemented a **content-based filtering** method using the `Cuisines` and `City` features.
   - Developed a **collaborative filtering** approach using ratings and user preferences.
   
4. **User Interface**:
   - Allows users to input preferences and receive restaurant recommendations dynamically.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Abithaabbas/restaurant-recommendation-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd restaurant-recommendation-system
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or the main script:
   ```bash
   jupyter notebook DATASCIENCE-checkpoint.ipynb
   ```

## Results and Insights
- Successfully built a recommendation system that can suggest top restaurants based on user input for `City` and `Cuisines`.
- Identified popular cuisines and top-rated restaurants for different cities, aiding in making informed decisions.

## Future Work
- **Integration of User Reviews**: Enhance recommendations by analyzing user reviews using Natural Language Processing (NLP).
- **Advanced Filtering**: Add more features like budget, meal types, and restaurant facilities.
- **Real-time Recommendations**: Implement real-time suggestions based on live user data and interactions.

## Requirements
- Python 3.7+
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## Contact
- **[Your Name]** - Developer
- **LinkedIn**: (https://www.linkedin.com/in/abitha-begam-855368289)
- **GitHub**: https://github.com/Abithaabbas


