![image](https://github.com/HtOfficial/Diskpart-Clean-Repair/assets/141419667/29508aa1-2e95-4cad-b9d8-9456c43ffd71)


<h1>Diskpart - Clean&Repair Drives</h1>
This tutorial helps a user to easily clean and repair a drive using the program called "DiskPart".
For example, the drives can be secondary drives or a USB stick. 

<h2>Environments and Technologies Used</h2>

- Command Prompt
- DiskPart

<h2>Operating Systems Used </h2>

- Windows 11</b> (22H2)

<h2>Installation Steps</h2>


Step 1: Launch command prompt, then type in "diskpart" and press enter.

Step 2: Type the command "list disk" and press enter.

Step 3: Select the disk you want to clean and type in "select disk #", then press enter.

Step 4: Type "clean" and press enter.

Step 5: Type "create partition primary" and press enter.

Step 6: Type "select partition 1" and press enter.

Step 7: Type "active" and press enter.

Step 8: Type "format FS=NTFS quick" and press enter.

Step 9: Type "assign letter=G" and press enter. In the command "G" can be any letter.

Step 10: Type "exit" and press enter.


<p>
  
![image](https://github.com/HtOfficial/Diskpart-Clean-Repair/assets/141419667/8f626a9f-8702-4787-960c-b8b9a9ceff40)

</p>


<p>
