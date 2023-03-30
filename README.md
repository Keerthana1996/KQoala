# KQoala
Enter your Kusto queries in natural language and have Azure OpenAI convert it into KQL for you.

Run the server so the extension can communicate with ChatGPT.

```bash
node server.js
```

This will automate interaction with our Aug loop resource and deployed models through OpenAI's API

Add the extension

1. Go to chrome://extensions in your Google Chrome browser
2. Check the Developer mode checkbox in the top right-hand corner
3. Click "Load Unpacked" to see a file-selection dialog
4. Select your local `KQoala/extension` directory
