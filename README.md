# Similarity-measure-between-the-text-using-NLTK-and-Scikit-Learn
Measure between text in each row of the given csv file and Search Text

#Cosine similarity: 
It calculates similarity by measuring the cosine of angle between two vectors.
Using cosine similarity, we have to convert the texts into vectors. It can be achieved
by using either TF (term frequency) or TF-IDF (term frequency- inverse document frequency).

# Steps used in the above program:
1. Import libraries.
2. Tokenization (Tokenization is the process of breaking up a sequence of strings into pieces such as words, keywords,
   phrases, symbols and other elements called tokens).
3. Stop word removal( A stop word is a commonly used word (such as “the”, “a”, “an”, “in”) and search engine will ignore such words.)
4. Stemming.
5. With our cleaned up text, we can now use it for searching or document similarity. Scikit-learn has a built in Tf-Idf implementation. 
   To preprocess the text we can use NLTK's tokenizer and stemmer.
6. SearchTxt is passed to the transform function, which will use existing NLTK preprocessor first.
7. call fit_and_transform() function, which adds the document to the model.

# How to Run the .ipynb file?
1.Open the terminal (Ctrl + Alt + T).

2.Navigate to the folder where your .ipynb file saved.

3.Type jupyter notebook

4.Open the file that you want to read.

5.To run the program line by line press shift+Enter.
