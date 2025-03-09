# Daily Property Directory Automation 🏠

## Description
This workflow automates the process of extracting property listings from emails, formatting the data, and then uploading it to a server. The goal 🚀 is to streamline the management of property listings by automating the retrieval and formatting of data received via email, and ensuring that the latest listings are always available on the server.

## Used Nodes and Integrations
- Email Trigger (IMAP) for fetching new emails
- Extract from File to handle file extraction from the email attachments
- Code for data manipulation and formatting
- Convert to File to prepare the data for upload
- FTP for uploading the formatted data to the server
- Read/Write Files from Disk for local file management

## Setup Instructions
1. **Configure IMAP Email Credentials**: Ensure you have the right IMAP settings and credentials configured for your email provider. ✅
2. **FTP Credentials Setup**: Make sure the FTP credentials are correctly configured to allow the workflow to upload the files to your server. ✅
3. **Environment Variables**: Verify all necessary environment variables are set up, especially if the workflow references any for paths or configurations. ✅
4. **Email Trigger Configuration**: Check the 'Email Trigger (IMAP)' node's settings to match your specific email fetching criteria, like subjects or senders to trigger on. ✅
5. **Test the Workflow**: Before going live, do a dry run with test emails to ensure everything works as expected. 🚀

With everything set up, you're all ready to automate your property listing management. Kick back, relax, and let n8n handle the daily grind. 🌟