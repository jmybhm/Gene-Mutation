# Classifying Gene Mutations into Subtypes using Text Data 

With the development of personalized medicine comes the need to create reliable models that can automate the process of detecting the type of gene mutations involved, and their potential targets. The understanding of mutational subtypes is crucial to the successful treatment of individual cancer subtypes. 


The dataset used for the project were 3823 document files with mutation’s text descriptions and the response variable “Class,” which contained nine different classes that a genetic mutation can be classified into. Our team’s goal was to use the text data in order to classify mutations into subtypes relevant to their mechanisms.   

My team members and I used Word2Vec package in R to create similarity matrix and convert the text data into numeric matrix. We increased testing data accuracy upto 55% with convolutional neural networks, from random guess baseline of 11%. There is definitely room for model improvement, for one thing we could utilize full documents instead of extracting first 100 words from each document due to computing power limitations. 
