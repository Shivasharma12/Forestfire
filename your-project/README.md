# Forest Fire Prediction Project

This project predicts the likelihood of a forest fire using machine learning. It uses a Streamlit web interface for user input and displays predictions based on a trained model.

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the app:
   ```bash
   streamlit run main.py
   ```

## Project Structure

```
your-project/
├── main.py              # Main Python file (Streamlit app)
├── requirements.txt     # Python dependencies
├── README.md            # Project description
├── .gitignore           # Ignored files/folders
├── Forest_fire.csv      # Dataset
├── fire_prediction_model.pkl # Trained model
├── forest_fire_prediction.ipynb # Jupyter notebook
├── synopsis.pdf         # Project synopsis
└── utils/               # Helper files, extra models, or notebooks
```

## Notes
- The app uses a trained model saved as `fire_prediction_model.pkl`.
- For more details, see the notebook `forest_fire_prediction.ipynb`.
