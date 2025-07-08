# Netflix-User-Behavior-Analysis
This project explores and analyzes user behavior on a video streaming platform like Netflix using Python and data visualization techniques. The goal is to extract insights from user interaction patterns, such as preferred genres, watch time, and viewing trends, to guide recommendations and strategic decisions.

## Project Structure

- `Sourcecode.ipynb` – The Jupyter Notebook containing all preprocessing, analysis, and visualization code.
- `netflix_dataset.csv` – The dataset containing user viewing history, genres, timestamps, and watch time.
- `Output_Screenshots.pdf` – Screenshots of output plots generated during analysis for documentation.

## Key Analysis Areas

The project performs a range of behavioral analyses, including:

1. **Top 10 Genres**  
   Most frequently watched content types.

2. **Top 10 Users by Watch Hours**  
   Identifies the most active users based on total hours watched.

3. **Genres by Total Watch Hours**  
   Which genres are watched the most in terms of time spent.

4. **Last Watch Timestamp by Genres**  
   Recent viewing activity categorized by genre.

5. **Top Genres per User**  
   Personal genre preferences per user.

6. **Trending Genres in Last 30 Days**  
   What’s trending now based on recent user activity.

7. **User Watch Segments**  
   Segments users based on engagement behavior.

8. **Under-Watched Genres**  
   Genres with relatively low viewership despite being available.

## Technologies Used

- **Python**
  - `pandas` for data manipulation
  - `matplotlib`, `seaborn` for data visualization
- **Jupyter Notebook** for code execution and documentation
- **CSV** for structured data input
- **PDF/Images** for showcasing visual output

## How to Run

1. Clone the repository:
   
   `git clone https://github.com/AnkamSaiPrasad/netflix-user-analysis.git
   cd netflix-user-analysis`
   #### If the above command didn't work
   you can also do this by placing the `Sourcecode.ipynb` and `netflix_dataset.csv` in same folder.
   
3. Install required packages:
  
   `pip install pandas matplotlib seaborn jupyter`
  
3. Launch the notebook:

   `jupyter notebook Sourcecode.ipynb`
  
4. Run each cell to see the model training and forecasting in action.

## Author
#### Ankam Sai prasad
#### B.Tech in Data Science
#### Email: ankamsaiprasad13@gmail.com
