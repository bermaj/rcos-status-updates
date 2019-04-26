My Final Blog Post

  This semester was a tough one in RCOS. This was the first semester that I worked on a project that was not 
purely software, but rather reliant on hardware. This introduced me to a new set of problems that I
was not accustomed to solving.
  
  First, I had to learn how to use documentation for hardware from a manufacturer. This was not easy to do. 
The documentation was often difficult to decipher for actual use cases or in once instance included 
instructions that were unnecessary, such as in the case of an operation on the checksum that was not needed. 

  Further, things did not go quite as planned with the hardware. We had overlooked that the radio, at 
least our test unit, required drivers from the manufacturer only available for Windows. This was of 
course a major setback for making our software available on all platforms. Additionally, after going back 
and forth with the manufacturer, I found out that documentation was not available for all models of radios, 
specifically for programming older models, which was another major setback. '

  Despite this, development continued, with a Windows machine and the radio used as a testing platform. 
This was the difficult part. I first worked in Python, which I am most comfortable with, to figure out 
how to handle the byte communication necessary to send messages to the radio. This required a fair amount 
of trial and error, which is why I did not have many early commits. Once I finally had this figured out, I 
transitioned the code to Typescript and utilized the package Node SerialPort for communication. 

  Node SerialPort functions a bit differently than how one might expect in other languages in regard to 
reading serial communication and is lacking in documentation. Thus, it was a bit difficult to get this 
code up and running. Even though write eventually worked successfully, read still encountered issues in 
getting it to work properly. Without a simple termination character like the Uniden models, it was harder 
to decide when to stop reading. Unfortunately, this was an issue we were not able to completely solve during 
the semester. 
  
  Overall, this semester in RCOS might have been my favorite. This is the first semester I worked on a 
project that stemmed from interests not related to RPI, which resulted in me being more motivated 
to try to solve the issues. I hope it is one I can continue working on in the future. 


