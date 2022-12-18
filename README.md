# MPA-DIE-project
https://studio.edgeimpulse.com/studio/165885/

https://studio.edgeimpulse.com/public/168559/latest

In this project I worked on embedded machine learning. Regarding the topic on the first part I’ve made the program understand and tell motions such as idle, up-down, left-right, clockwise and counter clockwise circle motion with 10 minutes’ worth of recorded data. In the second part I’ve made the program understand the word hello. 
  In the first part I connected my phone to edge impulse and used its motion detector to record the motions I’ve mentioned before. 20% of the data uploaded was taken for future testing. I had spectral analysis to analyze the data, classifier to classify the data and anomaly detection to see if there were any anomalies. When everything was done, I tested the data with the test part of the data that was put aside, the accuracy was said to be 100%. For final I tested it with my phone to see if it worked.
  In the latter part I’ve recorded myself saying hello with my phone. I opened an audio mixer and cut the parts of me saying hello to individual 1 second clips. I uploaded them to google colab and did the codes that were given by the course. After that I uploaded the recordings and some other from the google colab to the edge impulse. Once again 20% was taken as test. I had MFCC and classifier in this part. The data was tested after this, the accuracy was 96.56%. Like the other one I also tried it with my phone to make sure and it worked.
