# Movie Rating Prediction

## Project Overview
This project aims to predict movie ratings based on various features such as duration, genre, year, director, and actors. Using a dataset from IMDb, we perform exploratory data analysis and build a linear regression model to make rating predictions.

## Dataset
The dataset used in this project is `IMDb Movies India.csv`, which contains the following columns:
- **Name**: Name of the movie
- **Duration**: Duration of the movie (in minutes)
- **Genre**: Genre(s) of the movie
- **Year**: Release year of the movie
- **Rating**: IMDb rating of the movie
- **Votes**: Number of votes received by the movie
- **Director**: Director of the movie
- **Actor 1**: Lead actor in the movie
- **Actor 2**: Supporting actor in the movie
- **Actor 3**: Another supporting actor in the movie

## Project Structure
The project is structured as follows:
- `data/`: Contains the dataset file (`IMDb Movies India.csv`).
- `notebooks/`: Contains Jupyter notebooks for data analysis and model building.
- `scripts/`: Contains Python scripts for data preprocessing and model training.
- `README.md`: Project overview and documentation.

## Libraries and Tools
The following libraries and tools are used in this project:
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Exploratory Data Analysis
We perform exploratory data analysis (EDA) to understand the distribution of ratings and the factors influencing them. Key insights include:
- Analysis of top movies by rating.
- Distribution of movie genres.
- Analysis of top directors and actors by average rating.
- Relationship between votes and ratings.

## Data Visualization
Various plots are used to visualize the data:
- Histograms to visualize the distribution of movie ratings.
- Pie charts to show the distribution of movie genres.
- Bar plots to display top directors and actors by rating.
- Line plots to show trends over time.

## Data Preprocessing
The data is preprocessed to handle missing values, convert data types, and encode categorical variables:
- Missing values are handled by dropping rows with null values.
- String columns are converted to appropriate numerical formats.
- Categorical variables are encoded using Label Encoding.

## Model Building
We build a linear regression model to predict movie ratings:
1. **Data Splitting**: The data is split into training and testing sets.
2. **Model Training**: A linear regression model is trained using the training set.
3. **Model Evaluation**: The model's performance is evaluated using the testing set.

## Results
The linear regression model provides the following metrics:
- **R2 Score**: Measure of how well the model explains the variability of the data.
- **Mean Absolute Error**: Average absolute difference between predicted and actual ratings.
- **Mean Squared Error**: Average squared difference between predicted and actual ratings.

## Conclusion
The project demonstrates how various features of movies can be used to predict their ratings. This model can help stakeholders in the movie industry to forecast movie performance based on pre-release attributes.

## Usage
To run the project, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-rating-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-rating-prediction
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook or Python script for data analysis and model training.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
This project is part of the CodSoft Data Science Internship. Special thanks to the CodSoft team for their support and guidance.
