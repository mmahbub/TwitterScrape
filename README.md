# New twitter scraper under scraper folder

When you've gathered all the tweets from the scraper, use the ruby script CombineTweets.rb to make a single file of all the separate files that the scraper gave to you.

# Twitter Project

Repo for Getting and Cleaning Tweets for UTK CURENT

# Getting the Repo & Setting Up
All you need to do is either clone it with Git or if you don't know Git, just download the zip file containing it all.
Install **pyquery** & **urllib2** for Python 2.7 using pip. This will need to be used in an Unix environment. 

# Cleaning the Tweets
In the Cleaning Folder, **Main.py** will filter by date, remove unicode errors, translate (if enabled), and combine all files into a single one.

Right now the translation is commented out. To enable, please
uncomment.

To use:
cd Cleaning
cp "where the tweets files are" SepCleaning/
python MAIN.py

This works by doing a bit of hopscotch between two folders thanks to Python's CSV module. All you need to do is update path1 and path2 inside the main file and it should work. Replacing the osdir path needs to be done as well. When tested this worked on cleaning and removing all unneccessary files. 
