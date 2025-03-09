# Daily Facebook Tip for Renters Workflow

## Description
This workflow automates the process of generating engaging Facebook content for apartment renters. It identifies posts from the database that have not been updated in the last 90 days, creates a new post with a relevant image, and finally updates the post status on WordPress.

## Used Nodes and Integrations
- MySQL
- Schedule Trigger
- OpenAI (GPT-4O-MINI for text and image generation)
- Read/Write File
- WordPress
- HTTP Request (for media upload)

## Setup Instructions
To get this workflow up and running smoothly:

1. **Configure MySQL Credentials:** Ensure you have your MySQL database credentials at the ready. You'll need to enter these in the MySQL node settings.

2. **Set Up OpenAI Credentials:** Get your OpenAI API key and input it into the OpenAI node to enable text and image generation.

3. **Configure WordPress Credentials:** For posting the updated content, you will need access to a WordPress account. Input these credentials in the WordPress and HTTP Request nodes.

4. **Schedule Setup:** Adjust the Schedule Trigger node to match the frequency you desire for content generation and posting.

5. **File Handling:** Ensure the file paths in the Read/Write File nodes are correctly set up to store the generated images before they are uploaded.

✅ Once these steps are completed, you're ready to launch the workflow and begin automating your Facebook content creation, making apartment renting a little more engaging for everyone. 🚀