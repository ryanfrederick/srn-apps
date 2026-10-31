Student Accommodations Email Generator (version 0.5)
----------------------------------------------------

Purpose: 
	Provide a simple and elegant way to produce a health summary by asking the user basic input and selectable fields.

Background:
	I found myself recreating similar health summaries for IEPs. It often took several minutes each time I needed to recall all of the specific talking points I needed to address despite the repetition. This process was tedious, time consuming, and regularly deviated slightly from established recommendations. After seeing the benefit for myself, I shared this with a colleague and later modified the code the allow for some dynamic settings.

Usage:
	Save/Copy the file somewhere on the computer. I have decided on a location somewhere within OneDrive so that it is backed up, but this is not necessary. To update the current version replace original file with this file and delete the bookmark made in your browser in order to create a new one with appended settings saved.

	Open the web browser of your choice and hold ctrl+O to open a file location. Navigate to that file and open it.
	Alternative: Navigate a file browser to the saved html and file double click that file to open it with your default web browser.

	Once open your URL bar will contain something similar to one of the following:
		file:///C:/path/to/file/accommodations.html
		File C:/path/to/file/accommodations.html

	To the end of URL add the following:
		?rn=Your Name, Title
		*Spaces may be replaced with "%20"; this is normal.

	Press enter. Press ctrl+D to save this as a bookmark with the options saved

Changelog:
	v0.1 - Initial version with basic operation support
	v0.2 - Corrected grammar and typographical errors
	v0.3 - Changed name to support name style in Infinite Campus for copy/paste
	v0.4 - Added a field to add custom list of providers to the selectable list
	v0.5 - Added logic to combine some statements to sounds less robotic and reduce cleanup. Added support for setting URL variable to set nurse's signature line (rn)