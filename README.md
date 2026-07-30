## Project Title

**Natural Language Processing (NLP) Data Preprocessing using Python**

## Description

This project demonstrates basic NLP data preprocessing techniques using **Python**, **Pandas**, and **Regular Expressions (Regex)**. A raw dataset containing noisy text is created, cleaned, and saved as a new CSV file for further analysis.

## Features

* Create a raw dataset
* Read CSV file using Pandas
* Convert text to lowercase and uppercase
* Use Regular Expressions:

  * `re.findall()`
  * `re.search()`
  * `re.split()`
  * `re.sub()`
* Remove:

  * URLs
  * Email addresses
  * Mentions (@username)
  * Hashtags
  * Phone numbers
  * Numbers
  * HTML tags
  * Emojis and special characters
  * Extra spaces
* Save cleaned data into a new CSV file

## Project Structure

```
Preprocessing/
│
├── preprocessing.ipynb
├── raw_data.csv
├── cleaned_data.csv
└── README.md
```

## Libraries Used

* pandas
* re (Regular Expressions)

## Input

* `raw_data.csv` – Contains noisy text data.

## Output

* `cleaned_data.csv` – Contains cleaned and preprocessed text.

## How to Run

1. Open `preprocessing.ipynb`.
2. Run all the cells in order.
3. The program will create `raw_data.csv`.
4. The text will be cleaned automatically.
5. The cleaned dataset will be saved as `cleaned_data.csv`.

## Conclusion

This project demonstrates the essential preprocessing steps required in Natural Language Processing. The cleaned dataset can be used for text mining, sentiment analysis, text classification, and other machine learning applications.
