# How-to-download-UnrealEngine_4.24

When you want to play with Carla, Due to the documents in Chinese is very few, so you must look for the documents in English.

This link is the Official documents for Carla.
https://carla.readthedocs.io/en/latest/

If you want to install Carla in Linux, this link will be useful.
https://carla.readthedocs.io/en/latest/build_linux/

If you run the command as the document says, the process of installing will be successful.

When you run the command as follows, you will be more careful.

$ git clone --depth=1 -b 4.24 https://github.com/EpicGames/UnrealEngine.git ~/UnrealEngine_4.24

Maybe you will fail.

The exact step as follows:

First, you must sign up an account in the link:
https://www.unrealengine.com/en-US/feed

Click your account in the top-right-->PERSONAL-->CONNECTIONS, and connect with your github account.

In your github account, -->Settings-->Applications-->Authorized OAuth APPS, you will see the following:
You have granted 1 application access to your account. 

Epic Games

Second, use the link:
https://answers.unrealengine.com/questions/422750/why-cant-i-find-repository.html

if you can not see "UnrealEngine Private" in the top,
you will see the SignUP

Click the SignUP and use your account in the first step,
then you wiil see the "UnrealEngine Private"

Now when you run the command:

$ git clone --depth=1 -b 4.24 https://github.com/EpicGames/UnrealEngine.git ~/UnrealEngine_4.24

you will succeed.
