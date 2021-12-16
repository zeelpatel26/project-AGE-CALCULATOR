# project-AGE-CALCULATOR
Abstract:
Age Calculator is an android app developed for the purpose of calculating exact age of user.
The application works on any android devices fulfilling the basic requirement of app.
It mainly focuses at determination of exact age of user depending upon the input date of birth.


Implemented in this project:
- Intent
- BroadcastReceiver
- Animation
- CardView
- Database

STEPS OF THIS PROJECT:

Step1: Create a new project.

Step2: activity_main.xml 
	 An image of cake with animation .1 textview that display title AGE CALCULATOR with intent too .
	
Step3: MainActivity.kt
	Access animation of image.Then add intent for second view through a textview. Add a function for broadcast receiver.

Step4: ConnectivityReciever.kt
	It contain the code of broadcast receiver for online or offline mode .

Step5: cal_age.xml
	 In this xml  four textview and a card view is used.The second textview shows the current date and fourth display the selected date by user.
	 The third textview is used as a datepickerdialog.The card view displays the age of the user.And a button.

Step6: calage.kt
	Code for the current date and DatePickerDialogBox.And also a function to calculate the age by current date and the selected date
	 and intent for button get started to next page.

Step7: saveage.xml
	Design cardview for showing the saved data through sharedpreference.Three edittext are used to get data from the user.
	Two buttons , done and imagebutton works to save and display data that user enters.

Step8: saveage.kt
	Fetch data from the name , event date , event textview and store that using SharedPreferences by clicking button done .
	Also can display the saved data in the cardview by pressing the image button that blinks while storing the data by done button.




*Add required drawable,anim in res folder
*Add required permissions and receiver for broadcast in manifest file.





