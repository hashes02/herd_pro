# How to use Laravel Herd Pro

 1. Install Laravel Herd
 2. Run HERD, install the packages and Close Laravel herd
 3.  Open CMD as a administrator
 4. Run 
	    `cd C:\Program Files\Herd\resources`	
	    `npx asar extract app.asar app`
 6. Delete the *app.asar* file
 7. Open the app folder as an administrator in VScode
 8. Press **Shift + CTRL + F**
 9. Search for **beforeRouteEnter** Replace await **window.api.licensing.hasValidLicense()** with **true**
 10. Save the file
 11. Run `npx asar pack app app.asar` (optional)
 12.  run Herd and Enjoy
