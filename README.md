# DesignedProject.md
 Description of the project

The system is further divided into six parts: 
*Smart Medication Dispenser: dispense the correct type and quantity of medication to the patient on time. 
*SMS reminder System: remind the patient five minutes before the medication is dispensed.
*Emergency System: allow the patient to call a nurse in case of an emergency. 
*Heart Rate System: monitors the heart rate of the patient and shows this on the backend server.
*Oxygen level System: monitors the oxygen levels of the patient and displays this on the backend server. 
*Blood Pressure System: monitors the blood pressure levels of the patient and displays this on the backend server.

This system will send/retrieve information to/from the backend server to carry out specific tasks via the communication hub. 

# Functional Specifications

1.	The smart medication dispenser aims to dispense the right quantity and type of medication at the correct time, based on the information received from the backend server via the communications hub. 
2.	When the smart medication dispenser is out of medication, it will register on the backend server that the smart medication dispenser needs to be refilled and once refilled, this will be displayed on the backend server that the smart medication dispenser has been refilled. 
3.	The smart medication dispenser will display the day, date, time, and further information.
4.	The SMS reminder system reminds the patient and the nurse (via an SMS) that the medication will be dispensed within five minutes.
5.	When the emergency button is pressed it will notify the nurse that the patient needs help beyond the capabilities of the system. This will be registered on the backend server that the button was pressed.
6.	When the nurse tends to the patient and presses the response button, this will deactivate the emergency and register on the backend server that the patient has been delt with. 
7. Display the correct heart rate on the web server.
8. Display the correct ocygen levels on the web server.
9. Display the correct blood pressure on the web server. 

# Non-functional

1.	The time and medication list will be displayed on an LCD for easy understanding on the smart medication dispenser. (Useability)
2.	The time should be in 24 hours and not a.m./p.m. (Useability)
3.	Correct units and measurements should be used to not cause confusion. (Useability)
4.	A timeously refreshing system allows for correct communication with the backend server. (Performance)
5.	The information must also be stored offline in case power cuts or communication interruptions. (Reliability)

Figure 1: Flow chart for dispenser

![image](https://user-images.githubusercontent.com/117062128/199088183-9e20b350-fc9a-4e86-9c03-303bcb721491.png)

Figure 2: Flow chart for SMS

![image](https://user-images.githubusercontent.com/117062128/199088256-b059b667-232a-47ee-a1d4-778c683182a8.png)

Figure 3: Flow chart for emergency system

![image](https://user-images.githubusercontent.com/117062128/199088314-f7dc5216-e699-4d4f-9d11-d6bfe52309da.png)

