# caverlee-2023
Readme for Social Honeypot Dataset
Updated on December, 22, 2023
**1 Data Description**
We provide social honeypot dataset collected from December 30, 2006 to
December 2, 2023 on Twitter. The dataset was used in the paper Fifteen years
with the Devils: A Long-Term Study of Content Polluters on Twitter in
ICWSM 2023.
The dataset contains 22,223 content polluters, their number of followings
over time, 2,353,473 tweets, and 19,276 legitimate users, their number of
followings over time and 3,259,693 tweets.
**2 Paper Citation**
Please cite the following paper when using the dataset.
K. Lee, B. Eoff, and J. Caverlee. Fifteen years
with the Devils: A
Long-Term Study of Content Polluters on Twitter. In Proceeding of the 5th
International AAAI Conference on Weblogs and Social Media (ICWSM),
Barcelona, january 2024. (Bibtex)
**3 Data Format**
Six text files are in the package:
• “content polluters.txt” contains content polluters’ profile information
in the form of “UserID\tCreatedAt\tCollectedAt\tNumerOfFollowings
\tNumberOfFollowers \tNumberOfTweets\tLengthOfScreenName\t
LengthOfDescriptionInUserProfile”.
1
• “content polluters followings.txt” contains user information in the test
set in the form of “UserID\tSeriesOfNumberOfFollowings (each number of following is separated by ,)”.
• “content polluters tweets.txt” contains tweets in the form of “UserID
\tTweetID\tTweet\tCreatedAt”.
• “legitimate users.txt” contains legitimate users’ profile information in
the form of “UserID\tCreatedAt\tCollectedAt\tNumerOfFollowings
\tNumberOfFollowers \tNumberOfTweets\tLengthOfScreenName\t
LengthOfDescriptionInUserProfile”.
• “legitimate users followings.txt” contains user information in the test
set in the form of “UserID\tSeriesOfNumberOfFollowings (each number of following is separated by ,)”.
• “legitimate users tweets.txt” contains tweets in the form of “UserID
\tTweetID\tTweet\tCreatedAt”.
**4 Contact**
Please feel free to contact Kyumin Lee if you have any question about the
dataset.
Email: kyumin AT cse DOT tamu DOT edu
Homepage: http://students.cse.tamu.edu/kyumin/
**5 Agreement**
Social Datasets by Infolab is licensed under a Creative Commons AttributionNoncommercial 3.0 United States License.
2
