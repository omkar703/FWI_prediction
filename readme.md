# Algerian Forest Fires Dataset 🔥🌲🔥

This project aims to predict the Fire Weather Index (FWI) using machine learning based on the Algerian Forest Fires dataset. The dataset contains 244 instances from two regions of Algeria: **Bejaia** (Northeast) and **Sidi Bel-Abbes** (Northwest), collected from June 2012 to September 2012. 📊🌍🔥

## Dataset Information 📅📌🔥

- **Total Instances:** 244
  - **Bejaia Region:** 122 instances
  - **Sidi Bel-Abbes Region:** 122 instances
- **Time Period:** June 2012 - September 2012
- **Classes:**
  - Fire: 138 instances
  - No Fire: 106 instances

### Attributes:

- **Day** (June - September)
- **Month** (June - September)
- **Year** (June - September)
- **Temperature** (Celsius, 22 - 42)
- **RH** (Relative Humidity %, 21 - 90)
- **Ws** (Wind Speed in km/h, 6 - 29)
- **Rain** (Total rainfall in mm, 0 - 16.8)
- **FFMC** (Fine Fuel Moisture Code: 28.6 - 92.5)
- **DMC** (Duff Moisture Code)
- **DC** (Drought Code)
- **ISI** (Initial Spread Index)
- **BUI** (Buildup Index)
- **FWI** (Fire Weather Index - Prediction Target)
- **Classes** (Fire / No Fire)

## Project Structure 📂🛠️📑

- `app.py` - Flask web application for predicting FWI
- `templates/` - HTML files for UI (index & prediction pages)
- `static/` - CSS & JS files for frontend design
- `ridge.pkl` - Pretrained Ridge Regression model
- `sc.pkl` - StandardScaler for data preprocessing
- `README.md` - Project documentation

## How to Run the Project 🚀💻📡

1. Clone the repository:
   ```sh
   git clone https://github.com/omkar703/FWI_prediction
   cd FWI-prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Flask application:
   ```sh
   python app.py
   ```
4. Open the web browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

## Usage 🎯📈🌿

- The homepage provides an overview of the dataset.
- Users can enter environmental parameters in the prediction page to get an FWI prediction.

## Technologies Used 🖥️⚙️📡

- **Flask** - Web framework
- **Scikit-Learn** - Machine learning model
- **HTML, CSS, JavaScript** - Frontend UI
- **Python** - Backend scripting

## License 📜🔓🌎

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments 🌍🙏📚

This dataset is obtained from **Algerian Meteorological Services** for research and educational purposes. 📖📊🌎
