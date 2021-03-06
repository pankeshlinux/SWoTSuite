## SWoTSuite, a Toolkit for Prototyping Cross-domain Semantic Web of Things Applications

Semantic Web of Things (SWoT) applications focus on providing a wide-scale 
interoperability that allows the sharing of IoT devices across domains and the reusing 
of available knowledge on the web. However, the application development is difficult 
because developers have to do various tasks such as designing an application, 
annotating IoT data, interpreting data, and combining application domains. 

To address the above challenges, we have been implementing framework, called SWoTSuite. 
It is a Toolkit for Prototyping Cross-domain Semantic Web of Things
Applications. This project is extension of M3 framework (URL: http://sensormeasurement.appspot.com/) 
by Amelie Gyrard, in collaboration with Insight/NUIG-DERI, Ireland. 



For More detail, refer the following resources

- Our papers at ISWC 2016: https://arxiv.org/abs/1609.09014 (8 pages). 
- Application development process using SWoTSuite: https://www.youtube.com/watch?v=BMP8CXtXzGo
- SWoTSuite: A Toolkit for Prototyping End-to-End Semantic Web of Things Applications at WWW 2017 (URL: http://dl.acm.org/citation.cfm?id=3054736)
- Our tutorial on Semantic Web meets Internet of Things and Web of Things at WWW 2017 (URL : http://dl.acm.org/citation.cfm?id=3051100 )


## Installation

In order to play with SWoTSuite, follow this simple steps:

- Download the github repository.
- Download Eclipse IDE 
- Configure build path with jar files available in ./supportedFiles/jar.
- Run Main.java file, available in swotsuite.application.main package
- you can see the results, suggested by SWoTSuite, on Console.  

We take a hello world naturopathy application as an example to demonstrate the 
capabilities of SWoTSuite.  

The naturopathy application combines data produced by IoT devices (such as body temperature, 
heartbeat, blood pressure, cholesterol, skin conductance) with other healthcare domain and 
food knowledge bases. It suggests some preventive measures, such as home remedies when 
a fever is detected (e.g., drink orange or lemon juice because they contain Vitamin C) 
or consulting a doctor immediately in case of severity, that can be acted upon by patients.


## License

GNU GPL v2.0, check LICENSE.txt
