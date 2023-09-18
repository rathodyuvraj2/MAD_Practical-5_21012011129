# MAD_Practical-5_21012011129

Study: Intent, types of Intent, types of Intent Action, Intent.setData() method, Intent.setType() method, TextInputEditText, TextInputLayout, Button, ConstraintLayout, CoordinatorLayout, startActivity() method, ActivityResultContracts.StartActivityForResult() method, registerForActivityResult() method, Permission in manifest, ContextCompat.checkSelfPermission(), ActivityCompat.requestPermissions() method, Uri.parse() method, 

ContactsContract.Contacts.CONTENT_TYPE

CallLog.Calls.CONTENT_TYPE

"image/*"

"tel:"

<uses-permission android:name="android.permission.READ_CONTACTS" />

AIM: What is Intent? Write down types of Intent and types of Intent Action. Create an application which demonstrates implicit Intent for following features. 

1. Make call to specific number

2. Open specific URL

3. Open Call Log

4. Open Gallery

5. Set Alarm

6. Open Camera



**Ans:**

An Intent is a messaging object used to request an action from another app component in Android. It is mostly used to start an activity, send a broadcast receiver, start services, and send messages between two activities1.

There are two types of Intents in Android:

Implicit Intent: Using implicit Intent, components can’t be specified. An action to be performed is declared by implicit intent. Then the Android operating system will filter out components that will respond to the action. For example, opening a webpage.
The user does not name a specific component but declares a general action to perform
ex:When you tap the share button in any app you can see the Gmail, Bluetooth, and other sharing app options.

Explicit Intent: Explicit Intent specifies the component. In such a case, intent provides the external class to be invoked. For example, moving from one activity to another within your app.
The user has a clear vision and knows exactly which activity can handle the requests
ex:Suppose you have two activities in your application: MainActivity and SecondActivity. You want to navigate from MainActivity to SecondActivity when a button is clicked.

Types of Intent Actions:

1. Browser Intent:
Action: Open browser for search specific things.
2. Call Intent:
Action: Initiate a phone call to John Smith's phone number.
3. Call Log Intent:
Action: Retrieve and display the user's call log entries for the specified time period (in this case, 
today).
4. Gallery Intent:
Action: Retrieve and display photos from the user's photo gallery that are tagged or identified as 
being from their vacation.
5. Camera Intent:
Action: Activate the device's camera and prompt the user to capture a picture of the sunset.
6. Alarm Intent:
Action: Schedule an alarm to trigger at 7:30 AM the next day.

![image](https://github.com/rathodyuvraj2/MAD_Practical-5_21012011129/assets/124398921/c59178e7-5d32-4a41-8c9d-8bb4ca7fa9dc)

![image](https://github.com/rathodyuvraj2/MAD_Practical-5_21012011129/assets/124398921/ecf6bdbf-48d0-4880-880b-57df82d341ca)




   
