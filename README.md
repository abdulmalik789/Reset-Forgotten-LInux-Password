# Forgot-Kali-username-and-Password
**Once the Password is Forgot you see this `Message` Restart The `VirtualBox`

![image](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/b37ff5995cc6b168879bae95cba523c03a924d86/s2.PNG)

On this Booting Page Press the `UP` or `DOWN` arrow keys to saty `without Booting in again` Press the Letter `E` to go to edit Mood

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/b37ff5995cc6b168879bae95cba523c03a924d86/s3.PNG)

After you Press `E` you will come to screen like this And Scroll Down with the `arrow keys`

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/b37ff5995cc6b168879bae95cba523c03a924d86/s4.PNG)

Until you see this line 

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/2403c93ef6433319349b5a216edc7cd78659fb91/s5.PNG)

the Move the cursor to the corner of the line on the word and make read only `ro` to Read and write `rw` and type this `init= /bin/bash` and press `Ctrl + x`

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/2403c93ef6433319349b5a216edc7cd78659fb91/s6.PNG)

Now you Will get `root` terminal without UI

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/2403c93ef6433319349b5a216edc7cd78659fb91/s7.PNG)

Now Type `Passwd` and change the root password

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/409d520d096afead3c1070406485827a171fbdae/s8.PNG)

Now type to see This `grep -i "\b$\b" /etc/shadow` to see the User names that are available

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/409d520d096afead3c1070406485827a171fbdae/s10.PNG)

Now You will see the user Names below

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/409d520d096afead3c1070406485827a171fbdae/s11.PNG)

Now Select your user name you gave and type `(yourusername) Passwd` and change the forgtten password of you account

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/409d520d096afead3c1070406485827a171fbdae/s12.PNG)

Same as Above you cannot see the password when you are typing 

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/409d520d096afead3c1070406485827a171fbdae/s13.PNG)

And Finally Type `reboot -f` and reboot the system and use like Normal 

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/409d520d096afead3c1070406485827a171fbdae/s14.PNG)


> [!TIP]
> ## 🟢 For not forgetting the password

`TO not Forget your password save it on the Place`

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/409d520d096afead3c1070406485827a171fbdae/B1.PNG)

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/409d520d096afead3c1070406485827a171fbdae/B2.PNG)

![Alt Text](https://github.com/abdulmalik789/Reset-Forgotten-LInux-Password/blob/409d520d096afead3c1070406485827a171fbdae/B3.PNG)
