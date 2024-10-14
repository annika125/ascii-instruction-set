# How To Print an ASCII Art Heart Using Python

Making ASCII art is an easy way to practice coding, and create a cute drawing! My example prints a heart shape out of asterisks, but this method can be used to print any picture out of ASCII characters. To print a different image, just replace the content of the strings in my list with whatever symbols you like. 

This tutorial is for beginners and doesn’t require much Python experience, but it does require a basic understanding of the language, and a pre-installed Python application like IDLE. If your computer is running a different application, the code should be the same, but the steps to create and run the file may be slightly different.

Time Estimate: 5-10 minutes

Materials: Computer running IDLE

## Step 1
Open the IDLE shell and click File -> New File

<img width="197" alt="image" src="https://github.com/user-attachments/assets/41aa1f99-c7ae-4020-95d0-0910cf1cbff4">

## Step 2
In this file, define a new function to print the heart.

Type: def print_ascii_heart():

## Step 3 
On a new indented line, create a list called heart.

Type: heart = [

## Step 4
Indent the next line one more time and type: 

"     ******       ******",

## Step 5
Continue this process, keeping the indent at 2 tabs and creating a new comma-seperated line for each of the remaining layers of the heart:

"   **********   **********",

" ************* *************",

"*****************************",

"*****************************",

"*****************************",

" ***************************",

"   ***********************",

"     *******************",

"       ***************",

"         ***********",

"           *******",

"             ***",

"              *"

## Step 6
On the next line, delete one indent and type the closing bracket to complete the list 

Type: ]

## Step 7
On a new line (Still indented once), create a new loop to print each line in the list. 

Type: for line in heart: 

## Step 8
On the next line, add an indent and the print function. 

Type: print(line) 

## Step 9:
Create one last line, delete all indentation, and call the function to print the heart. 

Type: print_ascii_heart()

### Your code should look like this:

![image](https://github.com/user-attachments/assets/37590f42-1118-4940-8757-5847a2af7bc1)


## Step 10:
To display the heart, click Run -> Run Module (In the file menu near the top of the tab). You’ll get a prompt to save the file, click yes and give the file a name. 
If everything worked correctly, the Python Shell should open and display your heart.

![image](https://github.com/user-attachments/assets/6f9ca564-dd51-4d0a-bd4b-36c3fdf613ae)

### Your final product should look like this: 

![image](https://github.com/user-attachments/assets/139c24bc-2d04-4d87-b444-bfb073c07f3d)

If your program doesn’t run, check that each line is properly indented and all the code has been typed out properly. 
If the heart doesn’t look right, you may have typed the list incorrectly, or your display and spacing may be different if you’re using an application other than IDLE. 

If neither of these are true, congratulations! You’ve created an ASCII heart! 
