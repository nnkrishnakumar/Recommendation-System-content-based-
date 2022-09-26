# Recommendation-System-content-based-

working :

Step 1 ---> creating data on small scale first

Step 2 ---> filtering data means converting data into corpus into small letters and removing stop words

Step 3 ---> sparse_matrix to dense_matrix conversion

Step 4 ---> cosine_similarity help us to get the distance between vectors using math's cos angle, where cos 90 means 0 mean not match between 2 vector and cos0 means 1 
which mean it match 100%  to each other.

> In cosine_similarity, cos degree value lies between -1 to +1 where -1 is absolutly oppositive and +1 means absolutly same.

> Note: cosine similarity show similarity when degree is bigger

tep 5 ---> cosine_distance help to find the distance between two vector or more. If the distance is higher that means not match between two vectors. if distance is lower that means both vectors are same.

> Note: cosine distance show similarity when distance is smaller

step 6 --> importing pandas to read dataset of a movie and clean it.

step 7 ---> filterning columns which is required 

Step 9--->conversion of desciption of movies of dataframe into a corpus using pandas df1.description

Step 10---> TfidfVectorizer and countVectorizer both use for creating feature from corpus and also contain corpus preprocessing tools like       lowercase=True,stop_word='english'

Step 11---> Creating dense matrix from sparse matix with the help to toarray() method

Step 12 ---> importing algorithm for recommondation which is NearestNeighbors it partially work like KNN(KNN doesnot have cosinesimilarity in it) and NearestNeighbors have cosine_distance and cosine_similarity 

> Most import NearestNeighbors is for "Unsupervise learning" where "Target" is not required 

Step 13 ---> converting dataframe movies name in smaller case so when user inter the data we can match it with dataframe to check the availability of that film

Step 14 ---> Asking user to search any movie and my program will suggest whether there is any movies in dataframe matching to user seach. if yes then my program will suggest.
