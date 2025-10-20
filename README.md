# Interactive Data Preprocessing Project
This is mini data preprocessing project which makes the task simpler by interactively asking user for each step.

# Features
1.Interactive: The script asks you what you want to do (e.g., "Do you want to run imputation?").
2.Load Your Data: You can type in a path to your own .csv file.
3.Sample Data: If you don't have a file, just press Enter to use a built-in sample.
4.Fix Missing Data (Imputation): Automatically finds missing data (NaNs) and fills them using the mean, median, or mode as guided by that particular user input.
5.Encode Categories:
    Ordinal Encoding: Allows user to turn text into numbers that have an order (like "Small" = 0, "Medium" = 1, "Large" = 2) as taken as input from user itself.
    One-Hot Encoding: Allows user to turn text into simple 0 or 1 columns (like "Color\_Red", "Color\_Blue") as taken as input from user.
6.Fit and Transform:
    The script "fits" by learning the statistics from your data (like the average 'age' or the list of 'colors').
    It then "transforms" your data using these rules.
    It also shows how to use these same rules to transform new data, which is important for machine learning.

# How to Use

1.  Open the file (the `.ipynb` file) in a program like Google Colab, Jupyter Notebook, or VS Code.
2.  Run the main code cell (the one at the bottom that starts with `if __name__ == "__main__":`).
3.  Follow the instructions in the output.
4.  It will ask you for a file path. You can type one in or just press Enter to use the sample data.
5.  It will ask you "yes" or "no" (y/n) for each cleaning step.
6.  Answer the questions to build your own cleaning process.
7.  The script will print the final, clean data at the end.


# Limitation
As this project is built for AIMS-DTU society. As per their norms no pre-defined shortcut like functions eg .get,.map,.get_dummies etc must not be used so that it could showcase ur understanding.
# Requirements
You need to have Python installed, along with two common libraries:

pandas
numpy

You can install them by opening your terminal or command prompt and typing:
pip install pandas numpy
