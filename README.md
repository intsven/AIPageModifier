# AI Page Modifier

This extension allows you to modify the content of a webpage using the Gemini API. 

## Important notes

This extenion uses Manifest v2 because it executes AI generated code in the context of the page. This is not possible in Manifest v3. It works both in Firefox and Chromium based browsers using Manifest v2.

## Running this extension

1. Clone this repository.
2. Download the Gemini API client by running:
   ```sh
   npm install
   ```
3. Compile the JS bundle for the sidepanel implementation by running:
   ```sh
   npm run build
   ```
5. Load this directory in Chrome as an [unpacked extension](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked).
6. Click the extension icon.
7. [Retrieve an API key](https://ai.google.dev/gemini-api/docs/api-key) and put it in the extension popup API key field.
8. Enter a prompt to modify the content of the page.
