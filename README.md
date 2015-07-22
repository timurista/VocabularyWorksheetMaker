# VocabularyWorksheetMaker
Makes Vocabulary Worksheets for a list of vocabulary words

## How To Run
- Load the File into your browser
- Enter the title of your worksheet
- Enter your vocabulary words seperated by spaces, commas, or by new lines (the regex searches for words based on the flag \w+, so it will ignore periods inside words)
- Click "Make Worksheet" to create a set of new worksheets

## How It Works
This file pulls cdn from bootstrap, angularjs to create a dynamic website. It will loop through each word and group them into groups of 6. Each worksheet is about 2 pages (1 page double-sided) And the last page(s) is a list of all vocabulary words for reference later.


