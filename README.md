# Bangs for Google

Automatically use DuckDuckGo for [Bangs](https://duckduckgo.com/bang), keeping Google for all other searches.

## Installation
TODO: Upload to Firefox/Chrome Web store

## How does it work? How is the performance?

"Bangs for Google" uses the `webRequest` API, commonly also used in AdBlockers, to catch your Google Search queries before Google even loads. Due to this, the redirects to DuckDuckGo will happen very quickly.

The extension simply checks if you are currently on Google and your search query begins or ends with a "!" - if so, it will redirect you to DuckDuckGo using the same search query.

## Contributing
Please fork this repository and create a new pull request to contribute to it.

If you notice any errors, please create a new issue on GitHub.

# License
The extension is licensed under the MIT License.
