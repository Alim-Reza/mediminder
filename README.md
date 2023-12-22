
# mediminder
medicine reminder app using react-native

# Scope of the application
1. Patient can input medicine details.
2. Patient can update the status of if medicine was taken in specific part of the day.
3. Overseer can view the medicine details , status.
4. Patient and Overseer can connect with each other to share the information.
# Properties 
1. There will be two types of user.<br />
	 i.  patient<br />
	 ii. overseer<br />
 2. medicine detail will have following properties:<br />
	 a. name<br />
	 b. mg/ml (optional)<br />
	 c. image<br />
	 d. intake quantity ( physical amount / liquid amount e.g. ml)<br /> 
	 e. remainder amount<br />
	 f. intake time ( input format 1 + 0 + 1 )<br />
 # Connecting Process
 Every Patient will have a qr code or unique id that can be then shared with one or multiple Overseer who can use that to gain access to the Patients medicine details and status.
 # Functionality of Roles
 1. Patient: <br/>
	 a. can see and update the list and details of medicine.<br />
	 b. get alert when a medicine is due or near empty.<br />
	 c. acknowledge that a medicine was taken.<br />
	 d. can add or remove overseer from their account.<br />
 2. Overseer:<br />
	 a. can see and update the list and details of medicine.<br />
	 b. get alert when a medicine was due but the Patient has not acknowledged it yet.<br />
	 c. get alert before Patient runs out of medicine.
	 
