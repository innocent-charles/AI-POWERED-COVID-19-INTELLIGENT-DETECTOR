# AI-POWERED-COVID-19-INTELLIGENT-DETECTOR
COVID -19 is the acronym for coronavirus disease that discovered in the late of 2019 in wuhan china according to the WHO.With the outbreak of an unknown disease in late 2019 in China, some people became infected with the disease in a local market.The specific cause of this widespread disease was initially unknown, but after the laboratory examination and analysis of positive sputum by real-time polymerase chain reaction (PCR) test, the viral infection was confirmed and eventually named “COVID-19” upon the recommendation of the World Health Organization (WHO).

While the RT-PCR test is the early method and  gold standard for diagnosing COVID-19, it has limiting aspects with certain features that make it difficult to diagnose the disease. RT-PCR is a very time-consuming, complex, costly, and manual process. One of the drawbacks of this method is the need for a laboratory kit, the provision of which is difficult or even impossible for many countries during crises and epidemics. Like all diagnostic and laboratory methods in healthcare systems, this method is not error-free and is biased. It requires an expert laboratory technician to sample the nasal and throat mucosa which is a painful method.
One of the most important ways to diagnose COVID-19 is to use radiological images, including X-ray Chest imaging is a quick and easy procedure recommended by medical and health protocols and has been mentioned in several texts as the first tool in screening during epidemics.

The aim of this project is to creat an AI intelligent radiognose tool to simply easy making detection of the covid-19 from the given x-ray images and also collecting and storing the different cases for the covid-19 outbreak accross the different areas.

#### METHODS , DEPLOYMENT AND TOOLS USED 
- I used Two algorithms based on CNN(Convolutional Nerual Network) in Deep Learning one i named as CovidDetectorNet that i built from scratch and another built based on the transfer learning which resnet101.
- Then transfer learning showed high accuracy and performed well in both training and validation images ,therefore i deployed model based on transfer learning by using Flask API and resulted a Web Application that is simply as it saves time and quickly detect the covid-19 from the x-ray images.
<pre>
                      Accuracy  Sensitivity   Specificity 
CovidDetectorNet       84%         25.6%         69.6%

Resnet101              93%         92%           95%
</pre>
<img src="https://github.com/innocoder-official/AI-POWERED-COVID-19-INTELLIGENT-DETECTOR/blob/main/screenshot/COVID_19_image1_detector_system_GOODVIEW.png">

- I used Python 3.9.2,sqlite database for storing the data from system and dataset obtained from  https://github.com/ieee8023/covid-chestxray-dataset


### HOW TO USE FLASK APP 
<ul>
  <li>Install python version 3.9.2</li>
  <li>Download repo, change to directory of repo, go to command prompt and run <b>python app.py</b></li>
  <li>Then from command prompt write pip install name_of_packages </li>
  <li>On command prompt, run <b>python app.py</b></li>
  <li>Open your web browser and go to <b>127.0.0.1:5000</b> to access the Flask App</li>
</ul>


### CONCLUSION 
The application of deep learning in the field of COVID-19 radiologic image processing reduces false-positive and negative errors in the detection and diagnosis of this disease and offers a unique opportunity to provide fast, cheap, and safe diagnostic services to patients.

### DISCLAIMER
<strong>I am not from the medical background and this project has been developed for the demonstration of the concept so use it for study and research it does not yet approved by the medical proffesional</strong>.


### AUTHOR
#### INNOCENT CHARLES 
<ul>
<li>LinkedIn:https://www.linkedin.com/in/innocent-charles-329194214/</li>
<li>Portfolio:https://innocentcharles.com/</li>
</ul>

