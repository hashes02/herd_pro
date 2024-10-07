# How to remove Laravel Herd Pro

 1. Install Laravel Herd
 2. Close Laravel herd
 3.  Open CMD as a administrator
 4. Run 
	    `cd C:\Program Files\Herd\resources`	
	    `npx asar extract app.asar app`
 5. Open the app folder as an administrator in VScode
 6. Press **Shift + CTRL + F**
 7. Search for **beforeRouteEnter** Replace await **window.api.licensing.hasValidLicense()** with **true**
 8. Save the file, run Herd and Enjoy
