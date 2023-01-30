# _Week 1 Lab Report_

## Installing VS Code

![VSC Website][VSC%20Site.png]
- Go to https://code.visualstudio.com to install a build of VS Code
- Picture above shows what you should expect upon visiting the site
- Download Mac, Linux, or Windows version depending on your current OS

![VSC Zip][VSC%20Zip.png]
- (On Mac) There will be a zip file named <em><strong>VSCode-darwin-universal.zip<strong><em>
- Double click or extract the zip file
- An application file named <em><strong>Visual Studio Code<strong><em> should appear

![Applications Folder][Applications%20Folder.png]
- Drag the mentioned Visual Studio Code application file into Applications folder
- Should be on the left of your File Finder app under Favorites as pictured above

![VSC][VSC.png]
- Launch VS Code by double clicking/opening the application file
- VS Code should look like the picture above above launching successfully

## Remotely Connecting

![Account Lookup][Account%20Lookup.png]
- Go to https://sdacs.ucsd.edu/~icc/index.php to look for your CSE15L course specific account
- In the account lookup tool pictured above, type in your username and student id
- Username being the first letters/numbers of your ucsd.edu email

![SSH Username][SSH%20Username.png]
- Pictured above is what you should see upon successfully looking up your account
- Below the <em>Additional Accounts<em> you should see an account name in the form <em><strong>cs15lwi23xx<Strong><em>
- This account is the username you will use to <em><strong>ssh<strong><em> into the remote server

![SSH Password][SSH%20Password.png]
- Follow the following guide to resetting your course specific account password
- Link: [Resetting your password](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit)
- The password you resetted to will be used to <em><strong>ssh<strong><em> into the remote server

![SSH Terminal][SSH%20Terminal.png]
- Open your terminal app if you are on Mac or use the terminal in VS Code (Ctrl + `)
- Type in <em><strong>ssh ACCOUNT@ieng6.ucsd.edu<strong><em>, with ACCOUNT being the one you obtained from the account lookup tool
- If the terminal asks if you want to continue connecting, type in <em><strong>yes<strong><em>
- It will then ask you for the password that you resetted to in the previous step
- Picture above is what you should expect after logging in

## Trying Some Commands

![Commands][COMMANDS.png]

- Listed out all of the files/directories in the current direction using the <em><strong>ls -a<strong><em> command (with <em><strong>-a<strong><em> standing for "all)
- Changed current directory to perl5 using <em><strong>cd<strong><em> command
- Used the command <em><strong>echo<strong><em> to pass the string "test" to the <em><strong>>><strong><em> operator
- The <em><strong>>><strong><em> operator is used to create the textfile.txt file and append "test" to it
- Printed out the contents of testfile.txt to the terminal using <em><strong>cat<strong><em> command
