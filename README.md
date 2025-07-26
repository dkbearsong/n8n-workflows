# n8n-workflows
Storage for my n8n workflows


### RSS Feed Loader
A workflow that extracts URLs from the last day from an RSS feed, clears a google doc, and then loads the urls onto the doc. Intended to use with NotebookLM to have a notebook with the latest articles to get AI summaries on the latest articles in a topic.

### Trello Grocery List Loader
A workflow that triggers when a "Generate List" label is thrown on a Trello card. Takes the first list, sends it to Ollama for reorganizing, creates a new list with the reorganized items, deletes the old list and removes the label
