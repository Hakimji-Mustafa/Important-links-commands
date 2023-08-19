# Important-links-commands
all links and important commands only store here or codes may be.

------------------------------------------------------------------------------------------------------------------------------------
Best link to create SSH key in MAC:-
https://devqa.io/install-git-mac-generate-ssh-keys/
----------------------------------------------------------------------------------------------------------------------------------------------------
Best way to regenerate the SAH key for Firebase use case.
Youtube :- https://www.youtube.com/watch?v=dtn-AKKAQhc&ab_channel=TheDebugArena
By codes:-
To generate SHA key --> keytool -list -v -keystore ./android/App/debug.keystore -alias androiddebugkey -storepass android -keypass android

To generate debug.keystore file run this command in app folder inside android forler --> keytool -genkey -v -keystore debug.keystore -storepass android -alias androiddebugkey -keypass android -keyalg RSA -keysize 2048 -validity 10000
----------------------------------------------------------------------------------------------------------------------------------------------------------
How to Change the package name of React native app ?

link = https://stackoverflow.com/questions/37389905/change-package-name-for-android-in-react-native
Go to the above link and follow all the steps and your package name will be changed to any name you want to give.

----------------------------------------------------------------------------------------------------------------------------------------------------------
React native maps best link 

link = https://github.com/react-native-maps/react-native-maps/blob/HEAD/docs/installation.md

got to the above link for react native maps library integration.

----------------------------------------------------------------------------------------------------------------------------------------------------------
Free courses link
link = https://coursesity.com/free-tutorials-learn/react-native
----------------------------------------------------------------------------------------------------------------------------------------------------------
Generating the SSH Key

1. Creating the SSH Key on git email
**ssh-keygen -t rsa -b 4096 -C "mustafa.hakimji@techvalens.com"**

2. Checking the Agent is activated or not.
**$ eval "$(ssh-agent -s)"**

3. Adding the Key into agent
**ssh-add ~/.ssh/id_rsa **  

4. Checking the key if this won’t work then the next will.
**~/.ssh/id_rsa**   

5. If the above step won’t work than this will.
**cat ~/.ssh/id_rsa.pub**

----------------------------------------------------------------------------------------------------------------------------------------------------------

