# Speech_Therapy_Project
##Objective\
The main objective behind making this project was to be able to help the people who
are having impaired speech and want to improve their speech .The project focuses on helping the patient to improve his speech by interacting with the system and
based on the feedback it would be encourage the patient to do better in his improvement journey.It helps in handling the speech processing in a good way that the therapist can see the progress from distance and update the therapy based on the feedback.

##Model Description\
We are using the famous Hidden Markov Model to store the speech properties. Hidden Markov Model is a probabilistic model which is used to explain or derive the probabilistic characteristic of any random process. When we apply log function to the spectral representation of the speech during reverse Fourier transform, it is converted to cepstrum whose coefficients are steady because of application of log function and it represents the speech in a nice manner. This representation can be used as the speech property. We take all such cepstral coefficients and build a code book which helps in generating the observation sequences. Code book contains 30 speech samples for each word. We use a feed-forward model for modeling speech samples. While speaking, we speak a word from start to end. So, there is no need for backward movement.   
Since, speech signals depend a lot on 
the environment, live testing might not be very good. But, if we train the model live and
test it immediately, then we get significantly better accuracy.

Basic requirements to develop this project are as follows:-\
• Windows Operating System\
• Microsoft Visual Studio 2010\
• Recording Module\
• Cool Edit 2000\

#Future Improvement\
Future improvements include development of this project using High Level
Languages like Java or Python which can use multi-threading concepts to run the model
training part in the background. This will remove the waiting time during training of
new words. This will improve the live accuracy and give the project new wings.

Owners - \
Harsh verma - 224101021\
Kaushal Mistry - 224101031\
Chinmay Rathod - 224101063\
IIT Guwahati
