# Analysis of mental health concerns among students using Reddit community data

The mental health of university students is a major concern. Stress, depression, anxiety, and other mental health concerns can have a significant impact on a student's academic performance and overall well-being. This is why it is crucial to understand the factors that contribute to these problems and find ways to address them. A study shows that 8 out of 10 students get stressed, depressed, or feel anxiety during their time at university. This could lead to insomnia, cognitive deficit, mood swings, and even physical illness. Some of the major stressors for students are examinations, peer competition, finance, or personal issues.

This project analyzed students’ stress levels over the years to find patterns and causes that might contribute to them. It can be seen that the stress levels increased over the pandemic. It can also be noticed that students’ stress scores were the least over the holidays (especially in summer). We also tried to find common topics that occur among high-scoring posts to find insights into what stresses students. Campuses can understand these factors that contribute to their students’ stress levels and take measures to improve them. Universities can then use this information to develop targeted interventions, such as workshops or
counseling services, that address the specific stressors identified by students. In addition to that, universities can also raise awareness about mental health and provide students with the resources they need to manage stress and anxiety. This can include offering free therapy sessions or support groups, providing access to mindfulness and meditation resources, or even implementing policies that promote a healthy work-life balance.


The project is divided into the following:
1) Data collection: Scripts used to extract the data from University subreddits and preprocess them.
2) Sentiment classifier: Scripts to build and train the sentiment classifier with transfer learning on top
   of the lightweight DistilBERT transformer. The posts from 14 Mental Health subreddits such as r/Anxiety, r/Depression, etc.
   and posts from other non-Mental health subreddits were used to train this model. The classifier was then used to
   assign sentiment scores to the students' posts from 50 University subreddits.
3) Analytics: Scripts to analyze the sentiment scores and perform temporal analysis, topic modeling, and generate word clouds.
4) utils.py: This has all the util functions used in the rest of the Colab notebooks.
   
