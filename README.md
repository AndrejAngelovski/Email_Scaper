# Email Inbox Scraper

<h3>Description</h3><br>
This Python script allows you to scrape your own email inbox and categorize it for better organization. The script uses the Gmail API to access your email account and retrieve the email metadata, including the sender, subject, and labels. You can customize the script to group emails by sender, subject, label, or any combination of these criteria.

<h3>Usage</h3><br>
To use the script, you'll need to create a Google Cloud Platform project and enable the Gmail API. Then, you'll need to create a set of credentials and authorize the script to access your Gmail account. Once you've set up the credentials, you can run the script with the desired categorization parameters. The script will retrieve the email metadata and output the results to the console or to a file.

Example: 
```python
python inbox_scraper.py --group-by=sender
```
<h3>Note</h3> This script is intended for personal use only and is not meant for mass email scraping or spamming. Make sure to follow Google's terms of service and privacy policies when using the Gmail API.
