The File submitted is a .py file and made in a editor(Spyder).
The source code reads the tweets from the text file cnnhealth.txt.Hence before running the source change the path in line 15 to the relative path of where the file "cnnhealth.txt" is stored in your system.
The tweets are read from cnnhealth.txt and processed with regular expression and then loaded in “tweets_dict” dictionary. Then the centroids are alloted to the clusters initially using the random function.
To run the code:
Run the source file k-means.py
It will prompt for the value of k.
Input the value of k and press enter.
The output will give the following:
1. Value of k
2. Number of tweets in each cluster in the format [1 to k]:[Size of each cluster] tweets
3. SSE


