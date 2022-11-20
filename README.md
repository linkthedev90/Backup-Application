# Backup Application
 Small application to backup a directory to a external device
 
This program to allow the user to quickly backup the folders they choose, to the device they choose. This uses the Robocopy features from Microsoft to copy the folders. This is helpful if you have work you need to backup often.

Features:

Save / Load settings allowing quick setup of copy paths.
Uses the "/xo" copy flag for Robocopy, allowing for backups that excludes older files.
Current version allows up to 5 directories to be copied to destination of choice.
Required Modules: Guizero

Usage:

1. Download & unzip the folder.
2. Run the file labeled "Main.pyw" ( It should be in the same directory as the "icons" folder ).
3. Select the "Select Backup Destination" button, and choose your device path. 
![image](https://user-images.githubusercontent.com/118638677/202879028-880788b6-0ea7-4738-9781-c67fc45b6954.png)
4. Select the "+" icon to add the folders you would like to copy to your selected device.
![image](https://user-images.githubusercontent.com/118638677/202879064-ae0b22f0-3020-42bf-b301-0b0d253d340f.png)
5. Select the "Start" button. The copying process will start.
![image](https://user-images.githubusercontent.com/118638677/202879070-8387ee9f-aa01-4de7-bb44-fbf6c4c524da.png)
6. Once the copy is finished, you can now close the program. A copy of the files / folders will be inside "Backup_Folder" inside the destination folder.
![image](https://user-images.githubusercontent.com/118638677/202879077-43ce37d4-f2ab-4c09-9456-da2c41794143.png)

You can use the save / load options, under the file menu, to save your settings to a .ini file for quick setup!
![image](https://user-images.githubusercontent.com/118638677/202879085-9e89fc99-c3b2-4f74-b2e7-0f4cce2207d5.png)


Thank you for downloading!
Icons made by Pixel perfect from www.flaticon.com
"Folder" Icon Info:

Icons made by Freepik from www.flaticon.com
"Floppy Disk" Icon Info: Floppy disk icons created by Freepik - Flaticon
