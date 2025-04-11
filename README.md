---

# Recipe Recommendation System

A user-friendly web application that suggests recipes based on user-provided ingredients. Built with Python and Streamlit, it offers an intuitive interface for users to discover new recipes tailored to their preferences.

## Features

- **Ingredient-Based Recommendations**: Input available ingredients to receive relevant recipe suggestions.
- **Interactive Interface**: Utilizes Streamlit for a responsive and engaging user experience.
- **Visual Enhancements**: Incorporates images to make the interface more appealing.

## File Structure

- `main.py`: Main application script containing the Streamlit interface and recommendation logic.
- `recipes.db`: SQLite database storing recipe information.
- `labels.txt`: Text file containing labels or categories used in the application.
- `home_img.jpg` & `home_img.png`: Images used for the application's homepage or interface.
- `README.md`: This documentation file.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries:
  - `streamlit`
  - `sqlite3` (standard library)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rahulshah1122/recipe-recommendation.git
   ```


2. Navigate to the project directory:

   ```bash
   cd recipe-recommendation
   ```


3. Install the required libraries:

   ```bash
   pip install streamlit
   ```


4. Run the application:

   ```bash
   streamlit run main.py
   ```


## Usage

- Upon running the application, a new browser window will open displaying the interface.
- Enter the ingredients you have on hand.
- The application will suggest recipes that can be made using those ingredients.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

*Note: This project is a basic implementation and may not cover all aspects of a full-fledged recipe recommendation system.*

--- 
