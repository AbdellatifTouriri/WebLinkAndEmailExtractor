# WebLinkAndEmailExtractor
### Script Topic: Extracting Emails and Links from Google map and Local HTML Files

This script is designed to perform two primary tasks:
 
  **Extract Links from Local HTML Files**:
   - It reads a local HTML file and searches for specific `<div>` elements that contain certain classes.
   - The script then extracts the links (`href` attributes) from the `<a>` tags found within these `<div>` elements.

### Example Workflow:

1. **Link Extraction**:
   - The script starts by extracting links from a local HTML file.
   - The links are added to a list of URLs to be further processed.

2. **Email Extraction**:
   - It then loops through each URL in the list, scrapes the page for email addresses, and stores the results in a dictionary.

3. **Saving Results**:
   - Finally, the extracted email addresses are saved to a text file (`emails_extracted.txt`).

 1 go to google map and search to your nich 
 2 copy the code source of page hml and put it in file content html and click run 
 NEEDED .
 RDP + IP CHANGER AUTOMATICALY
