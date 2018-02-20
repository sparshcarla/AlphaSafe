##Alpha Secure

#Description

the goal of this project is to provide a mobile application that can tell if a user is in danger using environmental information, and notify authority if need be.

#Scope

The alpha-sec will use information from the user's environment to approximate the threat state of the user. The system will use voice data & motion data as key factors in making these predictions. The information collected are sent to a server for further analysis and threat response responsibility.
The control centre system will consist of a map showing all active users and their current threat status in real time.

#Functionality

*The user application should be able to get location data(GPS coordinate),voice data(Microphone data) and motion data(Accelerometer & gyroscope). The *client System will run a RNN on the different data sets to provide data an embedding of the collected data.
*The control system would process client's data embedding using an ANN to estimate the threat level of the particular user.
*The control system should display each client location on a map (google map ) and their information corresponding to their current threat level in real time.


##Development phases 

#Phase 1:
	*Develop a communication functionality between the client application, server side script and control centre system	
		*The client should be able to send information to the server
		*The server side script should be able to process the information recived from the client.
		*The control system should be able to display the client location a map (google map)

#Phase 2:
	Develop and pre-train the Machine learning interface.
	
#Phase 3:
	Real time integration and Data Training 
	
