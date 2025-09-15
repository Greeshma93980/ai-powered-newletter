This project uses n8n workflow automation to automate the summarization and email delivery of news.  It uses an HTTP Request node to retrieve articles from an RSS feed, an XML to JSON converter, a Code node to create JavaScript summaries, a Set node to map fields, and a Gmail email sender.

 Problem: It takes a lot of time to manually track news.

 Solution: Create brief summaries, email them as a newsletter, and automatically extract article titles, descriptions, and links.

 Use: Set up Gmail credentials, import newsletter-workflow.json into n8n, and execute manually or on a Cron schedule.
