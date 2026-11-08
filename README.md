# srn-apps
Offline JavaScript applications to assist and frequent tasks in school nursing.

## Purpose
These tools were created to simplify and automate some of the frequent and tedious tasks in my work as a school nurse. They are purposefully written 
in HTML and JavaScript in order to run on restricted computers with access to a browser. The code is, admittedly, a cludge to work around some of the security restrictions of offline JavaScript in the browser, mailto links within email clients, etc.

| Title | Description |
|-------|-------------|
| Accommodations | Generates and email to send to teachers with common requested accommodations/supports. |
| Health Information | Collects standard health information and generates a summary. Allows you to edit it before copying and pasting it elsewehre. |
| Contacts | Contact manager designed to suports nurses with multiple sites. The file generated is also used for an emailer to determine nurses at school to automatically add a nurse to CC for automated communication. |
| Illness Tracker | Simple program to add student schedules to cross-reference contacts with reportable illness. |
| STB Emailer | Program to generate individual emails from a list and CC idividuals from "Contacts" file. |
| Paraprofessional Support Plan | Support plan builder for paraprofessional using common charateristics. |
| CSV Formatter | ... |
| CSV Converter | ... |

## Accomodations
This generates a email to send to teachers with a list of common supports for students. It does not populate the 'To: ' section of the email allow the user to manually add recipients.

### Usage
After saving the html file to disk open the file directly from the filesystem or open it in your perferred browswer. Complete the form on the top with your name (this is the signature line of the email) and your email address (if you would like to send yourself a bcc'd copy by default). Click save and then bookmark the site in the browser to save that data for default use. The varibles are set in the URL.

Enter the student's name (Lastname, Firstname). Select from the option of note types. You may check common supports from the list or add individual supports as you might interperent from a physician's note. Lastly, click generate email to open the email in your desktop email client.

## Health Information
This tool is used to collect necessary health information to support student in an idividualized education plan.

### Usage
After saving the html file to disk open the file directly from the filesystem or open it in your preferred browser. Complete the form on the top with your name (this is the signautre line of the summary). Click save and then bookmark the site in the browswer to save that data for default use. The variables are set in the URL.

Complete the pertitenent for data regarding the student. Click 'Generate Health Information Summary' to generate the report in the text area. You may modify the text directly in the text area prior to copying the information from there to a permanant place.

## Contacts
This is a contact manager that focuses on allowing multiple sites per contact (nurses in school district for instance). This is designed to make it easy search contacts by location or name, to import contacts into a cell phone, or map to location listed. The file generated should be moved into the root directory of this applicaiton for default user. This file is also referenced by an emailer to determine the email address of contacts by school for automatic emailing. This file generates a file "contacts.js" which it loads by default when in the root direcotry. Additionally, the STB Emailer program uses this same file to determine the contact to CC. Without this file that program will fail to load recipients.

### Usage
Add contacts and complete the data by adding contact information and site information. Once completed click "Save JS" button to save the contact inforatmion. Move the file "contacts.js" to the root directory of the program. You may also create other file and load the files instead by clicking "Load JS." Contacts are located on the left pane.

## Illness Tracker
This program helps track ill contacts and cross references them with other ill contacts in a classroom environment. While the teacher information can be put into the program it can be used without modification with limitation of not auto-completing teacher name information. This program is not smart enough to catch typo-graphical errors.

### Usage
If you would like to add in your teacher information find the example code block in the source and add it using the template structure.
```
        const teachers = [
            'Lastname, Firstname',
            'Example, Teacher',
        ];
```
Open the applaction and add the pertitenent data. Once students are added you can save the json file to load for future use. Consider saving copies of the file with dates so that you can easily roll back if a mistake was made. By default it shows class rooms where there are 2 or more contacts of the same illnesses. You may select "Low Risk" or Green filter to show teachers that have reportable illness greater than 0 in their class room for each class period. You search and Replace [SCHOOL ID] with your school letters, but this is purely aesthetic.


## Paraprofessional Support Plan Builder

To be completed later.

### Usage

To be completed later. 
