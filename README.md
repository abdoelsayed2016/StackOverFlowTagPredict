# Predicting Tags for the Questions in Stack Overflow
What is Stack Overflow?<br>
Stack Overflow is the largest, most trusted online community for developers to learn, share their programming knowledge, and build their careers.
It is something which every programmer use one way or another. Each month, over 50 million developers come to Stack Overflow to learn, share their knowledge, and build their careers. It features questions and answers on a wide range of topics in computer programming. The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers in a fashion similar to a wiki or Digg. As of April 2014 Stack Overflow has over 4,000,000 registered users, and it exceeded 10,000,000 questions in late August 2015. Based on the type of tags assigned to questions, the top eight most discussed topics on the site are: Java, JavaScript, C#, PHP, Android, jQuery, Python and HTML. https://stackoverflow.com/.
# Machine Learning Problem Formation
A data set which contains xi and yi and yi belongs to one of the two classes/labels ‘0’ or ‘1’ is called a Binary Classification Problem. And If the yi belongs to two or more values, let’s say 0,1,2,3,4,5,6,7,8,9 and can’t belongs to two classes at a time is called a Multi-class classification problem.

But our present problem is entirely a different one compare to the above mentioned. We have xi,yi and yi is a set in itself! Because our yi’s represents tags in the questions and xi’s represents questions and a question in the Stack Overflow can have multiple tags Q1 = {t1,t2,t3,t4,…etc}.

There could be questions like

Q1 = {t1,t2,t3,t4}

Q2 = {t1,t2,t3}

Q3 = {t1,t2}

So our yi is a set of classes. This problem is called a Multi-label Classification. Unlike in Binary and Multi-class classifications, where each xi belongs to only one class label yi, here each question xi belongs to one or more classes yi’s.

Multi-label Classification: Multi-label classification assigns to each sample a set of target labels. This can be thought as predicting properties of a data-point that are not mutually exclusive, such as topics that are relevant for a document. A question on Stack Overflow might be about any of C, Pointers, FileIO and/or memory-management at the same time or none of these. Go through the link and know more details about Multi Label Classification ( http://scikit-learn.org/stable/modules/multiclass.html)
