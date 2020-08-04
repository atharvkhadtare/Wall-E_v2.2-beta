# Steps to setup and configure ESP-IDF in windows

## Step 1:
![step1](https://github.com/SRA-VJTI/Wall-E_v2.2-beta/blob/dhruva/windows/windows_instructions/step_1.png)

## Step 2:
![](https://github.com/SRA-VJTI/Wall-E_v2.2-beta/blob/dhruva/windows/windows_instructions/step_2.png)

## Step 3:
![](https://github.com/SRA-VJTI/Wall-E_v2.2-beta/blob/dhruva/windows/windows_instructions/step_3.png)

## Step 4:
![](https://github.com/SRA-VJTI/Wall-E_v2.2-beta/blob/dhruva/windows/windows_instructions/step_4.png)

## Step 5:
![](https://github.com/SRA-VJTI/Wall-E_v2.2-beta/blob/dhruva/windows/windows_instructions/step_5.png)

## Step 6:
Click on the windows icon in the bottom left corner and search for System properties, and then click on change or edit environment variables. A windows as shown below will appear on you screen. After that you have t click on the environment variable button. 

![](https://github.com/SRA-VJTI/Wall-E_v2.2-beta/blob/dhruva/windows/windows_instructions/step_6.png)

## Step 7:
Now, add a variable under Edit User variable  as follows: 

![](https://github.com/SRA-VJTI/Wall-E_v2.2-beta/blob/dhruva/windows/windows_instructions/step_7.png)

you can copy paste 
**Variable name:** ``IDF_PATH``
**Variabe value:** ```C:\esp\esp-idf```
Now click on `OK` and `OK` again after which the window will close. 
Now you can run ESP-IDF by 
- click on windows icon in bottom left corner
- search for esp-idf
- **OR** you can find a shortcut on your desktop itself
- click on the first result that you see, which will open up a new command shell where your variables and paths will all be configured.
- from this cmd window you can navigate to your desired location and clone or create new esp-idf projects! 
- Now, for this workshop, clone this repo in your C drive. 
