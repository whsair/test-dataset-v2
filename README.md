# CS598 

### Notice: I combine test and train into a larger corpus (followed the hints in task 2) so the input file should contain both test and train sets (the total size of movies corpus: 25000 + 25000 = 50000; the total size of news corpus: 120000 + 7600 = 1276
# Instruction:
1. cd code/category_guided_classification/ (go to the code directory)
2. run data preprocess.ipynb (I write clear instructions about how to preprocess the data in it)
  - details:
    - Step1: Create two directories to store the data
    - Step2: Put the output files from previous tasks under these two directories
    - Step3: generate the keywords.txt and classes.txt
3. run two bash file (test_movies.sh | test_news.sh)
For example: 
  ### ### Generating outputs ###
  Classification (test + train) results are written in ./news/out.txt
  Classification test results are written in ./news/test_prediction.txt


# Best results:
## news
labels + cnn: 0.86167/0.96 on the given validation sets
## movies
keywords + cnn  0.82985/0.83 on the given validation sets
