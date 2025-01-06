Project files:

1. ML_project.ipynb
   - contains most of the code used - model building, training, evaluation, making predictions on the final Reddit dataset
3. scraping.ipynb
   - contains the code used for scraping the comments from Reddit and cleaning the dataset - should be run first
5. reddit_posts.csv
   - contains the 100 post titles used in the scraped dataset - gets saved when running the scraping.ipynb code
7. reddit_comments.csv
   - contains the post titles and all the comments scraped from Reddit - gets saved when running the scraping.ipynb code
9. clean_reddit_comments.csv
    - contains the cleaned comments and the post titles scraped from Reddit, the final dataset used for predictions - gets saved when running the scraping.ipynb code
11. predictions_rcomments.csv
    - the file with cleaned comments and two extra columns with predictions from the baseline model and fine-tuned distilbert - gets saved when running the ML_project.ipynb code
13. Project_report.pdf
    - report summarising the project - methods, context etc.
   

The code files were downloaded from Google Colab which was the environment used in this project, here are the links to the online notebooks:

SCRAPING:
https://colab.research.google.com/drive/15YD8UQcbtpKZ7Anpj0hJ4pglMI9xM9IQ?usp=sharing 

MAIN CODE:
https://colab.research.google.com/drive/1I3NjZXUDcHpol0H1o2D0cgyHU3FvdQRf?usp=sharing 
