# European-Hotel-Analysis
The project analyzes various hotels based in Europe and their ratings given by one or more annotators. This data is then used to present and prove or disprove some of the hypothesis using multiple methodologies. The dataset from Kaggle hotel data contains 515,000 customer reviews and scoring of 1493 luxury hotels across Europe.
European Hotel Analysis
Extended Abstract
Aishwarya Gunasekar
University of North Carolina,
Charlotte
Charlotte, NC
agunasek@uncc.edu
Alisha Gujarathi
University of North Carolina,
Charlotte
Charlotte, NC
agujarat@uncc.edu
Dhiksha Ramkumar
University of North Carolina,
Charlotte
Charlotte, NC
dramkuma@uncc.edu
Priyanka Sawant
University of North Carolina,
Charlotte
Charlotte, NC
psawant2@uncc.edu
Shilpa Khandelwal
University of North Carolina,
Charlotte
Charlotte, NC
skhande1@uncc.edu
Siddhant Gokule
University of North Carolina,
Charlotte
Charlotte, NC
sgokule@uncc.edu
ABSTRACT
Hotel reviews are available in abundance today. This project focuses
on analyzing huge data set of hotel reviews and come up with
visualizations that can communicate all the information clearly.
CCS CONCEPTS
• Big Data→Data Mining; Data Analysis; • Machine Learning→
Regression; Classification;
KEYWORDS
Data visualization, Visualization, Hotel reviews, Rating, Score
ACM Reference Format:
Aishwarya Gunasekar, Alisha Gujarathi, Dhiksha Ramkumar, Priyanka
Sawant, Shilpa Khandelwal, and Siddhant Gokule . 2018. European Hotel
Analysis: Extended Abstract. In Proceedings of ACM Conference (Conference’
17). ACM, New York, NY, USA, 5 pages. https://doi.org/10.1145/
nnnnnnn.nnnnnnn
1 INTRODUCTION
Travelling is always an insight into a new side of the planet. Here
we analyze the hotel data containing 515,000 customer reviews and
scoring of 1493 luxury hotels across Europe. This is the exploratory
data analysis for 515k Hotel reviews in Europe. By looking at the
reviews of the Hotels we can get the information about the toprated
hotels in Europe and can predict which hotel is best to stay
while visiting Europe. Data-set used for this project is from Kaggle
and can be found at Kaggle dataset. This dataset contains 515,000
customer reviews and scoring of 1493 luxury hotels across Europe.
2 METHODOLOGY
First, the variables were studied and insights related to the dataset
was gained by observing the distribution of the data and checking
Permission to make digital or hard copies of part or all of this work for personal or
classroom use is granted without fee provided that copies are not made or distributed
for profit or commercial advantage and that copies bear this notice and the full citation
on the first page. Copyrights for third-party components of this work must be honored.
For all other uses, contact the owner/author(s).
Conference’17, July 2017, Washington, DC, USA
© 2018 Copyright held by the owner/author(s).
ACM ISBN 978-x-xxxx-xxxx-x/YY/MM.
https://doi.org/10.1145/nnnnnnn.nnnnnnn
the range, frequency and shape of the data. During analysis, data
preprocessing was done which involved activities like detecting
and removing errors and inconsistencies, eliminating duplicates,
convert numerical variable to categories, standardize the data and
deriving new variables to be used to examine the target variables
from different dimensions.
After the data was checked for tidiness, Business Use Cases were
formed that would prove beneficial to the hotel user as well as
the hotel owners. The hotel users can use these results to find out
the best option available while they are visiting any country of
their choice whereas the hotel owners or managers can request
information that would allow them improve their ratings, so that
more people visit their hotel.
The next step was to gain better understanding of the data by
visualizing the data and any relation that may have existed between
the data. This helped bolster the business use cases that were
formulated and helped improve the solutions provided.
The business use cases formulated and visualizations done led
to achieving multiple modeling techniques like regression, classification
and sentiment analysis. These models provided solutions
to the hypothesis that were formed in-order to help the users and
hotel managers.
2.1 Data Preprocessing
The raw dataset contained number of impurities like missing values,
inconsistent date column format, NULL values and duplicate values
which called for the data preprocessing. Data was cleaned following
a systematic and planned approach before running any models on
the data. For the purpose of data processing the CSV file was read
in a R data frame. Preprocessing was performed on this data frame
to remove the erroneous and null values, eliminating duplicates
and correct date column format.
Order of data preprocessing:
(1) Find the total number of rows with missing values:
(2) Remove Null values
(3) Eliminate duplicate values
(4) Uniformly format the date column to a single format
Conference’17, July 2017, Washington, DC, USA B. Trovato et al.
Figure 1: Data Preprocessing Statistics
2.2 Hypotheses
Depending on the pre-processed data, there were few hypothesis
that were formulated. These hypothesis were formed to improve
the experience of both the hotel users and the hotel managers.
2.2.1 Co-relation between Reviewer nationality and Reviewer
score: To find the co-relation between Reviewer nationality and
Reviewer score, so the hotel managers can anticipate what the score
of the reviewer could be and improve his hospitality towards the
guest in order to get a better rating.
2.2.2 Predicting Average score of the Hotel based on Country,
Hotel and Tags. Predict the average score of the Hotel based on
the country of travel, hotel name and type of trip(classified by tags
column) to help the User choose best hotel for his travel destination.
2.2.3 Suggest Best Hotel based on both Average score and Reviewer
Score. Average score and reviewer score are very important
features to suggest good hotels. Using these features in combined
to suggest best hotels to the user.
2.2.4 Sentiment Analysis. A sentiment intensity analysis is performed
over all the reviews to reflect the sentiments over people of a
particular nationality, a specific hotel, a specific location. The model
can also predict the sentiment of a particular hotel, nationality or
location.
2.2.5 Finding important words/phrases that are indicative of reviewer
score. Finding important words from the positive and negative
reviews is important as they reflect the score that is given by
the reviewer.
2.3 Data Visualization
Figure 2: Relationship between Tags and Total number of
reviews
2.3.1 Visualizing relationship between Tags and Total number of
reviews. The above plot is tags and total no of reviews. So from the
above plot we can observe that
(1) For Leisure trip we have the most number of reviews. So a
person going for leisure trip will have more number of hotel
and review options.
(2) Then, the business trip is the second most used tag and has
more number of reviews for user to analyze the hotel.
(3) While other tags like travellers with friends have no reviews
at all for any hotel.
Figure 3: Top 10 rated hotel
2.3.2 Visualizing the top 10 rated hotels. Here we are plotting
the average rating of the hotels against their names. Following are
the observations:
(1) Most of the hotels have average score 8 and above.
(2) Rare hotels have average score 7 or below
This is a primary observation of only 10 samples and it may be
possible that for samples of entire dataset the observations may
have slight variations.
European Hotel Analysis Conference’17, July 2017, Washington, DC, USA
Figure 4: The range of Average score
2.3.3 Visualizing the range of Average score. From above figure
we can observe that most of the Hotels average score lie in the
range of 8.0 and 9.1 range
Figure 5: Hotel Location with Average Score
2.3.4 Visualizing Hotel Location with Average Score. Here the
map shows the top hotels based on average score.
2.3.5 Correlation Matrix. In Figure 6, we see that there is a
surprisingly high negative correlation between the Negative word
counts and the Reviewer_score suggesting that a lot of people are
tending to give positive reviews.
Figure 6: Correlation Matrix
2.3.6 Figures. This article shows only the plainest form of the
citation command, using \cite.
Some examples. A paginated journal article [2], an enumerated
journal article [7], a reference to an entire issue [6], a monograph
(whole book) [19], a monograph/whole book in a series (see 2a
in spec. document) [13], a divisible-book such as an anthology or
compilation [9] followed by the same example, however we only
output the series if the volume number is given [10] (so Editor00a’s
series should NOT be present since it has no vol. no.), a chapter
in a divisible book [29], a chapter in a divisible book in a series
[8], a multi-volume work as book [18], an article in a proceedings
(of a conference, symposium, workshop for example) (paginated
proceedings article) [3], a proceedings article with all possible elements
[28], an example of an enumerated proceedings article [11],
an informally published work [12], a doctoral dissertation [5], a
master’s thesis: [4], an online document / world wide web resource
[1, 23, 30], a video game (Case 1) [22] and (Case 2) [21] and [20] and
(Case 3) a patent [27], work accepted for publication [24], ’YYYYb’-
test for prolific author [25] and [26]. Other cites might contain
’duplicate’ DOI and URLs (some SIAM articles) [17]. Boris / Barbara
Beeton: multi-volume works as books [15] and [14].
A couple of citations with DOIs: [16, 17].
Online citations: [30–32].
2.4 Data Modelling
The hypothesis formulated in the previous section are provided
with potential solutions using various modelling techniques.
2.4.1 Multiple Linear Regression. Regression was used to solve
the hypothesis for predicting the average score a reviewer with a
particular nationality would provide. Since the model of regression
was run on XL-Miner, there were few constraints that the input
data had to follow.
a. There was a size constraint on the input dataset that could be
fed to Multiple Linear Regression of 65,000 rows.
b. The reviewer nationality had 230 unique values and conversion
of categorical variable to ordinal could only contain 30 maximum
unique values.
In order to overcome these constraints, to deal with the hypothesis,
the top 5 most occurring countries were considered. This
had fewer than 65,000 rows and also less than 30 unique variables.
Performing this regression yielded that reviewers with Australian
nationality gave the highest scores vs Guests from United Arab
Emirates who gave the lowest among the 5 countries of Australia,
Canada, Israel, Saudi Arabia and United Arab Emirates.
2.4.2 Gradient Boosting Regressor. It is important to find out
words/phrases that are suggestive of the reviewers score. Positive
and negative words tend to affect the score. To regression model is
applied to the dataset to achieve this goal. The size of the data being
quite large, it is divided into train and test sets. The regression
model is trained on 20 percent of the data and validated on 80
percent of the data. The validation set is split into three parts for
analysis. Applying a Gradient Boosting Regressor yields a model
that tells us the importance of words. For instance, the presence
of words like negative not in the review reflect a lower reviewer
score. On the other hand, words like great, excellent tend to reflect
a higher reviewer score.
Like tables, figures cannot be split across pages; the best placement
for them is typically the top or the bottom of the page nearest
their initial cite. To ensure this proper “floating” placement of
Conference’17, July 2017, Washington, DC, USA B. Trovato et al.
Figure 7: Random Forest
figures, use the environment figure to enclose the figure and its
caption.
This sample document contains examples of .eps files to be
displayable with LATEX. If you work with pdfLATEX, use files in the
.pdf format. Note that most modern TEX systems will convert .eps
to .pdf for you on the fly. More details on each of these are found
in the Author’s Guide.
Aswas the case with tables, you may want a figure that spans two
columns. To do this, and still to ensure proper “floating” placement
of tables, use the environment figure* to enclose the figure and its
caption. And don’t forget to end the environment with figure*, not
figure!
2.4.3 Random Forest Model. Random forests are an ensemble
learning method for classification and regression that operate by
constructing a lot of decision trees at training time and outputting
the class that is the mode of the classes output by individual trees.
The dependent or target variable is recommendation which explains
whether the hotel is recommended or not based on hotel
profile. Since the data is too huge for processing in R, we will consider
data for one hotel. First, we selected the attribute from the
dataset. We are not going to use all the attributes. Once we select
the attributes, we can use Sample to split the data into 70percent
train data and 30 percent test data. Now we ran Random Forest
model.
3 CONCLUSIONS
This paragraph will end the body of this sample document. Remember
that you might still have Acknowledgments or Appendices;
brief samples of these follow. There is still the Bibliography to deal
with; and we will make a disclaimer about that here: with the exception
of the reference to the LATEX book, the citations in this paper
are to articles which have nothing to do with the present subject
and are used as examples only.
A HEADINGS IN APPENDICES
The rules about hierarchical headings discussed above for the body
of the article are different in the appendices. In the appendix environment,
the command section is used to indicate the start of
each Appendix, with alphabetic order designation (i.e., the first is
A, the second B, etc.) and a title (if you include one). So, if you need
hierarchical structure within an Appendix, start with subsection
as the highest level. Here is an outline of the body of this document
in Appendix-appropriate form:
A.1 Introduction
A.2 Methodology
A.2.1 Data Preprocessing.
A.2.2 Business Use Cases.
A.2.3 Data Visualization.
A.2.4 Data Modelling.
A.3 Conclusions
A.4 References
B MORE HELP FOR THE HARDY
Of course, reading the source code is always useful. The file acmart.
pdf contains both the user guide and the commented code.
ACKNOWLEDGMENTS
The authors would like to thank Dr. Yuhua Li for providing the
MATLAB code of the BEPS method.
The authors would also like to thank the anonymous referees
for their valuable comments and helpful suggestions. The work is
supported by the National Natural Science Foundation of China
under Grant No.: 61273304 and Young Scientists’ Support Program
(http://www.nnsf.cn/youngscientists).
REFERENCES
[1] Rafal Ablamowicz and Bertfried Fauser. 2007. CLIFFORD: a Maple 11 Package for
Clifford Algebra Computations, version 11. Retrieved February 28, 2008 from
http://math.tntech.edu/rafal/cliff11/index.html
[2] Patricia S. Abril and Robert Plant. 2007. The patent holder’s dilemma: Buy, sell,
or troll? Commun. ACM 50, 1 (Jan. 2007), 36–44. https://doi.org/10.1145/1188913.
1188915
[3] Sten Andler. 1979. Predicate Path expressions. In Proceedings of the 6th. ACM
SIGACT-SIGPLAN symposium on Principles of Programming Languages (POPL ’79).
ACM Press, New York, NY, 226–236. https://doi.org/10.1145/567752.567774
[4] David A. Anisi. 2003. Optimal Motion Control of a Ground Vehicle. Master’s thesis.
Royal Institute of Technology (KTH), Stockholm, Sweden.
[5] Kenneth L. Clarkson. 1985. Algorithms for Closest-Point Problems (Computational
Geometry). Ph.D. Dissertation. Stanford University, Palo Alto, CA. UMI Order
Number: AAT 8506171.
[6] Jacques Cohen (Ed.). 1996. Special issue: Digital Libraries. Commun. ACM 39, 11
(Nov. 1996).
[7] Sarah Cohen, Werner Nutt, and Yehoshua Sagic. 2007. Deciding equivalances
among conjunctive aggregate queries. J. ACM 54, 2, Article 5 (April 2007),
50 pages. https://doi.org/10.1145/1219092.1219093
[8] Bruce P. Douglass, David Harel, and Mark B. Trakhtenbrot. 1998. Statecarts in
use: structured analysis and object-orientation. In Lectures on Embedded Systems,
Grzegorz Rozenberg and Frits W. Vaandrager (Eds.). Lecture Notes in Computer
Science, Vol. 1494. Springer-Verlag, London, 368–394. https://doi.org/10.1007/
3-540-65193-4_29
[9] Ian Editor (Ed.). 2007. The title of book one (1st. ed.). The name of the series
one, Vol. 9. University of Chicago Press, Chicago. https://doi.org/10.1007/
3-540-09237-4
[10] Ian Editor (Ed.). 2008. The title of book two (2nd. ed.). University of Chicago Press,
Chicago, Chapter 100. https://doi.org/10.1007/3-540-09237-4
[11] Matthew Van Gundy, Davide Balzarotti, and Giovanni Vigna. 2007. Catch me, if
you can: Evading network signatures with web-based polymorphic worms. In
Proceedings of the first USENIX workshop on Offensive Technologies (WOOT ’07).
USENIX Association, Berkley, CA, Article 7, 9 pages.
[12] David Harel. 1978. LOGICS of Programs: AXIOMATICS and DESCRIPTIVE POWER.
MIT Research Lab Technical Report TR-200. Massachusetts Institute of Technology,
Cambridge, MA.
[13] David Harel. 1979. First-Order Dynamic Logic. Lecture Notes in Computer Science,
Vol. 68. Springer-Verlag, New York, NY. https://doi.org/10.1007/3-540-09237-4
[14] Lars Hörmander. 1985. The analysis of linear partial differential operators. III.
Grundlehren der Mathematischen Wissenschaften [Fundamental Principles of
European Hotel Analysis Conference’17, July 2017, Washington, DC, USA
Mathematical Sciences], Vol. 275. Springer-Verlag, Berlin, Germany. viii+525
pages. Pseudodifferential operators.
[15] Lars Hörmander. 1985. The analysis of linear partial differential operators. IV.
Grundlehren der Mathematischen Wissenschaften [Fundamental Principles of
Mathematical Sciences], Vol. 275. Springer-Verlag, Berlin, Germany. vii+352
pages. Fourier integral operators.
[16] IEEE 2004. IEEE TCSC Executive Committee. In Proceedings of the IEEE International
Conference onWeb Services (ICWS ’04). IEEE Computer Society,Washington,
DC, USA, 21–22. https://doi.org/10.1109/ICWS.2004.64
[17] Markus Kirschmer and John Voight. 2010. Algorithmic Enumeration of Ideal
Classes for Quaternion Orders. SIAM J. Comput. 39, 5 (Jan. 2010), 1714–1747.
https://doi.org/10.1137/080734467
[18] Donald E. Knuth. 1997. The Art of Computer Programming, Vol. 1: Fundamental
Algorithms (3rd. ed.). Addison Wesley Longman Publishing Co., Inc.
[19] David Kosiur. 2001. Understanding Policy-Based Networking (2nd. ed.). Wiley,
New York, NY.
[20] Newton Lee. 2005. Interview with Bill Kinder: January 13, 2005. Video. Comput.
Entertain. 3, 1, Article 4 (Jan.-March 2005). https://doi.org/10.1145/1057270.
1057278
[21] Dave Novak. 2003. Solder man. Video. In ACM SIGGRAPH 2003 Video Review on
Animation theater Program: Part I - Vol. 145 (July 27–27, 2003). ACM Press, New
York, NY, 4. https://doi.org/99.9999/woot07-S422
[22] Barack Obama. 2008. A more perfect union. Video. Retrieved March 21, 2008
from http://video.google.com/videoplay?docid=6528042696351994555
[23] Poker-Edge.Com. 2006. Stats and Analysis. Retrieved June 7, 2006 from http:
//www.poker-edge.com/stats.php
[24] Bernard Rous. 2008. The Enabling of Digital Libraries. Digital Libraries 12, 3,
Article 5 (July 2008). To appear.
[25] Mehdi Saeedi, Morteza Saheb Zamani, and Mehdi Sedighi. 2010. A library-based
synthesis methodology for reversible logic. Microelectron. J. 41, 4 (April 2010),
185–194.
[26] Mehdi Saeedi, Morteza Saheb Zamani, Mehdi Sedighi, and Zahra Sasanian. 2010.
Synthesis of Reversible Circuit Using Cycle-Based Approach. J. Emerg. Technol.
Comput. Syst. 6, 4 (Dec. 2010).
[27] Joseph Scientist. 2009. The fountain of youth. Patent No. 12345, Filed July 1st.,
2008, Issued Aug. 9th., 2009.
[28] Stan W. Smith. 2010. An experiment in bibliographic mark-up: Parsing metadata
for XML export. In Proceedings of the 3rd. annual workshop on Librarians and
Computers (LAC ’10), Reginald N. Smythe and Alexander Noble (Eds.), Vol. 3.
Paparazzi Press, Milan Italy, 422–431. https://doi.org/99.9999/woot07-S422
[29] Asad Z. Spector. 1990. Achieving application requirements. In Distributed
Systems (2nd. ed.), Sape Mullender (Ed.). ACM Press, New York, NY, 19–33.
https://doi.org/10.1145/90417.90738
[30] Harry Thornburg. 2001. Introduction to Bayesian Statistics. Retrieved March 2,
2005 from http://ccrma.stanford.edu/~jos/bayes/bayes.html
[31] TUG 2017. Institutional members of the TEX Users Group. Retrieved May 27,
2017 from http://wwtug.org/instmem.html
[32] Boris Veytsman. [n. d.]. acmart—Class for typesetting publications of ACM.
Retrieved May 27, 2017 from http://www.ctan.org/pkg/acmart
