# docsearch-preview

A simple HTML page with the DocSearch JavaScript, CSS, a form and a search box.
As soon as you have received an email notifying you that your DocSearch configuration is ready, you can test it out with this page.

## Prerequisites

- DocSearch Algolia API Key (this will be in your confirmation email)
- DocSearch Algolia index name (this will be in your confirmation email)

## Usage

Visit the Github Pages site of this repo at:

[https://community.algolia.com/docsearch-preview/](https://community.algolia.com/docsearch-preview/)

Fill in the "API key" and "Index Name" fields with the values from your email. If you ran the [DocSearch scraper](https://community.algolia.com/docsearch-scraper/) yourself, you should also make sure to change the App Id.

You should now be able to type queries into the search box and see results.

## Share a link

You can add query parameters for the apiKey, indexName and appId to the URL so that when you share a link these values are already populated and the search box is ready to go. Here's the format:

https://community.algolia.com/docsearch-preview/index.html?apiKey=XXXXXX&indexName=YYYYYYYY

Alternatively, specifying the appId as well:

https://community.algolia.com/docsearch-preview/index.html?apiKey=XXXXXX&indexName=YYYYYYYY&appId=zzzzzzzz
