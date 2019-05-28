# WordCloud-Generator
A website to generate word cloud chart based on personal settings, using d3.js, Bootstrap, MUI, etc., based on HTML, CSS and Javascript.

# Demo Page's URL
https://wordcloud-46f95.firebaseapp.com/

# Data Domain
The word cloud graph is a visual display of the "keywords" that appear frequently in the text. It filters out a large number of low-frequency and low-quality text information, so that the user can scan the text at a glance to learn the main idea of the text. From the perspective of Data Visualization, the word cloud is sometimes to provide user a starting view of dataset, sometimes to provide user context and useful information of the dataset and also sometimes to invite interaction and exploration to promote understanding of the original data.
So, the data domain is pure text. The text can be of any category, any length, in any language. I analyze the text, split text into words, remove punctuation, then calculate word frequency, and at last remove all stop words, to pick out the words used for display and get their respective weights( which corresponds to the proportion of their size in the word cloud graph).

# Brief Description
The application is a word-cloud generator. When using it, users can upload the text file or type text, choose the style they want including font, color, shape, theme, etc. Then our application will generate the word cloud for users based on the text they provide and the feature they choose. 

My aim of creating this application is to:
1.Provide a starting point — a big picture view — for users to orient themselves and begin delving into a dataset;
2.Provide enough context and useful information without overwhelming the viewer;
3. Invite interaction and exploration to promote understanding of a dataset; 

