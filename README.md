# burppro
Burp-Loader

Change java version:
sudo update-alternatives --config java  

OR 

update-java-alternatives -l
sudo update-java-alternatives -s <java version>

##################################** Prequisites **#############################################
https://javahelps.com/install-oracle-jdk-11-on-linux


################################** Execution and Activation **################################

**1. Place all files in 1 folder**
	For Example lets take as --> C:\Users\Decrypt3r\Desktop\burp\
----------------------------------------------
**2.1 Run This Command for Windows in CMD Prompt.**
	java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:"C:\Users\Decrypt3r\Desktop\burp\loader.jar" -noverify -jar "C:\Users\Decrypt3r\Desktop\burp\burpsuite_pro_v2022.1.jar"
**2.2 Run this command for Linux in Terminal. Suppose Your files are in /home/kali/Desktop/burp/**
	java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:/home/kali/Desktop/burp/loader.jar -noverify -jar /home/kali/Desktop/burp/burpsuite_pro_v2022.1.jar &
----------------------------------------------
**3. Use keygen.jar to generate the License key**
	java -jar keygen.jar
----------------------------------------------
**4. Activate Burp Suite Pro**
	1. Modify License String like "license to Decrypt3r"
	2. Copy License key from keygen.jar and paste in Burp Suite Pro and click Next.
	3. Select Manual Activation Option on your bottom Right in Burp Suite Pro.
	4. Copy License Request from BurpSuite_Pro and paste in keygen.jar
	5. Copy license response from keygen.jar and paste in BurpSuite_Pro, and next and Done
----------------------------------------------
**5.1 For Windows Follow These Steps**
	1. Open Notepad and Paste command at 2.1 and save the file with name burp.bat in C:\Users\Decrypt3r\Desktop\burp\   Folder.
	2. Open another Notepad and Paste below command and save it with burp.VBS extension in Desktop.
		Set WshShell = CreateObject("WScript.Shell")
		WshShell.Run chr(34) & "C:\Users\Decrypt3r/Desktop\burp\burp.bat" & Chr(34), 0
		Set WshShell = Nothing
**5.2 For Linux Follow these Steps**
	1. With Sudo Permissions, Create a file with command "gedit /bin/burp"
	2. Paste command in text editor "java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:/home/kali/Desktop/burp/loader.jar -noverify -jar /home/kali/Desktop/burp/burpsuite_pro_v2022.1.jar &"
	3. Change Permissions for files with command "chmod +x /bin/burp"
----------------------------------------------
**6.1 For Executing Burp in Windows, Double Click on burp.VBS file.**
**6.2 For Executing Burp in Linux, Write burp in Terminal and press Enter.**
