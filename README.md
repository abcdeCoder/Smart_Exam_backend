## Smart_Exam_ML+backend
# Hello Developers Todays I want to introduce Full stack (Django+react+ml)
#Here is frontend on react 
## <a href="https://github.com/abcdeCoder/Smart_exam_frontend">Smart Exam</a>                       
# Here The Live Link of Web

# <a href="http://gvprojects.ml:3000/">Smart Exam</a>
# What is Smart Exam?
# This is Smart Exam App in which user can give the test 
Backend: Django + Django Rest Framework + Machine Learning stuff 
Frontend: ReactJS + Material-UI Database: mysql Hosting : Virtual Machine( linode) Ubantu as Oprating Sysytem
Motivation and Methodology I tried to cluster text using traditional natural language processing techniques (such as TF-IDF), then assigning the same score to every point in the cluster as the score of centroid of the cluster. I looked at Kappa scores for different combination of preprocessing techniques and algorithms used for clustering. Then I tried using word embeddings, followed by Universal Sentence Encoder which transforms the entire sentence into a vector as compared to word embeddings which give vectors only word by word. The performance of Universal Sentence Encoder was found to be the best (other related stuff like BERT gave similar score). Dataset used: https://www.kaggle.com/c/asap-sas It has two human scorers, with their Kappa score being ~ 0.9 Using the dataset, on an average a Kappa score of ~ 0.5 can be achieved (averaged over the 10 essays in the dataset). For this, the teacher only needs to grade 20% of the total responses. A further improvement to this score can be by allowing teachers to observe word clouds and using topic modelling for each cluster, to improve any outlier cluster gradings. Different clustering techniques can also be looked at. There is a tradeoff here in the number of clusters vs. the human effort required. More are the number of cluster, better is the homogeneity of the data points, but so is an increased effort in grading the centroids of these clusters. You can find the Kaggle notebook with the research in Backend repository.

How to Install :- 
1.) pip install -r requirements.txt --use-deprecated=backtrack-on-build-failures
2.) if you gets some error then you can try following command and refer the zip file 
3.) copy universal-sentence to root directory 
you can try following cammond if you gets any errors
just copy pase django and rest_framework floder from env
and then install these
pip install pytz
pip install nltk
pip install contractions
pip install inflect
just copy floder corsheaders
sudo apt-get install libmysqlclient-dev
pip install mysqlclient
pip install sklearn
pip install tensorflow_hub
python -m pip install Pillow
pip install --no-deps tensorflow-io
# files link
https://drive.google.com/file/d/1TBzovq_F1NVmRqZSQ0HsMOs99-TCPt0n/view?usp=sharing
