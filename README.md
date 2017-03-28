# Password Manager

## You should not re-use passwords.

If an attacker gets hold of your password, they can login to many other sites using your account. This tool creates a unique password for each of your websites. All it needs is the website's name and a passphrase of 5 or more words.

## Instructions

- Type the website into the top left field.<br/>
- Type your passphrase into the field below. Use the same passphrase for all your accounts. Use something that's easy to remember, but contains five words or more. Remember it. Never write it down anywhere.<br/>
- Click one of the buttons to create a password.<br/>
- Some calculation details are displayed in the bottom right field.<br/>
- Your password will be displayed in the top right corner. Copy and paste it into the website.<br/>
- Remove the data from your browser by pressing Ctrl+F5 or the button Clear Data to prevent a bystander from reading your passphrase.<br/>


## How does this work?

Each generated password is unique for the website and the passphrase. Technically, the passphrase is split up into words, then the website name is combined with these words in a series of multiply, add and modulo operations. Every single character in the passphrase influences all characters in the resulting password. This make it impossible to retain the passphrase from the website and the password. Even if somebody gets hold of this password, all your other passwords are safe.

All mathematical operations are executed in your browser. Nothing is stored on the web. The source code is entirely inside this page, nothing is loaded from external sources. To check you may right-click and select "show page source".

Try online on github: https://rawgit.com/jkanev/password-manager/master/password-manager.html
