Student Accommodations Email Generator (version 0.6)
----------------------------------------------------

Purpose: 
	Provide a simple and elegant way to provide consistent recommendations for frequent conditions addressed by the School Nurse.

Background:
	I found myself recreating the same emails frequently to support students with medical conditions. This was intensified during various athletic seasons. This process was tedious, time consuming, and regularly deviated slightly from established recommendations. After seeing the benefit for myself, I shared this with a colleague and later modified the code the allow for some dynamic settings.

Usage:
	Save/Copy the file somewhere on the computer. I have decided on a location somewhere within OneDrive so that it is backed up, but this is not necessary.

	Open the web browser of your choice and hold ctrl+O to open a file location. Navigate to that file and open it.
	Alternative: Navigate a file browser to the saved html and file double click that file to open it with your default web browser.

	Once open your URL bar will contain something similar to one of the following:
		file:///C:/path/to/file/accommodations.html
		File C:/path/to/file/accommodations.html

---------------------------------------------------------------------------------------------

	Deprecated: To the end of URL add the following:
		Deprecated: ?rn=Your Name, Title
		

	Deprecated: Optionally, if you would like to send a copy to yourself by default add:
		Deprecated: ?rn=Your Name, Title&rnemail=your.email@asd20.org
	Deprecated: *Spaces may be replaced with "%20"; this is normal.
---------------------------------------------------------------------------------------------
	Complete the for on the top of the page asking for your name (Eg. Jane Smith, RN) and
		optionally your email address, if you would like the form to automatically
		BCC yourself on the email generated.

	Press enter. Press ctrl+D to save this as a bookmark with the options saved

Changelog:
	v0.1 - Initial version with basic operation support
	v0.2 - Added specific accommodations to support TACT accommodations.
	v0.3 - Added support for setting URL variable to set nurse's signature line (rn)
	v0.4 - Fixed minor grammatical errors. Added support to set URL variable for nurse email; check if variable not null; populate BCC (rnemail) if no null.
	v0.5 - Added text area under checkbox options to allow user to free-text add custom accommodations. Each line will add a new bullet to the list.
	v0.6 - Made small corrections to compound words within the accommodations. Added a place to set variables 'rn' and 'rnemail' without asking the user to make URL modifications.
	v0.6.1 - Added accommodation for "Extended time on Assignments"; Fixed grammar error