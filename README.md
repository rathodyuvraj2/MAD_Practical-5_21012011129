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

Implicit Intent: This type of Intent doesn’t specify the component. Instead, it provides information on available components provided by the system that is to be invoked2.
Explicit Intent: This type of Intent specifies the application that will satisfy the intent, by supplying either the target app’s package name or a fully-qualified component class name

Types of Intent Actions:

View Action: Intents with the "view" action are used to display data to the user. For example, opening a web page, displaying an image, or playing a video.

Edit Action: Intents with the "edit" action are used to modify existing data. For instance, opening a contact editing screen to modify contact details.

Send Action: Intents with the "send" action are used to send data to a target, which could be an email, a messaging app, or another app capable of receiving the data.

Dial Action: Intents with the "dial" action are used to initiate a phone call to a specified phone number.

Call Action: Intents with the "call" action are used to initiate a phone call to a specified phone number, just like the "dial" action, but without user interaction.

Search Action: Intents with the "search" action are used to perform a search based on the provided query.

View Settings Action: Intents with the "view settings" action are used to open system settings related to a specific app or feature.

Pick Action: Intents with the "pick" action are used to select and return data from a list or picker dialog.

Media Actions: These include various actions related to media playback, such as play, pause, stop, and skip.

![image](https://github.com/rathodyuvraj2/MAD_Practical-5_21012011129/assets/124398921/c59178e7-5d32-4a41-8c9d-8bb4ca7fa9dc)



   
