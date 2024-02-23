This APK requires you to make a Google Apps Script. Follow the following to set it up:
1. Go to https://script.google.com/home
2. Make a New Project
3. Paste "Code.gs" in this folder over the existing function
4. Go to Deploy -> New Deployment
    4a. Set type to Webapp
5. Add A Description (does not matter)
6. Set Execute as your Me(your_email@gmail.com)
7. Set who has access to Anyone and hit deploy!
8. Copy the Web app url and place it in calander.txt
9. Use ADB to push the calander.txt file to /sdcard on glass
10. Reboot your glass and if you have any upcoming events for the day depending on the settings in the calander.txt it should
pop up!
