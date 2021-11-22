# Chrome Password Stealer V.2
This is a modified version of Chrome Stealer for Ducky, originally written by (@nuk3leus)

## What It Does

Most people are already logged onto Google when you walk by their machine. It's just a fact and when I noticed the script was trying to export .csv passwords, and then email them to yourself I realized a much better and easier way to accomplish this. Not to mention it literally would not work, it would open chrome and then kind of tab around and never do it right. As well "Google Password.csv" is the official name of the exported passwords, which was wrong as well. 

1. As long as the target is logged into their google account, it works. 
2. If they are not logged into Google, it will not work. So I am working on a workaround and also for other browsers. 
3. Once plugged in, it immeditely opens Chrome through `GUI r`
4. Afterword, it goes directly to the user's google account password list URL. 
5. It then tabs it's way down to "Export", hits ENTER and after a DELAY, it saves the "Google Passwords.csv" in a newly created directory in the Rubber Ducky called "chrome loot". 
6. Finally, it opens powershell without admin priviledges and emails the exported passwords to your email of choice, so make sure to edit the duckycode.txt script to include your sender and receiver's usernames and passwords. 
7. That is it, 17 seconds at the most and you have the "Google Passwords.csv" file in your Rubber Ducky, and in your email Inbox. 
8. This also bypassed all anti-virus and cybersecurity measures. 



## Conclusion

Anyway, I heavily modified this payload so user's could quickly grab Chrome password credentials, have both options of having a physical copy and it emailed just in case. 

## Contributions & Help

If anyone would like to edit this payload or fork it and edit it to work better, faster or whatever you see fit, you are welcome to. Here is a list of my goals with this payload, as I love credential harvesting payloads the most so I work on those almost entirely. 

1. Find a way to get the Chrome Passwords without having to have the user be logged into Google on their Chrome Browser already. 

2. Create more credential payloads

3. And if anyone has any ideas or help, please let me know here or my contact details below:

   ## Contact | Modified By

   Email: sales@spragginsdesigns.com

   Website/Web Developer Portfolio: [Spraggins Designs](https://www.spragginsdesigns.com/)

   GitHub: [GitHub](https://github.com/spragginsdesigns)

   <img src="Spraggins Designs Logo/Spraggins Designs Cover Logo Wide.jpg" alt="Spraggins Designs Cover Logo Wide" style="zoom:100%;" />

   

