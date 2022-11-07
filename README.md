# Assignment-2

Hrishikesh Rajashekarbabu
11/7/2022

I have a created a python program that, once given the webpage for the book, pulls the raw text from the website. The program then first tries to obtain what year the book was written/orated/time period it is in. Now since, the books I am analysing are those in the Hinduism category, some of the books , the years the book was published is oftentimes not the year the book was actually written, therefore, using python code, I first abstracted all the numbers from the text between the years 100-2022 to obtain the most commonly recurring year in order to get the best chance at obtaining the right event date (the years of the setting of the book).

Then using a word counter api, I began to sort the text, by first removing the publishers text and stopwords, and then storing the 100 most commonly occurring words, Then after doing a sentiment analysis, I can store a sentiment analysis for each book, based on their years.

This program provides the backbone for a text analyser that can see how the verbiage/sentiment/and persuasion techniques of religions/other categories, has changed over the years, thus reflecting how the human population has changed over this time.


Ways to make it better : 

Create a web scraping tool that obtains the Plain UTF-8 file for every book in the Hinduism section (There’s 28 of them).

Add a function/dictionary that stores sentiment analysis data to its respective year.

Add a function that aggregates word counts for books from the same year. 2
