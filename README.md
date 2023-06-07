# rocketbook-productivity-tracker 
Converts a scanned handwritten Rocketbook page to corresponding rows in a Google Sheet, using Google Apps Script.
For example, if you wanted to track items such as weight loss, money, productive hours, notes for the day, or anything else, 
you would simply write it in your journal like normal, and take a picture of the page, and it is automatically updated to your Google Sheet database.

## Setup
You must have access to a Rocketbook notebook, as well as a smartphone to take the picture.
1. In the Rocketbook app, create a destination that leads to your Google Drive. Turn OCR transcription on, and choose to send the .txt file seperately from the PDF file. 
2. Create a Google Sheet, and use the link the Google Apps Script in this repo to it. 
3. Follow the instructions in the comments of the script to link your sheet ID, as well as describe what items you want to track.
4. Manage the script deployment such that it is deployed daily, (or more often if wanted). 

Now, whenever you want to add to the Google Sheet, just write the headers along with your data on a Rocketbook page on seperate lines, and mark the Google Drive as the destination, and it will be updated automatically. 

## Examples
<img width="720" alt="Screenshot 2023-06-07 at 12 39 49 PM" src="https://github.com/seanrosshughes/rocketbook-productivity-tracker/assets/92600908/3c81f74a-fa47-4d91-adf6-01c5c0197a61">

<img width="720" alt="Screenshot 2023-06-07 at 12 29 50 PM" src="https://github.com/seanrosshughes/rocketbook-productivity-tracker/assets/92600908/038968bb-774a-419d-a076-520ee5aaf3a2">

<img width="720" alt="Screenshot 2023-06-07 at 12 38 37 PM" src="https://github.com/seanrosshughes/rocketbook-productivity-tracker/assets/92600908/fe4f2375-f3a4-4896-a3f6-eda62d160271">

<img width="720" alt="Screenshot 2023-06-07 at 12 38 56 PM" src="https://github.com/seanrosshughes/rocketbook-productivity-tracker/assets/92600908/66c88907-488a-4527-9d15-f70853248dce">
