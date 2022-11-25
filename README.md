[vibrometer edited latest.docx](https://github.com/lali1605/Machine-learning-/files/10092749/vibrometer.edited.latest.docx)
# Machine-learning-
The  proposed model can be used for SHA . This will check and also inform about disasters and will be helpful in reduce of losses of life and property. the basic working technology for prediction and determining the  work proposes system aims to predict the health of a structure. 

Abstract. Vibrations are common phenomena seen in mechanical structures that can be detrimental to many systems. If not monitored, they can cause damage to structures, Vibrometer is sensor used for measuring vibrations of mechanical structures, machines, as well as sound level in an area and will collect lot of data that is to be analyzed to determine the strength of the structures. Machine learning is the basic working technology for prediction and determining the  work proposes system aims to predict the health of a structure, converting the cantilever  beam vibration reading to graph which is able to give the correct state or health of the structure. This work will cover all the major challenges faced due to natural down fall of quality of structure .The aims to able to check the Structural Health and able predict the condition of the structure . 


   Keywords : Vibrometer , Machine learning, Frequency , Structure strength 

1. Introduction

Vibration is a phenomenon where the oscillation takes place at the equilibrium point . The term vibration stands for Shaking ,brandishing . the Vibration are the singles consisting of number of frequencies , the reading of data set are pure reading in the time domain , which are required to be converted into frequency domain .
Cantilever Beam is a type of beam with one end projecting ahead the point of support ,this beam is free to move in a vertical plane under the influence of loads placed the free end and the support . This beam is generally small and is restricted to 2m to 3m .  



Vibrometer [1] is a two-beam laser measuring device used for measuring frequency difference between the internal refence beam and a test beam. the use of this device is to measure vibration amplitude. Automation System [2], is the demand and requirement of the future. 
 
Fig 1 [3] Vibrometer
. The system is the graphical representation of the vibrometer, the beam is the combination of two, infrared LDV and He-Ne SLDV from the target. 


. The reading of the vibrometer is in continuous numerical and in the time domain the domain required is frequency. 

The drawback of the vibrometer:
. the signal are vibrations and it requires a converter to convert the signal into binary which are understood by the computer system. 


Machine Learning is a sub category of  Artificial Intelligence that generally used for training the data and finding insights and accuracies , the type of machine learning depending upon the dataset and available output are Supervised ,Unsupervised , Reinforcement Learning , Vibration data is accompanied with output is under the Supervised Learning and the data is non-linear  thus SVM Support Vector Machine will produce  the most relevant result .  


2. Literature Survey

The study in [4] covered that the Laser Vibrometer through which beam reading are obtained even the shapes too boundary, the nature of beam is free, the nature of reading is in the time domain the domain to which it should or required to be converted is frequency. The software used for analysis of FFT Fast Fourier Transform [5]is FEM Finite Element Model.
The experimental and numerical model also covered the accurate boundary conditions and the determined results have certain errors with the real result. The outcomes from this article covered are Nature of Beam, Nature of frequency, software used for analysis of FFT, FEM. The drawback or the area to be included in these the changing methods or how the conversion took place and it is difficult to convert one domain to other domain without proper knowledge, 
The conversion of the beam reading, Shape boundary reading should also be done so the analysis and unit reading will become more understandable and the outcome will become more efficient after we convert these readings 





The approach in [6] has the properties of the PSV-3D Scanning Vibrometer with robotics and makes it viable to utilize CAE Computer Aided Engineering data for defining the test. The main advantage for the model updating process. is the potential to work with imported Finite Element  geometries and coordinate systems and to automatically gather data at all nodal points. Use of robotics is after the successful steps and after the model is working virtually then connecting IOT and robotics come into picture. The work that needed to be done is the data that is being gather from the nodal point of the beam should be observed carefully and made it very sure the reading should in the domain frequency format automatically before the modelling into 3D Scanning as the frequency domain have for accurate results in 3D modelling. 
The graphene NEMS [7] is working in a resonate mode which can be used for high performance of vibration sensors, the device is not able to predict the vibration value as expected but it does provide some fundamental effect with greater impact on device with high quality and have a very low stress. The idea or thing to overcome is the prediction value should be correct for the model to work according it, the values or reading must be accurate according to the resonant. Microelectromechanical systems (MEMS) proposed by authors of is a Structural Health Monitoring system, the lightweight construction build of material on which the Structural Monitoring System, this based on certain frequency to check the health, the frequency of 100kHz at a certain distance of 0.2m. The issue here is certain material which are not lightweight does not pass the ultra sound wave so no result check can be done. 


The Non-Linear data under the Supervised learning where the data does not follow any particular trend thus the use of classification algorithm of Supervised learning i.e is SVM , Support Vector Machine is best suitable with the data set used , the SVM will able to predict the accurate result of the dataset . 

If the dataset belong to the category , like images , the deep learning and neural networks  combined with Open cv and image processing methods of AI to included for performance measurement and predicting the result , CNN is the best suitable for image data , CNN is Convolution Neural Networks . [8] 






3. Proposed system
From the literature survey it is found that there are challenges in data collection using vibrometer and furthermore it is more difficult to predict the strength of the structures due to non-automated system of detection. Domain of automating vibrometer is very naïve and very less or no work is being found in the literature. This work hence proposes a system based on Machine learning techniques that will take the input from the vibrometer reading as shown in fig 1 .
 


fig 2 Flow-Chart  :  Working Flow  of the proposed System 
The working flow and the step by step assumed system is represented in this flowchart 



 
Fig 3 Original Dataset in Time Domain
The exact reading in seconds and volts, these reading are obtained through the cantilever Beam , through Vibrometer acting as a sensor . 

This work proposes a machine learning model that will be trained and tested for the captured data. The goal here is to make the system real time by converting the reading of the vibrometer into visual wave to be able to predict the value to keep a check on the strength. Once the model is built on the dataset then the aim is to use the real or random values and check that the outcome is accurately fits or is able to provide the solution. The machine learning algorithms like Linear regression , SVM that have worked on the similar kind of vibration data is been taken in consideration.
The objective of the work is designing an automatic vibration detection system that is capable of doing
1.	the data set analysis 
2.	machine learning model check 
3.	transformation of the data values into amplitude and frequency.
4.	the method of FFT fast Fourier Transform  for discrete data. 

The initial phase of the model is implemented and can be verified by visiting the Kaggle https://www.kaggle.com/datasets/lalisharma/vibrometerdataset?select=data+ml.csv [9] 





The goal here is to make the system real time by converting the reading of the vibrometer into visual wave to able to predict the value or to keep a check . Once the model is build on the dataset then the aim is to use the real or random values and check that the outcome is accurately fits or is able to provide the solution. This work proposes a real time implementation of Structure strength prediction using machine learning techniques.

. the methods are very much simple it the use of machine learning algorithms , time data , multi dimension linear regression algorithms . 





4 . Results :
The original dataset is converted and the pre-processing has been applied the information is also attached here [9]. The python version here used is python 3.9[10 ] , the practical or model building is done on the Vibrometer dataset project on Kaggle form account [9]. It is a Notebook platform where all the performance and working and progress is available real time , and contribution is also appreciable . 


 

Fig 4The conversion of time domain to frequency domain [9] 
 The time domain dataset from Fig 3 is converted into frequency domain 
Where the seconds in time to frequency in hertz . this was the first step where the domain conversion is the task and the outcome is in frequency domain . 



 
Fig5(a)The dataset is divided into two parts where major is the training part and the remaining is the testing , this figure is the algorithm and to find the discreate values in data also the spread  or normalization of the data is represented . 
 
Fig5 (b) Discrete Value Dataset representation  [9] 



 
Fig6  Training and Testing  representation [9]

the data is divided into training and testing so to work on it individually
the training and testing important because the machine learning is self learner once trained correctly , to find the accurate results , testing is to check the working on new data values . 

 
 
Fig 7 FFT algorithm implementation [11] 
This algorithm works on the principle of divide and conquer where it divides the problem to find the optimal and accurate solution . 






 

Fig8 SVM model implementation[9]  
SVM The supervised Classification algorithm used for the non linear kind of data , generally provides the support boundary depending on the type of data set its deal with . 


Though this algorithm the discrete Fourier in the dataset is being identified this the first algorithm to be worked on. it will return the coefficients A, B etc corresponding to some fixed frequencies. 

The methods fits the model and the real time data also fits the model we will able to see the working hardware called vibri (vibrometer laser system) converting and detecting the age, quality , vibration of the object or surface through the device which has the machine learning training and the real time data as the testing part .




 

                          Fig 9(a) Sine Wave plot from the time and amplitude 
The plot is between the x and y axis with  x label –time and y label – Amplitude 

Amplitude = np.sin(time )

Where np is numpy library of python 
And sin is the angel 

The values of  time and Amplitude are taken in a real time input as variable a, b also included 

 



Fig 9 (b)  time , Amplitude  sine wave graph 


 
                             

                                                          Fig 9 (b)
The implementation for forming the sine function graph for  analysis  of the oscillations 
with respect to Time  and amplitude . 






 
  Fig 10 (a)The real time oscillation though input ranges from the dataset       reading , the matlplotlib is a visualization library , which is able to produce the time and time Amplitude . 
 
Fig 10(a)    The real time oscillation though input from the dataset       reading , the matlplotlib is a visualization library , which is able to produce the  time and time Amplitude.                                      

 


Fig 10(b) the oscillation from -5 ,5  (the reading oftime  and Amplitude ) 
Fig 10(b) The plotting result is able to produce between the time  and  Amplitude . 
For Different reading the oscillations differ .

The values of  time and Amplitude are to be taken as input 
  
 
                                     Fig 10 (b)   the input reading differs the plot output 



\



 
  Fig 11(a) Expected is to check the view of result must be in these form 

. 
 

                                           Fig11(b) this for time and volts i.e seconds and volt 

The original data set and the refence from the MATLAB  result are certainly not exact as the actual outcome the difference is in the outcome along the FFT algorithm but some how due to error in the maybe training of the data using SVM it is not able to predict the precise result comparing with the actual outcome


Similarly as there is not the accurate result in the time similarly there is also issue with the frequency domain the result is precise but not accurate . 
 
                 Fig 11(c) the plot between the frequency domain 
 
                       Fig 11(c) the frequency domain graph plot but the ruslt doesn’t match as the model is not  able to predict the exact out of it as the training and testiin of the data set

5 . Future Scope of the Work 


The future scope of the proposed model can be used for detecting earthquake, the age or quality check of dams, bridges, railway lines etc . This will check and also inform about the natural disasters which will be a helpful and reduce of losses of life and property. It can also be used in medical field for finding the for human bone strength. It will also be helpful in various other fields yet to discovered. If in future the dataset is in form image , the image processing including the concept of deep learning and CNN can be used and implemented to get the results , the CNN will directly able to identify the strength of structure through images . 


