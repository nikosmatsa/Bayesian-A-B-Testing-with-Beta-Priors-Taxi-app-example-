# Bayesian-A-B-Testing-with-Beta-Priors-Taxi-app-example-


A/B Testing is comparison procedure of two different method of marketing.
Companies are very interested knowing which of the two marketing strategies is better or more highly likely to occur.
A simple mathematic division contains the outcome of a method.
This outcome is called Conversion Rate and is actually 
a proportion of the total number  customers e.g  divided by the total number of visitors in a web application . 
For example let us assume that you own a web application which provides to the user taxi services and calling 
a taxi cab by the single click in your mobile phone.
The marketing department of this company have done a study and tried two different versions 
of the app and wanted to know which one version is better according to the rides made from each version.
Data analysts received the numbers from the first version and concluded that 72 users from 600 that they visited
version A the same day took a taxi ride, and 120 from 750 that visited the version B took a ride the same day 
or some minutes after they saw the competition.
So now we have 72 conversions from method A and 120 from from method B.

Y1 ~ Binomial (n1,θ1)
Υ2 ~ Binomial (n2,θ2)


Using Beta priors for each θ due to conjugate bayesian analysis we have :

θ1 ~ Beta(3,25)
θ2 ~ Beta(3,25)
