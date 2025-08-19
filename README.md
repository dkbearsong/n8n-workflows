# n8n-workflows
Storage for my n8n workflows


### RSS Feed Loader
A workflow that extracts URLs from the last day from an RSS feed, clears a google doc, scrapes the articles from the URLs, and then loads the articles onto the doc. Intended to use with NotebookLM to have a notebook with the latest articles to get AI summaries. https://dereckbearsong.substack.com/p/rss-feed-to-notebooklm-n8n-automation

### Trello Grocery List Loader
A workflow that triggers when a "Generate List" label is thrown on a Trello card. Takes the first list, sends it to Ollama for reorganizing, creates a new list with the reorganized items, deletes the old list and removes the label

## Weekly Newsletter Roundup
A workflow that gathers all emails from a given week, pulls top takeaways from them, and sends a roundup email with those takeaways

## Daily Relevant Jobs Roundup
A workflow built off of the Weekly Newsletter Roundup that takes job alert emails from the previous day and identifies jobs that might be relevant to the user's skillset, emailing those back to the user. https://dereckbearsong.substack.com/p/the-automated-job-search-prototype
