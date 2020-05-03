# voice-prescription 
A PROBLEM STATMENT OF SIH(Smart india Hackathon) 2020
Technology Bucket : Health Care and Bio Medical Devices  	
Category: Software
Company Name/Ministry Name:  Bajaj Fin Serv
Problem Code :  AP63 (https://www.sih.gov.in/sih2020)

voice prescription: 🗣🩺⚕️

**desktop application : http://www.mediafire.com/folder/uqlw1t3fs5wpr/dist

**The process which we used is speech recognition i.e. “speech to text” where the doctor ask for patient’s data and then patient will respond to that data like name, age, symptoms etc. 

And now the doctor will dictate a medical prescription to patient  by diagnosing the symptoms through voice command according  to the symptoms and data. 

The speech is converted to text format and get appended on the template(prescription). By using a software called Adobe Photoshop the template (prescription) is designed . 

We used python packages like open-cv for image manipulation and pillow for  conversion of image into pdf and Tkinter for App(GUI)  And SMTPlib for sending prescription through mail. 

**A doctor will be able to dictate his prescription to the patient while talking to his PC running windows

• For all keywords data will be captured discreetly. 

**• Doctor will be able to edit / delete by voice or hand any entry that has been made. 

• Doctor will be able to preview the prescription. 

• Patient willget the PDF document either directly or as a link in SMS/WhatsApp

***•The main advantage of this prescription is : The patient will get prescription in pdf format  and there is no chance of wrapping/burning/loss/spoilation of prescription

**![application](Screenshot%20(33).png)

**![prescription](Screenshot%20(30).png)

**TECHNOLOGIES :

The  project  voice prescription  is  mainly  based  on internet . 
⇒ The  Technologies  that  are  used  for  the  project  are
**Python programming :
Speech Recognition.(pyaudio and speech Recognition)
Prescription Generation in pdf  format.(pilow)
Mailing  the pdf.(SMTPlib) 

Therefore,  the  patient  can  get  the details  from  the  doctor  in the  form  of  pdf  and it  automatically  gets saved  to user's device and is automatically sent to patient though email or SMS .    
-> Template Design and standard resolution

**Dependencies :  
Photoshop(template design and standard resolution)
Speech Recognition -> https://youtu.be/K_WbsFrPUCk
Python Packages:
Tkinter GUI(window application , Graphical User Interface)                                                                               Open cv(Image Manipulation) 
Pillow(Conversion of image to pdf)
gtts(Google text to speech)

**refer 'requirements.txt' for requirements and understanding the code.

**PLACE ALL THE CODES IN SAME LOCATION(UNZIP THE TEMPLETE.zip FILE) , unzipped templete folder should be in same location where codes are present.

**YOU THE CHOOOSE DIFFERENT TEMPLATES OF DIMENSION (600x849) AND REPLACE IT WITH PRESCRITION.JPG FILE. replacing the template should be done in folder location as well as in program too.
