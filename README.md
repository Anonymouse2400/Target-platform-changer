# Target-platform-changer 
Experimental python script that changes the target platform from windows to android only for unity 5.5.5f1 you might encounter shader getting pinks because android cant handle dx3d shader it only can handle opengl mobile shader so use with caution. You might need to rebuild the shader by extracting with tools likes assetripper 
1.It finds the hex base of target platform and changed it
2. It uses current bundle id to know it its not encrypted
3. might work on 2017 below
4. works on both 32 bit and 64 bit asset bundles


how to use the script :
 you must have python 3 installed check python --version via cmd if not type python on cmd and it will open microsoft store
 install some dependencies pip install tk and install pyperclip on cmd bytping pip install pyperclip  
 be sure to type on the cmd python assetbundle_converter.py on your current folder or just click the file script jsut be sured you sintall python 3

 THIS IS TO CONVERT THE CURRENT ASSET BUNDLE FROM WINDOWS(64) TO ANDROID . YOUR CURRENT ASSET BUNDLE MUST NOT BE ENCRYPTED  AND CAN BE EXTRACTED WITH ASSETRIPPER.
 PLEASE HAVE A BACKUP OF YOUR ASSETBUNDLE FIRST BEFORE MODIFYING.
