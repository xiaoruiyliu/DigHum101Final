# DigHum101Final, Hotel Review Analysis

This is my final digital humanities project for DigHum101.

![alt text](https://www.gohawaii.com/sites/default/files/styles/image_gallery_bg_xl/public/hero-unit-images/Island-of-Hawaii-Accommodations.jpg?itok=6rQtOfzn)

Look at this nice hotel in Hawaii... surely it has good reviews, right?

Abstract:

This project is an analysis of a hotel review dataset provided by Kaggle. The data has a lot of entries (~35000) so I was
interested in seeing how these methods would perform on a large dataset. The proprietary mission is to use gensim topic
modeling and TFID vectorizing to create a classifier to play around with. There were a couple of interests that were explored.
Reviews are rather fickle formations of text. Not only are they deeply independent, reflecting the writer's personal experience,
but they also reflect the writer's expectations versus reality rating. A review that sounds positive might receive a low rating
simply because the reviewer had blown-up expectations. 

Some initial preprocessing and analysis were done to understand various aspects of the data like the location of all the hotels
and the most used words in the reviews. Then, a gensim topic model is created to capture some of the topics (or non-topics) that
may be seen in the reviews. While not all the topics are too interesting, some of them are surprisingly intuitive, like 
topics about service, cleanliness, and location. Finally, a classifier is created. The user is then able to input various reviews
and see how they classify. 