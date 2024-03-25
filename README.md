Here we are going to discuss how we can build a machine learning system in python which can detect whether a person has Parkinsons disease or not.
This kind of projects comes under health care domain
Health care is one of those field where Machine learning can contribute a lot.
We can use this machine learning techniques to diagnose and find certain diseases in its early stages so that a person can get early treatment and its life can be saved.
That is why health care projects are very important for us.
So lets understand the problem statement.

It says that there is a Medical institution 
So it can be a Hospital or Medical college or  a research institutes
They are doing some researches on Parkinsons disease . How they can detect parkinsons disease early so that they can treat it.
They want us to built a model or system which can detect the Parkinson’s in a patient depending upon several condition.



Parkinson’s disease is a progressive nervous system disorder that affects movement leading to shaking, stiffness and difficulty with walking, balance and coordination. Parkinson’s symptoms usually begin gradually and get worse over time.

You know it affects mostly the person who are  more than 50 years of age.
Not necessary , because some cases are also there where people below that age  also get affected and it called Young onset of Parkinsons 
This one of the critical disease in Health care.

Here we have a data set in which there are details or information of patients who having Parkinson’s and who doesn’t have Parkinsons.

We know that  Machine Learning models can go through the data and can find Pattern in the data
And understand what are symptoms can found in patient having parkinsons and symptoms in people not having Parkinsons.
About Dataset
Context
Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of
dementia is increased.

Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician.

Data
The data & attributes information for this project is available at https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/

Attribute Information:
Matrix column entries (attributes):
name - ASCII subject name and recording number
MDVP:Fo(Hz) - Average vocal fundamental frequency
MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
MDVP:Flo(Hz) - Minimum vocal fundamental frequency
MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several
measures of variation in fundamental frequency
MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
NHR,HNR - Two measures of ratio of noise to tonal components in the voice
status - Health status of the subject (one) - Parkinson's, (zero) - healthy
RPDE,D2 - Two nonlinear dynamical complexity measures
DFA - Signal fractal scaling exponent
spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation

Citation Request:
If you use this dataset, please cite the following paper:
'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection',
Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM.
BioMedical Engineering OnLine 2007, 6:23 (26 June 2007)
