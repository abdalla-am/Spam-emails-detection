# Spam-data-detection

Classified Text as Spam or Ham using NLTK and Scikit-learn

**🔷Context**
The SMS Spam Collection is a set of text that have been collected for Spam text research. It contains 5,572 group of words to form a text , tagged acording being ham (legitimate) or spam.

**🔷Content**
The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

**🔷The dataset used is an open-source Spambase dataset , which contains 5572 emails, of which 747 are spam & 4825 ham .**

**🔷Preprocessing steps used :**
   - Remove missing (NULL) values if exist 
   - Remove duplicate values
   - converting all letters to lower or upper case
   - removing punctuations
   - removing stop words
   - Tokenization
   - Stemming
   - Lemmatization

 **🔷Created a deep learning model .**

 **🔷Since the percentage of spam in data is often low, measured the model’s performance by F1score.**
 
 **🔷Decision Tree Values :**
   - Precision: 97.14 %
   - Recall: 97.895 %
   - F1-score: 97.517 %
